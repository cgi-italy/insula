# Vector collection Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection.schema.json
```

Definition of a vector collection

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-collection.schema.json](schemas/common/vector-collection.schema.json"open original schema") |

## Vector collection Type

`object` ([Vector collection](vector-collection.md))

# Vector collection Properties

| Property                                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                   |
| :------------------------------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [renderConfig](#renderconfig)                     | Merged   | Optional | cannot be null | [Vector collection](vector-collection-render-config.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection-render-config.schema.json#/properties/renderConfig")                      |
| [feautreAttributes](#feautreattributes)           | `array`  | Optional | cannot be null | [Vector collection](vector-collection-properties-feature-attributes.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection.schema.json#/properties/feautreAttributes")               |
| [timeDimensionAttribute](#timedimensionattribute) | `string` | Optional | cannot be null | [Vector collection](vector-collection-properties-time-dimension-attribute-id.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection.schema.json#/properties/timeDimensionAttribute") |

## renderConfig

Definition of vector collection rendering configuration

`renderConfig`

* is optional

* Type: merged type ([Vector collection render config](vector-collection-render-config.md))

* cannot be null

* defined in: [Vector collection](vector-collection-render-config.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection-render-config.schema.json#/properties/renderConfig")

### renderConfig Type

merged type ([Vector collection render config](vector-collection-render-config.md))

one (and only one) of

* [Raster render mode](vector-collection-render-config-defs-raster-render-mode.md"check type definition")

* [Vector render mode](vector-collection-render-config-defs-vector-render-mode.md"check type definition")

### renderConfig Default Value

The default value is:

```json
{"mode":"raster"
}
```

## feautreAttributes

The feature attributes definitions

`feautreAttributes`

* is optional

* Type: an array of merged types ([Vector feature property](vector-feature-property.md))

* cannot be null

* defined in: [Vector collection](vector-collection-properties-feature-attributes.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection.schema.json#/properties/feautreAttributes")

### feautreAttributes Type

an array of merged types ([Vector feature property](vector-feature-property.md))

## timeDimensionAttribute

The attribute to use as time dimension (shall be of 'date' type)

`timeDimensionAttribute`

* is optional

* Type: `string` ([Time dimension attribute id](vector-collection-properties-time-dimension-attribute-id.md))

* cannot be null

* defined in: [Vector collection](vector-collection-properties-time-dimension-attribute-id.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-collection.schema.json#/properties/timeDimensionAttribute")

### timeDimensionAttribute Type

`string` ([Time dimension attribute id](vector-collection-properties-time-dimension-attribute-id.md))
