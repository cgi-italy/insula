# Dataset operation configuration Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/common/vector-operations-config.schema.json#/$defs/operationCommonProperties
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-operations-config.schema.json\*](schemas/common/vector-operations-config.schema.json) |

## operationCommonProperties Type

`object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))

# operationCommonProperties Properties

| Property              | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                        |
| :-------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [disabled](#disabled) | `boolean` | Optional | cannot be null | [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md) |

## disabled

When set the dataset operation will be disabled

`disabled`

* is optional

* Type: `boolean` ([Disable flag](vector-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md))

* cannot be null

* defined in: [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md)

### disabled Type

`boolean` ([Disable flag](vector-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md))
