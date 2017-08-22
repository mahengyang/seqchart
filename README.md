# seqchart
时序图生成工具

根据配置文件生成时序图

```
data: [
    ["a" "b" "请求b"]
    ["b" "c" "b请求c"]
    ["c" "b" "c响应b"]
    ["b" "c" "b请求c 又一次"]
    ["c" "d" "c请求d"]
    ["d" "c" "d响应c"]
    ["c" "b" "c响应b 又一次"]
    ["b" "a" "b响应a"]
    ["a" "c" "a请求c"]
    ["c" "a" "c响应a"]
]
```

# 使用方式

```
$ red main.red
```

#效果图

![时序图](https://github.com/mahengyang/seqchart/raw/master/seqchart.png)
