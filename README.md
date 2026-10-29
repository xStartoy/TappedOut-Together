# TappedOut-Together
PC version of the Building Mode you can play with your friends
TAPPED OUT TOGETHER — Sandbox (Playtest 1, with the game's assets)
==================================================================

Start: double-click TappedOutTogether.exe
The "assets" and "data" folders and steam_api64.dll must stay next to the exe. data\assets holds the game's graphics
(taken from its CDN) that the sandbox shows, losslessly packed into 3 archives; data\sounds holds the sounds.
2.2 GB in all: to share the game, zip the whole folder (without saves\ if you want to keep your towns to yourself).
On first launch you choose the language (English / Français); it can be changed later in the menu (Esc).

CONTENTS (everything comes from the game's files, final version 4.69)
  - The Springfield map at its original size: 40 x 40 land blocks of 16x16 tiles,
    the sea and the beach, the mountain range between Springfield and Springfield Heights,
    and the beach and mountains of Springfield Heights.
  - Starting town: saves\default_map.json (empty at first). It is a town like any other: to make one of your towns
    the start of every new town, copy its file from saves\ as default_map.json.
    It does not show in My towns. (A full generated town is kept in data\town_full.json.)
  - Catalog: 1,198 buildings, 1,971 decorations (with their variants), 11 terrains, search.
    The pieces the game places by itself (bridge railings, boat tops, gate halves…) are left out.
  - 986 characters and 412 costumes, animated, with their voices (349 characters have a tap line in the game;
    the others, like Milhouse, play the generic sound as in the original).
  - Springfield Heights: the sand beach, where the mountains meet the sea, and the great canyon
    (New Frontier) with its suspension bridge and its waterfall.

CONTROLS
  WASD / ZQSD / arrows    walk (Shift: run) — Space: center the camera
  Mouse wheel             zoom (out to the whole map)
  Right-click drag        move the camera
  B or Tab                (in build mode only, like T) catalog + search; on the left, the themes
                          (houses, shops, nature, city, then the events: Halloween, Christmas, Krustyland,
                          Wild West, superheroes…) with each one's item count (cards marked "variants": pick the variant)
  P                       change character / costume (or click the thumbnail at the top left)
  Enter                   chat: type a message, Enter to send it (bubble above your character, at most
                          3 lines), Esc to cancel; change your name in the menu (Esc)
  C                       build mode (off by default: you are visiting, a click moves nothing,
                          it "taps" the item as in the game: tap sound (2,067 items),
                          animation (578 items), state change)
                          in build mode: click an item to move it — R: flip —
                          V: next state, then variant (Shift+V: variant only) — Del: delete
                          (states: Krustyland and Itchy & Scratchy parking lot cars, presents,
                          stacked sheep… 10 items; they are saved)
  Selection               in build mode, click and drag on the ground: every item and every terrain tile
                          (roads, sidewalks, rivers, sand, piers…) touched by the diamond is
                          selected (yellow outline) and a bar shows at the bottom:
                          Move (or click a selected item or tile) — Flip (R) — Delete (Del) —
                          Blueprint — × (or Esc); right-click cancels a move in progress (everything goes back)
  Blueprints              "Blueprint" saves the selection under a name, items and terrain included;
                          it shows in the catalog's Blueprints tab: click to place it (R flips,
                          Shift + click places it several times). The files are in the blueprints\ folder
                          next to the exe (one .json per blueprint): send them to your friends, who copy them into
                          their own blueprints\ folder
                          The Blueprints tab also has the 56 ready-built sets sold in the game (Krustyland entrance
                          in 3 pieces with turnstiles and walls, Recycled Fort, Love Pack, Nature Pack…)
  Krustyland              both entrances (whole, or in 3 pieces): walking into the clown's mouth brings you out
                          behind, past the turnstiles; walking into the back of the entrance (or the turnstiles)
                          brings you out in front of the tongue, like the mountain tunnels
  Shift + click           place the same item several times
  Tunnels / ridge         the mountain tunnels, the Simpsons' hillside villa, the temple, etc. are placed
                          in place of a section of the ridge (the preview snaps to the nearest free spot);
                          walking into a tunnel entrance brings you out on the other side
  T                       Terrain palette (at the bottom of the screen, stays open while you paint):
                          road, sidewalk, river, dirt road and path, cobblestones, sand, frozen river,
                          gold road, Krustyland road (4x4 road tiles, brush 1-3); edges, sidewalks,
                          corners and banks adapt to their neighbors exactly as in the game
                          (road, dirt, cobblestones and gold road join each other; the sidewalk stays a slab)
  Monorail                T, "Monorail" tab of the palette: straight rail, short rail, curved rail, S rail and the
                          stations (central, Krusty drive-in, Mall-O-Rail, Tetanus terminal, magic station, North Pole,
                          futuristic). R flips the rail; brought near the free end of a line, it snaps on by
                          itself; it stays in hand to place the next one (right-click to stop)
                          E next to a station: drive the monorail (engine, two cars, caboose).
                          W forward, S back (or brake), E get off; + / - (or the panel's buttons) adds or
                          removes a car (0 to 10); top speed 200 km/h; at junctions it takes the straightest
                          track, it stops at the end of a line. You can walk under the rails: only the pillars
                          block
  Shuttles / booths       E next to a Krustyland shuttle: list of the other shuttles placed, "Go" to travel
                          there at once. Same with the phone booths (booth, old booth, Zenith City booth),
                          which make a network of their own. "Rename" names the stop you are at
                          (empty: default name "Shuttle 1", "Booth 2"…); the names are saved with the town
  Boardwalks              the boardwalk (Squidport) and the fancy pier painted on the sea work as ground: you can
                          place on them the buildings and decorations that go on grass (you cannot erase the
                          boardwalk under a building above the water)
  Beach stairs            (Springfield Heights) take you from the cliff down to the beach: you can walk on
                          every step, only the flower boxes and street lamps block
  Rivers                  everything that goes on the sea (boats, islets, floating presents…) also goes on a
                          river, if it fits; now and then Blinky (the three-eyed fish) jumps or a toxic barrel
                          floats up, as in the game (not on the frozen river)
  Bridge                  paint a road over a river: the river stays underneath and the railings
                          show on the river side (straight, corner and L bridges as in the game);
                          erasing the bridge gives the river back
  Click a character       they speak with their real voice
  Alt (held)              the character's action wheel, taken from the game's animated "jobs": while walking
                          (Bart on his skateboard, Agnes sweeping…) or in place (dance, meditate…); aim at an action and
                          release Alt (release in the middle: nothing changes; wheel: more actions); "Walk normally"
                          to go back; moving stops an in-place action
  Ctrl (held)             highlights the decorations this character / costume can use
  E                       next to one of these decorations: use it as in the game (Agnes feeds the pigeons on a
                          bench…); several actions possible: hold E, aim, release; move to get up
                          E next to an animated building: turn it on / off as when it works in the
                          game (Scratchy's Catapult swings its cannonballs…, about 1,670 items); kept when saving
                          Ctrl held + E: on the item under the mouse (blue frame), even far away (at sea…)
                          (3,260 actions in all: 906 while walking, 1,663 in place including 1,031 victory poses,
                          691 on a decoration)
  NPCs                    the townspeople also do their actions by themselves, now and then: walk differently
                          for a while, an action in place, or go to a decoration of the town that one of their
                          actions uses (Lisa plays the sax in front of the Simpsons' house, Quimby gives his speech
                          at town hall…); a decoration in use cannot be used by someone else
  G                       grid + land blocks — M: music off / on — F5: save
  F3                      info at the bottom left (tile under the mouse, zoom, FPS, memory)
  F11                     borderless fullscreen / back to a window (the game opens in a maximized window)
  F9                      my towns: play, rename, copy, delete a town, create a new one
                          (starting town or empty land)
  F8                      multiplayer (also in the Esc menu): see MULTIPLAYER below
  Esc                     cancel / menu (name, language English / Français, help, sound, multiplayer, my towns,
                          Discord, quit)
  Sound (menu)            volumes of music, ambience and effects / voices; the ambience is the game's
                          (town, sea, mountain) and follows the camera through the game's zones (landinfo.xml)

Saves: one town = one file in saves\ (the file name is the town's name).
The current town is saved every 2 minutes, when quitting and before switching towns.
saves\settings.json keeps your name, the language and the current town.
A deleted town goes to saves\supprimées\ (put it back in saves\ to get it back).
(ville_demo1_ancienne.json, the demo 1 save, is not compatible)

SAVES FROM THE REAL GAME (.pb)
  A save from The Simpsons: Tapped Out (.pb file) becomes a sandbox town: drag it onto the
  game window (it is imported and loaded), or put it in saves\ (imported when My towns opens).
  Brought over: buildings and decorations (with their variants and direction), characters and costumes, roads,
  sidewalks, rivers, paths, sand, boardwalks and piers. Not Krustyland (a separate land in the game), nor
  quests, money… The imported .pb file and a report (unknown items…) go to saves\importées\.

MULTIPLAYER (F8, up to 8 players)
  One player hosts their town, the others join it with a code. Everyone needs the same version of the game.
  Host through Steam      Steam must be running (the game goes through the "Spacewar" test app, so it is normal if
                          Steam says "playing Spacewar"). Nothing to set up: it works over the Internet, behind
                          any router. The code is 6 characters (e.g. K7M2QX); the "Invite Steam friends"
                          button opens the friends list, and a friend whose game is open can also use "Join
                          Game" from Steam.
  Host by IP              without Steam. "Local network" code (10 characters) for players on the same network or
                          a VPN (Radmin, ZeroTier, Tailscale…). "Internet" code when the router agrees to open the
                          port by itself (UPnP); otherwise, forward UDP port 28750 to this PC in the router. On first
                          launch, Windows asks to allow the game through the firewall: accept.
  Join                    type or paste (Ctrl+V) the code, or an IP address directly (192.168.1.20 or ip:port).
  During the game         everyone builds (items, terrain, monorail, characters), plays their character and
                          actions, drives their train, chats (Enter). A player's name shows when the mouse is over
                          them, messages and arrivals at the bottom left. The host can kick a player.
  Saving                  only the host's town is saved (on the host's PC). As a guest, your own town is not
                          touched: it comes back as soon as you leave the game. If the host switches towns (F9),
                          everyone follows.

WINDOWS SMARTSCREEN
  The exe is not signed, so Windows may show "Windows protected your PC" on first launch:
  click "More info" then "Run anyway".
