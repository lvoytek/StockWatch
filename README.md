# StockWatch

A live stock ticker for the [Adafruit MatrixPortal](https://learn.adafruit.com/adafruit-matrixportal-m4).

##Setup

1. Start by building the MatrixPortal using the instructions given [here](https://learn.adafruit.com/adafruit-matrixportal-m4/prep-the-matrixportal).

2. Next, [install CircuitPython](https://learn.adafruit.com/adafruit-matrixportal-m4/install-circuitpython) on the board.

3. Download this repository and copy it into the CIRCUITPY removable media directory.

4. Add a file called secrets.py with local network SSID and Password in the following format:

```python
secrets = {
    'ssid' : 'NETWORK NAME',
    'password' : 'PASSWORD',
}
```

5. If all is correct the MatrixPortal will automatically reboot and display stock information.
