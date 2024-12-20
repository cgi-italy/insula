# Raster dataset visualization config Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/common/raster-dataset-visualization-config.schema.json
```

Definition of the raster dataset visualization configuration

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                               |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-dataset-visualization-config.schema.json](schemas/common/raster-dataset-visualization-config.schema.json) |

## Raster dataset visualization config Type

`object` ([Raster dataset visualization config](raster-dataset-visualization-config.md))

# Raster dataset visualization config Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                  |
| :---------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [bands](#bands)               | `array`  | Optional | cannot be null | [Raster dataset visualization config](raster-dataset-visualization-config-properties-raster-bands.md)          |
| [renderConfig](#renderconfig) | `object` | Optional | cannot be null | [Raster dataset visualization config](raster-dataset-visualization-config-defs-raster-render-config.md) |
| [operations](#operations)     | `object` | Optional | cannot be null | [Raster dataset visualization config](raster-operations-config.md)                                                   |

## bands

The raster bands definitions

`bands`

* is optional

* Type: an array of merged types ([Raster band](raster-dataset-visualization-config-defs-raster-band.md))

* cannot be null

* defined in: [Raster dataset visualization config](raster-dataset-visualization-config-properties-raster-bands.md)

### bands Type

an array of merged types ([Raster band](raster-dataset-visualization-config-defs-raster-band.md))

## renderConfig



`renderConfig`

* is optional

* Type: `object` ([Raster render config](raster-dataset-visualization-config-defs-raster-render-config.md))

* cannot be null

* defined in: [Raster dataset visualization config](raster-dataset-visualization-config-defs-raster-render-config.md)

### renderConfig Type

`object` ([Raster render config](raster-dataset-visualization-config-defs-raster-render-config.md))

## operations

Configuration for raster dataset operations

`operations`

* is optional

* Type: `object` ([Dataset raster operations config](raster-operations-config.md))

* cannot be null

* defined in: [Raster dataset visualization config](raster-operations-config.md)

### operations Type

`object` ([Dataset raster operations config](raster-operations-config.md))

# Raster dataset visualization config Definitions

## Definitions group rasterBand

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/common/raster-dataset-visualization-config.schema.json#/$defs/rasterBand"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group rasterBandVisualizationConfig

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/common/raster-dataset-visualization-config.schema.json#/$defs/rasterBandVisualizationConfig"}
```

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                         |
| :------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [color](#color)     | `string` | Optional | cannot be null | [Raster dataset visualization config](raster-dataset-visualization-config-defs-band-visualization-configuration-properties-band-display-color.md) |
| [default](#default) | `object` | Optional | cannot be null | [Raster dataset visualization config](dataset-colormap.md)                                                                                                         |

### color

The band display color as CSS string. Used only in some UI widgets (e.g. band combination selectors)

`color`

* is optional

* Type: `string` ([Band display color](raster-dataset-visualization-config-defs-band-visualization-configuration-properties-band-display-color.md))

* cannot be null

* defined in: [Raster dataset visualization config](raster-dataset-visualization-config-defs-band-visualization-configuration-properties-band-display-color.md)

#### color Type

`string` ([Band display color](raster-dataset-visualization-config-defs-band-visualization-configuration-properties-band-display-color.md))

### default

Definition of a dataset color map

`default`

* is optional

* Type: `object` ([Dataset color map](dataset-colormap.md))

* cannot be null

* defined in: [Raster dataset visualization config](dataset-colormap.md)

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
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/common/raster-dataset-visualization-config.schema.json#/$defs/rasterRenderConfig"}
```

| Property                            | Type   | Required | Nullable       | Defined by                                                                                                                                                                                                            |
| :---------------------------------- | :----- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [defaultBandMode](#defaultbandmode) | Merged | Optional | cannot be null | [Raster dataset visualization config](raster-band-mode-config.md) |

### defaultBandMode

Definition of raster band mode rendering configuration

`defaultBandMode`

* is optional

* Type: merged type ([Raster band mode config](raster-band-mode-config.md))

* cannot be null

* defined in: [Raster dataset visualization config](raster-band-mode-config.md)

#### defaultBandMode Type

merged type ([Raster band mode config](raster-band-mode-config.md))

one (and only one) of

* [Single band render mode config](raster-band-mode-config-defs-single-band-render-mode-config.md)

* [Preset render mode config](raster-band-mode-config-defs-preset-render-mode-config.md)

* [Band combination render mode config](raster-band-mode-config-defs-band-combination-render-mode-config.md)
