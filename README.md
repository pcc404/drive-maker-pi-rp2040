# drive for maker pi RP2040
this is a drive library for the maker pi rp2040 by cytron.

## documentation
because there's nothing worse than not knowing how to use your python library

### installation
to use this library, you need to do the following:

1. download `drive.py`
1. In thonny, enable "show hidden files"
1. open the file in thonny
2. go to File > Save As
3. select "raspberry pi pico" or "RP2040"
4. save the file to the "lib" directory as "drive.py"

### getting started
this is a quick and simple test program:
```
import drive
drive.forward(2)
```
your robot should drive forward when you run this program

### parameters and commands
so far, this library includes the following commands:  
`init()`  
`stop()`  
`forward()`  
`backward()`  
`leftslow()`  
`leftfast()`  
`rightslow()`  
`leftslow()`  
For the commands `leftslow()`, `leftfast()`, `rightslow()`, and `rightfast()`, you have  speed and duration as the parameters. use them like this: `leftslow(speed, duration)`

For `forward()` and `backward()`, you only have speed

And for `init()` and `stop()`, you have none.
