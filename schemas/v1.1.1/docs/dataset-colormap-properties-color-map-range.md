# Color map range Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/common/dataset-colormap.schema.json#/properties/range
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [dataset-colormap.schema.json\*](schemas/common/dataset-colormap.schema.json) |

## range Type

`object` ([Color map range](dataset-colormap-properties-color-map-range.md))

# range Properties

| Property    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                              |
| :---------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [min](#min) | `number` | Required | cannot be null | [Dataset color map](dataset-colormap-properties-color-map-range-properties-range-min-value.md) |
| [max](#max) | `number` | Required | cannot be null | [Dataset color map](dataset-colormap-properties-color-map-range-properties-range-max-value.md) |

## min

The color map range minumum value

`min`

* is required

* Type: `number` ([Range min value](dataset-colormap-properties-color-map-range-properties-range-min-value.md))

* cannot be null

* defined in: [Dataset color map](dataset-colormap-properties-color-map-range-properties-range-min-value.md)

### min Type

`number` ([Range min value](dataset-colormap-properties-color-map-range-properties-range-min-value.md))

## max

The color map range maximum value

`max`

* is required

* Type: `number` ([Range max value](dataset-colormap-properties-color-map-range-properties-range-max-value.md))

* cannot be null

* defined in: [Dataset color map](dataset-colormap-properties-color-map-range-properties-range-max-value.md)

### max Type

`number` ([Range max value](dataset-colormap-properties-color-map-range-properties-range-max-value.md))
