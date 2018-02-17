YATCO
=====

Yet Another Tabbed Chat Option - this one blinks

Since 2.5, has been broken into Config and the actual YATCO package.

# To install
## YATCOConfig - install before YATCO 2.5 or later. Only need installing once

```
lua local a="https://raw.githubusercontent.com/demonnic/YATCO/master/YATCOConfig.xml"function d(b,c)if not c:find("YATCOConfig",1,true)then return end installPackage(c)os.remove(c)cecho("<lime_green>Package installed!\n")end registerAnonymousEventHandler("sysDownloadDone","d")downloadFile(getMudletHomeDir()..(a:ends("xml")and"/YATCOConfig.xml"or"/YATCOConfig.zip"),a)
```

## YATCO2.5 (from 2.5 onward make sure YATCOConfig is installed first
```
lua local a="https://raw.githubusercontent.com/demonnic/YATCO/master/YATCO2.5.xml"function d(b,c)if not c:find("YATCO",1,true)then return end installPackage(c)os.remove(c)cecho("<lime_green>Package installed!\n")end registerAnonymousEventHandler("sysDownloadDone","d")downloadFile(getMudletHomeDir()..(a:ends("xml")and"/YATCO.xml"or"/YATCO.zip"),a)
```
