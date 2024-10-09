# Insula JSON dataset group Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-datasets-group.schema.json
```

Insula JSON dataset group configuration

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [insula-json-datasets-group.schema.json](schemas/apps/insula-json-datasets-group.schema.json "open original schema") |

## Insula JSON dataset group Type

`object` ([Insula JSON dataset group](insula-json-datasets-group.md))

# Insula JSON dataset group Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                  |
| :---------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                     | `string` | Required | cannot be null | [Insula JSON dataset group](insula-json-datasets-group-properties-group-id.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-datasets-group.schema.json#/properties/id")                               |
| [name](#name)                 | `string` | Required | cannot be null | [Insula JSON dataset group](insula-json-datasets-group-properties-group-name.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-datasets-group.schema.json#/properties/name")                           |
| [description](#description)   | `string` | Optional | cannot be null | [Insula JSON dataset group](insula-json-datasets-group-properties-group-description.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-datasets-group.schema.json#/properties/description")             |
| [geoserverUrl](#geoserverurl) | `string` | Optional | cannot be null | [Insula JSON dataset group](insula-json-datasets-group-properties-group-geoserver-instance-url.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-datasets-group.schema.json#/properties/geoserverUrl") |
| [datasets](#datasets)         | `array`  | Required | cannot be null | [Insula JSON dataset group](insula-json-datasets-group-properties-datasets-list.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-datasets-group.schema.json#/properties/datasets")                    |

## id

The group identifier

`id`

* is required

* Type: `string` ([Group ID](insula-json-datasets-group-properties-group-id.md))

* cannot be null

* defined in: [Insula JSON dataset group](insula-json-datasets-group-properties-group-id.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-datasets-group.schema.json#/properties/id")

### id Type

`string` ([Group ID](insula-json-datasets-group-properties-group-id.md))

## name

The group name

`name`

* is required

* Type: `string` ([Group name](insula-json-datasets-group-properties-group-name.md))

* cannot be null

* defined in: [Insula JSON dataset group](insula-json-datasets-group-properties-group-name.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-datasets-group.schema.json#/properties/name")

### name Type

`string` ([Group name](insula-json-datasets-group-properties-group-name.md))

## description

The group description

`description`

* is optional

* Type: `string` ([Group description](insula-json-datasets-group-properties-group-description.md))

* cannot be null

* defined in: [Insula JSON dataset group](insula-json-datasets-group-properties-group-description.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-datasets-group.schema.json#/properties/description")

### description Type

`string` ([Group description](insula-json-datasets-group-properties-group-description.md))

## geoserverUrl

An optional URL of an external geoserver instance. If not provided the platform geoserver instance will be used

`geoserverUrl`

* is optional

* Type: `string` ([Group geoserver instance url](insula-json-datasets-group-properties-group-geoserver-instance-url.md))

* cannot be null

* defined in: [Insula JSON dataset group](insula-json-datasets-group-properties-group-geoserver-instance-url.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-datasets-group.schema.json#/properties/geoserverUrl")

### geoserverUrl Type

`string` ([Group geoserver instance url](insula-json-datasets-group-properties-group-geoserver-instance-url.md))

## datasets

The list of datasets for the group

`datasets`

* is required

* Type: an array of merged types ([Insula JSON dataset](insula-json-dataset.md))

* cannot be null

* defined in: [Insula JSON dataset group](insula-json-datasets-group-properties-datasets-list.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-datasets-group.schema.json#/properties/datasets")

### datasets Type

an array of merged types ([Insula JSON dataset](insula-json-dataset.md))
