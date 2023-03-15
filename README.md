# lab5_202001099

Project repository link that has been used: https://github.com/Python-World/python-mini-projects

Steps:
First we download pylint on our computer by opening the command prompt and typing “pip install pylint”.
Then we download any project from github.
We then track up to the file in our computer where we downloaded the project.
Then we type “py -m pylint projectName.py”.

Project Alaram clock

C:\Users\student\Downloads\python-mini-projects-master\python-mini-projects-master\projects\Alarm clock>py -m pylint alarm_clock.py
************* Module alarm_clock
alarm_clock.py:16:0: W0311: Bad indentation. Found 1 spaces, expected 4 (bad-indentation)
alarm_clock.py:17:0: W0311: Bad indentation. Found 1 spaces, expected 4 (bad-indentation)
alarm_clock.py:21:0: W0311: Bad indentation. Found 1 spaces, expected 4 (bad-indentation)
alarm_clock.py:23:0: W0311: Bad indentation. Found 2 spaces, expected 8 (bad-indentation)
alarm_clock.py:26:0: W0311: Bad indentation. Found 2 spaces, expected 8 (bad-indentation)
alarm_clock.py:29:0: W0311: Bad indentation. Found 2 spaces, expected 8 (bad-indentation)
alarm_clock.py:30:0: W0311: Bad indentation. Found 2 spaces, expected 8 (bad-indentation)
alarm_clock.py:33:0: W0311: Bad indentation. Found 2 spaces, expected 8 (bad-indentation)
alarm_clock.py:34:0: W0311: Bad indentation. Found 3 spaces, expected 12 (bad-indentation)
alarm_clock.py:36:0: W0311: Bad indentation. Found 3 spaces, expected 12 (bad-indentation)
alarm_clock.py:40:0: C0325: Unnecessary parens after '=' keyword (superfluous-parens)
alarm_clock.py:1:0: C0114: Missing module docstring (missing-module-docstring)
alarm_clock.py:6:0: W0622: Redefining built-in 'enumerate' (redefined-builtin)
alarm_clock.py:2:0: W0401: Wildcard import tkinter (wildcard-import)
alarm_clock.py:6:0: W0401: Wildcard import threading (wildcard-import)
alarm_clock.py:15:0: C0116: Missing function or method docstring (missing-function-docstring)
alarm_clock.py:15:0: C0103: Function name "Threading" doesn't conform to snake_case naming style (invalid-name)
alarm_clock.py:16:1: C0103: Variable name "t1" doesn't conform to snake_case naming style (invalid-name)
alarm_clock.py:19:0: C0116: Missing function or method docstring (missing-function-docstring)
alarm_clock.py:2:0: W0614: Unused import(s) enum, sys, types, TclError, re, wantobjects, TkVersion, TclVersion, READABLE, WRITABLE, EXCEPTION, EventType, Event, NoDefaultRoot, Variable, IntVar, DoubleVar, BooleanVar, mainloop, getint, getdouble, getboolean, Misc, CallWrapper, XView, YView, Wm, Tcl, Pack, Place, Grid, BaseWidget, Widget, Toplevel, Canvas, Checkbutton, Entry, Listbox, Menu, Menubutton, Message, Radiobutton, Scale, Scrollbar, Text, Image, PhotoImage, BitmapImage, image_names, image_types, Spinbox, LabelFrame, PanedWindow, NO, FALSE, OFF, YES, TRUE, ON, N, S, W, E, NW, SW, NE, SE, NS, EW, NSEW, CENTER, NONE, X, Y, BOTH, TOP, RIGHT, BOTTOM, RAISED, SUNKEN, FLAT, RIDGE, GROOVE, SOLID, HORIZONTAL, VERTICAL, NUMERIC, CHAR, WORD, BASELINE, INSIDE, OUTSIDE, SEL, SEL_FIRST, SEL_LAST, END, INSERT, CURRENT, ANCHOR, ALL, NORMAL, DISABLED, ACTIVE, HIDDEN, CASCADE, CHECKBUTTON, COMMAND, RADIOBUTTON, SEPARATOR, SINGLE, BROWSE, MULTIPLE, EXTENDED, DOTBOX, UNDERLINE, PIESLICE, CHORD, ARC, FIRST, LAST, BUTT, PROJECTING, ROUND, BEVEL, MITER, MOVETO, SCROLL, UNITS and PAGES from wildcard import of tkinter (unused-wildcard-import)
alarm_clock.py:6:0: W0614: Unused import(s) functools, get_ident, get_native_id, ThreadError, TIMEOUT_MAX, setprofile, getprofile, settrace, gettrace, Lock, RLock, Condition, Semaphore, BoundedSemaphore, Barrier, BrokenBarrierError, ExceptHookArgs, excepthook, Timer, current_thread, currentThread, active_count, activeCount, enumerate, main_thread, WeakSet, namedtuple, stack_size, local and lock from wildcard import of threading (unused-wildcard-import)

