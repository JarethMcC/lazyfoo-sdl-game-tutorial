#Copyright Notice:
#The files within this zip file are copyrighted by Lazy Foo' Productions (2004-2024)
#and may not be redistributed without written permission.

#SRCS specifies which files to compile as part of the project
SRCS = 05_optimized_surface_loading_and_soft_stretching.cpp

#CC specifies which compiler we're using
CC = g++

#COMPILER_FLAGS specifies the additional compilation options we're using
# -w suppresses all warnings
# -std=c++11 ensures we are using C++11
COMPILER_FLAGS = -w -std=c++11 -IC:/Users/jaret/Documents/Code/SDL2-2.32.8/x86_64-w64-mingw32/include/SDL2

#LINKER_FLAGS specifies the libraries we're linking against
LINKER_FLAGS = -LC:/Users/jaret/Documents/Code/SDL2-2.32.8/x86_64-w64-mingw32/lib -lmingw32 -lSDL2main -lSDL2 -mwindows

#OBJ_NAME specifies the name of our exectuable
OBJ_NAME = 05_optimized_surface_loading_and_soft_stretching.exe

#This is the target that compiles our executable
all : $(SRCS)
	$(CC) $(SRCS) $(COMPILER_FLAGS) $(LINKER_FLAGS) -o $(OBJ_NAME)

clean:
	del $(OBJ_NAME)