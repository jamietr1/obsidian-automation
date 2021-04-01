# obsidian-automation
A set of scripts to help with automating tasks around the Obsidian text editor

## Daily Notes (obsidian-daily)
This script generates a daily notes file in the format described in [this post](https://www.jamierubin.net/2021/02/08/automating-my-daily-notes-with-obsidian/). An example looks as follows:

![Example](/images/Annotated-Daily-Note.png)

Some configuration notes:

* I use a special version of icalBuddy to get my agenda. See the comment in the code about how to get this version. The regular version works fine if you don't want to run this from an automated job; the special version noted in the comment is required if you do.
* There is a sample .notes file in the repo. This file should be copied to your root folder and the paths updated with wherever you'd like your daily notes to go.
* There is a sample plist file for those who want to try to automate this on your Mac. Update the file for your configuration and preferences.
* The arrow and requests packages are dependencies of this script. You may need to install them via pip other other means if you get errors about these packages being missing

# A note on support
I'm posting this software as-is. It works for me, and a number of folks have requested it and I'm happy to put it here to share it. But I have no time to support it. If I make improvements, I'll try to post them, but there's no guarantee there either. I realize that this may not work perfectly on non-Mac systems, but the whole point of posting the code is to let folks see it, fork it, and roll your own from it. Hopefully it works for you the first time. If not, the code's there for you to mess with.