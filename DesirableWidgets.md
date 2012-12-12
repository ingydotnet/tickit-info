# Desirable Widgets

This document contains a collection of solid widgets found in various
terminal apps. These should be represented in Tickit.

Most of these examples are taken from Elinks and Finch, which are
fairly polished terminal apps.

## Menu Bar Widget

Menubar is a horizontal line with a set of drop down menus. Each menu
item has associated shortcut keys and menu selecting keys. They have
grouping borders. Should be able to specify from a simple data
structure.

Mouse, mousewheel, arrow keys, enter and escape should all DTRT.

From Elinks:

![Menubar](https://raw.github.com/ingydotnet/tickit-widgets-todo/master/image/menubar.png)

## Draggable Windows

Finch (with its mouse support turned on) has draggable chat windows. By clicking and holding the title bar of a box, then moving the mouse and releasing, then box will move to where you want (but not outside its parent box).

The finch dragging does not show the animation during dragging, which feels a bit clunky.

![Draggable Windows](https://raw.github.com/ingydotnet/tickit-widgets-todo/master/image/draggable-windows.png)

## Window Overlap

Boxes should be able to be positioned so that they overlap another
box. The top box should hide the bottom box only by the geometry of
the top one.

From Finch:

![Window Overlap](https://raw.github.com/ingydotnet/tickit-widgets-todo/master/image/window-overlap.png)

## Confirmation Dialog

This is a Yes/No or OK/Cancel interface to some statement or question.
It is modal and displays in the center of the screen.

From Elinks:

![Confirmation Dialog](https://raw.github.com/ingydotnet/tickit-widgets-todo/master/image/confirmation-dialog.png)

## Login Dialog

This is another popup dialog that prompts for a user id and a
password. The password text shows up as \*\*\*\*\*.

From Elinks and pause.org:

![Login Dialog](https://raw.github.com/ingydotnet/tickit-widgets-todo/master/image/login-dialog.png)

