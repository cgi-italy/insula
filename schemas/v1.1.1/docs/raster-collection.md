# Raster collection Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/common/raster-collection.schema.json
```

Definition of a raster collection

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-collection.schema.json](schemas/common/raster-collection.schema.json) |

## Raster collection Type

`object` ([Raster collection](raster-collection.md))

# Raster collection Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                            |
| :---------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [bands](#bands)               | `array`  | Optional | cannot be null | [Raster collection](raster-collection-properties-raster-bands.md)          |
| [renderConfig](#renderconfig) | `object` | Optional | cannot be null | [Raster collection](raster-collection-defs-raster-render-config.md) |
| [operations](#operations)     | `object` | Optional | cannot be null | [Raster collection](raster-operations-config.md)               |

## bands

The raster bands definitions

`bands`

* is optional

* Type: an array of merged types ([Raster band](raster-collection-defs-raster-band.md))

* cannot be null

* defined in: [Raster collection](raster-collection-properties-raster-bands.md)

### bands Type

an array of merged types ([Raster band](raster-collection-defs-raster-band.md))

## renderConfig



`renderConfig`

* is optional

* Type: `object` ([Raster render config](raster-collection-defs-raster-render-config.md))

* cannot be null

* defined in: [Raster collection](raster-collection-defs-raster-render-config.md)

### renderConfig Type

`object` ([Raster render config](raster-collection-defs-raster-render-config.md))

## operations

Configuration for raster dataset operations

`operations`

* is optional

* Type: `object` ([Dataset raster operations config](raster-operations-config.md))

* cannot be null

* defined in: [Raster collection](raster-operations-config.md)

### operations Type

`object` ([Dataset raster operations config](raster-operations-config.md))

# Raster collection Definitions

## Definitions group rasterBand

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.1.1/common/raster-collection.schema.json#/$defs/rasterBand"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group rasterBandVisualizationConfig

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.1.1/common/raster-collection.schema.json#/$defs/rasterBandVisualizationConfig"}
```

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                   |
| :------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [color](#color)     | `string` | Optional | cannot be null | [Raster collection](raster-collection-defs-band-visualization-configuration-properties-band-display-color.md) |
| [default](#default) | `object` | Optional | cannot be null | [Raster collection](dataset-colormap.md)                                                                     |

### color

The band display color as CSS string. Used only in some UI widgets (e.g. band combination selectors)

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

## Definitions group rasterRenderConfig

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.1.1/common/raster-collection.schema.json#/$defs/rasterRenderConfig"}
```

| Property                            | Type   | Required | Nullable       | Defined by                                                                                                                                                                                          |
| :---------------------------------- | :----- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [defaultBandMode](#defaultbandmode) | Merged | Optional | cannot be null | [Raster collection](raster-band-mode-config.md) |

### defaultBandMode

Definition of raster band mode rendering configuration

`defaultBandMode`

* is optional

* Type: merged type ([Raster band mode config](raster-band-mode-config.md))

* cannot be null

* defined in: [Raster collection](raster-band-mode-config.md)

#### defaultBandMode Type

merged type ([Raster band mode config](raster-band-mode-config.md))

one (and only one) of

* [Single band render mode config](raster-band-mode-config-defs-single-band-render-mode-config.md)

* [Preset render mode config](raster-band-mode-config-defs-preset-render-mode-config.md)

* [Band combination render mode config](raster-band-mode-config-defs-band-combination-render-mode-config.md)
