single assembly language code for RDA5807 family FM tuner controlled with PIC10F200, PIC10F202,  PIC10F204, PIC10F206,  PIC10F220, PIC10F222,PIC12F508, PIC12F509 and PIC12F510 microcontroller. 
EEPROM for storing last used channel and volume information. 
Two buttons for controlling volume and channel.

## PIN ASSIGNMENT FOR PIC10F2XX

sda      EQU GP2  
scl      EQU GP1  
but_up   EQU GP3  
but_down EQU GP0  

## PIN ASSIGNMENT FOR PIC12F5XX

but_up     EQU    GP0    ;Button Volume up/Next station  
but_down   EQU    GP1    ;Button Volume down/Previous station  
scl        EQU    GP4    ;SCL pin of the I²C Bus  
sda        EQU    GP5    ;SDA pin of the I²C Bus  
