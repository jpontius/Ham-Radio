Ham-Radio
=========

Vertex VX-2000 instructions for Linux.

1. Download DosBox. http://www.dosbox.com
2. Inside ~/.dosbox/dosbox-0.74.conf add serial port. serial1=directserial realport:ttyUSB0
3. Also inside ~/.dosbox/dosbox-0.74.conf add drive mount in Autoexec: mount c /home/justin/dos/c
4. place ce20.exe, ce20.cfg,and ce20.hlp in /home/justin/dos/c
5. Program radio as normal.  You should be able to read the radio's current config by pressing f10, then upload to radio.  This is backwards from my thinking.
