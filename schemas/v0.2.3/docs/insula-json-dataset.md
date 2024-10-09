# Insula JSON dataset Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-dataset.schema.json
```

Insula JSON dataset configuration

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                             |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [insula-json-dataset.schema.json](schemas/apps/insula-json-dataset.schema.json"open original schema") |

## Insula JSON dataset Type

merged type ([Insula JSON dataset](insula-json-dataset.md))

all of

* [Dataset common properties](insula-json-dataset-defs-dataset-common-properties.md"check type definition")

* one (and only one) of

  * all of

    * all of

      * [Raster collection tag](platform-collection-defs-raster-collection-tag.md"check type definition")

      * [Raster collection](raster-collection.md"check type definition")

    * [Raster layer configuration](insula-json-raster-dataset-allof-raster-layer-configuration.md"check type definition")

  * all of

    * all of

      * [Vector collection tag](platform-collection-defs-vector-collection-tag.md"check type definition")

      * [Vector collection](vector-collection.md"check type definition")

    * [Vector layer configuration](insula-json-vector-dataset-allof-vector-layer-configuration.md"check type definition")

# Insula JSON dataset Definitions

## Definitions group common

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-dataset.schema.json#/$defs/common"}
```

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                |
| :-------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                   | `string` | Required | cannot be null | [Insula JSON dataset](insula-json-dataset-defs-dataset-common-properties-properties-dataset-id.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-dataset.schema.json#/$defs/common/properties/id")                   |
| [name](#name)               | `string` | Required | cannot be null | [Insula JSON dataset](insula-json-dataset-defs-dataset-common-properties-properties-dataset-name.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-dataset.schema.json#/$defs/common/properties/name")               |
| [description](#description) | `string` | Optional | cannot be null | [Insula JSON dataset](insula-json-dataset-defs-dataset-common-properties-properties-dataset-description.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-dataset.schema.json#/$defs/common/properties/description") |
| [thumb](#thumb)             | `string` | Optional | cannot be null | [Insula JSON dataset](insula-json-dataset-defs-dataset-common-properties-properties-dataset-thumb.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-dataset.schema.json#/$defs/common/properties/thumb")             |

### id

The dataset unique identifier

`id`

* is required

* Type: `string` ([Dataset ID](insula-json-dataset-defs-dataset-common-properties-properties-dataset-id.md))

* cannot be null

* defined in: [Insula JSON dataset](insula-json-dataset-defs-dataset-common-properties-properties-dataset-id.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-dataset.schema.json#/$defs/common/properties/id")

#### id Type

`string` ([Dataset ID](insula-json-dataset-defs-dataset-common-properties-properties-dataset-id.md))

### name

The dataset name

`name`

* is required

* Type: `string` ([Dataset name](insula-json-dataset-defs-dataset-common-properties-properties-dataset-name.md))

* cannot be null

* defined in: [Insula JSON dataset](insula-json-dataset-defs-dataset-common-properties-properties-dataset-name.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-dataset.schema.json#/$defs/common/properties/name")

#### name Type

`string` ([Dataset name](insula-json-dataset-defs-dataset-common-properties-properties-dataset-name.md))

### description

The dataset description. HTML content is supported

`description`

* is optional

* Type: `string` ([Dataset description](insula-json-dataset-defs-dataset-common-properties-properties-dataset-description.md))

* cannot be null

* defined in: [Insula JSON dataset](insula-json-dataset-defs-dataset-common-properties-properties-dataset-description.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-dataset.schema.json#/$defs/common/properties/description")

#### description Type

`string` ([Dataset description](insula-json-dataset-defs-dataset-common-properties-properties-dataset-description.md))

### thumb

The dataset thumb URL

`thumb`

* is optional

* Type: `string` ([Dataset thumb](insula-json-dataset-defs-dataset-common-properties-properties-dataset-thumb.md))

* cannot be null

* defined in: [Insula JSON dataset](insula-json-dataset-defs-dataset-common-properties-properties-dataset-thumb.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/apps/insula-json-dataset.schema.json#/$defs/common/properties/thumb")

#### thumb Type

`string` ([Dataset thumb](insula-json-dataset-defs-dataset-common-properties-properties-dataset-thumb.md))
