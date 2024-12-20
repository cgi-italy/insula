# Insula raster dataset Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/apps/insula-json-raster-dataset.schema.json
```

Insula JSON raster dataset configuration

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                           |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [insula-json-raster-dataset.schema.json](schemas/apps/insula-json-raster-dataset.schema.json) |

## Insula raster dataset Type

`object` ([Insula raster dataset](insula-json-raster-dataset.md))

all of

* all of

  * [Raster dataset tag](platform-dataset-visualization-config-defs-raster-dataset-tag.md)

  * [Raster dataset visualization config](raster-dataset-visualization-config.md)

* [Raster layer configuration](insula-json-raster-dataset-allof-raster-layer-configuration.md)

## Insula raster dataset Examples

```json
{
  "type": "raster",
  "layer": "mylayer",
  "bands": [
    {
      "name": "NDVI",
      "quantity": {
        "id": "ndvi",
        "name": "NDVI"
      },
      "domain": {
        "min": -1,
        "max": 1
      },
      "color": "green",
      "default": {
        "colorScale": "turbo",
        "range": {
          "min": 0,
          "max": 1
        },
        "clamp": false
      }
    }
  ]
}
```
