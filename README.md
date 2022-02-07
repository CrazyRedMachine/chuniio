[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate?hosted_button_id=WT735CX4UMZ9U)

# chuniio

chuniio.dll implementations for various hardware

## chunitest

`chunitest.exe` is a windows binary which will load chuniio.dll to test its implementation.

## Build instructions

Tested with MinGW, but cmake should be able to generate files for other toolchains.

Go into one of the folders then run the following commands :

```
mkdir build
cd build
cmake .. -G "MinGW Makefiles"
make
```

This will generate both `chuniio.dll` and `chunitest.exe`

## Donation

If this project helps you and you want to give back, you can help me with my future projects.

While not necessary, donations are much appreciated and will only go towards funding future github projects (arcade hardware ain't cheap :( ).

Of course you'll also receive my gratitude and I'll remember you if you post a feature request ;)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate?hosted_button_id=WT735CX4UMZ9U)