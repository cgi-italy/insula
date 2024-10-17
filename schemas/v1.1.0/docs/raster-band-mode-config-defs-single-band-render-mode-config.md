# Single band render mode config Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.0/common/raster-band-mode-config.schema.json#/$defs/rasterSingleBandRenderModeConfig
```

Single band render mode config. In single band mode one band will be renderd with support for dynamic colormaps

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-band-mode-config.schema.json\*](schemas/common/raster-band-mode-config.schema.json) |

## rasterSingleBandRenderModeConfig Type

`object` ([Single band render mode config](raster-band-mode-config-defs-single-band-render-mode-config.md))

# rasterSingleBandRenderModeConfig Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                            |
| :------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [type](#type) | `string` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-single-band-render-mode-config-properties-single-band-type-constant.md) |
| [band](#band) | `number` | Optional | cannot be null | [Raster band mode config](raster-band-mode-config-defs-single-band-render-mode-config-properties-band-index.md)                |

## type



`type`

* is required

* Type: `string` ([Single band type constant](raster-band-mode-config-defs-single-band-render-mode-config-properties-single-band-type-constant.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-single-band-render-mode-config-properties-single-band-type-constant.md)

### type Type

`string` ([Single band type constant](raster-band-mode-config-defs-single-band-render-mode-config-properties-single-band-type-constant.md))

### type Constraints

**constant**: the value of this property must be equal to:

```json
"single"
```

## band

Raster band index

`band`

* is optional

* Type: `number` ([Band index](raster-band-mode-config-defs-single-band-render-mode-config-properties-band-index.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-single-band-render-mode-config-properties-band-index.md)

### band Type

`number` ([Band index](raster-band-mode-config-defs-single-band-render-mode-config-properties-band-index.md))
