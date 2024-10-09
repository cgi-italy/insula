# Vector render mode Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection-render-config.schema.json#/$defs/vectorRenderMode
```

The vector will be rendered on the client side

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-collection-render-config.schema.json\*](schemas/common/vector-collection-render-config.schema.json "open original schema") |

## vectorRenderMode Type

`object` ([Vector render mode](vector-collection-render-config-defs-vector-render-mode.md))

# vectorRenderMode Properties

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                          |
| :------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [mode](#mode)       | `string` | Required | cannot be null | [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-properties-vector-render-mode-constant.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection-render-config.schema.json#/$defs/vectorRenderMode/properties/mode") |
| [options](#options) | `object` | Optional | cannot be null | [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-options.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection-render-config.schema.json#/$defs/vectorRenderMode/properties/options")                             |

## mode



`mode`

* is required

* Type: `string` ([Vector render mode constant](vector-collection-render-config-defs-vector-render-mode-properties-vector-render-mode-constant.md))

* cannot be null

* defined in: [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-properties-vector-render-mode-constant.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection-render-config.schema.json#/$defs/vectorRenderMode/properties/mode")

### mode Type

`string` ([Vector render mode constant](vector-collection-render-config-defs-vector-render-mode-properties-vector-render-mode-constant.md))

### mode Constraints

**constant**: the value of this property must be equal to:

```json
"vector"
```

## options

The vector render mode rendering options

`options`

* is optional

* Type: `object` ([Vector render mode options](vector-collection-render-config-defs-vector-render-mode-options.md))

* cannot be null

* defined in: [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-options.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection-render-config.schema.json#/$defs/vectorRenderMode/properties/options")

### options Type

`object` ([Vector render mode options](vector-collection-render-config-defs-vector-render-mode-options.md))
