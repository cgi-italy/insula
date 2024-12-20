# Raster render config Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/common/raster-dataset-visualization-config.schema.json#/$defs/rasterRenderConfig
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-dataset-visualization-config.schema.json\*](schemas/common/raster-dataset-visualization-config.schema.json) |

## rasterRenderConfig Type

`object` ([Raster render config](raster-dataset-visualization-config-defs-raster-render-config.md))

# rasterRenderConfig Properties

| Property                            | Type   | Required | Nullable       | Defined by                                                                                                                                                                                                            |
| :---------------------------------- | :----- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [defaultBandMode](#defaultbandmode) | Merged | Optional | cannot be null | [Raster dataset visualization config](raster-band-mode-config.md) |

## defaultBandMode

Definition of raster band mode rendering configuration

`defaultBandMode`

* is optional

* Type: merged type ([Raster band mode config](raster-band-mode-config.md))

* cannot be null

* defined in: [Raster dataset visualization config](raster-band-mode-config.md)

### defaultBandMode Type

merged type ([Raster band mode config](raster-band-mode-config.md))

one (and only one) of

* [Single band render mode config](raster-band-mode-config-defs-single-band-render-mode-config.md)

* [Preset render mode config](raster-band-mode-config-defs-preset-render-mode-config.md)

* [Band combination render mode config](raster-band-mode-config-defs-band-combination-render-mode-config.md)
