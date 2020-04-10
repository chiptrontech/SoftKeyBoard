# SoftKeyBoard
SoftKeyBoard - WiredGTK plugin

Paste this folder to newwiredGTK\plugin and restart WiredGTK (if already running)

Create a new GTKapp in WiredGTK, place SoftKeyBoard and a couple of Entry widget or TexView widget.
Run the python script. Highlight desired Entry widget before pressing any key in SoftKeyBoard.

If you need to trap keys within your code, double click SoftKeyBoard in your form and select keypress or keyrelease
add print(key) inside that events. make sure WithEvents properties in SoftKeyBoard is set to True. if WithEvents is set to True
redirection of keypressed to any Entry or TextView Widget will be Disabled
