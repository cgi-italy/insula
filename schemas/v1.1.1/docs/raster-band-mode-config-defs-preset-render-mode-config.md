# Preset render mode config Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/common/raster-band-mode-config.schema.json#/$defs/rasterPresetBandRenderModeConfig
```

Preset render mode config. In preset mode the layer will be rendered using a WMS style

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-band-mode-config.schema.json\*](schemas/common/raster-band-mode-config.schema.json) |

## rasterPresetBandRenderModeConfig Type

`object` ([Preset render mode config](raster-band-mode-config-defs-preset-render-mode-config.md))

# rasterPresetBandRenderModeConfig Properties

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                  |
| :---------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)     | `string` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-type-constant.md) |
| [preset](#preset) | `string` | Optional | cannot be null | [Raster band mode config](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-name.md)        |

## type



`type`

* is required

* Type: `string` ([Preset type constant](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-type-constant.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-type-constant.md)

### type Type

`string` ([Preset type constant](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-type-constant.md))

### type Constraints

**constant**: the value of this property must be equal to:

```json
"preset"
```

## preset

The preset name. Typically the WMS style

`preset`

* is optional

* Type: `string` ([Preset name](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-name.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-name.md)

### preset Type

`string` ([Preset name](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-name.md))
