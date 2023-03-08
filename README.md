# Some things that I have added for my custom .vimrc
* allow editing of a file as superuser when not first run as superuser
    :w!!
* enter a shebang when typing <_sh> in insert mode.
* tweaks to how .txt and .md files are interacted with
* autosaves the file once every 60 seconds (vim-autosave)
* returns to last editable position when re-opening files
* persistant undo history between vim sessions (Super awesome to have as you will be able to undo even after you save and exit a file.)
    * uses a larger buffer to allow for more undo levels
* creates a swap directory where versions of the edited files will be located. 
* backs up files with meaningful names, ex: filename@2023-01-04.14:59
* overwrites the original backup copy but makes a backup before overwriting the current buffer.

# Vim reminder commands
:r !date -> `Wed Mar  8 10:50:58 AM CST 2023`
:_sh -> `#!/bin/bash`

:e [file] -> `Opens a file, where [file] is the name of the file you want opened`
:w -> `Saves the file you are working on`
:w [filename] -> `Allows you to save your file with the name you've defined`

#### Vim command for working with multiple files

:bn - Switch to next buffer 
:bp - Switch to previous buffer 
:bd - Close a buffer 
:sp [filename] - Opens a new file and splits your screen horizontally to show more than one buffer 
:vsp [filename] - Opens a new file and splits your screen vertically to show more than one buffer 
:ls - Lists all open buffers 
Ctrl + ws - Split windows horizontally 
Ctrl + wv - Split windows vertically
Ctrl + ww - Switch between windows 
Ctrl + wq - Quit a window 
Ctrl + wh - Moves your cursor to the window to the left 
Ctrl + wl - Moves your cursor to the window to the right 
Ctrl + wj - Moves your cursor to the window below the one you're in 
Ctrl + wk - Moves your cursor to the window above the one you're in

# Plugins

### goyo - Distraction-free writing tool that sets the writing dimensions suitable for non-technical and non-programming contexts.

* Turn on - :Goyo
* Turn off - :Goyo!

### limelight - Allows you to focus and highlight blocks of text and content dynamically, usually for writing oriented environments.

* Turn on - :Limelight
* Turn off - :Limelight (same)

### supertab - SuperTab is an auto-completion plugin that allows extra insert mode completion using the key. After typing a few letters of a word that exists withina current open buffer (vim session) SuperTab will list the auto-completion options. 

### lightline - Shows: 
1. which mode you are in
2. file name
3. type of file
4. word count
5. number of lines and which line you are currently on. 

### vim-markdown - Automatically sets up certain parameters for markdown content when a .md file is created or edited. 

### vim-sensible - Vim settings that we can all agree on. 

### vim-vividchalk - A particular theme I fancy. 
