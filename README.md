Brackets Bookmarks Extension
============================

This Extension provides functionality to bookmark lines in [Brackets](https://github.com/adobe/brackets).  

`Navigate > Toggle Bookmark` or press ⇧⌘K (`Ctrl+Shift+K` on Windows)

And recall those bookmarks later

`Navigate > Next Bookmark` or press ⌘P (`Ctrl+P` on Windows)

`Navigate > Previous Bookmark` or press ⇧⌘P (`Ctrl+Shift+P` on Windows)

Bookmarks are serialized and remembered globally. Add bookmarks to a file, close the file, reopen the file. Brackets will restore the bookmarks. Bookmarks are represented with a color and a bookmark icon.

Bookmarked lines with Live Editing Syntax Errors will show using a different color

 `View > Show Bookmarks Panel` To see all bookmarks of open files (open, temporary views and views of files in the working set which may not have been open yet) 



##TODO
1. Localize. I've set this extension up for localization so please contribute pull requests to translate this extension
1. Sync bookmarks if files are changed externally... Use a hash of the line maybe?
1. Better Bookmark Affordance (@larz0) especially when bookmarking lines in files with more than 999 lines since the bookmark UI encroaches on the line number
1. Bookmark UI when line numbers are turned off 
