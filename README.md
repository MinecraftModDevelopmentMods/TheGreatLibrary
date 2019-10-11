# The Great Library Mod:

## Table of Contents:
* [Overview](#overview);
* [Biomes](#biomes);
* [Sections](#sections):
  * [Workshops](#workshops);
  * [Sleeping Quarters](#sleepingquarters);
  * [Restricted Areas](#restrictedareas);
* [Tools](#tools);
* [Mobs](#mobs);
* [Books](#books);
* [Drops / Loot](#dropsloot);
* [Decorations](#decorations);
* [Integrations](#integrations):
  * [Thaumcraft](#thaumcraft);
  * [Astral Sorcery](#astralsorcery);
  * [Waystones](#waystones);
  * [Mystcraft](#mystcraft);
  * [Soulus](#soulus);
  * [Bibliocraft / Inspirations](#bibliocraftinspirations);
  * [Iron Age Furniture](#ironagefurniture);
  * [Iron Age Architecture](#ironagearchitecture);
  * [Better Portals](#betterportals);
  * [Tinker's Construct](#tconstruct);
  * [Construct's Armory](#conarm);
  * [Extra Golems](#extragolems);
* [Unsorted Notes](#unsortednotes);

## Overview:<a name="overview"></a>
`Labyrinthic dimension`, built in the style of a [`library`](https://github.com/YaibaToKen/The-Great-Library), by randomly picking a section for each chunk or set of chunks.
If possible, integration with [Cubic Chunks](https://www.curseforge.com/minecraft/mc-mods/opencubicchunks) should be provided, as it will give new depth (pun intended) to the dimension, essentially making it `truly infinite`.

Integration with other mods could provide new content in the form of:
- New Sections / Biomes;
- New Drops / Loot;
- New Mob Spawners;
- New Traps / Contraptions;

## Biomes:<a name="biomes"></a>
Biomes control:
- Section style;
- Section type;

## Sections:<a name="sections"></a>
> The sections can probably be done somewhat as json config files which means we could have expansion content packs with a bunch of sections.

`Sections` should be defined through [`JSON`](https://en.wikipedia.org/wiki/JSON) files, but the [`Structure Block File Format`](https://minecraft.gamepedia.com/Structure_block_file_format) might also be a nice alternative.

Possible Sections:
- Workshops:<a name="workshops"></a>

  > YaibaToKenToday at 4:53 PM
They'd be much rarer than actual library sections, but would also help anyone exploring and would work as checkpoints.
Since we could also use droptables to populate those sections with corresponding loot.

  > SkyBladeToday at 4:53 PM
and since bookshelfs can't be mined without making the mobs aggro, maybe a workshop where bookshelfs are made where the player can actually get bookshelfs without making the mobs aggro

  > YaibaToKenToday at 4:53 PM
We could have workshops of varying sizes, the bigger the better the loot
Well, if we make sure mobs don't spawn in those sections, and seeing as workshops would have gates or doors, that should be feasible

  * `Potion Brewery`;
  * `Potion Distillery`;
  * `Enchantment Lab`;
    > SkyBladeToday at 5:25 PM
 oh there should be an enchanting station section (a rare section with an enchanting table).

    > YaibaToKenToday at 5:26 PM
Oh yes! Perhaps with some enchanted books as well
  * `Book Binding Atelier`;
  * `Tannery` (Leather Works Integration);
    > YaibaToKenToday at 5:08 PM
I was thinking more about Leather Works for example

    > YaibaToKenToday at 5:08 PM
having a workshop where you can tan leather and process it further would make sense, as it provides a source of materials to make books

  * `Thaumaturge's Study` (Thaumcraft Integration);
  * `Astral Observatory` (Astral Sorcery Integration);
  * `Misty Library` (MystCraft Integration);
  * `Misty Binding Atelier` (MystCraft Integration);
  * `Soul Workshop` (Soulus Integration);
  * `Golem Workshop` (Extra Golems Integration);
    > YaibaToKenToday at 5:24 PM
Yeah
Oh, lost golem workshop sections :stuck_out_tongue: with a thaumcraft variant.

  * `Tool / Armour Workshop / Smithy` (Tinker's Construct / Construct's Armory Integration);
    > YaibaToKenToday at 5:27 PM
A toolsmith section for TiC and ConArm users and a vanilla variant

- Sleeping Quarters:<a name="sleepingquarters"></a>
  * `Abandoned Camp` (Inspirations Integration);
  * `Ruined Inn`;
  * `Librarian Dorm`;

- Restricted Areas:<a name="restrictedareas"></a>
  > SkyBladeToday at 4:55 PM
oh yes there was one I had in mind, like a 'restricted section', like in Doctor Strange, a gates section to the library with more magical book drops but also with aggro mobs inside maybe

  > YaibaToKenToday at 4:55 PM
So, like same dimension, but special conditions to access? We could perhaps encase the sections in bedrock?

  > SkyBladeToday at 4:56 PM
yeah good idea, well bedrock wrapped in bookshelves, if they try and mine into the side of the section they'll hit bedrock
what would be fun would be to have a key they had to find to get in
keep them busy..
so the chest with the key always spawned within a certain range of the gate

  > YaibaToKenToday at 4:58 PM
Yup, the section with the key could even have some noticeable details, just to exclaim there's something there

  * ~~Placeholder~~;

Sections control:
- Drop / Loot selection;
- Mob selection;
- Trap / Contraption selection;

## Tools:<a name="tools"></a>
New tools:
- `The "Book" - Vanilla Edition` - That's actually the name. Right click acts like a `shield`, left click `attacks` with a book whacking sound (Thank you @jriwanek and @kat\`\`);
- `The "Book" - TiC Edition` - Works just like the `Vanilla Edition`. Made with two `Large Tool Plates`, a `Stack of Pages` (custom tool part) and a `Bowstring`. The materials used in it's construction lend themselves to the `ancient lore` of `The Librarians`;

## Mobs:<a name="mobs"></a>
New mobs:
- `Rat`;
- `Skeleton Rat`;
- `Librarian` - There are several variants, some neutral, others aggressive and a few even passive. Should drop book materials and writing supplies;
- `Angry Book` - Can be made to work similarly to Silverfish, when breaking `Bookshelves` in `The Library`. Should randomly drop a `written book`;
- `Friendly Book`. Should randomly drop a `written book`;
- > ProxyNekoToday at 8:33 PM
Could also make a good book that you can tame that would fight the angry books and evil books would be like the good books mob counterpart or rival

- > SkyBladeToday at 8:36 PM
maybe in the book workshop. ah I like that idea, something like a crafting table, it spawns only in the book workshop and it (like bedrock) can't be mined or moved
so you have to go to the book workshop to craft the friendly book mobs..
I imagine them like wolves

## Books:<a name="books"></a>
`Books` should be randomly generated in `The Library`, with emphasis on `written books`. These could be `obtained` from a `community repository`, hosting a myriad of `copyright free or otherwise authorized` books:
- > I think having books with actual short stories in would be cool, there's so many unpublished authors works floating around it must be possible to build up a load of copywrite free work to stick into books.;
- > Make a public repo containing just those book files, this way, the community can PR new stories smile and we could have the mod pull a random story from the repo each time it has to generate a book.;
- > Though perhaps we could make the book part an optional plugin.;
- > With a big enough repository of random books to find it could give more motivation to go exploring looking for new books...;
- > Imagine if you could hook with patchouli and similar libs to grab whatever manuals were generated with those libs and place them in The Library.;

## Drops / Loot:<a name="dropsloot"></a>
- `Empty Books`;
- `Written Books`;
- `Book and Quill`;
- `Paper`
> (Random stacks of paper laying around.);
- `Enchanted Books`
> (With enchantment books being rare, but possible finds.);

## Decorations:<a name="decorations"></a>
- > We should also randomly generate signs pointing to stuff (like reading areas or book genres) mostly as decoration.;
- > Biomes could have signs at the entries, like "The Catacombs" or "Magical Studies".;

## Integrations:<a name="integrations"></a>
All of the `mods` mentioned below have a [1.12.2 version](https://minecraft.gamepedia.com/Java_Edition_1.12.2), with the majority either having a [1.14 version](https://minecraft.gamepedia.com/Java_Edition_1.14) as well, a successor or a spiritual successor.

### [Thaumcraft](https://www.curseforge.com/minecraft/mc-mods/thaumcraft) <sup><sub>([GitHub](https://github.com/Azanor/thaumcraft-api))</sub></sup> :<a name="thaumcraft"></a>
- `Research Notes`;
- `Greatwood / Silverwood Library Sections`:
  * Mobs:
    * ~~Placeholder~~;
  * Drops / Loot:
    * ~~Placeholder~~;
    * `Greatwood Style`;
    * `Silverwood Style`;
- `Eldritch Library Sections`:
  * Mobs:
    * ~~Placeholder~~;
  * Drops / Loot:
    * ~~Placeholder~~;
  * `Eldritch Style`;
- `Crimson Library Sections`:
  * Mobs:
    * ~~Placeholder~~;
  * Drops / Loot:
    * ~~Placeholder~~;
  * `Crimson Style`;

### [Astral Sorcery](https://www.curseforge.com/minecraft/mc-mods/astral-sorcery) <sup><sub>([GitHub](https://github.com/HellFirePvP/AstralSorcery))</sub></sup> :<a name="astralsorcery"></a>
- `Constellation Papers`;
- `Marble Library Sections`:
  * Drops / Loot:
    * ~~Placeholder~~;
  * `Astral Sorcery Marble Style`;

### [Waystones](https://www.curseforge.com/minecraft/mc-mods/waystones) <sup><sub>([GitHub](https://github.com/blay09/Waystones))</sub></sup> :<a name="waystones"></a>
- Randomly placed `Waystones` with `Section` names being used as part of the `Waypoint` name;

### [Mystcraft](https://www.curseforge.com/minecraft/mc-mods/mystcraft) :<a name="mystcraft"></a>
- > Picture sections of the Library with books for unknown worlds, full of untold stories. Or even just groups of pages, randomly strewn around.;

#### Add-ons:
- [`Linking Through The Ages`](https://www.curseforge.com/minecraft/mc-mods/ltta);
- [`More Mystcraft`](https://www.curseforge.com/minecraft/mc-mods/more-mystcraft);
- [`Pages`](https://www.curseforge.com/minecraft/mc-mods/pages);

### [Soulus](https://www.curseforge.com/minecraft/mc-mods/soulus) <sup><sub>([GitHub](https://github.com/Yuudaari/soulus))</sub></sup> :<a name="soulus"></a>
- > We could have summoners (the soulus version of a spawner), with randomly filled soul books in shelves.;

### [Bibliocraft](https://www.curseforge.com/minecraft/mc-mods/bibliocraft) / [Inspirations](https://www.curseforge.com/minecraft/mc-mods/inspirations) <sup><sub>([GitHub](https://github.com/KnightMiner/Inspirations))</sub></sup> :<a name="bibliocraftinspirations"></a>
- > If Bibliocraft, Inspirations or other similar mods that add 3D bookshelves (those where you can place books directly and see them there), we could generate the library sections with those instead. Aside from that, I'd say verify what bookshelf variants we can use (mostly for wood types).
Whenever possible, smaller mods should be favored over bigger ones, as that can reduce bloat;

### [Iron Age Furniture](https://www.curseforge.com/minecraft/mc-mods/ironagefurniture) <sup><sub>([GitHub](https://github.com/MinecraftModDevelopmentMods/IronAgeFurniture))</sub></sup> :<a name="ironagefurniture"></a>
- Furniture and other furnishings for `The Library`;

### Iron Age Architecture:<a name="ironagearchitecture"></a>
- Architectural elements for new `Styles` and `Sections`;

### [BetterPortals](https://www.curseforge.com/minecraft/mc-mods/betterportals) <sup><sub>([GitHub](https://github.com/Johni0702/BetterPortals))</sub></sup> :<a name="betterportals"></a>
- Whatever design we opt on for the `Portals` leading to and from `The Library`, they should behave like `Nether Portals` from the `Better Portals` mod if it's loaded;

### [Tinker's Construct](https://www.curseforge.com/minecraft/mc-mods/tinkers-construct)  <sup><sub>([GitHub](https://github.com/SlimeKnights/TinkersConstruct))</sub></sup> :<a name="tconstruct"></a>
- See `Sections` section above;

### [Construct's Armory](https://www.curseforge.com/minecraft/mc-mods/constructs-armory)  <sup><sub>([GitHub](https://github.com/TheIllusiveC4/ConstructsArmory))</sub></sup> :<a name="conarm"></a>
- See `Sections` section above;

### [Extra Golems](https://www.curseforge.com/minecraft/mc-mods/extra-golems)  <sup><sub>([GitHub](https://github.com/MinecraftModDevelopmentMods/Extra-Golems))</sub></sup> :<a name="extragolems"></a>
- See `Sections` section above;

### Unsorted Notes:<a name="unsortednotes"></a>
> SkyBladeToday at 5:08 PM
yes some nice book recipes and models with different leathers woudl be good

> YaibaToKenToday at 5:09 PM
panda's wood mod might also be nice if we could figure out a way to generate bookshelfs in Inspirations' (if the mod is loaded) or vanilla's style for all wood types

> SkyBladeToday at 5:10 PM
will be cool to have some really good short stories hidden in there,  imagine a player logging on just to carry on ready a book

> YaibaToKenToday at 5:10 PM
Mineralogy could provide new section styles, using the different stone types

> SkyBladeToday at 5:10 PM
I suppose some polished stone floors and pillars could be nice

> YaibaToKenToday at 5:10 PM
oh yes, the section file must contain what mods it depends on

> SkyBladeToday at 5:10 PM
and the lamps
some bits it can use the thing from the mod if it has it, and if not substitute it for a vanilla thing  like mineralogy stone floor could be swapped for vanilla stone brick, except ironage* which I plan to be a required mod
as it will provide all the furniture etc

> YaibaToKenToday at 5:16 PM
I was thinking we'd be doing the section generation in two steps, at least for blocks that have vanilla counterparts. First step generates the section using as many vanilla blocks as possible, the second step replaces them with the corresponding blocks from the picked style template

> SkyBladeToday at 5:17 PM
ah yes good idea

> YaibaToKenToday at 5:17 PM
This also means that if a mod changes block names, it won't break new sections, just break the style

> SkyBladeToday at 5:17 PM
thats how mineralogy works

> YaibaToKenToday at 5:17 PM
And the section picking needs to be tied to the seed, so that the same seed will always generate the exact same sections
This way we can add a retrogen system for the section generator

> SkyBladeToday at 5:19 PM
I like the idea of getting lost in the library, because the mobs get aggro if you start smashing through the bookshelves it would be a gamble for the player, if they wanted to hack through the bookshelves or walk around the long way

> YaibaToKenToday at 5:21 PM
Yeah, would also encourage the player to use a bread crumbs system

> SkyBladeToday at 5:21 PM
I do that in the nether, with torches usually

> YaibaToKenToday at 5:21 PM
I sometimes use signs
Btw, who was it that was working on a simple golem framework?
I want that for bookshelves and the like :stuck_out_tongue:

> SkyBladeToday at 5:23 PM
well the golems are by skyjay, i assumed we would include his bookshelf golems

> YaibaToKenToday at 5:23 PM
Yes please then :smirk:

> SkyBladeToday at 5:24 PM
which I think means it'll use mmdlib
but thats expected
