# Categorical domain item Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.8/common/dataset-variable-domain.schema.json#/$defs/categoricalDomain/properties/values/items
```

Definition of a categorical domain item

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [dataset-variable-domain.schema.json\*](schemas/common/dataset-variable-domain.schema.json) |

## items Type

`object` ([Categorical domain item](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item.md))

# items Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                           |
| :-------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [value](#value)             | Multiple | Required | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-value.md)             |
| [label](#label)             | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-label.md)             |
| [description](#description) | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-description.md) |
| [color](#color)             | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-color.md)             |

## value

The domain item value

`value`

* is required

* Type: any of the following: `string` or `number` ([Domain item value](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-value.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-value.md)

### value Type

any of the following: `string` or `number` ([Domain item value](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-value.md))

## label

The human-readable domain item label

`label`

* is optional

* Type: `string` ([Domain item label](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-label.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-label.md)

### label Type

`string` ([Domain item label](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-label.md))

## description

The domain item description

`description`

* is optional

* Type: `string` ([Domain item description](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-description.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-description.md)

### description Type

`string` ([Domain item description](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-description.md))

## color

The color associated to the value. Used for dynamic coloring

`color`

* is optional

* Type: `string` ([Domain item color](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-color.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-color.md)

### color Type

`string` ([Domain item color](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item-properties-domain-item-color.md))
