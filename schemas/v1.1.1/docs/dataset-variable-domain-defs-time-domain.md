# Time domain Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/common/dataset-variable-domain.schema.json#/$defs/timeDomain
```

Definition of a date variable domain

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [dataset-variable-domain.schema.json\*](schemas/common/dataset-variable-domain.schema.json) |

## timeDomain Type

`object` ([Time domain](dataset-variable-domain-defs-time-domain.md))

## timeDomain Examples

```json
{
  "min": "1928-12-16T00:00:00Z",
  "max": "1982-03-02T23:59:59Z"
}
```

# timeDomain Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                        |
| :------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [min](#min)   | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md) |
| [max](#max)   | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md) |
| [step](#step) | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-domain-step.md)    |

## min

The domain minimum date

`min`

* is optional

* Type: `string` ([Min domain date](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md)

### min Type

`string` ([Min domain date](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md))

### min Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

## max

The domain maximum date

`max`

* is optional

* Type: `string` ([Max domain date](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md)

### max Type

`string` ([Max domain date](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md))

### max Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

## step

The domain time step period

`step`

* is optional

* Type: `string` ([Domain step](dataset-variable-domain-defs-time-domain-properties-domain-step.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-domain-step.md)

### step Type

`string` ([Domain step](dataset-variable-domain-defs-time-domain-properties-domain-step.md))

### step Constraints

**duration**: the string must be a duration string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)
