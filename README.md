**Yublin Text Expansion**

Yublin is a shorthand created by Jon Aquino to make it faster to write the most common English words.

You can read more and see what the abbreviations are [here.](https://jonaquino.blogspot.com/2007/06/yublin-shorthand-for-speed-writing.html)

I tried to set up the Yublin shorthand abbreviations in text expansion programs to save a few keystrokes.

For instance, using the below described set-ups, you could type "t" and hit the "TAB" key and it would output "the".

I did this just to test out how it felt.

**Installation**

Linux (in Gedit - Mac Too?):

1. Clone/Download this repo (or just the yublin.xml file).

1. Download and install [Gedit](https://wiki.gnome.org/Apps/Gedit) if you haven't already.

2. Enable Snippets Plugin: Go to File > Preferences > Plugins, and check the box for the "Snippets" Plugin.

(A restart may be required but I don't think so)

3. Now go to File > "Manage Snippets..."

4. Click "Import Snippets" button and then find the yublin.xml file and click "Open", then close that window.

5. You should now be abe to type "t+TAB" anywhere in Gedit and it will expand to "the" for instance (see top link for list of Yublin abbreviations).

(Mac: Note, you should be able to do this with Gedit on Mac in theory, but I was not successful in testing it, however someone might be able to try it again and let me know if it works).

Windows (With AutoHotKey):

1. Clone/Download this repo (or just the yublin.ahk file).

2. Install AutoHotKey (if you haven't already).

3. Right click the "yublin.ahk" file and click "Run Script".

4. You should now be abe to type "t+TAB" anywhere in Gedit and it will expand to "the" for instance (see top link for list of Yublin abbreviations).

**Future**

1. Port to Autokey on Linux so the abbreviations can be used anywhere?

2. Port to some program on Mac so abbreviations can be used anywhere?

**Other**

Let me know if something isn't working and I'll try to look at it! Happy text expanding!
