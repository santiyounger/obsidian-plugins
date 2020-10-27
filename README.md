# Obsidian-plugins

Small plugins for [Obsidian](https://obsidian.md) note taking tool. These plugins now support official obsidian alpha [plugin api](https://github.com/obsidianmd/obsidian-api).

## Fullscreen mode

`fullscreen.js` adds a command to obsidians command palette, that allows you to expand the current document to full screen focus mode for more distraction free and easier reading. Pressing `Esc` should return obsidian back to the previous layout.

## Windows paths to  markdown links

`windowspaths.js` adds a command to reformat windows paths to working markdown links for example `[licence](windir("C:\Program Files\dotnet\LICENSE.txt"))`) will be formatted to `[licence](file:///C:/Program%20Files/dotnet/LICENSE.txt)` and the link will be clickable in preview mode. This is especially helpful, if you often use the 'Copy as path' Windows feature from file explorer as now your memos can have links to any type of object that is opened by the default application when you click on it.