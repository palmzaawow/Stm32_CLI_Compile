main.c

- gpio output portc 0,3  blink 50 ms
- Pwm porta 0 
- uart6 tx portc 6 rx portc7
- dac porta 4 (0,1241,2482,3723)
- i2c SDA portb 9 SCL portb 6

Setup

install
- git
- Cmake
- MinGW
- gcc -arm -none -eabi toolchain

copy file to folder project target

- CmakeLists  ** change name project file path **
- gcc -arm -none -eabi
- Makefile

CLI command

    'alias make="mingw32-make"'
    'cmake -G "MinGW Makefiles" -B build_mingw .'
    'make -j4'


When the code is edited to be recompiled

    'make clean'
     ** 'make -j8' ** use when change code and save it for new compile
