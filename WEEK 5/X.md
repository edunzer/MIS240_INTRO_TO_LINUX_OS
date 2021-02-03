## X DISCUSSION POST


explain the purpose of the X Window System
  -X window system is the basic technology that is used in developing graphical user interfaces at a very basic level. X is responsible for drawing out the elements of the GUI on the screen and builds the methods that are responsible for user interaction with the application.

list and describe the components of the X Window System
  -There are multiple layers to make up X Window System. There is the XX library, X toolkit intrinsics, and widget set. The latest version of X Window System includes XINERAMA, easy resource configuration, DPMS power saving, EVI extension.

give some command-line examples one would use to troubleshoot the system
  -display [host]:display[.screen] (This option specifies the X server display to use. This is often used where applications are run on one system, and displayed on another.)
  -geometry geometry (The initial size and location of the window, in a format such as width x height +horz_offset +vert_offset or +horz_offset -vert_offset.)
  -font fontname (The font to use for displaying the text in your window)

think of a reason or two why an administrator may choose not to install the X Window System on their systems
  -The simplest reason not to install the X Window System is because you don't want a graphical interface. So you wouldn't need to install a package that creates a graphical interface.

what is needed to run GUI-only applications on a system that does not have a graphical desktop interface? In other words, can you launch programs from the command line and get a GUI for that program?  How?
  -In order to run certain programs like internet browsers in a non graphical environment you will need to have text based browser. You can also install XDM which is a minimal display manager that will have a similar effect of no graphical interface. 
