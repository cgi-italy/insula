# Raster collection tag Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.0/common/platform-collection.schema.json#/$defs/platformRasterCollectionTypeObject
```

The raster collection tag

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [platform-collection.schema.json\*](schemas/common/platform-collection.schema.json) |

## platformRasterCollectionTypeObject Type

`object` ([Raster collection tag](platform-collection-defs-raster-collection-tag.md))

# platformRasterCollectionTypeObject Properties

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                               |
| :------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)       | `string` | Required | cannot be null | [Platform collection](platform-collection-defs-raster-collection-tag-properties-raster-collection-type-constant.md) |
| [version](#version) | `string` | Required | cannot be null | [Platform collection](platform-collection-defs-raster-collection-tag-properties-metadata-version.md)             |

## type

The raster collection type constant value

`type`

* is required

* Type: `string` ([Raster collection type constant](platform-collection-defs-raster-collection-tag-properties-raster-collection-type-constant.md))

* cannot be null

* defined in: [Platform collection](platform-collection-defs-raster-collection-tag-properties-raster-collection-type-constant.md)

### type Type

`string` ([Raster collection type constant](platform-collection-defs-raster-collection-tag-properties-raster-collection-type-constant.md))

### type Constraints

**constant**: the value of this property must be equal to:

```json
"raster"
```

## version

The collection metadata version

`version`

* is required

* Type: `string` ([Metadata version](platform-collection-defs-raster-collection-tag-properties-metadata-version.md))

* cannot be null

* defined in: [Platform collection](platform-collection-defs-raster-collection-tag-properties-metadata-version.md)

### version Type

`string` ([Metadata version](platform-collection-defs-raster-collection-tag-properties-metadata-version.md))

### version Constraints

**constant**: the value of this property must be equal to:

```json
"v1.1.0"
```
