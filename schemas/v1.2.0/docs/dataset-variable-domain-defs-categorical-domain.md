# Categorical domain Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/common/vector-feature-property.schema.json#/$defs/enumProperty/properties/domain
```

Definition of a categorical variable domain

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-feature-property.schema.json\*](schemas/common/vector-feature-property.schema.json) |

## domain Type

`object` ([Categorical domain](dataset-variable-domain-defs-categorical-domain.md))

## domain Examples

```json
{
  "values": [
    {
      "value": 0,
      "label": "First"
    },
    {
      "value": 1,
      "label": "Second"
    }
  ]
}
```

# domain Properties

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                   |
| :---------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [values](#values) | `array`  | Required | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values.md) |
| [noData](#nodata) | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-domain-no-data-value.md)      |

## values

The domain allowed values

`values`

* is required

* Type: `object[]` ([Categorical domain item](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values.md)

### values Type

`object[]` ([Categorical domain item](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item.md))

### values Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## noData

The data domain no data value

`noData`

* is optional

* Type: `number` ([Domain no data value](dataset-variable-domain-defs-categorical-domain-properties-domain-no-data-value.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-domain-no-data-value.md)

### noData Type

`number` ([Domain no data value](dataset-variable-domain-defs-categorical-domain-properties-domain-no-data-value.md))
