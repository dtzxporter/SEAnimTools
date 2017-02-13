# SEAToolsMaya (v1.4.9)
A .SE format import / export plugin for maya (2012+)

## Installation:
Download the latest [seanim.py](https://raw.githubusercontent.com/dtzxporter/SEATools/master/seanim.py) and [SEAToolsPlugin.py](https://raw.githubusercontent.com/dtzxporter/SEATools/master/SEAToolsPlugin.py) from the repo and save them in `Documents\maya\<mayaversion\scripts`

If you have a usersetup.mel edit it and put `python("import SEAToolsPlugin");` on it's own line, otherwise create this file and add the line to it. Close and reopen maya to see the new SEA Tools menu.

## Updating:
Replace the files in the `Documents\maya\<mayaversion\scripts` folder with the new ones AND delete all of the `.pyc` files. Go to SEA Tools->Reload Plugin to finish.
