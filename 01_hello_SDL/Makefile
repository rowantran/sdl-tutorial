# Specify which files to compile
OBJS = 01_hello_SDL.cpp

# Specify which compiler we are using
CC = g++

# Specify additional compilation options
# -w suppresses all warnings
COMPILER_FLAGS = -w

# Specify libraries we are linking against
LINKER_FLAGS = -lSDL2

# Name of our executable
OBJ_NAME = 01_hello_SDL

all : $(OBJS)
	$(CC) $(OBJS) $(COMPILER_FLAGS) $(LINKER_FLAGS) -o $(OBJ_NAME)
