# CSS盒模型详解

我们可以认为网页中的每一个html标签都是一个小盒子，然后这个盒子又包着几个小的盒子，这几个盒子最终铺满了整个网页，这就是所谓的盒模型。
该盒子包括:边距(margin)、边框(border)、填充(padding)和实际内容(content)。
盒模型分为IE盒模型和W3C标准盒模型。

## IE盒模型

IE盒模型:
`
box-sizing:border-box;
`
IE盒模型:宽度 = 内容宽度(content + border + padding) + margin。

## W3C标准盒模型

W3C标准盒模型:
`
box-sizing:content-box;
`
W3C标准盒模型:宽度 = 内容的宽度(宽度) + boder + padding + margin。
