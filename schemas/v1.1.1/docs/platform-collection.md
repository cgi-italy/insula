# Platform collection Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.1/common/platform-collection.schema.json
```

Platform collection metadata

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                               |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [platform-collection.schema.json](schemas/common/platform-collection.schema.json) |

## Platform collection Type

`object` ([Platform collection](platform-collection.md))

one (and only one) of

* all of

  * [Raster collection tag](platform-collection-defs-raster-collection-tag.md)

  * [Raster collection](raster-collection.md)

* all of

  * [Vector collection tag](platform-collection-defs-vector-collection-tag.md)

  * [Vector collection](vector-collection.md)

# Platform collection Definitions

## Definitions group platformRasterCollection

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.1.1/common/platform-collection.schema.json#/$defs/platformRasterCollection"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group platformVectorCollection

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.1.1/common/platform-collection.schema.json#/$defs/platformVectorCollection"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group platformRasterCollectionTypeObject

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.1.1/common/platform-collection.schema.json#/$defs/platformRasterCollectionTypeObject"}
```

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                               |
| :------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)       | `string` | Required | cannot be null | [Platform collection](platform-collection-defs-raster-collection-tag-properties-raster-collection-type-constant.md) |
| [version](#version) | `string` | Required | cannot be null | [Platform collection](platform-collection-defs-raster-collection-tag-properties-metadata-version.md)             |

### type

The raster collection type constant value

`type`

* is required

* Type: `string` ([Raster collection type constant](platform-collection-defs-raster-collection-tag-properties-raster-collection-type-constant.md))

* cannot be null

* defined in: [Platform collection](platform-collection-defs-raster-collection-tag-properties-raster-collection-type-constant.md)

#### type Type

`string` ([Raster collection type constant](platform-collection-defs-raster-collection-tag-properties-raster-collection-type-constant.md))

#### type Constraints

**constant**: the value of this property must be equal to:

```json
"raster"
```

### version

The collection metadata version

`version`

* is required

* Type: `string` ([Metadata version](platform-collection-defs-raster-collection-tag-properties-metadata-version.md))

* cannot be null

* defined in: [Platform collection](platform-collection-defs-raster-collection-tag-properties-metadata-version.md)

#### version Type

`string` ([Metadata version](platform-collection-defs-raster-collection-tag-properties-metadata-version.md))

#### version Constraints

**constant**: the value of this property must be equal to:

```json
"v1.1.1"
```

## Definitions group platformVectorCollectionTypeObject

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.1.1/common/platform-collection.schema.json#/$defs/platformVectorCollectionTypeObject"}
```

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                               |
| :-------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type-1)       | `string` | Required | cannot be null | [Platform collection](platform-collection-defs-vector-collection-tag-properties-vector-collection-type-constant.md) |
| [version](#version-1) | `string` | Required | cannot be null | [Platform collection](platform-collection-defs-vector-collection-tag-properties-metadata-version.md)             |

### type

The vector collection type constant value

`type`

* is required

* Type: `string` ([Vector collection type constant](platform-collection-defs-vector-collection-tag-properties-vector-collection-type-constant.md))

* cannot be null

* defined in: [Platform collection](platform-collection-defs-vector-collection-tag-properties-vector-collection-type-constant.md)

#### type Type

`string` ([Vector collection type constant](platform-collection-defs-vector-collection-tag-properties-vector-collection-type-constant.md))

#### type Constraints

**constant**: the value of this property must be equal to:

```json
"vector"
```

### version

The collection metadata version

`version`

* is required

* Type: `string` ([Metadata version](platform-collection-defs-vector-collection-tag-properties-metadata-version.md))

* cannot be null

* defined in: [Platform collection](platform-collection-defs-vector-collection-tag-properties-metadata-version.md)

#### version Type

`string` ([Metadata version](platform-collection-defs-vector-collection-tag-properties-metadata-version.md))

#### version Constraints

**constant**: the value of this property must be equal to:

```json
"v1.1.1"
```
