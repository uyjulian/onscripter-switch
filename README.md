# ONScripter for Nintendo Switch

ONScripter has been ported to the Nintendo Switch.  
SDL2 build fixes from https://bitbucket.org/jh10001/onscripter-jh are included in this repository.  

## Building

After installing the preresiqute libraries from `dkp-pacman`, a simple `make` will generate `onscripter-switch.nro`.

## RomFS Integration

To integrate the game into one single `nro` file, uncomment line 45 of `Makefile`, place game files in a directory named `romfs`, and build as described in the "Building" section.

## License

This project is licensed under the GPL version 2. Please read the `COPYING` file for more information.

