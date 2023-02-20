# How to setup and run

In the root directory, run

```
composer install
```

To start the server run

```
php -S 127.0.0.1:8000 -t public
```

Your server will start running on `http://127.0.0.1:8000`

To get the list of hotels, hit this the below URL in browser or postman (this will list down the list of hotel only based in Dubai - using AE as countryCode)

```
http://127.0.0.1:8000/hotels
```
