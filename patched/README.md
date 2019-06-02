shift to free up RAM

IO_AREA = $F000 -> $FF00 ; set I/O area for this monitor

Ram_top = $C000 -> $D600 ; end of user RAM+1 (set as needed, should be page aligned)
*= $C000 -> $D600 ; This start can be changed to suit your system

user RAM: $0300 - $D600 - 1 = 54015 bytes

![](https://raw.githubusercontent.com/Klapautsiy/6502_EhBASIC_V2.22/master/patched/6502_EhBASIC_V2.22%20free%20RAM.png)
