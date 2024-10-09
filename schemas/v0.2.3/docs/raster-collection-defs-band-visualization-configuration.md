# Band visualization configuration Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/raster-collection.schema.json#/$defs/rasterBandVisualizationConfig
```

Define band additional parameters used for visualization

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                             |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-collection.schema.json\*](schemas/common/raster-collection.schema.json"open original schema") |

## rasterBandVisualizationConfig Type

`object` ([Band visualization configuration](raster-collection-defs-band-visualization-configuration.md))

## rasterBandVisualizationConfig Examples

```json
{"color":"#aa2233","default": {"colorScale":"turbo","range": {"min": 0,"max": 10
    },"clamp": false
  }
}
```

# rasterBandVisualizationConfig Properties

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                   |
| :------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [color](#color)     | `string` | Optional | cannot be null | [Raster collection](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/raster-collection.schema.json#/$defs/rasterBandVisualizationConfig/properties/color") |
| [default](#default) | `object` | Optional | cannot be null | [Raster collection](dataset-colormap.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-colormap.schema.json#/$defs/rasterBandVisualizationConfig/properties/default")                                                                     |

## color

The band display color as CSS string

`color`

* is optional

* Type: `string` ([Band display color](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md))

* cannot be null

* defined in: [Raster collection](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/raster-collection.schema.json#/$defs/rasterBandVisualizationConfig/properties/color")

### color Type

`string` ([Band display color](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md))

## default

Definition of a dataset color map

`default`

* is optional

* Type: `object` ([Dataset color map](dataset-colormap.md))

* cannot be null

* defined in: [Raster collection](dataset-colormap.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-colormap.schema.json#/$defs/rasterBandVisualizationConfig/properties/default")

### default Type

`object` ([Dataset color map](dataset-colormap.md))

### default Examples

```json
{"colorScale":"viridis","range": {"min": 0,"max": 66
  },"clamp": true
}
```