# Insula platform STAC Extension Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.0.0/stac/insula-stac-extension.schema.json
```

STAC Extension for Insula platform collections.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                 |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [insula-stac-extension.schema.json](schemas/stac/insula-stac-extension.schema.json) |

## Insula platform STAC Extension Type

merged type ([Insula platform STAC Extension](insula-stac-extension.md))

one (and only one) of

* any of

  * all of

    * [Required fields](insula-stac-extension-oneof-basic-collection-properties-anyof-0-allof-required-fields.md)

    * [Insula STAC collection fields](insula-stac-extension-defs-insula-stac-collection-fields.md)

## Insula platform STAC Extension Examples

```json
{
  "id": "my_raster_collection",
  "type": "Collection",
  "stac_extensions": [
    "https://cgi-italy.github.io/insula/schemas/v1.0.0/stac/insula-stac-extension.schema.json"
  ],
  "insula:metadata": {
    "type": "raster",
    "bands": [
      {
        "id": "B01",
        "name": "NIR Band",
        "color": "#CC0000",
        "domain": {
          "min": 0,
          "max": 4000,
          "noData": -1
        },
        "quantity": {
          "id": "reflectance",
          "name": "Reflectance"
        },
        "default": {
          "colorScale": "turbo",
          "range": {
            "min": 0,
            "max": 3200
          },
          "clamp": true
        }
      }
    ]
  }
}
```

```json
{
  "id": "my_vector_collection",
  "type": "Collection",
  "stac_extensions": [
    "https://cgi-italy.github.io/insula/schemas/v1.0.0/stac/insula-stac-extension.schema.json"
  ],
  "insula:metadata": {
    "type": "vector",
    "feautreAttributes": [
      {
        "id": "name",
        "name": "Name",
        "type": "string",
        "description": "Entity name",
        "filterable": true,
        "sortable": true
      },
      {
        "id": "total",
        "name": "Total",
        "type": "number",
        "filterable": true,
        "sortable": true
      },
      {
        "id": "class",
        "name": "Class",
        "type": "enum",
        "domain": {
          "values": [
            {
              "value": 1,
              "label": "First Class"
            },
            {
              "value": 2,
              "label": "Second Class"
            }
          ]
        },
        "filterable": true,
        "sortable": true
      },
      {
        "id": "date",
        "name": "Date",
        "type": "date",
        "domain": {
          "min": "1928-12-16T00:00:00Z",
          "max": "1982-03-02T23:59:59Z"
        }
      }
    ],
    "timeDimensionProperty": "date"
  }
}
```

# Insula platform STAC Extension Definitions

## Definitions group stac\_extensions

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.0.0/stac/insula-stac-extension.schema.json#/$defs/stac_extensions"}
```

| Property                             | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                               |
| :----------------------------------- | :------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [stac\_extensions](#stac_extensions) | `array` | Required | cannot be null | [Insula platform STAC Extension](insula-stac-extension-defs-stac-extensions-attributes-properties-stac-extensions-array.md) |

### stac\_extensions



`stac_extensions`

* is required

* Type: `array` ([STAC extensions array](insula-stac-extension-defs-stac-extensions-attributes-properties-stac-extensions-array.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-defs-stac-extensions-attributes-properties-stac-extensions-array.md)

#### stac\_extensions Type

`array` ([STAC extensions array](insula-stac-extension-defs-stac-extensions-attributes-properties-stac-extensions-array.md))

## Definitions group fields

Reference this group by using

```json
{"$ref":"https://cgi-italy.github.io/insula/schemas/v1.0.0/stac/insula-stac-extension.schema.json#/$defs/fields"}
```

| Property                           | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                |
| :--------------------------------- | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [insula:metadata](#insulametadata) | Merged        | Optional | cannot be null | [Insula platform STAC Extension](platform-collection.md)                                                                              |
| `^(?!insula:)`                     | Not specified | Optional | cannot be null | [Insula platform STAC Extension](insula-stac-extension-defs-insula-stac-collection-fields-patternproperties-namespace-sealing.md) |

### insula:metadata

Platform collection metadata

> Regarding raster collections we should probably extend the 'bands' array and use the raster extension instead of defining it again

`insula:metadata`

* is optional

* Type: `object` ([Platform collection](platform-collection.md))

* cannot be null

* defined in: [Insula platform STAC Extension](platform-collection.md)

#### insula:metadata Type

`object` ([Platform collection](platform-collection.md))

one (and only one) of

* all of

  * [Raster collection tag](platform-collection-defs-raster-collection-tag.md)

  * [Raster collection](raster-collection.md)

* all of

  * [Vector collection tag](platform-collection-defs-vector-collection-tag.md)

  * [Vector collection](vector-collection.md)

### Pattern: `^(?!insula:)`

Prevent setting additional insula properties

`^(?!insula:)`

* is optional

* Type: unknown ([Namespace sealing](insula-stac-extension-defs-insula-stac-collection-fields-patternproperties-namespace-sealing.md))

* cannot be null

* defined in: [Insula platform STAC Extension](insula-stac-extension-defs-insula-stac-collection-fields-patternproperties-namespace-sealing.md)

#### ^(?!insula:) Type

unknown ([Namespace sealing](insula-stac-extension-defs-insula-stac-collection-fields-patternproperties-namespace-sealing.md))
