# Enum feature attribute Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.6/common/vector-feature-property.schema.json#/$defs/enumProperty
```

Definition of vector feature enum property specific attributes

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-feature-property.schema.json\*](schemas/common/vector-feature-property.schema.json) |

## enumProperty Type

`object` ([Enum feature attribute](vector-feature-property-defs-enum-feature-attribute.md))

# enumProperty Properties

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                  |
| :---------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)     | `string` | Required | cannot be null | [Vector feature property](vector-feature-property-defs-enum-feature-attribute-properties-enum-property-type-constant.md) |
| [domain](#domain) | `object` | Required | cannot be null | [Vector feature property](dataset-variable-domain-defs-categorical-domain.md)                                          |

## type



`type`

* is required

* Type: `string` ([Enum property type constant](vector-feature-property-defs-enum-feature-attribute-properties-enum-property-type-constant.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-enum-feature-attribute-properties-enum-property-type-constant.md)

### type Type

`string` ([Enum property type constant](vector-feature-property-defs-enum-feature-attribute-properties-enum-property-type-constant.md))

### type Constraints

**constant**: the value of this property must be equal to:

```json
"enum"
```

## domain

Definition of a categorical variable domain

`domain`

* is required

* Type: `object` ([Categorical domain](dataset-variable-domain-defs-categorical-domain.md))

* cannot be null

* defined in: [Vector feature property](dataset-variable-domain-defs-categorical-domain.md)

### domain Type

`object` ([Categorical domain](dataset-variable-domain-defs-categorical-domain.md))

### domain Examples

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
