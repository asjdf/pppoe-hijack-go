## 介绍

模仿[PPPoE-hijack](https://github.com/Karblue/PPPoE-hijack)的golang版本

原理: [解密古老又通杀的路由器攻击手法：从嗅探PPPoE到隐蔽性后门](http://www.freebuf.com/articles/wireless/163480.html)

## 用法

```bash
go install github.com/asjdf/pppoe-hijack-go
```

### 列网卡

```bash
./pppoe-hijack-go -l
```

### 嗅探

```bash
./pppoe-hijack-go -i 网卡名
```
