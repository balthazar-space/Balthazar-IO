# balthazar
open-hardware laptop computer modules
These are electronic schematic modules as presented at https://balthazar.space/wiki/Balthazar with the main aim for team access
KiCad 5.1.5 files

# balthazarIO

module BalthazarIO is a simple USB2.0 four-port hub for the internal devices: keyboard and touchpad, webcam and optional audiocard.

IO-board basically means connectivity with peripheral devices. These can be seen as on-board and out-board. On-board devices here include: keyboard + trackpad, webcam and optional audio-card. 

Since we are targeting the mini-computer family of systems (Raspberry PI. Banana PI, Orange PI, ...) - USB is the usual solution for this. 

A simple usb 2.0 hub is enough. Main mini-computer board usually provides a much better hub for 4 downstream usb devices. At this point this is still mainly USB 2.0. 

Some type of mass storage / system disk would be needed: microSD – and especially versions of SSD (sata or pcie) – directly or via usb adapter. This would benefit a faster usb port – USB3.x (part of the mini-computer system-on-chip) – or PCIE bus.  
