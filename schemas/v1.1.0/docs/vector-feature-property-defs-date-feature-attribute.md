# Date feature attribute Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.0/common/vector-feature-property.schema.json#/$defs/dateProperty
```

Definition of vector feature date property specific attributes

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-feature-property.schema.json\*](schemas/common/vector-feature-property.schema.json) |

## dateProperty Type

`object` ([Date feature attribute](vector-feature-property-defs-date-feature-attribute.md))

# dateProperty Properties

| Property                                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                       |
| :---------------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)                             | `string` | Required | cannot be null | [Vector feature property](vector-feature-property-defs-date-feature-attribute-properties-type.md)                             |
| [domain](#domain)                         | `object` | Optional | cannot be null | [Vector feature property](dataset-variable-domain-defs-time-domain.md)                                                      |
| [outputStringFormat](#outputstringformat) | `string` | Optional | cannot be null | [Vector feature property](vector-feature-property-defs-date-feature-attribute-properties-string-format.md)      |
| [inputStringFormat](#inputstringformat)   | `string` | Optional | cannot be null | [Vector feature property](vector-feature-property-defs-date-feature-attribute-properties-input-string-format.md) |

## type



`type`

* is required

* Type: `string`

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-date-feature-attribute-properties-type.md)

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

* defined in: [Vector feature property](dataset-variable-domain-defs-time-domain.md)

### domain Type

`object` ([Time domain](dataset-variable-domain-defs-time-domain.md))

### domain Examples

```json
{
  "min": "1928-12-16T00:00:00Z",
  "max": "1982-03-02T23:59:59Z"
}
```

## outputStringFormat

The format used for displaying the date values (ref: <https://momentjs.com/docs/#/displaying/format/>)

`outputStringFormat`

* is optional

* Type: `string` ([String format](vector-feature-property-defs-date-feature-attribute-properties-string-format.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-date-feature-attribute-properties-string-format.md)

### outputStringFormat Type

`string` ([String format](vector-feature-property-defs-date-feature-attribute-properties-string-format.md))

## inputStringFormat

The format used to parse date values from input string. Not supported. Use ISO8601 format

`inputStringFormat`

* is optional

* Type: `string` ([Input string format](vector-feature-property-defs-date-feature-attribute-properties-input-string-format.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-date-feature-attribute-properties-input-string-format.md)

### inputStringFormat Type

`string` ([Input string format](vector-feature-property-defs-date-feature-attribute-properties-input-string-format.md))
