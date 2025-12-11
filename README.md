# PornBlock

## keep nofap bro!!!!保持戒色，兄弟！！！

### 如何使用/How to use&#x20;

这个是全局覆盖文件，适合pc端使用

&#x20;https://cdn.jsdelivr.net/gh/yaohongweiisme/PornBlock@master/BlockPorn.yaml &#x20;

<img width="1915" height="969" alt="image" src="https://github.com/user-attachments/assets/e560aa28-023b-4261-9cd4-66c3f2971ffe" />

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

