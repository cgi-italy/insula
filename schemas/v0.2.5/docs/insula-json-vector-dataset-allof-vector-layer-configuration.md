# Vector layer configuration Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-vector-dataset.schema.json#/allOf/1
```

Geoserver vector layer information

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                             |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [insula-json-vector-dataset.schema.json\*](schemas/apps/insula-json-vector-dataset.schema.json) |

## 1 Type

`object` ([Vector layer configuration](insula-json-vector-dataset-allof-vector-layer-configuration.md))

# 1 Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                              |
| :---------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [featureTypeName](#featuretypename) | `string` | Required | cannot be null | [Insula vector dataset](insula-json-vector-dataset-allof-vector-layer-configuration-properties-feature-typename.md) |
| [timeDynamicData](#timedynamicdata) | `object` | Optional | cannot be null | [Insula vector dataset](insula-vector-dataset-time-dynamic-data.md)                                    |

## featureTypeName

The WFS feature type name

`featureTypeName`

* is required

* Type: `string` ([Feature typename](insula-json-vector-dataset-allof-vector-layer-configuration-properties-feature-typename.md))

* cannot be null

* defined in: [Insula vector dataset](insula-json-vector-dataset-allof-vector-layer-configuration-properties-feature-typename.md)

### featureTypeName Type

`string` ([Feature typename](insula-json-vector-dataset-allof-vector-layer-configuration-properties-feature-typename.md))

## timeDynamicData

Definition of a vector dataset time dynamic data. Allows to perform time series on one or more attribute, for which the data is stored in an external collection. All numeric properties of the external collection will be considered as time dynamic attributes.

`timeDynamicData`

* is optional

* Type: `object` ([Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data.md))

* cannot be null

* defined in: [Insula vector dataset](insula-vector-dataset-time-dynamic-data.md)

### timeDynamicData Type

`object` ([Vector dataset time dynamic data](insula-vector-dataset-time-dynamic-data.md))

### timeDynamicData Examples

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
