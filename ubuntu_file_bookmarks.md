# Add/Remove bookmarks(linux file manager sidebar)

## Add bookmarks  
In `~/.config/gtk-3.0/bookmarks` (full path: `/home/$USER/.config/gtk-3.0/bookmarks`), add  
	- Format : `file:///(path to file) (name of bookmark)`  
	- Example: `file:///media/devilsu/M`  
This will have bookmark name M.  

## Remove bookmarks
1. Goto /home/$USER/.config
2. Create a file name user-dirs.conf
3. Type "enabled=false" in it
4. Under the same ".config" folder, open file "user-dirs.dirs"
5. Comment the directories you don't want (add # at the beginning of the line)
