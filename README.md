# My-Makefile

Just a Makefile that I use for simple projects.

### Usage

You can edit this variables for your programs :

```makefile

# Debug mode, can modify CXXFLAGS and LDFLAGS.
DEBUG = yes

SRC_DIR = src
INC_DIR = src
OBJ_DIR = obj
BIN_DIR = bin

# You can add subdirs with any depth like utils/string, utils/math/ ...
SUB_DIRS = utils core

CXX = gcc
CXXFLAGS = -ansi -Wall -Wextra -pedantic
LDFLAGS =
```
