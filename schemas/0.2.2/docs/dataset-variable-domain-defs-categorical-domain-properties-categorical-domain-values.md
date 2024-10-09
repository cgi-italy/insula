# Categorical domain values Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/categoricalDomain/properties/values
```

The domain allowed values

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [dataset-variable-domain.schema.json\*] (schemas/common/dataset-variable-domain.schema.json) |

## values Type

`object[]` ([Categorical domain item](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item.md))

## values Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.
