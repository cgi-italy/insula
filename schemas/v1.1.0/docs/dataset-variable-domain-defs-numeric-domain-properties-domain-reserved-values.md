# Domain reserved values Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.0/common/dataset-variable-domain.schema.json#/$defs/numericDomain/properties/reservedValues
```

Reserved values with special meaning

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [dataset-variable-domain.schema.json\*](schemas/common/dataset-variable-domain.schema.json) |

## reservedValues Type

`object` ([Domain reserved values](dataset-variable-domain-defs-numeric-domain-properties-domain-reserved-values.md))

# reservedValues Properties

| Property        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                         |
| :-------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `^[+-]?[0-9]+$` | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-reserved-values-patternproperties--0-9.md) |

## Pattern: `^[+-]?[0-9]+$`



`^[+-]?[0-9]+$`

* is optional

* Type: `string`

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-reserved-values-patternproperties--0-9.md)

### ^\[+-]?\[0-9]+$ Type

`string`
