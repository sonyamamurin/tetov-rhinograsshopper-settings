# rh-gh-setup Rhino 6 branch
Repo with my config for Rhinoceros and Grasshopper

## Files

### [grasshopper-utils](./grasshopper-utils)

#### [`Hydra_ExportFile.ghuser`](./grasshopper-utils/Hydra_ExportFile.ghuser)
*  [Source](https://github.com/HydraShare/hydra/)
*  Location: File > Special Folders > User Object Folder, drag & drop into folder.

#### [`WireDisplayToggle.gh`](./grasshopper-utils/WireDisplayToggle.gh)
*   [Source](http://www.grasshopper3d.com/profiles/blogs/wire-display-toggle-switch)
*  Location: Drag & drop in Grasshopper window, select the C# block File > Create User Object

### [rhino-utils](./rhino-utils)

#### [`Rhino-options-export.ini`](./rhino-utils/rhino-options-export.ini)
* `_OptionsImport` in Rhino

#### [`Aliases-rhino.txt`](./rhino-utils/aliases-rhino.txt)
*  `_Options` > Rhino Options > Aliases > Import

#### [`ACADAliasesForRhino.txt`](./rhino-utils/ACADAliasesForRhino.txt) from [AutoCAD Aliases for Rhino](https://wiki.mcneel.com/rhino/acadaliases)
*  `_Options` > Rhino Options > Aliases > Import

## Grasshopper plugins

### Install through `TestPackageManager`

*  [WeaverBird - Topological Mesh Editor](http://www.giuliopiacentino.com/weaverbird/)
*  [Kangaroo Physics](http://www.food4rhino.com/app/kangaroo-physics)
*  [Plankton](https://github.com/meshmash/Plankton)

### Install manually

*  [Milliepede](http://www.sawapan.eu/)
*  [Anemone](http://www.food4rhino.com/app/anemone)
*  [Octopus](http://www.food4rhino.com/app/octopus)
*  [Boid](http://www.food4rhino.com/app/boid-library)
*  [Human](https://www.food4rhino.com/app/human)
*  [MetaHopper](https://www.food4rhino.com/app/metahopper)
*  [Heteroptera](https://www.food4rhino.com/app/heteroptera)
*  [Lunchbox](https://www.food4rhino.com/app/lunchbox)
*  [Dendro](https://www.food4rhino.com/app/dendro)
   - Need to disable "Memory load \*.GHA assemblies using COFF byte arrays" in `GrasshopperDeveloperSettings` (from Rhino).
*  [Pufferfish](https://www.food4rhino.com/app/pufferfish)
*  [Cocoon](http://www.bespokegeometry.com/2015/07/22/cocoon/)
*  [MeshEdit](https://www.food4rhino.com/app/meshedit)
   - Don't install Plankton files, only Meshedit2000.gha
*  [Fox](https://www.food4rhino.com/app/fox)
*  [MeshMachine Static](https://www.grasshopper3d.com/xn/detail/2985220:Comment:1841560)
*  [Droid](https://www.food4rhino.com/app/droid)
*  [IntraLattice](https://www.food4rhino.com/app/intralattice)
*  [Ladybug & Honeybee](https://www.food4rhino.com/app/ladybug-tools)
   - [Installation instructions](https://github.com/mostaphaRoudsari/ladybug/wiki/Installation-Instructions)
*  [Clipper](https://www.food4rhino.com/app/clipper-grasshopper-and-rhino)
*  [Bifocals](https://www.food4rhino.com/app/bifocals)
*  [AutoAnnotate.py](https://gist.github.com/yuhan0/3c6ef309ef3205e972ac6eeaed32383c)
*  [Telepathy](https://www.food4rhino.com/app/telepathy)

Don't use goo.
