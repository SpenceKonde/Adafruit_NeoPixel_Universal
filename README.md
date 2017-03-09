# Adafruit NeoPixel Library

Modified by Spence Konde to support port A (as well as ports B, C, D, and F, as with the stock version), at the expense of compile size. 

This repo contains two versions of the library: 

The .h and .cpp files (Adafruit_Neopixel_Universal.*) - this can be installed as a separate library, and will not conflict with the stock version. 

The drop-in version (in the .zip file) - this is the same code, but with the files and class named to match the stock version; to use this, the normal version of the library should be *replaced* with this version. 

In both cases, the examples should work, and were compile tested on a tiny1634 under ATTinyCore (github latest) at 8 and 12mhz. 