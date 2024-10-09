# Raster layer configuration Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.8/apps/insula-json-raster-dataset.schema.json#/allOf/1
```

Geoserver raster layer information

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                             |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [insula-json-raster-dataset.schema.json\*](schemas/apps/insula-json-raster-dataset.schema.json) |

## 1 Type

`object` ([Raster layer configuration](insula-json-raster-dataset-allof-raster-layer-configuration.md))

# 1 Properties

| Property        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                             |
| :-------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [layer](#layer) | `string` | Required | cannot be null | [Insula raster dataset](insula-json-raster-dataset-allof-raster-layer-configuration-properties-wms-layer.md) |

## layer

The WMS layer name

`layer`

* is required

* Type: `string` ([WMS layer](insula-json-raster-dataset-allof-raster-layer-configuration-properties-wms-layer.md))

* cannot be null

* defined in: [Insula raster dataset](insula-json-raster-dataset-allof-raster-layer-configuration-properties-wms-layer.md)

### layer Type

`string` ([WMS layer](insula-json-raster-dataset-allof-raster-layer-configuration-properties-wms-layer.md))
