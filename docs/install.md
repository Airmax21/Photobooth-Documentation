# Installation DSLRBooth Automation

## Requirements
* `Windows 10 1903 or Latest`
* `WSL 2.0`
* `Python 3.12 or Latest`
* `Redis Server`
* `SQLite`
* `Python Dependencies`

## Configuration
Konfigurasi pada aplikasi berada file environtment pada rvn_backend/.env

Contoh dari konfigurasi:
    
    DEBUG = True

    REDIS_URL = redis://10.10.10.105:6379/0

    DSLRBOOTH_DIR = C:\Program Files\dslrBooth\dslrBooth.exe
    CHROME_DIR = C:\Program Files\Google\Chrome\Application\chrome.exe

    MIDTRANS_SERVER_KEY = server_key
    MIDTRANS_CLIENT_KEY = client_key

    TRANSACTION_PATTERN = Transaction-
    PRODUCT_PRICE = 25000

## Running App
Untuk melakukan running pada aplikasi ada beberapa step yang dilakukan sebagai berikut.

1. Buka aplikasi DSLRBooth
2. Pilih Event dari DSLRBooth
3. Run App.bat pada direktori aplikasi