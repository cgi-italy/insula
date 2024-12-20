# Colormap clamp Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/common/dataset-colormap.schema.json#/properties/clamp
```

Define clamping colormap behaviour. If enabled values beyond the range limits will be colored using the colorScale extreme colors. If disabled values beyond the range will be filtered out in the visualization

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [dataset-colormap.schema.json\*](schemas/common/dataset-colormap.schema.json) |

## clamp Type

`boolean` ([Colormap clamp](dataset-colormap-properties-colormap-clamp.md))

## clamp Default Value

The default value is:

```json
true
```
