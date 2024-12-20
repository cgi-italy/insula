# Raster band variable Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/common/raster-dataset-visualization-config.schema.json#/$defs/rasterBand/allOf/0
```

Raster band variable definition

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-dataset-visualization-config.schema.json\*](schemas/common/raster-dataset-visualization-config.schema.json) |

## 0 Type

`object` ([Raster band variable](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable.md))

# 0 Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                        |
| :-------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [idx](#idx)                 | `number` | Optional | cannot be null | [Raster dataset visualization config](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-index.md)               |
| [id](#id)                   | `string` | Optional | cannot be null | [Raster dataset visualization config](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-identifier.md)           |
| [name](#name)               | `string` | Required | cannot be null | [Raster dataset visualization config](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-name.md)               |
| [description](#description) | `string` | Optional | cannot be null | [Raster dataset visualization config](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-description.md) |
| [quantity](#quantity)       | `object` | Optional | cannot be null | [Raster dataset visualization config](measured-quantity.md)                                                                                                                |
| [domain](#domain)           | Merged   | Optional | cannot be null | [Raster dataset visualization config](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-domain.md)                |

## idx

The band index. If not specified position in the array will be used as band index

`idx`

* is optional

* Type: `number` ([Band index](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-index.md))

* cannot be null

* defined in: [Raster dataset visualization config](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-index.md)

### idx Type

`number` ([Band index](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-index.md))

## id

The band internal identifier. Deprecated: use idx instead

`id`

* is optional

* Type: `string` ([Band identifier](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-identifier.md))

* cannot be null

* defined in: [Raster dataset visualization config](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-identifier.md)

### id Type

`string` ([Band identifier](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-identifier.md))

## name

The name of the band

`name`

* is required

* Type: `string` ([Band name](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-name.md))

* cannot be null

* defined in: [Raster dataset visualization config](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-name.md)

### name Type

`string` ([Band name](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-name.md))

## description

A description for the band

`description`

* is optional

* Type: `string` ([Band description](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-description.md))

* cannot be null

* defined in: [Raster dataset visualization config](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-description.md)

### description Type

`string` ([Band description](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-band-description.md))

## quantity

The quantity measured by a variable

`quantity`

* is optional

* Type: `object` ([Measured quantity](measured-quantity.md))

* cannot be null

* defined in: [Raster dataset visualization config](measured-quantity.md)

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

* Type: merged type ([Details](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-domain.md))

* cannot be null

* defined in: [Raster dataset visualization config](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-domain.md)

### domain Type

merged type ([Details](raster-dataset-visualization-config-defs-raster-band-allof-raster-band-variable-properties-domain.md))

one (and only one) of

* [Numeric domain](dataset-variable-domain-defs-numeric-domain.md)

* [Categorical domain](dataset-variable-domain-defs-categorical-domain.md)
