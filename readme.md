# fceux-Lite 

This is a 'Lite' variant of fceux intended for real-time modifications of games through lua. It removes some lua's potentially dangerous commands, making it safer for consumers when developers wish to compile into luac instead of using a traditional lua file.

This version removes the os commands from lua, making lua files unable to execute outside programs. However, it leaves the 'io' class and all other classes intact. While this allows developers to read and save from files, it also allows them to write to anywhere on the PC.

All previous fceux lua scripts should be compatible with this one at the time of this writing, provided they don't use the above class(es).

Other classes may be removed in the future depending on whether they can be considered dangerous to the user's computer. If you feel there's a class that should be removed, submit a pull request!

This fork of fceux is not endorsed by the developers the original fceux. Please support the official release!

## Builds and Releases

FCEUX-Lite is still in development.
