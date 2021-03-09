<p>
  <h1 align="center">HySippnet</h1>
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=entenity.hy-sippnets">
    <img src="https://vsmarketplacebadge.apphb.com/version-short/entenity.hy-sippnets.svg">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=entenity.hy-sippnets">
    <img src="https://vsmarketplacebadge.apphb.com/installs-short/entenity.hy-sippnets.svg">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=entenity.hy-sippnets">
    <img src="https://vsmarketplacebadge.apphb.com/rating-star/entenity.hy-sippnets.svg">
  </a>
  <br>
</p>

### 自动填充代码片段插件

为了更方便快捷满足开发，适应当前快速开发模式，代码片段自动补充插件应运而生，该插件目前分**JavaScript TypeScript Vue-template**三种代码片段，[sippnets 语法参考](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

### JavaScript

写在snippets中的hy-javascript.json中

```javascript
{
    "ajax": {
        "prefix": "ajax",
        "body": [
            "$.ajax({",
            "    url: '$1',",
            "    method: '${2:POST}',",
            "    datatype: 'json',",
            "    success: data => {",
            "        $3;",
            "    },",
            "    error: err => {",
            "        $4;",
            "    }",
            "})"
        ],
        "description": "ajax模块"
    }
}

```

### TypeScript

写在snippets中的hy-typescript.json中

```javascript
{
    "class": {
        "prefix": "class",
        "body": [
            "import { Vue, Component, Prop } from 'vue-property-decorator'",
            "@Component({'$1'})",
            "export default class Class extends Vue {'$2'}"
        ],
        "description": "声明class模块"
    }
}
```


### Vue-template

写在snippets中的hy-vue.json中

```javascript
{
    "hy-button": {
        "prefix": "hy-button",
        "body": [
            "<hy-button type='primary'>主要按钮</hy-button>"
        ],
        "description": "hy-button基础组件"
    }
}
```

