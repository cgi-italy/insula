# Vector collection tag Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.6/common/platform-collection.schema.json#/$defs/platformVectorCollectionTypeObject
```

The vector collection tag

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [platform-collection.schema.json\*](schemas/common/platform-collection.schema.json) |

## platformVectorCollectionTypeObject Type

`object` ([Vector collection tag](platform-collection-defs-vector-collection-tag.md))

# platformVectorCollectionTypeObject Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                               |
| :------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type) | `string` | Required | cannot be null | [Platform collection](platform-collection-defs-vector-collection-tag-properties-vector-collection-type-constant.md) |

## type

The vector collection type constant value

`type`

* is required

* Type: `string` ([Vector collection type constant](platform-collection-defs-vector-collection-tag-properties-vector-collection-type-constant.md))

* cannot be null

* defined in: [Platform collection](platform-collection-defs-vector-collection-tag-properties-vector-collection-type-constant.md)

### type Type

`string` ([Vector collection type constant](platform-collection-defs-vector-collection-tag-properties-vector-collection-type-constant.md))

### type Constraints

**constant**: the value of this property must be equal to:

```json
"vector"
```
