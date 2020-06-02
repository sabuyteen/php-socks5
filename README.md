# socks5-proxy
Socks5 proxy written in PHP based on [workerman](https://github.com/walkor/Workerman). Now with username/password authentication according to RFC 1929.
รัน Default เป็น No-AUTH ที่ Port: 10800 
**ติดตั้ง PHP กับ COMPOSER ก่อน***

sudo apt install php libapache2-mod-php php-mysql composer -y

## Install
1. ```git clone https://github.com/sabuyteen/php-socks5```

2. ```composer install```

## Config
Edit file ```config.php```

## Start
```php start.php start -d```

## Stop
```php start.php stop```

## Status
```php start.php status```

## Other links
https://github.com/walkor/shadowsocks-php  
https://github.com/walkor/php-http-proxy
