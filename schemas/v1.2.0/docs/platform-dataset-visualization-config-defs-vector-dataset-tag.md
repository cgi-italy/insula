# Vector dataset tag Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/common/platform-dataset-visualization-config.schema.json#/$defs/platformVectorDatasetTypeObject
```

The vector dataset tag

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [platform-dataset-visualization-config.schema.json\*](schemas/common/platform-dataset-visualization-config.schema.json) |

## platformVectorDatasetTypeObject Type

`object` ([Vector dataset tag](platform-dataset-visualization-config-defs-vector-dataset-tag.md))

# platformVectorDatasetTypeObject Properties

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                            |
| :------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)       | `string` | Required | cannot be null | [Platform dataset visualization config](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-vector-dataset-type-constant.md) |
| [version](#version) | `string` | Required | cannot be null | [Platform dataset visualization config](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-metadata-version.md)          |

## type

The vector dataset type constant value

`type`

* is required

* Type: `string` ([Vector dataset type constant](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-vector-dataset-type-constant.md))

* cannot be null

* defined in: [Platform dataset visualization config](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-vector-dataset-type-constant.md)

### type Type

`string` ([Vector dataset type constant](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-vector-dataset-type-constant.md))

### type Constraints

**constant**: the value of this property must be equal to:

```json
"vector"
```

## version

The metadata version

`version`

* is required

* Type: `string` ([Metadata version](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-metadata-version.md))

* cannot be null

* defined in: [Platform dataset visualization config](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-metadata-version.md)

### version Type

`string` ([Metadata version](platform-dataset-visualization-config-defs-vector-dataset-tag-properties-metadata-version.md))

### version Constraints

**constant**: the value of this property must be equal to:

```json
"v1.2.0"
```
