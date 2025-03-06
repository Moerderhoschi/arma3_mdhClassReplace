mdhClassReplace
replace classnames in sqm,sqf files
made by moerderhoschi
2016.09.17

a simple javaprogram to replace classes in all sqm, sqf, sqs, ext files in the folder and subfolders of the toollocation. Set classnames in the mdhClassReplace.cfg file

i wrote it to replace all the A2 classnames of my arma 2 missions with the CUP ones. So the tool scans all ext, sqs, sqm, sqf files and replace the classnames with the ones set in the mdhClassReplace.cfg.

how does it work:
1. create and write log messages into the mdhClassReplaceLog.txt
2. read the mdhClassReplace.cfg to get the old and new classnames for the replacement
3. check every sqm, sqf, sqs, ext file in the folder and subfolders of the toollocation for the old classnames and replace them with the new one

create a﻿﻿nd write log messages into the mdhClassReplaceLog.txt

read the mdhClassReplace.cfg to get the old and new classnames for the replacement

check every ext, sqs, sqm, sqf file in the fold﻿er a﻿nd subfolders of the toollocation for the old classnames and replace them with the new one

how to use it, example to port A2 mission to A3 with CUP:

download the mdhClassReplace.7z

extract it to an empty folder

put your arma 2 missions into the same folder

doubleklick the mdhClassReplace.jar file

check the mdhClassReplaceLog.txt file to see what the tool has done

copy your arma 2 mission into your arma 3 missions folder and open it in the 3D editor (hopefully it works :D)

attention, use this tool/mdhClassReplace.jar on your own risk

 ![Alt text](http://moerderhoschi.bplaced.net/public/tools/arma3/mdhClassReplace.cfg.png)

 ![Alt text](http://moerderhoschi.bplaced.net/public/tools/arma3/mdhClassReplaceLog.txt.png)
