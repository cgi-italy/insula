# Dataset processings configuration Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.0/common/vector-operations-config.schema.json#/properties/processings
```

Configuration of dataset processings and tools

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-operations-config.schema.json\*](schemas/common/vector-operations-config.schema.json) |

## processings Type

`object` ([Dataset processings configuration](vector-operations-config-properties-dataset-processings-configuration.md))

# processings Properties

| Property                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                               |
| :------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [pointInfo](#pointinfo)               | `object` | Optional | cannot be null | [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration.md)        |
| [areaDistribution](#areadistribution) | `object` | Optional | cannot be null | [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration.md) |
| [timeDistribution](#timedistribution) | `object` | Optional | cannot be null | [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration.md) |
| [pointSeries](#pointseries)           | `object` | Optional | cannot be null | [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration.md)      |
| [featureTable](#featuretable)         | `object` | Optional | cannot be null | [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration.md)     |

## pointInfo

Configuration of vector feature info tool

`pointInfo`

* is optional

* Type: `object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))

* cannot be null

* defined in: [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration.md)

### pointInfo Type

`object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))

## areaDistribution

Configuration of vector area distribution info tool

`areaDistribution`

* is optional

* Type: `object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))

* cannot be null

* defined in: [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration.md)

### areaDistribution Type

`object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))

## timeDistribution

Configuration of vector time distribution tool

`timeDistribution`

* is optional

* Type: `object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))

* cannot be null

* defined in: [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration.md)

### timeDistribution Type

`object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))

## pointSeries

Configuration of vector point series tool

`pointSeries`

* is optional

* Type: `object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))

* cannot be null

* defined in: [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration.md)

### pointSeries Type

`object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))

## featureTable

Configuration of vector feature table tool

`featureTable`

* is optional

* Type: `object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))

* cannot be null

* defined in: [Dataset vector operations config](vector-operations-config-defs-dataset-operation-configuration.md)

### featureTable Type

`object` ([Dataset operation configuration](vector-operations-config-defs-dataset-operation-configuration.md))
