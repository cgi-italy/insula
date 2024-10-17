# Untitled undefined type in Insula JSON dataset Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.0/apps/insula-json-dataset.schema.json#/allOf/1
```



| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                               |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [insula-json-dataset.schema.json\*](schemas/apps/insula-json-dataset.schema.json) |

## 1 Type

merged type ([Details](insula-json-dataset-allof-1.md))

one (and only one) of

* all of

  * all of

    * [Raster collection tag](platform-collection-defs-raster-collection-tag.md)

    * [Raster collection](raster-collection.md)

  * [Raster layer configuration](insula-json-raster-dataset-allof-raster-layer-configuration.md)

* all of

  * all of

    * [Vector collection tag](platform-collection-defs-vector-collection-tag.md)

    * [Vector collection](vector-collection.md)

  * [Vector layer configuration](insula-json-vector-dataset-allof-vector-layer-configuration.md)

* [Insula STAC collection dataset](insula-json-stac-collection-dataset.md)
