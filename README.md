# Advanced-C-files-and-headers-generator
A little tool to create .c and .h files in specified directory
These 2 files contains basic files declaration (no loop include, include .h in .c)

fileName.c
```c
#include "fileName.h"
```

fileName.h
```c
#ifndef fileName__H
#define fileName__H
#include "definitions.h"

#endif

```

![alt text](https://ibb.co/8dHWtCX)

Features:

- List box of each names of files to create
- Buttons add and remove to interact with list
- Folder explorer to select in wich folder create files
- CheckBox to include "definitions.h" in header files
- Button to create files
- Error exceptions and corrections (special characters, empty file name, not enought rights to write, already existing file, deleted folder)

Enjoy it !
