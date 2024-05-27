# i2c notes


i2cset command example:

```
i2cset -y  6  0x63 0x08 0x53

-y      Disable interactive mode
6       SMBus adress from 'i2cdetect -l'
0x63    Device address
0x08    Value (Need to be understand)
0x53    Register inside device
```

Understanding values
Set low brightness
value address
0x01 0x20

Set high brightness
value address
0x64 0x20