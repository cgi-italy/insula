# Vector feature string property Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.6/common/vector-feature-property.schema.json#/$defs/stringProperty
```

Definition of vector feature string property specific attributes

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-feature-property.schema.json\*](schemas/common/vector-feature-property.schema.json) |

## stringProperty Type

`object` ([Vector feature string property](vector-feature-property-defs-vector-feature-string-property.md))

# stringProperty Properties

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                              |
| :------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)       | `string` | Required | cannot be null | [Vector feature property](vector-feature-property-defs-vector-feature-string-property-properties-string-property-type-constant.md) |
| [subType](#subtype) | `string` | Optional | cannot be null | [Vector feature property](vector-feature-property-defs-vector-feature-string-property-properties-string-property-subtype.md)    |

## type



`type`

* is required

* Type: `string` ([String property type constant](vector-feature-property-defs-vector-feature-string-property-properties-string-property-type-constant.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-vector-feature-string-property-properties-string-property-type-constant.md)

### type Type

`string` ([String property type constant](vector-feature-property-defs-vector-feature-string-property-properties-string-property-type-constant.md))

### type Constraints

**constant**: the value of this property must be equal to:

```json
"string"
```

## subType



`subType`

* is optional

* Type: `string` ([String property subtype](vector-feature-property-defs-vector-feature-string-property-properties-string-property-subtype.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-vector-feature-string-property-properties-string-property-subtype.md)

### subType Type

`string` ([String property subtype](vector-feature-property-defs-vector-feature-string-property-properties-string-property-subtype.md))

### subType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation                                      |
| :----------- | :----------------------------------------------- |
| `"url"`      | The string should be interpreted as an URL       |
| `"imageUrl"` | The string should be interpreted as an image URL |
