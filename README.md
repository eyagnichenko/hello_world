Autotools Setup
---------------
Run the commands.
1. Generate m4 env: `aclocal`
2. Generate 'configure' file: `autoconf`
3. Generate 'Makefile.in' file: `automake --add-missing`

Building
--------
Run the commands.
1. Generate Makefile: `./configure`
2. Compile app: `make`
3. Install app: `sudo make install`

Cleaning
--------
Run the command: `sudo make clean-all`

