# Band visualization configuration Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.0/common/raster-collection.schema.json#/$defs/rasterBandVisualizationConfig
```

Define band additional parameters used for visualization

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                             |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-collection.schema.json\*](schemas/common/raster-collection.schema.json) |

## rasterBandVisualizationConfig Type

`object` ([Band visualization configuration](raster-collection-defs-band-visualization-configuration.md))

## rasterBandVisualizationConfig Examples

```json
{
  "color": "#aa2233",
  "default": {
    "colorScale": "turbo",
    "range": {
      "min": 0,
      "max": 10
    },
    "clamp": false
  }
}
```

# rasterBandVisualizationConfig Properties

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                   |
| :------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [color](#color)     | `string` | Optional | cannot be null | [Raster collection](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md) |
| [default](#default) | `object` | Optional | cannot be null | [Raster collection](dataset-colormap.md)                                                                     |

## color

The band display color as CSS string. Used only in some UI widgets (e.g. band combination selectors)

`color`

* is optional

* Type: `string` ([Band display color](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md))

* cannot be null

* defined in: [Raster collection](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md)

### color Type

`string` ([Band display color](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md))

## default

Definition of a dataset color map

`default`

* is optional

* Type: `object` ([Dataset color map](dataset-colormap.md))

* cannot be null

* defined in: [Raster collection](dataset-colormap.md)

### default Type

`object` ([Dataset color map](dataset-colormap.md))

### default Examples

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
