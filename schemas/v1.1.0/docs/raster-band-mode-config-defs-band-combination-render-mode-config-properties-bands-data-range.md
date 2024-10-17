# Bands data range Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.0/common/raster-band-mode-config.schema.json#/$defs/rasterBandCombinationRenderModeConfig/properties/dataRange
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [raster-band-mode-config.schema.json\*](schemas/common/raster-band-mode-config.schema.json) |

## dataRange Type

`object` ([Bands data range](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range.md))

# dataRange Properties

| Property    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                            |
| :---------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [min](#min) | `number` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range-properties-range-min-value.md) |
| [max](#max) | `number` | Required | cannot be null | [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range-properties-range-max-value.md) |

## min

The band map range minumum value

`min`

* is required

* Type: `number` ([Range min value](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range-properties-range-min-value.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range-properties-range-min-value.md)

### min Type

`number` ([Range min value](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range-properties-range-min-value.md))

## max

The band map range maximum value

`max`

* is required

* Type: `number` ([Range max value](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range-properties-range-max-value.md))

* cannot be null

* defined in: [Raster band mode config](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range-properties-range-max-value.md)

### max Type

`number` ([Range max value](raster-band-mode-config-defs-band-combination-render-mode-config-properties-bands-data-range-properties-range-max-value.md))
