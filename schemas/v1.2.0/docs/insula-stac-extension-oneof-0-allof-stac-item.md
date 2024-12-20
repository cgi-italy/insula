# STAC item Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/stac/insula-stac-extension.schema.json#/oneOf/0/allOf/1
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [insula-stac-extension.schema.json\*](schemas/stac/insula-stac-extension.schema.json) |

## 1 Type

`object` ([STAC item](insula-stac-extension-oneof-0-allof-stac-item.md))

# 1 Properties

| Property                  | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                  |
| :------------------------ | :------------ | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)             | Not specified | Required | cannot be null | [Insula platform STAC Extension](insula-stac-extension-oneof-0-allof-stac-item-properties-type.md)                              |
| [properties](#properties) | Merged        | Required | cannot be null | [Insula platform STAC Extension](insula-stac-extension-oneof-0-allof-stac-item-properties-insula-stac-item-properties.md) |
| [assets](#assets)         | `object`      | Required | cannot be null | [Insula platform STAC Extension](insula-stac-extension-oneof-0-allof-stac-item-properties-assets.md)                          |

## type



`type`

* is required

* Type: unknown

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-oneof-0-allof-stac-item-properties-type.md)

### type Type

unknown

### type Constraints

**constant**: the value of this property must be equal to:

```json
"Feature"
```

## properties

STAC Item properties

`properties`

* is required

* Type: `object` ([Insula STAC Item properties](insula-stac-extension-oneof-0-allof-stac-item-properties-insula-stac-item-properties.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-oneof-0-allof-stac-item-properties-insula-stac-item-properties.md)

### properties Type

`object` ([Insula STAC Item properties](insula-stac-extension-oneof-0-allof-stac-item-properties-insula-stac-item-properties.md))

all of

* [Insula STAC item property fields](insula-stac-extension-definitions-insula-stac-item-property-fields.md)

## assets



`assets`

* is required

* Type: `object` ([Details](insula-stac-extension-oneof-0-allof-stac-item-properties-assets.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-oneof-0-allof-stac-item-properties-assets.md)

### assets Type

`object` ([Details](insula-stac-extension-oneof-0-allof-stac-item-properties-assets.md))
