# Platform file type Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/stac/insula-stac-extension.schema.json#/definitions/itemFields/properties/insula:platformFileType
```

Internal platform file type

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                   |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [insula-stac-extension.schema.json\*](schemas/stac/insula-stac-extension.schema.json) |

## insula:platformFileType Type

`string` ([Platform file type](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-file-type.md))

## insula:platformFileType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                | Explanation |
| :------------------- | :---------- |
| `"REFERENCE_DATA"`   |             |
| `"OUTPUT_PRODUCT"`   |             |
| `"EXTERNAL_PRODUCT"` |             |
| `"REMOTE_DATA"`      |             |
