# Time domain Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-property.schema.json#/$defs/dateProperty/properties/domain
```

Definition of a date variable domain

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [vector-feature-property.schema.json\*](schemas/common/vector-feature-property.schema.json"open original schema") |

## domain Type

`object` ([Time domain](dataset-variable-domain-defs-time-domain.md))

## domain Examples

```json
{"min":"1928-12-16T00:00:00Z","max":"1982-03-02T23:59:59Z"
}
```

# domain Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                        |
| :------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [min](#min)   | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/min") |
| [max](#max)   | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/max") |
| [step](#step) | `string` | Optional | cannot be null | [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-domain-step.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/step")    |

## min

The domain minimum date

`min`

* is optional

* Type: `string` ([Min domain date](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/min")

### min Type

`string` ([Min domain date](dataset-variable-domain-defs-time-domain-properties-min-domain-date.md))

### min Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339"check the specification")

## max

The domain maximum date

`max`

* is optional

* Type: `string` ([Max domain date](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/max")

### max Type

`string` ([Max domain date](dataset-variable-domain-defs-time-domain-properties-max-domain-date.md))

### max Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339"check the specification")

## step

The domain time step period

`step`

* is optional

* Type: `string` ([Domain step](dataset-variable-domain-defs-time-domain-properties-domain-step.md))

* cannot be null

* defined in: [Dataset variable domain](dataset-variable-domain-defs-time-domain-properties-domain-step.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/step")

### step Type

`string` ([Domain step](dataset-variable-domain-defs-time-domain-properties-domain-step.md))

### step Constraints

**duration**: the string must be a duration string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339"check the specification")
