# StockWatch

A live stock ticker for the [Adafruit MatrixPortal](https://learn.adafruit.com/adafruit-matrixportal-m4).

##Setup

1. Start by building the MatrixPortal using the instructions given [here](https://learn.adafruit.com/adafruit-matrixportal-m4/prep-the-matrixportal).

2. Next, [install CircuitPython](https://learn.adafruit.com/adafruit-matrixportal-m4/install-circuitpython) on the board.

3. Download this repository and copy it into the CIRCUITPY removable media directory.

4. Obtain a stock API key from [Alpha Vantage](https://www.alphavantage.co/) (API key is free and does not require any payment information).

5. Add a file called secrets.py with local network SSID and Password, timezone, and Alpha Vantage API key in the following format:

```python
secrets = {
    'ssid' : 'NETWORK NAME',
    'password' : 'PASSWORD',
    'timezone': 'America/CITY',  # http://worldtimeapi.org/timezones
    "apiKey": "APIKEY"
}
```

5. If all is correct the MatrixPortal will automatically reboot and display stock information.
