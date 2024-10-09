# Date feature attribute Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-property.schema.json#/$defs/dateProperty
```

Definition of vector feature date property specific attributes

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-feature-property.schema.json\*](schemas/common/vector-feature-property.schema.json "open original schema") |

## dateProperty Type

`object` ([Date feature attribute](vector-feature-property-defs-date-feature-attribute.md))

# dateProperty Properties

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                           |
| :---------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)     | `string` | Required | cannot be null | [Vector feature property](vector-feature-property-defs-date-feature-attribute-properties-type.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-property.schema.json#/$defs/dateProperty/properties/type") |
| [domain](#domain) | `object` | Optional | cannot be null | [Vector feature property](dataset-variable-domain-defs-time-domain.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-property.schema.json#/$defs/dateProperty/properties/domain")                          |

## type



`type`

* is required

* Type: `string`

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-date-feature-attribute-properties-type.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-property.schema.json#/$defs/dateProperty/properties/type")

### type Type

`string`

### type Constraints

**constant**: the value of this property must be equal to:

```json
"date"
```

## domain

Definition of a date variable domain

`domain`

* is optional

* Type: `object` ([Time domain](dataset-variable-domain-defs-time-domain.md))

* cannot be null

* defined in: [Vector feature property](dataset-variable-domain-defs-time-domain.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-property.schema.json#/$defs/dateProperty/properties/domain")

### domain Type

`object` ([Time domain](dataset-variable-domain-defs-time-domain.md))

### domain Examples

```json
{
  "min": "1928-12-16T00:00:00Z",
  "max": "1982-03-02T23:59:59Z"
}
```
