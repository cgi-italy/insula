# Dataset vector operations config Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.0/common/vector-operations-config.schema.json
```

Configuration for vector dataset operations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-operations-config.schema.json](schemas/common/vector-operations-config.schema.json) |

## Dataset vector operations config Type

`object` ([Dataset vector operations config](vector-operations-config.md))

# Dataset vector operations config Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                           |
| :-------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [download](#download)       | `object` | Optional | cannot be null | [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration.md)            |
| [processings](#processings) | `object` | Optional | cannot be null | [Dataset vector operations config](vector-operations-config-properties-dataset-processings-configuration.md) |

## download



`download`

* is optional

* Type: `object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))

* cannot be null

* defined in: [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration.md)

### download Type

`object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))

## processings

Configuration of dataset processings and tools

`processings`

* is optional

* Type: `object` ([Dataset processings configuration](vector-operations-config-properties-dataset-processings-configuration.md))

* cannot be null

* defined in: [Dataset vector operations config](vector-operations-config-properties-dataset-processings-configuration.md)

### processings Type

`object` ([Dataset processings configuration](vector-operations-config-properties-dataset-processings-configuration.md))

# Dataset vector operations config Definitions

## Definitions group operationCommonProperties

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.1.0/common/vector-operations-config.schema.json#/$defs/operationCommonProperties"}
```

| Property              | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                        |
| :-------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [disabled](#disabled) | `boolean` | Optional | cannot be null | [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md) |

### disabled

When set the dataset operation will be disabled

`disabled`

* is optional

* Type: `boolean` ([Disable flag](vector-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md))

* cannot be null

* defined in: [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md)

#### disabled Type

`boolean` ([Disable flag](vector-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md))
