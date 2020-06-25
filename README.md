# xlabel
* This only works for systems that are using the **X window system**. (most linux distributions and *BSD systems).
## What
Label any window, and then find it or cycle through windows with the same label.

## Usage
To get help for the ``xlabel`` command, type ``xlabel -h`` in your terminal.

* You can only have **one** label for eachy window.


## Installation
* Make sure you have xdotool installed.
* It's just a shell script, so just download it, make it executable and run it.

## Why
I needed a way to quickly switch between windows of the same application, but it may be used for other use cases too.

### Why don't you use the window's title for that?
Because two windows can both have the same or similar title, but not belong to the same application.

### Why don't you use the window's class name for that?
That works fine for graphical applications, but it doesn't work for terminal applications.
