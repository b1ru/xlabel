# xlabel
* This only works for **Linux** systems that are using the **X window system**.
## What
Label any window, and then find it or cycle through windows with the same label.

## Usage
Two tools are provided:
* (TODO) ``xlabel``       (command line)
* (TODO)``xlabel-gui``

Both offer the same functionality but since ``xlabel`` is a command line tool, it can be used in scripting.

The ''xlabel-gui'' is self-explanatory.

To get help for the ``xlabel`` command, type ``xlabel -h`` in your terminal.

* You can only have **one** label for eachy window.


## Installation
... TODO

## Why
I needed a way to quickly switch between windows of the same application, but it may be used for other use cases too.

### Why don't you use the window's title for that?
Because two windows can both have the same or similar title, but not belong to the same application.

### Why don't you use the window's class name for that?
That works fine for graphical applications, but it doesn't work for terminal applications.

### My use case
One terminal application that I wanted this functionality for is vim. 

I want a key binding to quickly open or switch to -if it's already open- to vim.

Also if have many instances of vim open, I want to cycle through them when I press the same keybinding.

This is accomplished this way:

... TODO
