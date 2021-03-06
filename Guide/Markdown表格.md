# Markdown表格

> 你可能可以想到，在 Excel 或 Word 里可以使用表格，但你曾想象过在纯文本文件里使用表格吗[^1]？Markdown 可以做到。

## 基本语法

Markdown 制作表格使用 `|` 分隔不同的单元格，使用 `-` 分隔表头和其他行

## 对齐方式

> 我们可以设置表格的对其方式

- 设置内容和标题栏居右对齐：`v-:`

- 设置内容和标题栏居左对齐：`:-`

- 设置内容和标题栏居中对齐: `:-:`

## 代码示例

```markdown
| 商品 | 价格 |
| --- | --- |
| 牛奶 | 5￥ |
| 饼干 | 10￥ |

| 科目（左对齐） | 成绩（右对齐） | 平均分（居中对齐） |
| :- | -: | :-: |
| 语文 | 80 | 91 |
| 数学 | 90 | 85 |
```

## 效果展示

| 商品 | 价格 |
| ---- | ---- |
| 牛奶 | 5￥  |
| 饼干 | 10￥ |

| 科目（左对齐） | 成绩（右对齐） | 平均分（居中对齐） |
| :------------- | -------------: | :----------------: |
| 语文           |             80 |         91         |
| 数学           |             90 |         85         |

[^1]:如果您稍稍了解前端,那么请忽视这段话 :/

***

本作品采用知识共享 署名-非商业性使用 4.0 国际 许可协议进行许可。要查看该许可协议，可访问 http://creativecommons.org/licenses/by-nc/4.0/ 或者写信到 Creative Commons, PO Box 1866, Mountain View, CA 94042, USA。

![cc](http://ice-kylin.gitee.io/icekylinfigurebed/images/PublicFile/License/cc-colourful.svg) ![nc](http://ice-kylin.gitee.io/icekylinfigurebed/images/PublicFile/License/nc-colourful.svg) ![by](http://ice-kylin.gitee.io/icekylinfigurebed/images/PublicFile/License/by-colourful.svg)