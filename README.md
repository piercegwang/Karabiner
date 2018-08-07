# Karabiner

My karabiner config. This is just the collection of complex modifications on karabiner that I use.

## Simple Modifications

None for now

## Complex Modifications:


#### Mouse Keys 

You can operate mouse via keyboard. (motion, click and scroll)
Mouse keys mode is active by the following procedure.

    x key_down
    any keys of mouse keys key_down (h, j, k, l,...)
    any keys of mouse keys key_up (h, j, k, l,...)
    Then mouse keys is active until you release x key.

Example:

    Press x
    Press h
    Press j
    Release h
    Release j
    Release x

Key bindings:

    x: activate mouse keys
    h: mouse left
    j: mouse down
    k: mouse up
    l: mouse right
    b: left click
    n: middle click
    m: right click
    c: fast mode (fast mouse move by f+hjkl)
    v: slow mode (slow mouse move by g+hjkl)
    z: scroll mode (scroll by s+hjkl)

## Version Control

**Version 1.0**
- Just Changed Keybinds for Mouse Keys
  - [x] moved s,d,f,g keys to z,x,c,v

