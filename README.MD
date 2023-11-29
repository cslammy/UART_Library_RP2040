This library abstracts some of the serial functions in the RP2040 C SDK. 

it instantiates a 1K buffer to read incoming an incoming serial stream and then a few functions to modify what is in the buffer and then return of true if what is in the buffer matches an incoming string of a given length.  

The library is more me trying to better understand the Pico C SDK's abstractions by writing my own abstractions on top of the SDK's abstractions. I am not sure others will find it useful, but I am posting it anyway.

See the UART.h file for more detail about functions etc.
