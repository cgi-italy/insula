# Vector collection render config Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.0.0/common/vector-collection-render-config.schema.json
```

Definition of vector collection rendering configuration

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                       |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [vector-collection-render-config.schema.json](schemas/common/vector-collection-render-config.schema.json) |

## Vector collection render config Type

merged type ([Vector collection render config](vector-collection-render-config.md))

one (and only one) of

* [Raster render mode](vector-collection-render-config-defs-raster-render-mode.md)

* [Vector render mode](vector-collection-render-config-defs-vector-render-mode.md)

# Vector collection render config Definitions

## Definitions group rasterRenderMode

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.0.0/common/vector-collection-render-config.schema.json#/$defs/rasterRenderMode"}
```

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                          |
| :------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [mode](#mode) | `string` | Required | cannot be null | [Vector collection render config](vector-collection-render-config-defs-raster-render-mode-properties-raster-render-mode-constant.md) |

### mode



`mode`

* is required

* Type: `string` ([Raster render mode constant](vector-collection-render-config-defs-raster-render-mode-properties-raster-render-mode-constant.md))

* cannot be null

* defined in: [Vector collection render config](vector-collection-render-config-defs-raster-render-mode-properties-raster-render-mode-constant.md)

#### mode Type

`string` ([Raster render mode constant](vector-collection-render-config-defs-raster-render-mode-properties-raster-render-mode-constant.md))

#### mode Constraints

**constant**: the value of this property must be equal to:

```json
"raster"
```

## Definitions group vectorRenderMode

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.0.0/common/vector-collection-render-config.schema.json#/$defs/vectorRenderMode"}
```

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                          |
| :------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [mode](#mode-1)     | `string` | Required | cannot be null | [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-properties-vector-render-mode-constant.md) |
| [options](#options) | `object` | Optional | cannot be null | [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-options.md)                             |

### mode



`mode`

* is required

* Type: `string` ([Vector render mode constant](vector-collection-render-config-defs-vector-render-mode-properties-vector-render-mode-constant.md))

* cannot be null

* defined in: [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-properties-vector-render-mode-constant.md)

#### mode Type

`string` ([Vector render mode constant](vector-collection-render-config-defs-vector-render-mode-properties-vector-render-mode-constant.md))

#### mode Constraints

**constant**: the value of this property must be equal to:

```json
"vector"
```

### options

The vector render mode rendering options

`options`

* is optional

* Type: `object` ([Vector render mode options](vector-collection-render-config-defs-vector-render-mode-options.md))

* cannot be null

* defined in: [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-options.md)

#### options Type

`object` ([Vector render mode options](vector-collection-render-config-defs-vector-render-mode-options.md))

## Definitions group vectorRenderModeOptions

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.0.0/common/vector-collection-render-config.schema.json#/$defs/vectorRenderModeOptions"}
```

| Property                                      | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                       |
| :-------------------------------------------- | :------------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [defaultColorProperty](#defaultcolorproperty) | `string`      | Optional | cannot be null | [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-options-properties-default-color-property-id.md) |
| [optimizeSpeed](#optimizespeed)               | Not specified | Optional | cannot be null | [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-options-properties-optimize-speed.md)                   |

### defaultColorProperty

The attribute to use by default (on layer initialization) for class coloring (shall be of 'enum' type)

`defaultColorProperty`

* is optional

* Type: `string` ([Default color property id](vector-collection-render-config-defs-vector-render-mode-options-properties-default-color-property-id.md))

* cannot be null

* defined in: [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-options-properties-default-color-property-id.md)

#### defaultColorProperty Type

`string` ([Default color property id](vector-collection-render-config-defs-vector-render-mode-options-properties-default-color-property-id.md))

### optimizeSpeed

When set layer will rendere to optimize speed rather than interactivity

`optimizeSpeed`

* is optional

* Type: unknown ([Optimize speed](vector-collection-render-config-defs-vector-render-mode-options-properties-optimize-speed.md))

* cannot be null

* defined in: [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-options-properties-optimize-speed.md)

#### optimizeSpeed Type

unknown ([Optimize speed](vector-collection-render-config-defs-vector-render-mode-options-properties-optimize-speed.md))
