# PicoTemp
A little and simple project for have a web interface for temperature and humidity 

# Hardware

- Raspberry Pi [Pico W](https://www.raspberrypi.com/products/raspberry-pi-pico/?variant=raspberry-pi-pico-w) (! it's important to be Wirless for the web server);
- DHT11 temp/humid sensor (you can use any sensor, but be carreful to change the library);
- 5V USB Micro B power supply;
- 3 cable;

**OPTIONAL**

- Plastic or 3D printed box (if you can create a .stl file create a commit).

# Software

- [Thonny IDE](https://thonny.org/),
- Latest [UF2](https://micropython.org/download/rp2-pico-w/) bootloader file **(! Pico W only)**, the normal Pico have a different file;
- Sensor [Python Library](https://github.com/ikornaselur/pico-libs/tree/master/src/dht11).

# Process

0. **! ONLY If the Pi is new or with a different bootloader** hold the "BOOTSEL" buttone while connect to a computer and drag the UF2 file;
1. Open Thonny IDE and copy and paste the library then save on the board;
2. Copy and paste the `main.py` and `index.html` then save;
3. Copy and paste the `secrets.py`, **⚠ BEFORE SAVE CHANGE 'SSID' AND 'PW'** then save;
4. Look in the debug setion for the ip adress and open it on a browser.

# Outside
## ⚠⚠ DO AT YOUR RISK, TAKE PRECAUTION FOR NOT BURN THE PI AND ANYTING CONNECTED, PROTECT IT FROM WIND, RAIN AND SNOW ⚠⚠.
For an outside use I had a tasparent plastic box, where I put all the compenets and connected to the power.

# Credits
- [Rasperry Pi Fundation](https://www.raspberrypi.com);
- Thonny IDE;
- [@ikornaselur](https://github.com/ikornaselur/)'s DHT11 MicroPython library.
