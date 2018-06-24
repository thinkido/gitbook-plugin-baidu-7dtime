# 百度统计代码
==============

## 示例网站 
tlog.7dtime.com
book.7dtime.com

You can use install it via **NPM**:

```
$ npm install gitbook-plugin-baidu-7dtime
```

And use it for your book with in the book.json:

```
{
    "plugins": ["baidu-7dtime"]
}
```

You can set the Google Analytics tracking ID using the plugins configuration in the book.json:

```
{
    "plugins": ["baidu-7dtime"],
    "pluginsConfig": {
        "3-ba": {
            "token": "xxxxxxxx"
        }
    }
}
```

