# Dataset variable domain Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/common/dataset-variable-domain.schema.json
```

Definition of a variable domain

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                       |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [dataset-variable-domain.schema.json](schemas/common/dataset-variable-domain.schema.json) |

## Dataset variable domain Type

`object` ([Dataset variable domain](dataset-variable-domain.md))

one (and only one) of

* [Categorical domain](dataset-variable-domain-defs-categorical-domain.md)

* [Numeric domain](dataset-variable-domain-defs-numeric-domain.md)

* [Time domain](dataset-variable-domain-defs-time-domain.md)

# Dataset variable domain Definitions

## Definitions group numericDomain

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.1.1/common/dataset-variable-domain.schema.json#/$defs/numericDomain"}
```

| Property                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                |
| :-------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [min](#min)                       | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-min-domain-value.md)                  |
| [max](#max)                       | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-max-domain-value.md)                  |
| [noData](#nodata)                 | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-no-data-value.md)           |
| [step](#step)                     | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-step.md)                      |
| [scale](#scale)                   | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-scale.md)                    |
| [offset](#offset)                 | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-offset.md)                  |
| [reservedValues](#reservedvalues) | `object` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-reserved-values.md) |

### min

The data domain minimum value

`min`

* is optional

* Type: `number` ([Min domain value](dataset-variable-domain-defs-numeric-domain-properties-min-domain-value.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-min-domain-value.md)

#### min Type

`number` ([Min domain value](dataset-variable-domain-defs-numeric-domain-properties-min-domain-value.md))

### max

The data domain maximum value

`max`

* is optional

* Type: `number` ([Max domain value](dataset-variable-domain-defs-numeric-domain-properties-max-domain-value.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-max-domain-value.md)

#### max Type

`number` ([Max domain value](dataset-variable-domain-defs-numeric-domain-properties-max-domain-value.md))

### noData

The data domain no data value

`noData`

* is optional

* Type: `number` ([Domain no data value](dataset-variable-domain-defs-numeric-domain-properties-domain-no-data-value.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-no-data-value.md)

#### noData Type

`number` ([Domain no data value](dataset-variable-domain-defs-numeric-domain-properties-domain-no-data-value.md))

### step

The data domain step value (discrete domain)

`step`

* is optional

* Type: `number` ([Domain step](dataset-variable-domain-defs-numeric-domain-properties-domain-step.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-step.md)

#### step Type

`number` ([Domain step](dataset-variable-domain-defs-numeric-domain-properties-domain-step.md))

### scale

The scale to apply to the raw values

`scale`

* is optional

* Type: `number` ([Domain scale](dataset-variable-domain-defs-numeric-domain-properties-domain-scale.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-scale.md)

#### scale Type

`number` ([Domain scale](dataset-variable-domain-defs-numeric-domain-properties-domain-scale.md))

#### scale Default Value

The default value is:

```json
1
```

### offset

The offset to apply to the raw values

`offset`

* is optional

* Type: `number` ([Domain offset](dataset-variable-domain-defs-numeric-domain-properties-domain-offset.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-offset.md)

#### offset Type

`number` ([Domain offset](dataset-variable-domain-defs-numeric-domain-properties-domain-offset.md))

### reservedValues

Reserved values with special meaning

`reservedValues`

* is optional

* Type: `object` ([Domain reserved values](dataset-variable-domain-defs-numeric-domain-properties-domain-reserved-values.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-numeric-domain-properties-domain-reserved-values.md)

#### reservedValues Type

`object` ([Domain reserved values](dataset-variable-domain-defs-numeric-domain-properties-domain-reserved-values.md))

## Definitions group timeDomain

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.1.1/common/dataset-variable-domain.schema.json#/$defs/timeDomain"}
```

| Property        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                        |
| :-------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [min](#min-1)   | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md) |
| [max](#max-1)   | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md) |
| [step](#step-1) | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-domain-step.md)    |

### min

The domain minimum date

`min`

* is optional

* Type: `string` ([Min domain date](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md)

#### min Type

`string` ([Min domain date](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md))

#### min Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

### max

The domain maximum date

`max`

* is optional

* Type: `string` ([Max domain date](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md)

#### max Type

`string` ([Max domain date](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md))

#### max Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

### step

The domain time step period

`step`

* is optional

* Type: `string` ([Domain step](dataset-variable-domain-defs-time-domain-properties-domain-step.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-domain-step.md)

#### step Type

`string` ([Domain step](dataset-variable-domain-defs-time-domain-properties-domain-step.md))

#### step Constraints

**duration**: the string must be a duration string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

## Definitions group categoricalDomain

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.1.1/common/dataset-variable-domain.schema.json#/$defs/categoricalDomain"}
```

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                   |
| :------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [values](#values)   | `array`  | Required | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values.md) |
| [noData](#nodata-1) | `number` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-domain-no-data-value.md)      |

### values

The domain allowed values

`values`

* is required

* Type: `object[]` ([Categorical domain item](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values.md)

#### values Type

`object[]` ([Categorical domain item](dataset-variable-domain-defs-categorical-domain-properties-categorical-domain-values-categorical-domain-item.md))

#### values Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.

### noData

The data domain no data value

`noData`

* is optional

* Type: `number` ([Domain no data value](dataset-variable-domain-defs-categorical-domain-properties-domain-no-data-value.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-categorical-domain-properties-domain-no-data-value.md)

#### noData Type

`number` ([Domain no data value](dataset-variable-domain-defs-categorical-domain-properties-domain-no-data-value.md))
