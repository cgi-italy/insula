# Dataset processings configuration Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/common/raster-operations-config.schema.json#/properties/processings
```

Configuration of dataset processings and tools

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-operations-config.schema.json\*](schemas/common/raster-operations-config.schema.json) |

## processings Type

`object` ([Dataset processings configuration](raster-operations-config-properties-dataset-processings-configuration.md))

# processings Properties

| Property                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                             |
| :-------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [pointInfo](#pointinfo)           | `object` | Optional | cannot be null | [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration.md)      |
| [pointSeries](#pointseries)       | `object` | Optional | cannot be null | [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration.md)    |
| [transectValues](#transectvalues) | `object` | Optional | cannot be null | [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration.md) |
| [areaStats](#areastats)           | `object` | Optional | cannot be null | [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration.md)      |
| [areaSeries](#areaseries)         | `object` | Optional | cannot be null | [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration.md)     |

## pointInfo

Configuration of raster point info tool

`pointInfo`

* is optional

* Type: `object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))

* cannot be null

* defined in: [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration.md)

### pointInfo Type

`object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))

## pointSeries

Configuration of raster point series tool

`pointSeries`

* is optional

* Type: `object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))

* cannot be null

* defined in: [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration.md)

### pointSeries Type

`object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))

## transectValues

Configuration of raster transect values tool

`transectValues`

* is optional

* Type: `object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))

* cannot be null

* defined in: [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration.md)

### transectValues Type

`object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))

## areaStats

Configuration of raster area stats series tool

`areaStats`

* is optional

* Type: `object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))

* cannot be null

* defined in: [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration.md)

### areaStats Type

`object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))

## areaSeries

Configuration of raster area stats series tool

`areaSeries`

* is optional

* Type: `object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))

* cannot be null

* defined in: [Dataset raster operations config](raster-operations-config-defs-dataset-operation-configuration.md)

### areaSeries Type

`object` ([Dataset operation configuration](raster-operations-config-defs-dataset-operation-configuration.md))