------------------------------------------------------------------
Your code has been rated at 4.75/10 (previous run: 4.75/10, +0.00)


Project Ascii_art

C:\Users\student\Downloads\python-mini-projects-master\python-mini-projects-master\projects\Ascii_art>py -m pylint make_art.py
************* Module make_art
make_art.py:27:31: C0303: Trailing whitespace (trailing-whitespace)
make_art.py:1:0: C0114: Missing module docstring (missing-module-docstring)
make_art.py:3:0: E0401: Unable to import 'cv2' (import-error)
make_art.py:4:0: E0401: Unable to import 'numpy' (import-error)
make_art.py:15:12: C0103: Variable name "e" doesn't conform to snake_case naming style (invalid-name)
make_art.py:21:17: W0621: Redefining name 'image' from outer scope (line 51) (redefined-outer-name)
make_art.py:45:8: C0103: Constant name "image_path" doesn't conform to UPPER_CASE naming style (invalid-name)
make_art.py:48:14: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)
make_art.py:49:8: C0103: Constant name "image_path" doesn't conform to UPPER_CASE naming style (invalid-name)
make_art.py:6:0: C0411: standard import "import sys" should be placed before "import cv2" (wrong-import-order)

-----------------------------------
Your code has been rated at 3.79/10

Project ChatBot 

C:\Users\student\Downloads\python-mini-projects-master\python-mini-projects-master\projects>cd chatbot

C:\Users\student\Downloads\python-mini-projects-master\python-mini-projects-master\projects\chatbot>py -m pylint bot.py
************* Module bot
bot.py:5:0: E0401: Unable to import 'wechaty_puppet' (import-error)
bot.py:6:0: E0401: Unable to import 'wechaty' (import-error)
bot.py:190:8: C0103: Variable name "MAX_ROOM_MEMBER_COUNT" doesn't conform to snake_case naming style (invalid-name)
bot.py:214:27: W0613: Unused argument 'inviter' (unused-argument)
bot.py:214:45: W0613: Unused argument 'date' (unused-argument)

-----------------------------------
Your code has been rated at 9.02/10

Project Digial clock


C:\Users\student\Downloads\python-mini-projects-master\python-mini-projects-master\projects>cd Digital_clock

C:\Users\student\Downloads\python-mini-projects-master\python-mini-projects-master\projects\Digital_clock>py -m pylint digital_clock.py
************* Module digital_clock
digital_clock.py:1:0: C0114: Missing module docstring (missing-module-docstring)
digital_clock.py:5:0: C0116: Missing function or method docstring (missing-function-docstring)
digital_clock.py:6:4: W0621: Redefining name 'frame' from outer scope (line 38) (redefined-outer-name)
digital_clock.py:12:4: W0621: Redefining name 'time' from outer scope (line 44) (redefined-outer-name)
digital_clock.py:19:0: C0116: Missing function or method docstring (missing-function-docstring)
digital_clock.py:20:4: W0621: Redefining name 'frame' from outer scope (line 38) (redefined-outer-name)
digital_clock.py:26:4: W0621: Redefining name 'time' from outer scope (line 44) (redefined-outer-name)
digital_clock.py:44:0: C0116: Missing function or method docstring (missing-function-docstring)

-----------------------------------
Your code has been rated at 8.10/10


