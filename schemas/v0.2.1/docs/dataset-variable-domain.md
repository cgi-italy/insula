# Dataset variable domain Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json
```

Definition of a variable domain

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                       |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [dataset-variable-domain.schema.json](schemas/common/dataset-variable-domain.schema.json "open original schema") |

## Dataset variable domain Type

`object` ([Dataset variable domain](dataset-variable-domain.md))

one (and only one) of

* [Categorical domain](dataset-variable-domain-defs-categorical-domain.md "check type definition")

* [Numeric domain](dataset-variable-domain-defs-numeric-domain.md "check type definition")

* [Time domain](dataset-variable-domain-defs-time-domain.md "check type definition")

# Dataset variable domain Definitions

## Definitions group numericDomain

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/numericDomain"}
```

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                      |
| :---------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [min](#min)       | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-min-domain-value.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/numericDomain/properties/min")        |
| [max](#max)       | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-max-domain-value.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/numericDomain/properties/max")        |
| [noData](#nodata) | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-no-data-value.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/numericDomain/properties/noData") |
| [step](#step)     | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-step.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/numericDomain/properties/step")            |

### min

The data domain minimum value

`min`

* is optional

* Type: `number` ([Min domain value](dataset-variable-domain-defs-numeric-domain-properties-min-domain-value.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-min-domain-value.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/numericDomain/properties/min")

#### min Type

`number` ([Min domain value](dataset-variable-domain-defs-numeric-domain-properties-min-domain-value.md))

### max

The data domain maximum value

`max`

* is optional

* Type: `number` ([Max domain value](dataset-variable-domain-defs-numeric-domain-properties-max-domain-value.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-max-domain-value.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/numericDomain/properties/max")

#### max Type

`number` ([Max domain value](dataset-variable-domain-defs-numeric-domain-properties-max-domain-value.md))

### noData

The data domain no data value

`noData`

* is optional

* Type: `number` ([Domain no data value](dataset-variable-domain-defs-numeric-domain-properties-domain-no-data-value.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-no-data-value.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/numericDomain/properties/noData")

#### noData Type

`number` ([Domain no data value](dataset-variable-domain-defs-numeric-domain-properties-domain-no-data-value.md))

### step

The data domain step value (discrete domain)

`step`

* is optional

* Type: `number` ([Domain step](dataset-variable-domain-defs-numeric-domain-properties-domain-step.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-step.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/numericDomain/properties/step")

#### step Type

`number` ([Domain step](dataset-variable-domain-defs-numeric-domain-properties-domain-step.md))

## Definitions group timeDomain

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain"}
```

| Property        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                        |
| :-------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [min](#min-1)   | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/min") |
| [max](#max-1)   | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/max") |
| [step](#step-1) | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-domain-step.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/step")    |

### min

The domain minimum date

`min`

* is optional

* Type: `string` ([Min domain date](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/min")

#### min Type

`string` ([Min domain date](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md))

#### min Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

### max

The domain maximum date

`max`

* is optional

* Type: `string` ([Max domain date](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/max")

#### max Type

`string` ([Max domain date](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md))

#### max Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

### step

The domain time step period

`step`

* is optional

* Type: `string` ([Domain step](dataset-variable-domain-defs-time-domain-properties-domain-step.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-domain-step.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/step")

#### step Type

`string` ([Domain step](dataset-variable-domain-defs-time-domain-properties-domain-step.md))

#### step Constraints

**duration**: the string must be a duration string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## Definitions group categoricalDomain

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/categoricalDomain"}
```

| Property          | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                   |
| :---------------- | :------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [values](#values) | `array` | Required | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/categoricalDomain/properties/values") |

### values

The domain allowed values

`values`

* is required

* Type: `object[]` ([Categorical domain item](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values.md "https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/categoricalDomain/properties/values")

#### values Type

`object[]` ([Categorical domain item](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item.md))

#### values Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.
