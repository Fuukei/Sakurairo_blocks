# Sakurairo_Blocks
WordPress 主题 [Sakurairo](https://github.com/mirai-mamori/Sakurairo) 的客户端区块编辑器部分。

##  目录结构

```tree
│  iro_blocks.php
│  package.json
│
├─build
│
└─src
    │  index.js
    │
    └─modules
            bilibili.js
            converstation.js
            hljs.js
            notice.js
            showcard.js
            ......
```

## 说明  
>index: 模块载入部分，添加主题块分类

>modules: 短代码的区块实现，其中hljs为原生代码块添加语言指定支持，便于hljs准确解析