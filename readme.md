# FlashCookie.js

JavaScript interface library to manage persistent cross-browser Flash cookies.

## Method

* get(key)
* set(key, value)
* remove(key)
* clear()

## Example

```html
<html>
<head>
    <title>Flash Cookie sample</title>
</head>
<body>
<script type="text/javascript" src="flash-cookie.min.js"></script>
<script type="text/javascript">
    FlashCookie.onReady(function (cookie) {
        cookie.set("key1", "you can see me in any browser");
        cookie.set("key2", "me too!");

    });
</script>
</body>
</html>
```

## License

MIT License

Copyright © 2013 Faisalman <<fyzlman@gmail.com>>