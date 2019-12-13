**Yublin Text Expansion**

Yublin is a shorthand created by Jon Aquino to make it faster to write the most common English words.

You can read more and see what the abbreviations are [here.](https://jonaquino.blogspot.com/2007/06/yublin-shorthand-for-speed-writing.html)

I tried to set up the Yublin shorthand abbreviations in text expansion programs to save a few keystrokes.

For instance, using the below described set-ups, you could type "t" and hit the "TAB" key and it would output "the".

I did this just to test out how it felt.

**Installation**

Cross-Platform (Linux, Mac, Windows) in Atom Text Editor:

1. Clone/Download this repo (or just the snippets.cson file).

2. Download [Atom Text Editor](https://atom.io/) if you haven't already.

3. Find your ~/.atom folder (it is a hidden folder).

4. Either open the snippets.cson file in that folder and copy and paste the contents of the snippets.cson file from this project (if you have other snippets in your snippets.cson file that you want to keep), or drop the file from this project in to that folder and overwrite the file that is already there (if you don't already have any snippets you need to keep).

5. Optional Note: It shouldn't interfere with the Yublin snippets, but you may want to go to settings and disable some Autocomplete options as you'll see a lot of possible text pop up as you type that you could autocomplete to.

This also only works with plain text files I believe; you can make it work with other ones by changing the first line of the snippets code ('.source.gfm, .comment, .string, .text') to whatever kind of file you are editing. For instance, if you are editing a Javascript file that ends in .js, the code could be changed to ('.source.js'), or you could copy the entire snippets list and paste it again in the same file and change the code (if you want to keep it for multiple kinds of file formats).

This was only tested on Mac but should work in the same (or a similar way) in Linux and Windows.

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

2. Install [AutoHotKey](https://www.autohotkey.com/download/) (if you haven't already).

3. Right click the "yublin.ahk" file and click "Run Script".

4. You should now be abe to type "t+TAB" anywhere in Gedit and it will expand to "the" for instance (see top link for list of Yublin abbreviations).

**Future**

1. Port to Autokey on Linux so the abbreviations can be used anywhere?

**Other**

Let me know if something isn't working and I'll try to look at it! Happy text expanding!
