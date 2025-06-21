![hellij](hellij.png)

# Hellij

Guide that shows you how to configure your IntellIJ IDEA instance as you are driving Helix Editor.

## Features

### IdeaVim

Firstly, you should install IdeaVim plugin to bring in Vim engine to perform vim like
motions, https://github.com/JetBrains/ideavim, if you never tried this style I recommend to give it a try.

#### Installation

Using IDE Plugins menu simply install it by searching `IdeaVim`.

### Helix.vim

Secondly, https://github.com/chtenb/helix.vim, set of helix keybindings that override default behaivor of IdeaVim plugin
and almost make it work as you are
in Helix editor.

#### Installation

Go to https://github.com/chtenb/helix.vim and copy `helix.idea.vim` into IdeaVim configuration file. You can access
configuraiton by clicking on IdeaVim icon in right bottom corner.

## How to build theme

### Prerequisities

- IntellIJ IDEA
- JetBrains JDK 21+

### Build

With use of IDE itself you can build the project by selecting
`Build -> Prepare Plugin Module 'hellij' For Deployment`

### Installation

After the build you can grab the `hellij.jar` file that represents our plugin theme and install it via IDE UI
`File --> Settings --> Plugins --> Install Plugin From Disk...`