AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = hello_world
hello_world_SOURCES = hello_world.c hello_func.c hello_make.h

clean-all:
	GLOBIGNORE=*.c:*.h:*.ac:*.am:*.md:.git; rm -rf *; unset GLOBIGNORE
	rm -f /usr/local/bin/hello_world

