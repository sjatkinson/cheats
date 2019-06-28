# cheats

Display and manage your own cheat sheets in the shell.

### Usage
    $ cheats ln      # displays cheat sheet ln
    $ cheats         # lanuch fzf to find a cheat to display
    $ cheats -e ln   # edits cheat sheet 'ln' in $EDITOR
    $ cheats -s term # searchs all cheat sheets and display lines which match term
    $ cheats -l      # lists all the cheat sheets
    $ cheats -h      # displays help

### Installation
    One of the followihg:
      - put cheats/bin/ in your path
      - copy cheats/bin to your path
      - run cheats/install # creates a symlink to ~/src/cheats/bin/cheats

    Create cheat sheets in ~/doc/cheats. You can use sub directories if you want.
    
### Requirements
- $EDITOR must be set to edit a cheat sheet.
- ranger is used to manage cheat sheets.
- fzf - fuzzy finder allows for fuzzy finding of cheat sheets.
- cheats sheets must be located in ~/doc/cheats
- to run the install script you must have a ~/bin directory
- cheat sheets must have a unique name
