# String property subtype Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.6/common/vector-feature-property.schema.json#/$defs/stringProperty/properties/subType
```



| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [vector-feature-property.schema.json\*](schemas/common/vector-feature-property.schema.json) |

## subType Type

`string` ([String property subtype](vector-feature-property-defs-vector-feature-string-property-properties-string-property-subtype.md))

## subType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation                                      |
| :----------- | :----------------------------------------------- |
| `"url"`      | The string should be interpreted as an URL       |
| `"imageUrl"` | The string should be interpreted as an image URL |
