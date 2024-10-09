# Time dynamic data foreign key Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.6/apps/insula-vector-dataset-time-dynamic-data.schema.json#/$defs/timeDynamicDataSourceForeignKey
```

Define the relation between the source and the target collection. In SQL terms: FOREIGN KEY(sourceAttribute) REFERENCE targetCollection(targetAttribute)

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                                       |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [insula-vector-dataset-time-dynamic-data.schema.json\*](schemas/apps/insula-vector-dataset-time-dynamic-data.schema.json) |

## timeDynamicDataSourceForeignKey Type

`object` ([Time dynamic data foreign key](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key.md))

# timeDynamicDataSourceForeignKey Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                   |
| :---------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [sourceAttribute](#sourceattribute) | `string` | Required | cannot be null | [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-source-property.md)  |
| [targetLayer](#targetlayer)         | `string` | Required | cannot be null | [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-layer.md)         |
| [targetAttribute](#targetattribute) | `string` | Required | cannot be null | [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-attribute.md) |

## sourceAttribute

The id of the attribute in the source collection to use as foreign key

`sourceAttribute`

* is required

* Type: `string` ([Source property](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-source-property.md))

* cannot be null

* defined in: [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-source-property.md)

### sourceAttribute Type

`string` ([Source property](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-source-property.md))

## targetLayer

The ID of the collection containing the time dynamic data

`targetLayer`

* is required

* Type: `string` ([Target layer](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-layer.md))

* cannot be null

* defined in: [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-layer.md)

### targetLayer Type

`string` ([Target layer](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-layer.md))

## targetAttribute

The ID of the attribute referenced in the target collection

`targetAttribute`

* is required

* Type: `string` ([Target attribute](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-attribute.md))

* cannot be null

* defined in: [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-attribute.md)

### targetAttribute Type

`string` ([Target attribute](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-attribute.md))
