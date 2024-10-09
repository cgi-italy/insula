# Dataset color map Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.8/common/dataset-colormap.schema.json
```

Definition of a dataset color map

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [dataset-colormap.schema.json](schemas/common/dataset-colormap.schema.json) |

## Dataset color map Type

`object` ([Dataset color map](dataset-colormap.md))

## Dataset color map Examples

```json
{
  "colorScale": "viridis",
  "range": {
    "min": 0,
    "max": 66
  },
  "clamp": true
}
```

# Dataset color map Properties

| Property                  | Type      | Required | Nullable       | Defined by                                                                                                                                                                    |
| :------------------------ | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [colorScale](#colorscale) | `string`  | Optional | cannot be null | [Dataset color map](dataset-colorscale.md)                   |
| [range](#range)           | `object`  | Optional | cannot be null | [Dataset color map](dataset-colormap-properties-color-map-range.md) |
| [clamp](#clamp)           | `boolean` | Optional | cannot be null | [Dataset color map](dataset-colormap-properties-colormap-clamp.md)  |

## colorScale



`colorScale`

* is optional

* Type: `string` ([Dataset colorscale](dataset-colorscale.md))

* cannot be null

* defined in: [Dataset color map](dataset-colorscale.md)

### colorScale Type

`string` ([Dataset colorscale](dataset-colorscale.md))

### colorScale Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                | Explanation |
| :------------------- | :---------- |
| `"viridis"`          |             |
| `"inferno"`          |             |
| `"turbo"`            |             |
| `"rainbow"`          |             |
| `"jet"`              |             |
| `"hsv"`              |             |
| `"hot"`              |             |
| `"cool"`             |             |
| `"spring"`           |             |
| `"summer"`           |             |
| `"autumn"`           |             |
| `"winter"`           |             |
| `"bone"`             |             |
| `"copper"`           |             |
| `"greys"`            |             |
| `"ylgnbu"`           |             |
| `"greens"`           |             |
| `"ylorrd"`           |             |
| `"bluered"`          |             |
| `"rdbu"`             |             |
| `"picnic"`           |             |
| `"portland"`         |             |
| `"blackbody"`        |             |
| `"earth"`            |             |
| `"electric"`         |             |
| `"magma"`            |             |
| `"plasma"`           |             |
| `"redblue"`          |             |
| `"coolwarm"`         |             |
| `"diverging_1"`      |             |
| `"diverging_2"`      |             |
| `"blackwhite"`       |             |
| `"twilight"`         |             |
| `"twilight_shifted"` |             |

## range



`range`

* is optional

* Type: `object` ([Color map range](dataset-colormap-properties-color-map-range.md))

* cannot be null

* defined in: [Dataset color map](dataset-colormap-properties-color-map-range.md)

### range Type

`object` ([Color map range](dataset-colormap-properties-color-map-range.md))

## clamp

Define clamping colormap behaviour. If enabled values beyond the range limits will be colored using the colorScale extreme colors. If disabled values beyond the range will be filtered out in the visualization

`clamp`

* is optional

* Type: `boolean` ([Colormap clamp](dataset-colormap-properties-colormap-clamp.md))

* cannot be null

* defined in: [Dataset color map](dataset-colormap-properties-colormap-clamp.md)

### clamp Type

`boolean` ([Colormap clamp](dataset-colormap-properties-colormap-clamp.md))

### clamp Default Value

The default value is:

```json
true
```
