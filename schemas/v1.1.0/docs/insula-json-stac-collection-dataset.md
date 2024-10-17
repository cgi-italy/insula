# Insula STAC collection dataset Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.0/apps/insula-json-stac-collection-dataset.schema.json
```

Dataset initialized from a platform STAC collection. The collection must have the STAC metadata required to initialize the dataset

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                             |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [insula-json-stac-collection-dataset.schema.json](schemas/apps/insula-json-stac-collection-dataset.schema.json) |

## Insula STAC collection dataset Type

`object` ([Insula STAC collection dataset](insula-json-stac-collection-dataset.md))

## Insula STAC collection dataset Examples

```json
{
  "type": "stac_collection",
  "collection": "eopaas90e071b58f00477eb3534291e0690da5"
}
```

# Insula STAC collection dataset Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                |
| :------------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)             | `string` | Required | cannot be null | [Insula STAC collection dataset](insula-json-stac-collection-dataset-properties-the-type-constant-value.md)     |
| [collection](#collection) | Multiple | Required | cannot be null | [Insula STAC collection dataset](insula-json-stac-collection-dataset-properties-collection-identifier.md) |

## type



`type`

* is required

* Type: `string` ([The type constant value](insula-json-stac-collection-dataset-properties-the-type-constant-value.md))

* cannot be null

* defined in: [Insula STAC collection dataset](insula-json-stac-collection-dataset-properties-the-type-constant-value.md)

### type Type

`string` ([The type constant value](insula-json-stac-collection-dataset-properties-the-type-constant-value.md))

### type Constraints

**constant**: the value of this property must be equal to:

```json
"stac_collection"
```

## collection

The platform collection identifier. Can be the internal numeric ID or ther RESTO collection identifier

`collection`

* is required

* Type: any of the following: `string` or `number` ([Collection identifier](insula-json-stac-collection-dataset-properties-collection-identifier.md))

* cannot be null

* defined in: [Insula STAC collection dataset](insula-json-stac-collection-dataset-properties-collection-identifier.md)

### collection Type

any of the following: `string` or `number` ([Collection identifier](insula-json-stac-collection-dataset-properties-collection-identifier.md))
