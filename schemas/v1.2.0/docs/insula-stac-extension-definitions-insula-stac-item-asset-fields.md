# Insula STAC item asset fields Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/stac/insula-stac-extension.schema.json#/definitions/assetFields
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [insula-stac-extension.schema.json\*](schemas/stac/insula-stac-extension.schema.json) |

## assetFields Type

`object` ([Insula STAC item asset fields](insula-stac-extension-definitions-insula-stac-item-asset-fields.md))

# assetFields Properties

| Property                                                                 | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                  |
| :----------------------------------------------------------------------- | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [insula:catalogueSpecificProperties](#insulacataloguespecificproperties) | `object`      | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-additional-catalogue-specific-metadata.md)             |
| `^(?!insula:)`                                                           | Not specified | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-asset-fields-patternproperties-namespace-sealing.md) |

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

* Type: unknown ([Namespace sealing](insula-stac-extension-definitions-insula-stac-item-asset-fields-patternproperties-namespace-sealing.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-definitions-insula-stac-item-asset-fields-patternproperties-namespace-sealing.md)

### ^(?!insula:) Type

unknown ([Namespace sealing](insula-stac-extension-definitions-insula-stac-item-asset-fields-patternproperties-namespace-sealing.md))
