# Vector collection Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/common/vector-collection.schema.json
```

Definition of a vector collection

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-collection.schema.json](schemas/common/vector-collection.schema.json) |

## Vector collection Type

`object` ([Vector collection](vector-collection.md))

# Vector collection Properties

| Property                                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                   |
| :------------------------------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [renderConfig](#renderconfig)                     | Merged   | Optional | cannot be null | [Vector collection](vector-collection-render-config.md)                      |
| [featureAttributes](#featureattributes)           | `array`  | Optional | cannot be null | [Vector collection](vector-collection-properties-feature-attributes.md)               |
| [timeDimensionAttribute](#timedimensionattribute) | `string` | Optional | cannot be null | [Vector collection](vector-collection-properties-time-dimension-attribute-id.md) |
| [titleAttribute](#titleattribute)                 | `string` | Optional | cannot be null | [Vector collection](vector-collection-properties-title-attribute-id.md)                  |
| [operations](#operations)                         | `object` | Optional | cannot be null | [Vector collection](vector-operations-config.md)                                      |

## renderConfig

Definition of vector collection rendering configuration

`renderConfig`

* is optional

* Type: merged type ([Vector collection render config](vector-collection-render-config.md))

* cannot be null

* defined in: [Vector collection](vector-collection-render-config.md)

### renderConfig Type

merged type ([Vector collection render config](vector-collection-render-config.md))

one (and only one) of

* [Raster render mode](vector-collection-render-config-defs-raster-render-mode.md)

* [Vector render mode](vector-collection-render-config-defs-vector-render-mode.md)

### renderConfig Default Value

The default value is:

```json
{
  "mode": "raster"
}
```

## featureAttributes

The feature attributes definitions

`featureAttributes`

* is optional

* Type: an array of merged types ([Vector feature property](vector-feature-property.md))

* cannot be null

* defined in: [Vector collection](vector-collection-properties-feature-attributes.md)

### featureAttributes Type

an array of merged types ([Vector feature property](vector-feature-property.md))

## timeDimensionAttribute

The attribute to use as time dimension (shall be of 'date' type)

`timeDimensionAttribute`

* is optional

* Type: `string` ([Time dimension attribute id](vector-collection-properties-time-dimension-attribute-id.md))

* cannot be null

* defined in: [Vector collection](vector-collection-properties-time-dimension-attribute-id.md)

### timeDimensionAttribute Type

`string` ([Time dimension attribute id](vector-collection-properties-time-dimension-attribute-id.md))

## titleAttribute

The attribute to use as feature title

`titleAttribute`

* is optional

* Type: `string` ([Title attribute id](vector-collection-properties-title-attribute-id.md))

* cannot be null

* defined in: [Vector collection](vector-collection-properties-title-attribute-id.md)

### titleAttribute Type

`string` ([Title attribute id](vector-collection-properties-title-attribute-id.md))

## operations

Configuration for vector dataset operations

`operations`

* is optional

* Type: `object` ([Dataset vector operations config](vector-operations-config.md))

* cannot be null

* defined in: [Vector collection](vector-operations-config.md)

### operations Type

`object` ([Dataset vector operations config](vector-operations-config.md))
