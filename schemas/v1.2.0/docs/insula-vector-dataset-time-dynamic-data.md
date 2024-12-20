# Vector dataset time dynamic data Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/apps/insula-vector-dataset-time-dynamic-data.schema.json
```

Definition of a vector dataset time dynamic data. Allows to perform time series on one or more attribute, for which the data is stored in an external collection. All numeric properties of the external collection will be considered as time dynamic attributes.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [insula-vector-dataset-time-dynamic-data.schema.json](schemas/apps/insula-vector-dataset-time-dynamic-data.schema.json) |

## Vector dataset time dynamic data Type

`object` ([Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data.md))

## Vector dataset time dynamic data Examples

```json
{
  "nameProperty": "idrometer_name",
  "dataSources": [
    {
      "foreignKey": {
        "sourceAttribute": "id",
        "targetLayer": "idrometer_levels",
        "targetAttribute": "idrometer_id"
      },
      "targetTimeAttribute": "obs_time"
    }
  ]
}
```

# Vector dataset time dynamic data Properties

| Property                                                | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                               |
| :------------------------------------------------------ | :------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [dataSources](#datasources)                             | `array` | Required | cannot be null | [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-properties-time-dynamic-data-sources.md)                 |
| [targetDimensionAttributes](#targetdimensionattributes) | `array` | Optional | cannot be null | [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-properties-target-dimension-attributes.md) |

## dataSources

The list of tyme dynamic attributes data sources

`dataSources`

* is required

* Type: `object[]` ([Vector time dynamic data source](insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source.md))

* cannot be null

* defined in: [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-properties-time-dynamic-data-sources.md)

### dataSources Type

`object[]` ([Vector time dynamic data source](insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source.md))

## targetDimensionAttributes

Define the target collection attributes to use as dimensions. Dimensions should be defined in the featureAttributes of the target collections specificied in the dataSources. All data sources should share the same definition.

`targetDimensionAttributes`

* is optional

* Type: `array` ([Target dimension attributes](insula-vector-dataset-time-dynamic-data-properties-target-dimension-attributes.md))

* cannot be null

* defined in: [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-properties-target-dimension-attributes.md)

### targetDimensionAttributes Type

`array` ([Target dimension attributes](insula-vector-dataset-time-dynamic-data-properties-target-dimension-attributes.md))

# Vector dataset time dynamic data Definitions

## Definitions group timeDynamicDataSource

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/apps/insula-vector-dataset-time-dynamic-data.schema.json#/$defs/timeDynamicDataSource"}
```

| Property                                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                               |
| :------------------------------------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [foreignKey](#foreignkey)                   | `object` | Required | cannot be null | [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key.md)                                                        |
| [targetTimeAttribute](#targettimeattribute) | `string` | Required | cannot be null | [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source-properties-target-collection-time-attribute.md) |
| [targetAttributes](#targetattributes)       | `array`  | Optional | cannot be null | [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source-properties-target-layer-feature-attributes.md)     |

### foreignKey

Define the relation between the source and the target collection. In SQL terms: FOREIGN KEY(sourceAttribute) REFERENCE targetCollection(targetAttribute)

`foreignKey`

* is required

* Type: `object` ([Time dynamic data foreign key](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key.md))

* cannot be null

* defined in: [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key.md)

#### foreignKey Type

`object` ([Time dynamic data foreign key](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key.md))

### targetTimeAttribute

The target collection attribute to be used as time. Shall be of 'date' type

`targetTimeAttribute`

* is required

* Type: `string` ([Target collection time attribute](insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source-properties-target-collection-time-attribute.md))

* cannot be null

* defined in: [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source-properties-target-collection-time-attribute.md)

#### targetTimeAttribute Type

`string` ([Target collection time attribute](insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source-properties-target-collection-time-attribute.md))

### targetAttributes



`targetAttributes`

* is optional

* Type: an array of merged types ([Vector feature property](vector-feature-property.md))

* cannot be null

* defined in: [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-vector-time-dynamic-data-source-properties-target-layer-feature-attributes.md)

#### targetAttributes Type

an array of merged types ([Vector feature property](vector-feature-property.md))

## Definitions group timeDynamicDataSourceForeignKey

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/apps/insula-vector-dataset-time-dynamic-data.schema.json#/$defs/timeDynamicDataSourceForeignKey"}
```

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                   |
| :---------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [sourceAttribute](#sourceattribute) | `string` | Required | cannot be null | [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-source-property.md)  |
| [targetLayer](#targetlayer)         | `string` | Required | cannot be null | [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-layer.md)         |
| [targetAttribute](#targetattribute) | `string` | Required | cannot be null | [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-attribute.md) |

### sourceAttribute

The id of the attribute in the source collection to use as foreign key

`sourceAttribute`

* is required

* Type: `string` ([Source property](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-source-property.md))

* cannot be null

* defined in: [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-source-property.md)

#### sourceAttribute Type

`string` ([Source property](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-source-property.md))

### targetLayer

The ID of the collection containing the time dynamic data

`targetLayer`

* is required

* Type: `string` ([Target layer](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-layer.md))

* cannot be null

* defined in: [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-layer.md)

#### targetLayer Type

`string` ([Target layer](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-layer.md))

### targetAttribute

The ID of the attribute referenced in the target collection

`targetAttribute`

* is required

* Type: `string` ([Target attribute](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-attribute.md))

* cannot be null

* defined in: [Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-attribute.md)

#### targetAttribute Type

`string` ([Target attribute](insula-vector-dataset-time-dynamic-data-defs-time-dynamic-data-foreign-key-properties-target-attribute.md))
