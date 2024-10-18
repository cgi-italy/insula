# Band combination render mode config Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/common/raster-band-mode-config.schema.json#/$defs/rasterBandCombinationRenderModeConfig
```

Band combination render mode config. In band combination mode the layer will be rendered with dynamic band combination selection

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-band-mode-config.schema.json\*](schemas/common/raster-band-mode-config.schema.json) |

## rasterBandCombinationRenderModeConfig Type

`object` ([Band combination render mode config](raster-band-mode-config-defs-band-combination-render-mode-config.md))

# rasterBandCombinationRenderModeConfig Properties

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                           |
| :---------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)           | `string` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-band-combination-type-constant.md) |
| [red](#red)             | `number` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-red-band.md)                        |
| [green](#green)         | `number` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-green-band.md)                    |
| [blue](#blue)           | `number` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-blue-band.md)                      |
| [dataRange](#datarange) | `object` | Optional | cannot be null | [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range.md)          |

## type



`type`

* is required

* Type: `string` ([Band combination type constant](raster-band-mode-config-defs-band-combination-render-mode-config-properties-band-combination-type-constant.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-band-combination-type-constant.md)

### type Type

`string` ([Band combination type constant](raster-band-mode-config-defs-band-combination-render-mode-config-properties-band-combination-type-constant.md))

### type Constraints

**constant**: the value of this property must be equal to:

```json
"combination"
```

## red

Index of the band to use for red channel

`red`

* is required

* Type: `number` ([Red band](raster-band-mode-config-defs-band-combination-render-mode-config-properties-red-band.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-red-band.md)

### red Type

`number` ([Red band](raster-band-mode-config-defs-band-combination-render-mode-config-properties-red-band.md))

## green

Index of the band to use for green channel

`green`

* is required

* Type: `number` ([Green band](raster-band-mode-config-defs-band-combination-render-mode-config-properties-green-band.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-green-band.md)

### green Type

`number` ([Green band](raster-band-mode-config-defs-band-combination-render-mode-config-properties-green-band.md))

## blue

Index of the band to use for blue channel

`blue`

* is required

* Type: `number` ([Blue band](raster-band-mode-config-defs-band-combination-render-mode-config-properties-blue-band.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-blue-band.md)

### blue Type

`number` ([Blue band](raster-band-mode-config-defs-band-combination-render-mode-config-properties-blue-band.md))

## dataRange



`dataRange`

* is optional

* Type: `object` ([Bands data range](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range.md)

### dataRange Type

`object` ([Bands data range](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range.md))
