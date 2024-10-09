# Numeric feature attribute Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.8/common/vector-feature-property.schema.json#/$defs/numericProperty
```

Definition of vector feature numeric property specific attributes

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-feature-property.schema.json\*](schemas/common/vector-feature-property.schema.json) |

## numericProperty Type

`object` ([Numeric feature attribute](vector-feature-property-defs-numeric-feature-attribute.md))

# numericProperty Properties

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                           |
| :---------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)     | `string` | Required | cannot be null | [Vector feature property](vector-feature-property-defs-numeric-feature-attribute-properties-numeric-property-type-constant.md) |
| [domain](#domain) | `object` | Optional | cannot be null | [Vector feature property](dataset-variable-domain-defs-numeric-domain.md)                                                    |

## type



`type`

* is required

* Type: `string` ([Numeric property type constant](vector-feature-property-defs-numeric-feature-attribute-properties-numeric-property-type-constant.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-numeric-feature-attribute-properties-numeric-property-type-constant.md)

### type Type

`string` ([Numeric property type constant](vector-feature-property-defs-numeric-feature-attribute-properties-numeric-property-type-constant.md))

### type Constraints

**constant**: the value of this property must be equal to:

```json
"number"
```

## domain

Definition of a numeric variable domain

`domain`

* is optional

* Type: `object` ([Numeric domain](dataset-variable-domain-defs-numeric-domain.md))

* cannot be null

* defined in: [Vector feature property](dataset-variable-domain-defs-numeric-domain.md)

### domain Type

`object` ([Numeric domain](dataset-variable-domain-defs-numeric-domain.md))

### domain Examples

```json
{
  "min": 0,
  "max": 100,
  "step": 1,
  "noData": -1
}
```
