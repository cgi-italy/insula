# Raster collection Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.0.0/common/raster-collection.schema.json
```

Definition of a raster collection

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-collection.schema.json](schemas/common/raster-collection.schema.json) |

## Raster collection Type

`object` ([Raster collection](raster-collection.md))

# Raster collection Properties

| Property        | Type    | Required | Nullable       | Defined by                                                                                                                                                                   |
| :-------------- | :------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [bands](#bands) | `array` | Optional | cannot be null | [Raster collection](raster-collection-properties-raster-bands.md) |

## bands

The raster bands definitions

`bands`

* is optional

* Type: an array of merged types ([Raster band](raster-collection-defs-raster-band.md))

* cannot be null

* defined in: [Raster collection](raster-collection-properties-raster-bands.md)

### bands Type

an array of merged types ([Raster band](raster-collection-defs-raster-band.md))

# Raster collection Definitions

## Definitions group rasterBand

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.0.0/common/raster-collection.schema.json#/$defs/rasterBand"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group rasterBandVisualizationConfig

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.0.0/common/raster-collection.schema.json#/$defs/rasterBandVisualizationConfig"}
```

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                   |
| :------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [color](#color)     | `string` | Optional | cannot be null | [Raster collection](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md) |
| [default](#default) | `object` | Optional | cannot be null | [Raster collection](dataset-colormap.md)                                                                     |

### color

The band display color as CSS string

`color`

* is optional

* Type: `string` ([Band display color](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md))

* cannot be null

* defined in: [Raster collection](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md)

#### color Type

`string` ([Band display color](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md))

### default

Definition of a dataset color map

`default`

* is optional

* Type: `object` ([Dataset color map](dataset-colormap.md))

* cannot be null

* defined in: [Raster collection](dataset-colormap.md)

#### default Type

`object` ([Dataset color map](dataset-colormap.md))

#### default Examples

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
