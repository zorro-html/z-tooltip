# tooltip

小提示。本身是 `inline-block` 的，如果用于浮层，需要和其它外部样式配合使用

## Attributes

* `[side="left|top|right|bottom"]`: 出现的方向
* `[warning]`: 是否为警示状态
* `::content p[type="title"]`: 标题

## Example

```
<z-tooltip side="top">
    顶部提示文字
</z-tooltip>

<z-tooltip side="left">
    左侧提示文字
</z-tooltip>

<z-tooltip>
    <p type="title">带标题的提示</p>
    文字内容文字内容文字内容<br>
    文字内容文字内容文字内容
</z-tooltip>
```
