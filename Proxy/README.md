# 生成自己的 GFW block list

## MacOS带||

``` sh
wget https://raw.githubusercontent.com/wooodypan/blog/master/Proxy/PandaImageURL.txt && sed -e 's/^/||/' PandaImageURL.txt > myGFWList.txt
```

## MacOS不带||

``` sh
wget https://raw.githubusercontent.com/wooodypan/blog/master/Proxy/PandaImageURL.txt
```
