# Insula STAC item property fields Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/stac/insula-stac-extension.schema.json#/definitions/itemFields
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [insula-stac-extension.schema.json\*](schemas/stac/insula-stac-extension.schema.json) |

## itemFields Type

`object` ([Insula STAC item property fields](insula-stac-extension-definitions-insula-stac-item-property-fields.md))

# itemFields Properties

| Property                                                                 | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                    |
| :----------------------------------------------------------------------- | :------------ | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [insula:productIdentifier](#insulaproductidentifier)                     | `string`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-product-identifier.md)  |
| [insula:collection](#insulacollection)                                   | `string`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-product-collection.md)         |
| [insula:owner](#insulaowner)                                             | `string`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-resource-owner.md)                  |
| [insula:platformparam](#insulaplatformparam)                             | `string`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-params.md)         |
| [insula:platformFileType](#insulaplatformfiletype)                       | `string`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-file-type.md)   |
| [insula:filename](#insulafilename)                                       | `string`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-file-name.md)           |
| [insula:jobOwner](#insulajobowner)                                       | `string`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-owner.md)                    |
| [insula:jobId](#insulajobid)                                             | `string`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-identifier.md)                  |
| [insula:intJobId](#insulaintjobid)                                       | `integer`     | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-numeric-identifier.md)       |
| [insula:jobStartDate](#insulajobstartdate)                               | `string`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-start-date.md)           |
| [insula:jobEndDate](#insulajobenddate)                                   | `string`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-end-date.md)               |
| [insula:serviceName](#insulaservicename)                                 | `string`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-service-name.md)              |
| [insula:catalogueSpecificProperties](#insulacataloguespecificproperties) | `object`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-additional-catalogue-specific-metadata.md)                |
| `^(?!insula:)`                                                           | Not specified | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-patternproperties-namespace-sealing.md) |

## insula:productIdentifier

Catalogue product identifier

`insula:productIdentifier`

* is optional

* Type: `string` ([Product identifier](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-product-identifier.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-product-identifier.md)

### insula:productIdentifier Type

`string` ([Product identifier](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-product-identifier.md))

## insula:collection

Product collection

`insula:collection`

* is optional

* Type: `string` ([Product collection](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-product-collection.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-product-collection.md)

### insula:collection Type

`string` ([Product collection](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-product-collection.md))

## insula:owner

The platform user owner of the resource

`insula:owner`

* is optional

* Type: `string` ([Resource owner](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-resource-owner.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-resource-owner.md)

### insula:owner Type

`string` ([Resource owner](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-resource-owner.md))

## insula:platformparam

Internal platform metadata encoded as JSON string

`insula:platformparam`

* is optional

* Type: `string` ([Platform params](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-params.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-params.md)

### insula:platformparam Type

`string` ([Platform params](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-params.md))

## insula:platformFileType

Internal platform file type

`insula:platformFileType`

* is optional

* Type: `string` ([Platform file type](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-file-type.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-file-type.md)

### insula:platformFileType Type

`string` ([Platform file type](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-file-type.md))

### insula:platformFileType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                | Explanation |
| :------------------- | :---------- |
| `"REFERENCE_DATA"`   |             |
| `"OUTPUT_PRODUCT"`   |             |
| `"EXTERNAL_PRODUCT"` |             |
| `"REMOTE_DATA"`      |             |

## insula:filename

Internal platform file name

`insula:filename`

* is optional

* Type: `string` ([Platform file name](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-file-name.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-file-name.md)

### insula:filename Type

`string` ([Platform file name](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-platform-file-name.md))

## insula:jobOwner

The platform user that executed the job that produced the product

`insula:jobOwner`

* is optional

* Type: `string` ([Job owner](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-owner.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-owner.md)

### insula:jobOwner Type

`string` ([Job owner](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-owner.md))

## insula:jobId

String identifier of the job that produced the product

`insula:jobId`

* is optional

* Type: `string` ([Job identifier](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-identifier.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-identifier.md)

### insula:jobId Type

`string` ([Job identifier](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-identifier.md))

## insula:intJobId

Numeric identifier of the job that produced the product

`insula:intJobId`

* is optional

* Type: `integer` ([Job numeric identifier](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-numeric-identifier.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-numeric-identifier.md)

### insula:intJobId Type

`integer` ([Job numeric identifier](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-numeric-identifier.md))

## insula:jobStartDate

Start time of the job that produced the product

`insula:jobStartDate`

* is optional

* Type: `string` ([Job start date](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-start-date.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-start-date.md)

### insula:jobStartDate Type

`string` ([Job start date](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-start-date.md))

### insula:jobStartDate Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

## insula:jobEndDate

End time of the job that produced the product

`insula:jobEndDate`

* is optional

* Type: `string` ([Job end date](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-end-date.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-end-date.md)

### insula:jobEndDate Type

`string` ([Job end date](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-job-end-date.md))

### insula:jobEndDate Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

## insula:serviceName

Name of the processing service that produced the product

`insula:serviceName`

* is optional

* Type: `string` ([Service name](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-service-name.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-service-name.md)

### insula:serviceName Type

`string` ([Service name](insula-stac-extension-definitions-insula-stac-item-property-fields-properties-service-name.md))

## insula:catalogueSpecificProperties



`insula:catalogueSpecificProperties`

* is optional

* Type: `object` ([Additional catalogue specific metadata](insula-stac-extension-definitions-additional-catalogue-specific-metadata.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-additional-catalogue-specific-metadata.md)

### insula:catalogueSpecificProperties Type

`object` ([Additional catalogue specific metadata](insula-stac-extension-definitions-additional-catalogue-specific-metadata.md))

## Pattern: `^(?!insula:)`

Prevent setting additional insula properties

`^(?!insula:)`

* is optional

* Type: unknown ([Namespace sealing](insula-stac-extension-definitions-insula-stac-item-property-fields-patternproperties-namespace-sealing.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-property-fields-patternproperties-namespace-sealing.md)

### ^(?!insula:) Type

unknown ([Namespace sealing](insula-stac-extension-definitions-insula-stac-item-property-fields-patternproperties-namespace-sealing.md))
