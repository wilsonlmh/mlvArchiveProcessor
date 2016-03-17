# mlvArchiveProcessor
Implement MLV Dump, GUI MLV RAW copying&amp;compression in a click

##Features
 - Lossless compression
 - Fast compression
 - Easy&friendly

##Installation
- Install `MLV Dump` (CompressMLV.dmg in https://bitbucket.org/dmilligan/mlvfs/downloads)
- Install this app(`mlvArchiveProcessor`) workflow in OS X

##Usage
 - Right click any folder (contains MLVs) -> `Services` -> `MLV Archive Processor`
 - Select destnation folder and waiting for processing
 - No worry, it will scan for any subfolers and create same folder structure into destnation
 
 
##Extra usage
The `mlvProcessor` inside `Contents` folder is the soul of this app. You can simply call it via

    ./mlvProcessor <path to folder contains MLVs>

You can also config the bit depth and arguments passed to `mlv_dump`(CompressMLV.dmg). Take a look of the first few lines.
