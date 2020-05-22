# balthazar
open-hardware laptop computer modules
These are electronic schematic modules as presented at https://balthazar.space/wiki/Balthazar with the main aim for team access

KiCad 5.1.5 files

# balthazarIO

BalthazarIO module is a simple USB2.0 four-port hub for the internal devices: keyboard and touchpad, webcam and optional audiocard. Additional simplification and pcb size reduction was done recently.

IO-board (here) means connectivity with peripheral devices. These can be seen as on-board and out-board. On-board Balthazar devices include: combined usb1.1 keyboard + trackpad, usb2.0 webcam and optional audio-card. 

Since we are targeting the mini-computer family of systems (Raspberry PI. Banana PI, Orange PI, ...) - USB is the usual solution for this. 

A simple usb 2.0 hub is enough, so a very ubiquitous usb hub chip was chosen. Main mini-computer board usually provides a much better hub for 4 downstream usb devices. At this point this is still mainly USB 2.x - slowly moving to usb3.x.

Mass storage / system disk - microSD – and especially versions of SSD (sata or pcie) – should be plugged to usb3.x directly (via usb adapter).
