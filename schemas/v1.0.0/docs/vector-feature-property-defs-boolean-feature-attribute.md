# Boolean feature attribute Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.0.0/common/vector-feature-property.schema.json#/$defs/booleanProperty
```

Definition of vector feature boolean property specific attributes

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-feature-property.schema.json\*](schemas/common/vector-feature-property.schema.json) |

## booleanProperty Type

`object` ([Boolean feature attribute](vector-feature-property-defs-boolean-feature-attribute.md))

# booleanProperty Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                           |
| :------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type) | `string` | Required | cannot be null | [Vector feature property](vector-feature-property-defs-boolean-feature-attribute-properties-boolean-property-type-constant.md) |

## type



`type`

* is required

* Type: `string` ([Boolean property type constant](vector-feature-property-defs-boolean-feature-attribute-properties-boolean-property-type-constant.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-boolean-feature-attribute-properties-boolean-property-type-constant.md)

### type Type

`string` ([Boolean property type constant](vector-feature-property-defs-boolean-feature-attribute-properties-boolean-property-type-constant.md))

### type Constraints

**constant**: the value of this property must be equal to:

```json
"boolean"
```
