# set executable name
EXECNAME    = HO1024

# default compiler settings
CC          =  gcc
OPT			= -fopenmp
OPT2        = -O2 
LDFLAGS     = -lm

SRC         = *.c
OBJS        = $*(SRC).o

# compilation for runs
all:
	$(CC) $(OPT) $(OPT2) $(SRC) -o $(EXECNAME) $(LDFLAGS) 
	/bin/rm -rf *.o

# clean up
clean:
	rm -rf *.o $(EXECNAME)

