Terasology
==========

[Download now from GitHub](https://github.com/MovingBlocks/Terasology/downloads) - Hello Gronkh users and internet at large!

![Terasology](https://github.com/MovingBlocks/Terasology/raw/develop/src/main/resources/org/terasology/data/textures/loadingBackground.png "Terasology")

Terasology is a game that pays ample tribute to [Minecraft](http://www.minecraft.net) in initial look and origin, but stakes out its own niche by adopting the NPC-helper and caretaker feel from such games as [Dwarf Fortress](http://www.bay12games.com/dwarves) and [Dungeon Keeper](http://en.wikipedia.org/wiki/Dungeon_Keeper), while striving for added depth and sophistication.

Terasology is an open source project started by Benjamin "begla" Glatzel to research procedural terrain generation and efficient rendering techniques in Java using the [LWJGL](http://lwjgl.org). The engine uses a block-based voxel-like approach as seen in Minecraft. After proving itself as a solid tech demo begla was joined at first by Anton "small-jeeper" Kireev and Rasmus "Cervator" Praestholm and a full-fledged game concept was born.

The creators of Terasology are a diverse mix of software developers, game testers, graphic artists, and musicians. Get involved by checking out our [Community Portal](http://forum.movingblocks.net/index.php), our blog [Moving Blocks!](http://blog.movingblocks.net), and our [Facebook Page](http://www.facebook.com/pages/Blockmania/248329655219905).

Terasology is licensed under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html) and available in source code form at [GitHub](https://github.com/MovingBlocks/Terasology).

Setup
-----

Terasology requires the latest version of Oracle's [Java Virtual Machine (JVM)](http://www.java.com/de/download/). Also make sure that your graphics card driver is up to date.

You can use one of the default launch scripts to start the game. The scripts will setup your JVM to allocate up to 1024 MB of heap space. Under Linux and Mac OS X the run script needs the access permission "Execute" to run properly: "chmod +x script.sh".

Controls
--------

* [W,A,S,D]               - Movement
* [E]                     - Activate (Chest, TNT, etc)
* [Space]                 - Jump
* [Double Space]          - God mode (fly / no-clip)
* [Shift]                 - Hold to run
* [Left click]            - Activate left click action (default = place block)
* [Right click]           - Activate right click action (default = remove block)
* [Mouse wheel up/down]   - Cycle through toolbar slots
* [1,..,0]                - Change the active toolbar slot
* [I]                     - Toggle inventory screen
* [F]                     - Toggle viewing distance (near, moderate, far, ultra)
* [Tab]                   - Toggle developer console
* [F3]                    - Toggle debug mode and information
* [F4]                    - Different debug metrics
* [K]                     - Don't try this :-)
* [Escape]                - Show/hide the game menu screen

Debug features 
------------------------

Only works when the F3 debug mode is enabled (and may come and go)

* [Arrow up/down]         - Adjust the current time in small steps
* [P]                     - Activate first-person player camera
* [O]                     - Activate animated spawning point camera

Examples tools 
------------------------

May move slot or disappear as development continues

* Companion Cube          - Poorly hidden easter egg almost guaranteed to never talk with or attempt to stab you
* Torch                   - Shiny! Place with left click
* Pickaxe / shovel        - Faster right-click removal of some blocks
* Blueprint               - Left click one block, then another, then somewhere else to "clone" your selection (right-click resets)
* Explosion tool          - Big bada boom!
* Railgun                 - Bigger bada boom, in a straight line!
* Debug tool              - Experimental

Example console commands 
------------------------

Press Tab to toggle the in-game console (all you'll see is a tiny underscore cursor when active, just start typing!)

* giveBlock "Water"                 - Gives 16 water blocks
* giveBlock "IronPyrites", 42       - Gives 42 Iron Pyrite (Fool's Gold) blocks
* giveBlock "Chest"                 - Gives you a Chest block you can place, activate ('E'), put stuff in, destroy, pick up, place elsewhere, find same stuff in it!
* giveBlock "Tnt"                   - Gives you 16 TNT blocks you can place and activate ('E') to blow up
* teleport 42, 42, 42               - Warps the player to x = 42, y = 42, z = 42
* fullHealth                        - Fully restores the player's health
* gotoWorld "GhostTown"             - Loads the world "GhostTown" if present, otherwise initializes a new world "GhostTown" with a randomized seed value
* gotoWorld "GhostTown", "Pie!"     - Loads the world "GhostTown" if present, otherwise initializes a new world "GhostTown" with the seed value "Pie!"

Options
------------------------

* Graphics Quality        - Defaults to support somewhat low-end computers, can be bumped up for very snazzy effects (possibly even _too_ shiny!)
* Viewing Distance        - How many chunks to load around the player for display
* Field of View           - Special effect related to distance and visual warping (more distant with greater value)

Many more options are available via config file but not yet exposed in the GUI

Building and running source
------------------------

*  Download / clone the source from GitHub
*  To prepare for IntelliJ run: $ gradlew idea
*  To prepare for Eclipse run: $ gradlew eclipse
*  To run from the command line: $ gradlew run
*  For more tasks: $ gradlew tasks

You may also need to tweak IDE settings further for your convenience. See [Dev Setup](http://wiki.movingblocks.net/bin/view/Main/DevSetup) in our wiki for more details.

Credits
=======

This is an incomplete list and the team is constantly growing. See [Dev Team](http://wiki.movingblocks.net/bin/view/Main/DevTeam) in the wiki for the latest updates

Contributors
---------

* Benjamin "begla" Glatzel
* Anton "small-jeeper" Kireev
* Rasmus "Cervator" Praestholm
* Immortius
* Richard "rapodaca" Apodaca
* Kai Kratz
* t3hk0d3

Soundtrack and Sound Effects
----------

* Sunrise, Afternoon and Sunset composed by Karina Kireev.
* Dimlight, Resurface and Other Side composed and produced by Exile.
* Sound effects created by Exile.

Additional Notes
================

Terasology's base graphics use the awesome <strong><a href="http://www.carrotcakestudios.co.uk/gmcraft/">Good Morning Craft!</a></strong> texture pack by Louis Durrant. Make sure to visit his <a href="http://www.carrotcakestudios.co.uk/">homepage</a> and support his work.
