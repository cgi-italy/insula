# Numeric domain Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-property.schema.json#/$defs/numericProperty/properties/domain
```

Definition of a numeric variable domain

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [vector-feature-property.schema.json\*](schemas/common/vector-feature-property.schema.json) |

## domain Type

`object` ([Numeric domain](dataset-variable-domain-defs-numeric-domain.md))

## domain Examples

```json
{
  "min": 0,
  "max": 100,
  "step": 1,
  "noData": -1
}
```

# domain Properties

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                      |
| :---------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [min](#min)       | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-min-domain-value.md)        |
| [max](#max)       | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-max-domain-value.md)        |
| [noData](#nodata) | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-no-data-value.md) |
| [step](#step)     | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-step.md)            |

## min

The data domain minimum value

`min`

* is optional

* Type: `number` ([Min domain value](dataset-variable-domain-defs-numeric-domain-properties-min-domain-value.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-min-domain-value.md)

### min Type

`number` ([Min domain value](dataset-variable-domain-defs-numeric-domain-properties-min-domain-value.md))

## max

The data domain maximum value

`max`

* is optional

* Type: `number` ([Max domain value](dataset-variable-domain-defs-numeric-domain-properties-max-domain-value.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-max-domain-value.md)

### max Type

`number` ([Max domain value](dataset-variable-domain-defs-numeric-domain-properties-max-domain-value.md))

## noData

The data domain no data value

`noData`

* is optional

* Type: `number` ([Domain no data value](dataset-variable-domain-defs-numeric-domain-properties-domain-no-data-value.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-no-data-value.md)

### noData Type

`number` ([Domain no data value](dataset-variable-domain-defs-numeric-domain-properties-domain-no-data-value.md))

## step

The data domain step value (discrete domain)

`step`

* is optional

* Type: `number` ([Domain step](dataset-variable-domain-defs-numeric-domain-properties-domain-step.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-step.md)

### step Type

`number` ([Domain step](dataset-variable-domain-defs-numeric-domain-properties-domain-step.md))
