AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = hello_world
hello_world_SOURCES = hello_world.c hello_func.c hello_make.h

clean-all:
	rm -rf autom4te.cache aclocal.m4
	rm -f configure 
	rm -f compile install-sh missing depcomp Makefile.in 
	rm -rf .deps config.log config.status confcache Makefile 
	rm -f hello_func.o hello_world.o hello_world
	rm -f /usr/local/bin/hello_world

