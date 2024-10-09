# Vector feature property Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-property.schema.json
```

Definition of a vector feature property

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                       |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [vector-feature-property.schema.json](schemas/common/vector-feature-property.schema.json) |

## Vector feature property Type

merged type ([Vector feature property](vector-feature-property.md))

all of

* [Vector feature property common attributes](vector-feature-property-defs-vector-feature-property-common-attributes.md)

* one (and only one) of

  * [Vector feature string property](vector-feature-property-defs-vector-feature-string-property.md)

  * [Boolean feature attribute](vector-feature-property-defs-boolean-feature-attribute.md)

  * [Numeric feature attribute](vector-feature-property-defs-numeric-feature-attribute.md)

  * [Enum feature attribute](vector-feature-property-defs-enum-feature-attribute.md)

  * [Date feature attribute](vector-feature-property-defs-date-feature-attribute.md)

## Vector feature property Examples

```json
{:,:,:,: {: 0,: 100
  },: true,: true
}
```

```json
{:,:,:,: true,: true
}
```

```json
{:,:,:,: {: [
      {: 0,:,:
      },
      {: 1,:,:
      }
    ]
  },: true,: true
}
```

# Vector feature property Definitions

## Definitions group common

Reference this group by using

```json
{:}
```

| Property                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                 |
| :-------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                   | `string`  | Required | cannot be null | [Vector feature property](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-identifier.md)             |
| [name](#name)               | `string`  | Required | cannot be null | [Vector feature property](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-title.md)                |
| [description](#description) | `string`  | Optional | cannot be null | [Vector feature property](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-description.md)   |
| [filterable](#filterable)   | `boolean` | Optional | cannot be null | [Vector feature property](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-filtering-flag.md) |
| [sortable](#sortable)       | `boolean` | Optional | cannot be null | [Vector feature property](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-sorting-flag.md)     |
| [quantity](#quantity)       | `object`  | Optional | cannot be null | [Vector feature property](measured-quantity.md)                                                                                                 |

### id

The property id (e.g. column name)

`id`

* is required

* Type: `string` ([Property identifier](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-identifier.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-identifier.md)

#### id Type

`string` ([Property identifier](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-identifier.md))

### name

The property human readable title

`name`

* is required

* Type: `string` ([Property title](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-title.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-title.md)

#### name Type

`string` ([Property title](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-title.md))

### description

The property description

`description`

* is optional

* Type: `string` ([Property description](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-description.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-description.md)

#### description Type

`string` ([Property description](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-description.md))

### filterable

A flag indicating if filtering should be enabled for this property

`filterable`

* is optional

* Type: `boolean` ([Property filtering flag](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-filtering-flag.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-filtering-flag.md)

#### filterable Type

`boolean` ([Property filtering flag](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-filtering-flag.md))

#### filterable Default Value

The default value is:

```json
true
```

### sortable

A flag indicating if sorting should be enabled for this property

`sortable`

* is optional

* Type: `boolean` ([Property sorting flag](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-sorting-flag.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-sorting-flag.md)

#### sortable Type

`boolean` ([Property sorting flag](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-sorting-flag.md))

#### sortable Default Value

The default value is:

```json
true
```

### quantity

The quantity measured by a variable

`quantity`

* is optional

* Type: `object` ([Measured quantity](measured-quantity.md))

* cannot be null

* defined in: [Vector feature property](measured-quantity.md)

#### quantity Type

`object` ([Measured quantity](measured-quantity.md))

#### quantity Examples

```json
{:,:,:,:
}
```

## Definitions group stringProperty

Reference this group by using

```json
{:}
```

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                              |
| :------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)       | `string` | Required | cannot be null | [Vector feature property](vector-feature-property-defs-vector-feature-string-property-properties-string-property-type-constant.md) |
| [subType](#subtype) | `string` | Optional | cannot be null | [Vector feature property](vector-feature-property-defs-vector-feature-string-property-properties-string-property-subtype.md)    |

### type



`type`

* is required

* Type: `string` ([String property type constant](vector-feature-property-defs-vector-feature-string-property-properties-string-property-type-constant.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-vector-feature-string-property-properties-string-property-type-constant.md)

#### type Type

`string` ([String property type constant](vector-feature-property-defs-vector-feature-string-property-properties-string-property-type-constant.md))

#### type Constraints

**constant**: the value of this property must be equal to:

```json
```

### subType



`subType`

* is optional

* Type: `string` ([String property subtype](vector-feature-property-defs-vector-feature-string-property-properties-string-property-subtype.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-vector-feature-string-property-properties-string-property-subtype.md)

#### subType Type

`string` ([String property subtype](vector-feature-property-defs-vector-feature-string-property-properties-string-property-subtype.md))

#### subType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation                                      |
| :----------- | :----------------------------------------------- |
| ``      | The string should be interpreted as an URL       |
| `` | The string should be interpreted as an image URL |

## Definitions group booleanProperty

Reference this group by using

```json
{:}
```

| Property        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                           |
| :-------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type-1) | `string` | Required | cannot be null | [Vector feature property](vector-feature-property-defs-boolean-feature-attribute-properties-boolean-property-type-constant.md) |

### type



`type`

* is required

* Type: `string` ([Boolean property type constant](vector-feature-property-defs-boolean-feature-attribute-properties-boolean-property-type-constant.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-boolean-feature-attribute-properties-boolean-property-type-constant.md)

#### type Type

`string` ([Boolean property type constant](vector-feature-property-defs-boolean-feature-attribute-properties-boolean-property-type-constant.md))

#### type Constraints

**constant**: the value of this property must be equal to:

```json
```

## Definitions group numericProperty

Reference this group by using

```json
{:}
```

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                           |
| :---------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type-2)   | `string` | Required | cannot be null | [Vector feature property](vector-feature-property-defs-numeric-feature-attribute-properties-numeric-property-type-constant.md) |
| [domain](#domain) | `object` | Optional | cannot be null | [Vector feature property](dataset-variable-domain-defs-numeric-domain.md)                                                    |

### type



`type`

* is required

* Type: `string` ([Numeric property type constant](vector-feature-property-defs-numeric-feature-attribute-properties-numeric-property-type-constant.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-numeric-feature-attribute-properties-numeric-property-type-constant.md)

#### type Type

`string` ([Numeric property type constant](vector-feature-property-defs-numeric-feature-attribute-properties-numeric-property-type-constant.md))

#### type Constraints

**constant**: the value of this property must be equal to:

```json
```

### domain

Definition of a numeric variable domain

`domain`

* is optional

* Type: `object` ([Numeric domain](dataset-variable-domain-defs-numeric-domain.md))

* cannot be null

* defined in: [Vector feature property](dataset-variable-domain-defs-numeric-domain.md)

#### domain Type

`object` ([Numeric domain](dataset-variable-domain-defs-numeric-domain.md))

#### domain Examples

```json
{: 0,: 100,: 1,: -1
}
```

## Definitions group enumProperty

Reference this group by using

```json
{:}
```

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                  |
| :------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type-3)     | `string` | Required | cannot be null | [Vector feature property](vector-feature-property-defs-enum-feature-attribute-properties-enum-property-type-constant.md) |
| [domain](#domain-1) | `object` | Required | cannot be null | [Vector feature property](dataset-variable-domain-defs-categorical-domain.md)                                          |

### type



`type`

* is required

* Type: `string` ([Enum property type constant](vector-feature-property-defs-enum-feature-attribute-properties-enum-property-type-constant.md))

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-enum-feature-attribute-properties-enum-property-type-constant.md)

#### type Type

`string` ([Enum property type constant](vector-feature-property-defs-enum-feature-attribute-properties-enum-property-type-constant.md))

#### type Constraints

**constant**: the value of this property must be equal to:

```json
```

### domain

Definition of a categorical variable domain

`domain`

* is required

* Type: `object` ([Categorical domain](dataset-variable-domain-defs-categorical-domain.md))

* cannot be null

* defined in: [Vector feature property](dataset-variable-domain-defs-categorical-domain.md)

#### domain Type

`object` ([Categorical domain](dataset-variable-domain-defs-categorical-domain.md))

#### domain Examples

```json
{: [
    {: 0,:
    },
    {: 1,:
    }
  ]
}
```

## Definitions group dateProperty

Reference this group by using

```json
{:}
```

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                           |
| :------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type-4)     | `string` | Required | cannot be null | [Vector feature property](vector-feature-property-defs-date-feature-attribute-properties-type.md) |
| [domain](#domain-2) | `object` | Optional | cannot be null | [Vector feature property](dataset-variable-domain-defs-time-domain.md)                          |

### type



`type`

* is required

* Type: `string`

* cannot be null

* defined in: [Vector feature property](vector-feature-property-defs-date-feature-attribute-properties-type.md)

#### type Type

`string`

#### type Constraints

**constant**: the value of this property must be equal to:

```json
```

### domain

Definition of a date variable domain

`domain`

* is optional

* Type: `object` ([Time domain](dataset-variable-domain-defs-time-domain.md))

* cannot be null

* defined in: [Vector feature property](dataset-variable-domain-defs-time-domain.md)

#### domain Type

`object` ([Time domain](dataset-variable-domain-defs-time-domain.md))

#### domain Examples

```json
{:,:
}
```
