# Sign Bunny Video Stream CDN

To sign the Stream videos before loading it on your player. Example, on your mobile app player where you cannot embed the Bunny stream code.
### Usage:

```py
url = "https://{CDN}/{VideoID}/playlist.m3u8"
securityKey = "{Your secret key from Security under Stream}"
path_allowed = "/"
url_to_load = sign_bcdn_url(url, securityKey, path_allowed, True)
```

`url_to_load` can be used for 60 minutes.

Things to consider:
![to-consider](https://github.com/karmicdice/bunny-cdn-signing-python/blob/master/to-consider.jpg?raw=true)
