# PornBlock

## keep nofap bro!!!!保持戒色，兄弟！！！

### 如何使用/How to use&#x20;

这个是全局覆盖文件，适合pc端使用

&#x20;https://cdn.jsdelivr.net/gh/yaohongweiisme/PornBlock@master/BlockPorn.yaml &#x20;

![](README_md_files/e142be20-d62f-11f0-a18c-adbc1266e11d.jpeg?v=1&type=image)

这个是规则集

https://cdn.jsdelivr.net/gh/yaohongweiisme/PornBlock@master/payload-rules.yaml

用法：

```markup
rule-providers:
  MyPornBlock:
    type: http
    behavior: classical  
    url: "https://cdn.jsdelivr.net/gh/yaohongweiisme/PornBlock@master/payload-rules.yaml"
    interval: 86400
rules:
    - RULE-SET,MyPornBlock,REJECT
```

