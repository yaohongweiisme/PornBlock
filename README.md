# PornBlock

keep nofap bro!!!!保持戒色，兄弟！！！

&#x23;如何使用/How to use
复制以下链接/Copy this link
https://cdn.jsdelivr.net/gh/yaohongweiisme/PornBlock@master/BlockPorn.yaml &#x20;



这个是规则集

https://cdn.jsdelivr.net/gh/yaohongweiisme/PornBlock@master/payload-rules.yaml

用法：

```markup
rule-providers:
  MyBlockAds:
    type: http
    behavior: classical  # <--- 重点：这里必须改！原来是 domain
    url: "https://cdn.jsdelivr.net/gh/yaohongweiisme/PornBlock@master/payload-rules.yaml"
    path: ./ruleset/porn.yaml
    interval: 86400
rules:
    - RULE-SET,MyBlockAds,REJECT
```

