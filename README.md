# [AnimeBTDownloader](https://github.com/blake31113/AnimeBTDownloader)

Animation BT Downloader

## Contents
 - [Get Start](#get-start)
 - [What's included](#whats-included)
 - [How to use](#whats-included)
 

## Get Start

####1.[install JRE](http://java.com/zh_TW/download/)

####2.Check if Java can run:

    $ java -version
    
If can run like as follows, it works.

    
```
java version "1.7.0_45"
Java(TM) SE Runtime Environment (build 1.7.0_45-b18)
Java HotSpot(TM) 64-Bit Server VM (build 24.45-b08, mixed mode)
```
If Java is acutually installed, but cannot use `$java ` to run, continue to follow the steps 


####3.[Download the latest release Animation BT Downloader](https://github.com/blake31113/AnimeBTDownloader/raw/master/AnimeBTDownloader_ver1.0.0.zip)

####4.Use command line to execute:

    $ java -Dfile.encoding=UTF-8 -jar AnimeBTDownloader.jar

If don't use command line to execute, lots of garbled text will come out!

#####If Java installed but cannot use `$java ` to run, try to find where Java installed and use command line to execute:

    $ "C:\Program Files\Java\jre7\bin\java" -Dfile.encoding=UTF-8 -jar AnimeBTDownloader.jar

p.s. my java is installed in `"C:\Program Files\Java\jre7\bin\"`

### What's included
Within the download you'll find the following directories and files like this:

```
/
├── config/
│   ├── AnimeList.txt       (for recording animation lists captured from dmhy)
│   ├── MissionList.txt     (for recording download missions)
│   ├── MoveRule.txt        (for recording moving videos rule)
│   └── Torrentlog.txt      (for recording downloaded torrents)
│
├── torrent/                (for saving the download torrent)
│   
├── AnimeBTDownloader.jar   (the executable file)
│
└── Config.txt              (for setting)
```
## How to use
