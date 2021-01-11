# Tutorial for SF2DLIB

## Introduction

The  sf2dlib is a simple abstraction layer over citro3d with extra functions over citro3d to make displaying simple shapes and 2d sprites easy.

## Usage
### Preparation
You need clone and build the library:
1. Clone the library
2. In the directory sf2dlib/libsf2d/ run:
    ```
    make
    make install
    ```

### LIBS in make file
* You need to add the LIBS variable the ```-lsf2d```.
* If  you get LD errors check the dependencies also added in the rigth order (for example: ```LIBS	:= -lsf2d -lcitro3d -lctru -lm``` )

### Adding to include
* You should add it to the include section in your code: ```#include <sf2d.h>```

## Examining the sample file

Sample 3dsx available from [here](https://github.com/vargaviktor/sf2dlib/tree/master/sample) for test runs.

```c
int main()
{
	// Set the random seed based on the time
	srand(time(NULL));
```
