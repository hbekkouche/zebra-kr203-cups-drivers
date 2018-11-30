# Printer Install

### Building and Installing Zebra 2030 TPP Printer Drivers on the Raspberry PI
```
sudo apt-get install build-essential git gcc cups
```

Since we installed cups above just need to copy the driver for the Zebra kr230 Printer
```
sudo cp filter/rastertozebrakiosk /usr/lib/cups/filter/
```
Restart CUPs
When adding printer in CUPS use the custom ppd file as driver
