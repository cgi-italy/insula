# Dataset raster operations config Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/common/raster-operations-config.schema.json
```

Configuration for raster dataset operations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-operations-config.schema.json](schemas/common/raster-operations-config.schema.json) |

## Dataset raster operations config Type

`object` ([Dataset raster operations config](raster-operations-config.md))

# Dataset raster operations config Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                           |
| :-------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [download](#download)       | `object` | Optional | cannot be null | [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration.md)            |
| [processings](#processings) | `object` | Optional | cannot be null | [Dataset raster operations config](raster-operations-config-properties-dataset-processings-configuration.md) |

## download

Configuration of download tool

`download`

* is optional

* Type: `object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))

* cannot be null

* defined in: [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration.md)

### download Type

`object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))

## processings

Configuration of dataset processings and tools

`processings`

* is optional

* Type: `object` ([Dataset processings configuration](raster-operations-config-properties-dataset-processings-configuration.md))

* cannot be null

* defined in: [Dataset raster operations config](raster-operations-config-properties-dataset-processings-configuration.md)

### processings Type

`object` ([Dataset processings configuration](raster-operations-config-properties-dataset-processings-configuration.md))

# Dataset raster operations config Definitions

## Definitions group operationCommonProperties

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/common/raster-operations-config.schema.json#/$defs/operationCommonProperties"}
```

| Property              | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                        |
| :-------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [disabled](#disabled) | `boolean` | Optional | cannot be null | [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md) |

### disabled

When set the dataset operation will be disabled

`disabled`

* is optional

* Type: `boolean` ([Disable flag](raster-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md))

* cannot be null

* defined in: [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md)

#### disabled Type

`boolean` ([Disable flag](raster-operations-config-defs-dataset-operation-configuration-properties-disable-flag.md))
