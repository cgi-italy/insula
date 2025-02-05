# Insula STAC collection fields Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/stac/insula-stac-extension.schema.json#/$defs/fields
```



> Add your new fields here. Don't require them here, do that above in the corresponding schema.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [insula-stac-extension.schema.json\*](schemas/stac/insula-stac-extension.schema.json) |

## fields Type

`object` ([Insula STAC collection fields](insula-stac-extension-defs-insula-stac-collection-fields.md))

# fields Properties

| Property                           | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                |
| :--------------------------------- | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [insula:metadata](#insulametadata) | Merged        | Optional | cannot be null | [Insula platform STAC Extension](platform-collection.md)                                                                              |
| `^(?!insula:)`                     | Not specified | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-defs-insula-stac-collection-fields-patternproperties-namespace-sealing.md) |

## insula:metadata

Platform collection metadata

> Regarding raster collections we should probably extend the 'bands' array and use the raster extension instead of defining it again

`insula:metadata`

* is optional

* Type: `object` ([Platform collection](platform-collection.md))

* cannot be null

* defined in: [Insula platform STAC Extension](platform-collection.md)

### insula:metadata Type

`object` ([Platform collection](platform-collection.md))

one (and only one) of

* all of

  * [Raster collection tag](platform-collection-defs-raster-collection-tag.md)

  * [Raster collection](raster-collection.md)

* all of

  * [Vector collection tag](platform-collection-defs-vector-collection-tag.md)

  * [Vector collection](vector-collection.md)

## Pattern: `^(?!insula:)`

Prevent setting additional insula properties

`^(?!insula:)`

* is optional

* Type: unknown ([Namespace sealing](insula-stac-extension-defs-insula-stac-collection-fields-patternproperties-namespace-sealing.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-defs-insula-stac-collection-fields-patternproperties-namespace-sealing.md)

### ^(?!insula:) Type

unknown ([Namespace sealing](insula-stac-extension-defs-insula-stac-collection-fields-patternproperties-namespace-sealing.md))
