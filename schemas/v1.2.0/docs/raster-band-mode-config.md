# Raster band mode config Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/common/raster-band-mode-config.schema.json
```

Definition of raster band mode rendering configuration

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                       |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [raster-band-mode-config.schema.json](schemas/common/raster-band-mode-config.schema.json) |

## Raster band mode config Type

merged type ([Raster band mode config](raster-band-mode-config.md))

one (and only one) of

* [Single band render mode config](raster-band-mode-config-defs-single-band-render-mode-config.md)

* [Preset render mode config](raster-band-mode-config-defs-preset-render-mode-config.md)

* [Band combination render mode config](raster-band-mode-config-defs-band-combination-render-mode-config.md)

# Raster band mode config Definitions

## Definitions group rasterSingleBandRenderModeConfig

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/common/raster-band-mode-config.schema.json#/$defs/rasterSingleBandRenderModeConfig"}
```

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                            |
| :------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [type](#type) | `string` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-single-band-render-mode-config-properties-single-band-type-constant.md) |
| [band](#band) | `number` | Optional | cannot be null | [Raster band mode config](raster-band-mode-config-defs-single-band-render-mode-config-properties-band-index.md)                |

### type



`type`

* is required

* Type: `string` ([Single band type constant](raster-band-mode-config-defs-single-band-render-mode-config-properties-single-band-type-constant.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-single-band-render-mode-config-properties-single-band-type-constant.md)

#### type Type

`string` ([Single band type constant](raster-band-mode-config-defs-single-band-render-mode-config-properties-single-band-type-constant.md))

#### type Constraints

**constant**: the value of this property must be equal to:

```json
"single"
```

### band

Raster band index

`band`

* is optional

* Type: `number` ([Band index](raster-band-mode-config-defs-single-band-render-mode-config-properties-band-index.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-single-band-render-mode-config-properties-band-index.md)

#### band Type

`number` ([Band index](raster-band-mode-config-defs-single-band-render-mode-config-properties-band-index.md))

## Definitions group rasterPresetBandRenderModeConfig

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/common/raster-band-mode-config.schema.json#/$defs/rasterPresetBandRenderModeConfig"}
```

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                  |
| :---------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type-1)   | `string` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-type-constant.md) |
| [preset](#preset) | `string` | Optional | cannot be null | [Raster band mode config](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-name.md)        |

### type



`type`

* is required

* Type: `string` ([Preset type constant](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-type-constant.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-type-constant.md)

#### type Type

`string` ([Preset type constant](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-type-constant.md))

#### type Constraints

**constant**: the value of this property must be equal to:

```json
"preset"
```

### preset

The preset name. Typically the WMS style

`preset`

* is optional

* Type: `string` ([Preset name](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-name.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-name.md)

#### preset Type

`string` ([Preset name](raster-band-mode-config-defs-preset-render-mode-config-properties-preset-name.md))

## Definitions group rasterBandCombinationRenderModeConfig

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/common/raster-band-mode-config.schema.json#/$defs/rasterBandCombinationRenderModeConfig"}
```

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                           |
| :---------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type-2)         | `string` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-band-combination-type-constant.md) |
| [red](#red)             | `number` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-red-band.md)                        |
| [green](#green)         | `number` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-green-band.md)                    |
| [blue](#blue)           | `number` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-blue-band.md)                      |
| [dataRange](#datarange) | `object` | Optional | cannot be null | [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range.md)          |

### type



`type`

* is required

* Type: `string` ([Band combination type constant](raster-band-mode-config-defs-band-combination-render-mode-config-properties-band-combination-type-constant.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-band-combination-type-constant.md)

#### type Type

`string` ([Band combination type constant](raster-band-mode-config-defs-band-combination-render-mode-config-properties-band-combination-type-constant.md))

#### type Constraints

**constant**: the value of this property must be equal to:

```json
"combination"
```

### red

Index of the band to use for red channel

`red`

* is required

* Type: `number` ([Red band](raster-band-mode-config-defs-band-combination-render-mode-config-properties-red-band.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-red-band.md)

#### red Type

`number` ([Red band](raster-band-mode-config-defs-band-combination-render-mode-config-properties-red-band.md))

### green

Index of the band to use for green channel

`green`

* is required

* Type: `number` ([Green band](raster-band-mode-config-defs-band-combination-render-mode-config-properties-green-band.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-green-band.md)

#### green Type

`number` ([Green band](raster-band-mode-config-defs-band-combination-render-mode-config-properties-green-band.md))

### blue

Index of the band to use for blue channel

`blue`

* is required

* Type: `number` ([Blue band](raster-band-mode-config-defs-band-combination-render-mode-config-properties-blue-band.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-blue-band.md)

#### blue Type

`number` ([Blue band](raster-band-mode-config-defs-band-combination-render-mode-config-properties-blue-band.md))

### dataRange



`dataRange`

* is optional

* Type: `object` ([Bands data range](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range.md)

#### dataRange Type

`object` ([Bands data range](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range.md))
