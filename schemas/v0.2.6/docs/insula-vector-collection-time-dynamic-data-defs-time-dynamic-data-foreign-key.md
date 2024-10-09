# Time dynamic data foreign key Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.6/stac/insula-vector-collection-time-dynamic-data.schema.json#/$defs/timeDynamicDataSourceForeignKey
```

Define the relation between the source and the target collection. In SQL terms: FOREIGN KEY(sourceAttribute) REFERENCE targetCollection(targetAttribute)

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                                             |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [insula-vector-collection-time-dynamic-data.schema.json\*](schemas/stac/insula-vector-collection-time-dynamic-data.schema.json) |

## timeDynamicDataSourceForeignKey Type

`object` ([Time dynamic data foreign key](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key.md))

# timeDynamicDataSourceForeignKey Properties

| Property                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                              |
| :------------------------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [sourceAttribute](#sourceattribute)   | `string` | Required | cannot be null | [Vector collection time dynamic data](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-source-property.md)    |
| [targetCollection](#targetcollection) | `string` | Required | cannot be null | [Vector collection time dynamic data](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-collection.md) |
| [targetAttribute](#targetattribute)   | `string` | Required | cannot be null | [Vector collection time dynamic data](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-attribute.md)   |

## sourceAttribute

The id of the attribute in the source collection to use as foreign key

`sourceAttribute`

* is required

* Type: `string` ([Source property](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-source-property.md))

* cannot be null

* defined in: [Vector collection time dynamic data](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-source-property.md)

### sourceAttribute Type

`string` ([Source property](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-source-property.md))

## targetCollection

The ID of the collection containing the time dynamic data

`targetCollection`

* is required

* Type: `string` ([Target collection](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-collection.md))

* cannot be null

* defined in: [Vector collection time dynamic data](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-collection.md)

### targetCollection Type

`string` ([Target collection](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-collection.md))

## targetAttribute

The ID of the attribute referenced in the target collection

`targetAttribute`

* is required

* Type: `string` ([Target attribute](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-attribute.md))

* cannot be null

* defined in: [Vector collection time dynamic data](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-attribute.md)

### targetAttribute Type

`string` ([Target attribute](insula-vector-collection-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-attribute.md))
