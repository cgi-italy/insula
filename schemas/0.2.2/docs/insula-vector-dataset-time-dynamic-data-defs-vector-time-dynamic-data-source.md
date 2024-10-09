# Vector time dynamic data source Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-vector-dataset-time-dynamic-data.schema.json#/$defs/timeDynamicDataSource
```

Vector time dynamic data source

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                                       |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [insula-vector-dataset-time-dynamic-data.schema.json\*] (schemas/apps/insula-vector-dataset-time-dynamic-data.schema.json) |

## timeDynamicDataSource Type

`object` ([Vector time dynamic data source](insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source.md))

# timeDynamicDataSource Properties

| Property                                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                               |
| :------------------------------------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [foreignKey](#foreignkey)                   | `object` | Required | cannot be null | [Vector dataset time dynamic data] (insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key.md)                                                        |
| [targetTimeAttribute](#targettimeattribute) | `string` | Required | cannot be null | [Vector dataset time dynamic data] (insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source-properties-target-collection-time-attribute.md) |
| [targetAttributes](#targetattributes)       | `array`  | Optional | cannot be null | [Vector dataset time dynamic data] (insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source-properties-target-layer-feature-attributes.md)     |

## foreignKey

Define the relation between the source and the target collection. In SQL terms: FOREIGN KEY(sourceAttribute) REFERENCE targetCollection(targetAttribute)

`foreignKey`

* is required

* Type: `object` ([Time dynamic data foreign key](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key.md))

* cannot be null

* defined in: [Vector dataset time dynamic data] (insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key.md)

### foreignKey Type

`object` ([Time dynamic data foreign key](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key.md))

## targetTimeAttribute

The target collection attribute to be used as time. Shall be of 'date' type

`targetTimeAttribute`

* is required

* Type: `string` ([Target collection time attribute](insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source-properties-target-collection-time-attribute.md))

* cannot be null

* defined in: [Vector dataset time dynamic data] (insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source-properties-target-collection-time-attribute.md)

### targetTimeAttribute Type

`string` ([Target collection time attribute](insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source-properties-target-collection-time-attribute.md))

## targetAttributes



`targetAttributes`

* is optional

* Type: an array of merged types ([Vector feature property](vector-feature-property.md))

* cannot be null

* defined in: [Vector dataset time dynamic data] (insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source-properties-target-layer-feature-attributes.md)

### targetAttributes Type

an array of merged types ([Vector feature property](vector-feature-property.md))
