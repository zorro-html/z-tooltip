# `<z-tooltip>`

The element itself is an `inline-block` one. But could be used as a absolute layer aside certain box element

## Attributes

- `side`: `"left"` | `"top"` | `"right"` | `"bottom"` the direction to be aside to
- `warning`: warning style

## Child Elements

- `::content [type="title"]`: the title

## Examples

```
<z-tooltip>
  Tooltip
</z-tooltip>
```

### Tooltip with Title

```
<z-tooltip>
  <p type="title">Title</p>
  Lorem ipsum dolor sit amet,<br>
  consectetur adipiscing elit
</z-tooltip>
```

### Title with Arrow

```
<z-tooltip side="top">
  Tooltip on the top
</z-tooltip>
<z-tooltip side="left">
  Tooltip on the left
</z-tooltip>
```

### Tooltip beside element

```
<z-btn style="position: relative;">
    Button
    <z-tooltip side="right" style="position: absolute; left: 100%; top: 50%; -webkit-transform: translateY(-50%); margin-left: 10px; width: 120px;">
      Tooltip
    </z-tooltip>
</z-btn>
```
