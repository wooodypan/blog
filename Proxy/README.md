# 生成自己的 GFW block list （PAC模式走代理的域名）

## MacOS、开头带"||"

``` sh
wget https://raw.githubusercontent.com/wooodypan/blog/master/Proxy/PandaImageURL.txt && sed -e 's/^/||/' PandaImageURL.txt > myGFWList.txt
```

## MacOS、开头不带"||"

``` sh
wget https://raw.githubusercontent.com/wooodypan/blog/master/Proxy/PandaImageURL.txt
```
