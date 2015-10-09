# 連続撮影するために...

```
system "screencapture -R#{x},#{y},#{width},#{height} --out \"#{tmpfile}\""
```

で部分撮影


# フィルターを付けるために...

[RMagick](http://qiita.com/scleen_x_x/items/14a80fd52e41dfcfb660) でもいいけど
OpenCV もあり
