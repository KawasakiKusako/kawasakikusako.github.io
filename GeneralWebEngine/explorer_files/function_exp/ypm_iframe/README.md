# iframe framework experimental pool

## UA for test
```JavaScript
Mozilla/5.0 (Windows NT 6.1; WOW64; rv:6.0) Gecko/20100101 Firefox/6.0
```
## iframe code
```JavaScript
var __originalNavigator = navigator;
navigator = new Object();
navigator.__defineGetter__('userAgent', function () {
    return 'Custom';
});

var iframe='<iframe id="frame" name="widget" src ="http://www.useragentstring.com/" width="100%" height="400" marginheight="0" marginwidth="0" frameborder="no" scrolling="no"></iframe>';        

document.write("User-agent header sent: " + navigator.userAgent + iframe);
```

```JavaScript
setUserAgent(document.querySelector('iframe').contentWindow, 'MANnDAaR Fake Agent');
```

```html
<!DOCTYPE html>
    <html>
        <head>
        <meta name="referrer" content="no-referrer" />
        </head>
    <body>
        <iframe height='100%' width='100%' src=' URL HRER！' ></iframe>
    </body>
</html>
```

test links

[direct](https://music.hexo.icu)
[iframe](http://www.nmc.cn)
