# TweakScale Companion :: Universal Storage

Adds (up to date) TweakScale /L patches for Universal Storage I & II.


## Installation Instructions

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
	+ Delete `<KSP_ROOT>/GameData/TweakScaleCompanion/US`
* Extract the package's `GameData/` folder into your KSP's as follows:
	+ `<PACKAGE>/GameData/TweakScaleCompanion/US` --> `<KSP_ROOT>/GameData/TweakScaleCompanion`
		- Overwrite any preexisting file.

The following file layout must be present after installation:

```
<KSP_ROOT>
	[GameData]
		[TweakScale]
			[Plugins]
				KSPe.Light.TweakScale.dll
				Scale.dll
			[patches]
				...
			CHANGE_LOG.md
			DefaultScales.cfg
			Examples.cfg
			LICENSE
			NOTICE
			README.md
			ScaleExponents.cfg
			TweakScale.version
			documentation.txt
		999_Scale_Redist.dll
		ModuleManager.dll
		...
		[TweakScaleCompanion]
			[...]
			[US]
				CHANGE_LOG.md
				LICENSE*
				NOTICE
				README.md
				[patches]
					...
			[...]
	KSP.log
	PastDatabase.cfg
	...
```


### Dependencies

* TweakScale /L 2.4.4 or later
	+ **NOT** included
* Universal Storage (if available for your KSP version)
	+ **NOT** included 
* Universal Storage II (if available for your KSP version)
	+ **NOT** included 
* Module Manager 3.1.1 or later
	+ **NOT** included
