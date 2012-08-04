# colorprintf by VittGam

A simple C / C++ header file to output colored text to ANSI (Linux, iPhone) and Windows terminals.

This function wraps printf (by using vprintf), and adds a 'color' parameter to it.

    color = 0 -> red
            1 -> green
            2 -> yellow
            3 -> blue
            4 -> magenta
            5 -> cyan

## Usage

Just include the header at the beginning of your C / C++ code:

    #include "colorprintf.h"

The syntax is the same as printf, with the added color parameter.

    colorprintf(1, "Welcome!\n");
    colorprintf(5, "i is equal to %d\n", i);
    colorprintf(0, "An unknown error occurred: %s (error code: %d)\n", error_description, error_code);

## License

Copyright (C) 2012 VittGam.net. All Rights Reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

