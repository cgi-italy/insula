# Platform dataset visualization config Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/common/platform-dataset-visualization-config.schema.json
```

Platform dataset visualization configuration

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                                   |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [platform-dataset-visualization-config.schema.json](schemas/common/platform-dataset-visualization-config.schema.json) |

## Platform dataset visualization config Type

`object` ([Platform dataset visualization config](platform-dataset-visualization-config.md))

one (and only one) of

* all of

  * [Raster dataset tag](platform-dataset-visualization-config-defs-raster-dataset-tag.md)

  * [Raster dataset visualization config](raster-dataset-visualization-config.md)

* all of

  * [Vector dataset tag](platform-dataset-visualization-config-defs-vector-dataset-tag.md)

  * [Vector dataset visualization config](vector-dataset-visualization-config.md)

# Platform dataset visualization config Definitions

## Definitions group platformRasterDatasetVisualizationConfig

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/common/platform-dataset-visualization-config.schema.json#/$defs/platformRasterDatasetVisualizationConfig"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group platformVectorDatasetVisualizationConfig

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/common/platform-dataset-visualization-config.schema.json#/$defs/platformVectorDatasetVisualizationConfig"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group platformRasterDatasetTypeObject

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/common/platform-dataset-visualization-config.schema.json#/$defs/platformRasterDatasetTypeObject"}
```

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                            |
| :------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)       | `string` | Required | cannot be null | [Platform dataset visualization config](platform-dataset-visualization-config-defs-raster-dataset-tag-properties-raster-dataset-type-constant.md) |
| [version](#version) | `string` | Required | cannot be null | [Platform dataset visualization config](platform-dataset-visualization-config-defs-raster-dataset-tag-properties-metadata-version.md)          |

### type

The raster dataset type constant value

`type`

* is required

* Type: `string` ([Raster dataset type constant](platform-dataset-visualization-config-defs-raster-dataset-tag-properties-raster-dataset-type-constant.md))

* cannot be null

* defined in: [Platform dataset visualization config](platform-dataset-visualization-config-defs-raster-dataset-tag-properties-raster-dataset-type-constant.md)

#### type Type

`string` ([Raster dataset type constant](platform-dataset-visualization-config-defs-raster-dataset-tag-properties-raster-dataset-type-constant.md))

#### type Constraints

**constant**: the value of this property must be equal to:

```json
"raster"
```

### version

The metadata version

`version`

* is required

* Type: `string` ([Metadata version](platform-dataset-visualization-config-defs-raster-dataset-tag-properties-metadata-version.md))

* cannot be null

* defined in: [Platform dataset visualization config](platform-dataset-visualization-config-defs-raster-dataset-tag-properties-metadata-version.md)

#### version Type

`string` ([Metadata version](platform-dataset-visualization-config-defs-raster-dataset-tag-properties-metadata-version.md))

#### version Constraints

**constant**: the value of this property must be equal to:

```json
"v1.2.0"
```

## Definitions group platformVectorDatasetTypeObject

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.2.0/common/platform-dataset-visualization-config.schema.json#/$defs/platformVectorDatasetTypeObject"}
```

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                            |
| :-------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type-1)       | `string` | Required | cannot be null | [Platform dataset visualization config](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-vector-dataset-type-constant.md) |
| [version](#version-1) | `string` | Required | cannot be null | [Platform dataset visualization config](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-metadata-version.md)          |

### type

The vector dataset type constant value

`type`

* is required

* Type: `string` ([Vector dataset type constant](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-vector-dataset-type-constant.md))

* cannot be null

* defined in: [Platform dataset visualization config](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-vector-dataset-type-constant.md)

#### type Type

`string` ([Vector dataset type constant](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-vector-dataset-type-constant.md))

#### type Constraints

**constant**: the value of this property must be equal to:

```json
"vector"
```

### version

The metadata version

`version`

* is required

* Type: `string` ([Metadata version](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-metadata-version.md))

* cannot be null

* defined in: [Platform dataset visualization config](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-metadata-version.md)

#### version Type

`string` ([Metadata version](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-metadata-version.md))

#### version Constraints

**constant**: the value of this property must be equal to:

```json
"v1.2.0"
```
