# tpRenamer

Renamer Tool to easily rename DCC objects in a visual way

## Dependencies
* **tpPyUtils**: https://github.com/tpoveda/tpPyUtils
* **tpDccLib**: https://github.com/tpoveda/tpDccLib
* **tpQtLib**: https://github.com/tpoveda/tpQtLib

Depending on the DCC you are going to use you will need to download and install one of the following repositories:
* **3ds Max**: https://github.com/tpoveda/tpMaxLib
* **Maya**: https://github.com/tpoveda/tpMayaLib
* **Houdini**: *Work in Progress*
* **Nuke**: *Work in Progress*
* **Blender**: *Work in Progress*

To use the auto rename feature you will need to clone/download and install following the instructions tpNameIt module:
* **tpNameIt**: https://github.com/tpoveda/tpNameIt

## Installation
### Manual
1. Clone/Download tpRenamer dependencies Python packages and follow instructions to install them.
2. Clone/Download tpRenamer anywhere in your PC (If you download the repo, you will need to extract
the contents of the .zip file).
3. Copy **tpRenamer** folder located inside **source** folder in a path added to **sys.path**

### Automatic
Automatic installation for tpRenamer is not finished yet.

## Usage

### Initialization Code
```python
import tpPyUtils
tpPyUtils.init()

import tpDccLib
tpDccLib.init()

import tpQtLib
tpQtLib.init()

import tpRenamer
tpRenamer.run()
```

