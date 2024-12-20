# Untitled undefined type in Insula JSON dataset Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/apps/insula-json-dataset.schema.json#/allOf/1
```



| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                               |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [insula-json-dataset.schema.json\*](schemas/apps/insula-json-dataset.schema.json) |

## 1 Type

merged type ([Details](insula-json-dataset-allof-1.md))

one (and only one) of

* all of

  * all of

    * [Raster dataset tag](platform-dataset-visualization-config-defs-raster-dataset-tag.md)

    * [Raster dataset visualization config](raster-dataset-visualization-config.md)

  * [Raster layer configuration](insula-json-raster-dataset-allof-raster-layer-configuration.md)

* all of

  * all of

    * [Vector dataset tag](platform-dataset-visualization-config-defs-vector-dataset-tag.md)

    * [Vector dataset visualization config](vector-dataset-visualization-config.md)

  * [Vector layer configuration](insula-json-vector-dataset-allof-vector-layer-configuration.md)

* [Insula STAC collection dataset](insula-json-stac-collection-dataset.md)
