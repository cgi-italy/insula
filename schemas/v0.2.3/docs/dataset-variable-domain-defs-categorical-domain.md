# Categorical domain Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-property.schema.json#/$defs/enumProperty/properties/domain
```

Definition of a categorical variable domain

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [vector-feature-property.schema.json\*](schemas/common/vector-feature-property.schema.json"open original schema") |

## domain Type

`object` ([Categorical domain](dataset-variable-domain-defs-categorical-domain.md))

## domain Examples

```json
{"values": [
    {"value": 0,"label":"First"
    },
    {"value": 1,"label":"Second"
    }
  ]
}
```

# domain Properties

| Property          | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                   |
| :---------------- | :------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [values](#values) | `array` | Required | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/categoricalDomain/properties/values") |

## values

The domain allowed values

`values`

* is required

* Type: `object[]` ([Categorical domain item](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/categoricalDomain/properties/values")

### values Type

`object[]` ([Categorical domain item](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item.md))

### values Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.
