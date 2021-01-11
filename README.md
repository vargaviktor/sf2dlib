# SF2DLIB

Simple and Fast 2D library for the Nintendo 3DS (using [citro3d](https://github.com/fincs/citro3d) and [ctrulib](https://github.com/devkitPro/libctru))

## Overview
sf2dlib is now a simple abstraction layer over citro3d with extra functions over citro3d to make displaying simple shapes and 2d sprites easy. As long as you are not drawing millions of shapes/sprites, this library should be able to fit your use case. If you are seeking to squeeze all of the power out of your 3ds and have full control over the GPU then sf2dlib will probably not fit your use case and you should use citro3d instead. Note that there is a small overhead in using sf2dlib over citro3d, but it is negligible as long as you aren't rendering too much in a single frame.

## Special Note for new users.
If you are a new user to 3ds homebrew or starting new code, you would be much better served trying out SDL. 

## Changes
Modified to compile with citro3d 1.4.0 or higher.

## Documentation (original documentation)
http://xerpi.github.io/sf2dlib/html/sf2d_8h.html

## Tutorial (unfinished)
Available from [here](https://github.com/vargaviktor/sf2dlib/blob/master/Tutorial.MD)
