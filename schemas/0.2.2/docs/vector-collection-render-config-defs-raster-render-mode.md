# Raster render mode Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection-render-config.schema.json#/$defs/rasterRenderMode
```

The vector will be rasterized for rendering

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-collection-render-config.schema.json\*] (schemas/common/vector-collection-render-config.schema.json) |

## rasterRenderMode Type

`object` ([Raster render mode](vector-collection-render-config-defs-raster-render-mode.md))

# rasterRenderMode Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                          |
| :------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [mode](#mode) | `string` | Required | cannot be null | [Vector collection render config] (vector-collection-render-config-defs-raster-render-mode-properties-raster-render-mode-constant.md) |

## mode



`mode`

* is required

* Type: `string` ([Raster render mode constant](vector-collection-render-config-defs-raster-render-mode-properties-raster-render-mode-constant.md))

* cannot be null

* defined in: [Vector collection render config] (vector-collection-render-config-defs-raster-render-mode-properties-raster-render-mode-constant.md)

### mode Type

`string` ([Raster render mode constant](vector-collection-render-config-defs-raster-render-mode-properties-raster-render-mode-constant.md))

### mode Constraints

**constant**: the value of this property must be equal to:

```json
"raster"
```
