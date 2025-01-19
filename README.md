# slink
blink for SSI, includes I2C scanner and runs on debugger using the Raspberry Pi extension in Visual Code

you can see the output by running
screen /dev/ttyACM0 115200

It will output a dot each time it blinks the LED, and it will output an @ symbol at addresses the scan finds a device on the I2C.
