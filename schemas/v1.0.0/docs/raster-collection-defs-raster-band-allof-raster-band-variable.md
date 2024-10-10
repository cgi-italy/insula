# Raster band variable Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.0.0/common/raster-collection.schema.json#/$defs/rasterBand/allOf/0
```

Raster band variable definition

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                             |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-collection.schema.json\*](schemas/common/raster-collection.schema.json) |

## 0 Type

`object` ([Raster band variable](raster-collection-defs-raster-band-allof-raster-band-variable.md))

# 0 Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                  |
| :-------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [idx](#idx)                 | `number` | Optional | cannot be null | [Raster collection](raster-collection-defs-raster-band-allof-raster-band-variable-properties-band-index.md)               |
| [name](#name)               | `string` | Required | cannot be null | [Raster collection](raster-collection-defs-raster-band-allof-raster-band-variable-properties-band-name.md)               |
| [description](#description) | `string` | Optional | cannot be null | [Raster collection](raster-collection-defs-raster-band-allof-raster-band-variable-properties-band-description.md) |
| [quantity](#quantity)       | `object` | Optional | cannot be null | [Raster collection](measured-quantity.md)                                                                            |
| [domain](#domain)           | Merged   | Optional | cannot be null | [Raster collection](raster-collection-defs-raster-band-allof-raster-band-variable-properties-domain.md)                |

## idx

The band index

`idx`

* is optional

* Type: `number` ([Band index](raster-collection-defs-raster-band-allof-raster-band-variable-properties-band-index.md))

* cannot be null

* defined in: [Raster collection](raster-collection-defs-raster-band-allof-raster-band-variable-properties-band-index.md)

### idx Type

`number` ([Band index](raster-collection-defs-raster-band-allof-raster-band-variable-properties-band-index.md))

## name

The name of the band

`name`

* is required

* Type: `string` ([Band name](raster-collection-defs-raster-band-allof-raster-band-variable-properties-band-name.md))

* cannot be null

* defined in: [Raster collection](raster-collection-defs-raster-band-allof-raster-band-variable-properties-band-name.md)

### name Type

`string` ([Band name](raster-collection-defs-raster-band-allof-raster-band-variable-properties-band-name.md))

## description

A description for the band

`description`

* is optional

* Type: `string` ([Band description](raster-collection-defs-raster-band-allof-raster-band-variable-properties-band-description.md))

* cannot be null

* defined in: [Raster collection](raster-collection-defs-raster-band-allof-raster-band-variable-properties-band-description.md)

### description Type

`string` ([Band description](raster-collection-defs-raster-band-allof-raster-band-variable-properties-band-description.md))

## quantity

The quantity measured by a variable

`quantity`

* is optional

* Type: `object` ([Measured quantity](measured-quantity.md))

* cannot be null

* defined in: [Raster collection](measured-quantity.md)

### quantity Type

`object` ([Measured quantity](measured-quantity.md))

### quantity Examples

```json
{
  "id": "area_m2",
  "name": "Area",
  "description": "Area in squared meters",
  "units": "m²"
}
```

## domain



`domain`

* is optional

* Type: merged type ([Details](raster-collection-defs-raster-band-allof-raster-band-variable-properties-domain.md))

* cannot be null

* defined in: [Raster collection](raster-collection-defs-raster-band-allof-raster-band-variable-properties-domain.md)

### domain Type

merged type ([Details](raster-collection-defs-raster-band-allof-raster-band-variable-properties-domain.md))

one (and only one) of

* [Numeric domain](dataset-variable-domain-defs-numeric-domain.md)

* [Categorical domain](dataset-variable-domain-defs-categorical-domain.md)
