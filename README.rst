music.txt
=========

* Create playlists in a .txt file
* push the playlist to the cloud
* listen to your music

The idea is to have a python script that will interact with various
services. So once you have created at text file you are done.

How it will work
----------------

1. create a music.txt file with a formate like this

::
  
  Alternative Music
    song name - artist
    song name - artist

  Rock Music
    song name - artist
    song name - artist

2. run push-music.py [service]

where service will be a local playlist file such as m3u, wpl, b4s, xspf,
pls, or asx. By generating different types of playlist formats you can
easily switch between different music players. The downside to local
playlists is you must have the music files on your computer.

Alternativly services can also be on the cloud, and so push-music.py can
interact with various API's to generate playlists using online music
players such as grooveshark. The advantage to cloud services is that you
don't always need to have the music localy (particularly usefull when you
have little hard drive space).

more ideas to come!
