# RetroDSPi
The Raspberry Pi is a fun hobby project that has been around for over a decade <sup><a href="#source1">[1]</a></sup>. Selling more than 40 million units and having a market share of 1 billion dollars plus <sup><a href="#source1">[1]</a></sup>. This shouldn't come as a surprise when developers started to wonder what the limits are of this tiny device. Thanks to the introduction of the Raspberry Pi Zero 2 W, pushing the limits of the Raspberry Pi boards went much further than before. This small board is powered by a 64-bit quad-core Arm Cortex-A53 CPU clocking at 1GHz with 512MB of LPDDR2 SDRAM, and integrated wifi/bluetooth communications. <br> 
All of these fancy specs allow the Raspberry Pi Zero 2 w to perform some impressive tasks. Over the past few years, I have slowly been tinkering with retro games and building an emulator, however, I never had the chance to fully develop a prototype for a handheld system that I could use on the go. The first thing I wanted to start with was an outline of what I wanted:
#### The Outline
1. Portable
2. Fits comfortably in the hands
3. Lasts longer than an hour on one battery
4. Can play Nintendo DS games
5. Ideally, can play Nintendo Wii games (This didn't happen in the current version)
6. Cheap and easily replicable

## The Plan
As with most projects, this first began with specing parts and making sure that they would be compatible. I began with the board: <br> <a href="https://www.adafruit.com/product/5291" style="text-align: center;">Raspberry Pi Zero 2 w</a> <br>
Next, I needed an OS to power the board, I went with <a>RetroPie</a> as I had prior knowledge and experience working with it. <br>
This left the final bits of the hardware to tackle, the battery, screen, buttons, and the joystick. <br>
The screen is a standard SPI interface thats connects to the Pi Zero using the GPIO pins. I got a similar one to <a href="https://www.aliexpress.us/item/3256805561097205.html?spm=a2g0o.productlist.main.4.31c2G23VG23VjF&algo_pvid=60fc123f-304b-4759-9b69-bbde1714b200&algo_exp_id=60fc123f-304b-4759-9b69-bbde1714b200-3&pdp_ext_f=%7B%22order%22%3A%22425%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%217.32%215.49%21%21%217.32%215.49%21%40210327ef17851874661901240e0e50%2112000048092178994%21sea%21US%216100465143%21X%211%210%21n_tag%3A-29919%3Bd%3Ad9b6d60c%3Bm03_new_user%3A-29895&curPageLogUid=vfuWQXgOcnN0&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005747411957%7C_p_origin_prod%3A">this screen</a> from Aliexpress for around $11 at the time, but price changes may have occurred since I purchased mine. The buttons are the usual tactile switch buttons similar to <a href="https://www.adafruit.com/product/1490">these.</a> <br>
While the screen and buttons can connect to the Pi board, the wires get crowded and tangled,

### Sources
1. <a href="https://www.cam.ac.uk/stories/raspberrypi">The life of Pi: Ten years of Raspberry Pi</a>
2. <a href="https://pip-assets.raspberrypi.com/categories/584-raspberry-pi-zero-2-w/documents/RP-008359-DS-1-raspberry-pi-zero-2-w-product-brief.pdf" id="source2">Raspberry Pi Zero 2 W [DataSheet]</a>


