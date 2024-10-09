# Measured quantity Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/measured-quantity.schema.json
```

The quantity measured by a variable

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [measured-quantity.schema.json](schemas/common/measured-quantity.schema.json) |

## Measured quantity Type

`object` ([Measured quantity](measured-quantity.md))

## Measured quantity Examples

```json
{
  "id": "area_m2",
  "name": "Area",
  "description": "Area in squared meters",
  "units": "m²"
}
```

# Measured quantity Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                 |
| :-------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                   | `string` | Required | cannot be null | [Measured quantity](measured-quantity-properties-quantity-identifier.md)           |
| [name](#name)               | `string` | Optional | cannot be null | [Measured quantity](measured-quantity-properties-quantity-name.md)               |
| [description](#description) | `string` | Optional | cannot be null | [Measured quantity](measured-quantity-properties-quantity-description.md) |
| [units](#units)             | `string` | Optional | cannot be null | [Measured quantity](measured-quantity-properties-quantity-units.md)             |

## id

The quantity identifier. Used to match variables measuring the same quantity

`id`

* is required

* Type: `string` ([Quantity identifier](measured-quantity-properties-quantity-identifier.md))

* cannot be null

* defined in: [Measured quantity](measured-quantity-properties-quantity-identifier.md)

### id Type

`string` ([Quantity identifier](measured-quantity-properties-quantity-identifier.md))

## name

The quantity name

`name`

* is optional

* Type: `string` ([Quantity name](measured-quantity-properties-quantity-name.md))

* cannot be null

* defined in: [Measured quantity](measured-quantity-properties-quantity-name.md)

### name Type

`string` ([Quantity name](measured-quantity-properties-quantity-name.md))

## description

The quantity description

`description`

* is optional

* Type: `string` ([Quantity description](measured-quantity-properties-quantity-description.md))

* cannot be null

* defined in: [Measured quantity](measured-quantity-properties-quantity-description.md)

### description Type

`string` ([Quantity description](measured-quantity-properties-quantity-description.md))

## units

The quantity units symbol

`units`

* is optional

* Type: `string` ([Quantity units](measured-quantity-properties-quantity-units.md))

* cannot be null

* defined in: [Measured quantity](measured-quantity-properties-quantity-units.md)

### units Type

`string` ([Quantity units](measured-quantity-properties-quantity-units.md))
