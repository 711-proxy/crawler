# [711Proxy](https://www.711proxy.com/?utm_t=1&utm_i=441)
## What is 711Proxy?
711Proxy is the most cost-effective proxy with more than 100 million IP resources from 200+ countries/regions around the world, which can help you bypass geographic restrictions and get more data information!

Why Choose **[711Proxy](https://www.711proxy.com/?utm_t=1&utm_i=441)**?  
* 99.9% Uptime Guarantee  
* 200+ Global IP Locations  
* 24/7 Professional Support  

## How to use 711Proxy Crawler？
```
import requests

proxies = {
    'http': 'http://username:password@proxy_ip:proxy_port',
    'https': 'http://username:password@proxy_ip:proxy_port'
}

try:
    response = requests.get('http://example.com', proxies=proxies, timeout=10)
    print(response.text)
except requests.exceptions.RequestException as e:
    print(f"Request Failed: {e}")
```
For SOCKS Proxies, you may need to install additional packages such as requests[socks]:
```
pip install requests[socks]
```
Then it can be used like this:
```
proxies = {
    'http': 'socks5://user:pass@host:port',
    "https": "socks5://user:pass@host:port",
}
```
