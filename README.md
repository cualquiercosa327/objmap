# botw-objmap
_Breath of the Wild_ object map.

## Features
* Polished UI: clean BotW look.
* Location texts
  * Show them at the correct level. (Location.mubin)
  * Map waypoints. (Static.mubin LocationPointer)
* Common objects
  * groups:
    * Labo
    * Tower
    * ShopJewel, ShopColor, ShopYorozu, ShopBougu, ShopYadoya
    * Hatago, Village, CheckPoint, Castle
  * DLC shrines should have a different icon.
* Shrine details
  * Shrine name
  * Shrine title
  * CDungeon number
  * All treasure chests
* Search
  * search base locations too (no extra work required thanks to how LocationTags work)
  * object by ID
  * object by name (+ other filters?)
  * should work with chest contents, parameters, etc.
  * "Add to map"
  * "Remove from map" to exclude and hide some search results (suggested by Zant)
  * Show up to 2000 search results (suggested by Zant)
  * Color by actor type / by search result group (suggested by Zant)
* Objects
  * Custom handling for:
    * weapons
    * enemies
    * RememberTag
    * rafts
    * cooking pots
    * Koroks:
      * TODO [low-priority] autogenerate information on puzzles if possible?
      * TODO [low-priority] show colors, leaf shapes using embedded UMii data?
    * treasure chests (show contents)
    * Goddess Statues
  * Presets
    * BTB Enemies
    * Launchable Objects
    * Treasure Chests
    * Arrows
  * Custom presets
  * Search query syntax documentation
  * Show all objects in area.
* Object details
  * Respawn information, no-revival area...
  * Scaling information
  * Instance parameters
  * Generation group and links
  * Object shape
  * Object scale
* Routes
* Regions
  * Tower regions
  * Map areas (internal)
* TODO Region details
  * TODO Climate information
  * TODO Autogen information
* TODO Dynamic map data
  * TODO Scaling slider (to scale enemies, weapons, etc.)
  * Master Mode (auto rankup, Master Mode only actors)
  * One-Hit Obliterator challenge mode
  * Final boss placement mode
* Polygon/line drawing
  * UI
  * Saving
  * Import/Export
  * Colors
* Measuring
* TODO Object tracking
  * TODO Track used objects.
  * TODO Have checklist views for shrines, locations, Korok seeds, etc.
    * TODO The shrine list should show name + title to easily see e.g. combat shrines at a glance.
    * TODO Sort by name optionally. For Korok seeds, sort by HashId.
    * TODO Group by region optionally
    * TODO See also *object details*
    * TODO For locations: locations that have save flags are trackable, those that don't appear by default and aren't trackable.

## Integration
* Integration with other tools/viewers for special objects, such as:
  * EventTag: open event flow in EventEditor (if it exists)
  * SignalFlowchart: same
  * TODO any actor with an event flow: same
* TODO Autogen: link to EventEditor for AutoPlacement event flows.

## Credit
* The authors of the [Sheikah Complete](https://fontstruct.com/fontstructions/show/1371125/sheikah-complete) and [Calamity Sans](https://www.reddit.com/r/zelda/comments/5txuba/breath_of_the_wild_ui_font/) fonts
* Yoshi.noir for the UI map marker icons
* [Korok seed icon](https://www.zeldadungeon.net/breath-of-the-wild-interactive-map/markers/seed.png)
* MrCheeze for the [list of names](https://github.com/MrCheeze/botw-tools/blob/master/botw_names.json)
