# Dataset operation configuration Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/common/raster-operations-config.schema.json#/$defs/operationCommonProperties
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-operations-config.schema.json\*](schemas/common/raster-operations-config.schema.json) |

## operationCommonProperties Type

`object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))

# operationCommonProperties Properties

| Property              | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                        |
| :-------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [disabled](#disabled) | `boolean` | Optional | cannot be null | [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md) |

## disabled

When set the dataset operation will be disabled

`disabled`

* is optional

* Type: `boolean` ([Disable flag](raster-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md))

* cannot be null

* defined in: [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md)

### disabled Type

`boolean` ([Disable flag](raster-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md))
