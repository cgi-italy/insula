# Dataset variable definition Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable.schema.json
```

Definition of a dataset variable

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [dataset-variable.schema.json](schemas/common/dataset-variable.schema.json"open original schema") |

## Dataset variable definition Type

`object` ([Dataset variable definition](dataset-variable.md))

## Dataset variable definition Examples

```json
{"id":"height","name":"Height","quantity": {"id":"altitude_m","name":"Altitude","units":"m"
  },"domain": {"min": 0,"max": 10000
  }
}
```

# Dataset variable definition Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                         |
| :-------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                   | `string` | Required | cannot be null | [Dataset variable definition](dataset-variable-properties-variable-id.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable.schema.json#/properties/id")                   |
| [name](#name)               | `string` | Required | cannot be null | [Dataset variable definition](dataset-variable-properties-variable-name.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable.schema.json#/properties/name")               |
| [description](#description) | `string` | Optional | cannot be null | [Dataset variable definition](dataset-variable-properties-variable-description.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable.schema.json#/properties/description") |
| [quantity](#quantity)       | `object` | Optional | cannot be null | [Dataset variable definition](measured-quantity.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/measured-quantity.schema.json#/properties/quantity")                                  |
| [domain](#domain)           | Merged   | Optional | cannot be null | [Dataset variable definition](dataset-variable-domain.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/properties/domain")                        |

## id

The id of the variable

`id`

* is required

* Type: `string` ([Variable ID](dataset-variable-properties-variable-id.md))

* cannot be null

* defined in: [Dataset variable definition](dataset-variable-properties-variable-id.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable.schema.json#/properties/id")

### id Type

`string` ([Variable ID](dataset-variable-properties-variable-id.md))

## name

The name of the variable

`name`

* is required

* Type: `string` ([Variable name](dataset-variable-properties-variable-name.md))

* cannot be null

* defined in: [Dataset variable definition](dataset-variable-properties-variable-name.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable.schema.json#/properties/name")

### name Type

`string` ([Variable name](dataset-variable-properties-variable-name.md))

## description

A description for the variable

`description`

* is optional

* Type: `string` ([Variable description](dataset-variable-properties-variable-description.md))

* cannot be null

* defined in: [Dataset variable definition](dataset-variable-properties-variable-description.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable.schema.json#/properties/description")

### description Type

`string` ([Variable description](dataset-variable-properties-variable-description.md))

## quantity

The quantity measured by a variable

`quantity`

* is optional

* Type: `object` ([Measured quantity](measured-quantity.md))

* cannot be null

* defined in: [Dataset variable definition](measured-quantity.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/measured-quantity.schema.json#/properties/quantity")

### quantity Type

`object` ([Measured quantity](measured-quantity.md))

### quantity Examples

```json
{"id":"area_m2","name":"Area","description":"Area in squared meters","units":"m²"
}
```

## domain

Definition of a variable domain

`domain`

* is optional

* Type: `object` ([Dataset variable domain](dataset-variable-domain.md))

* cannot be null

* defined in: [Dataset variable definition](dataset-variable-domain.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/properties/domain")

### domain Type

`object` ([Dataset variable domain](dataset-variable-domain.md))

one (and only one) of

* [Categorical domain](dataset-variable-domain-defs-categorical-domain.md"check type definition")

* [Numeric domain](dataset-variable-domain-defs-numeric-domain.md"check type definition")

* [Time domain](dataset-variable-domain-defs-time-domain.md"check type definition")
