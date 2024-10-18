# Domain step Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/common/dataset-variable-domain.schema.json#/$defs/timeDomain/properties/step
```

The domain time step period

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [dataset-variable-domain.schema.json\*](schemas/common/dataset-variable-domain.schema.json) |

## step Type

`string` ([Domain step](dataset-variable-domain-defs-time-domain-properties-domain-step.md))

## step Constraints

**duration**: the string must be a duration string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)
