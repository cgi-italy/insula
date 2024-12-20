# Vector render mode options Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.2.0/common/vector-dataset-render-config.schema.json#/$defs/vectorRenderModeOptions
```

The vector render mode rendering options

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-dataset-render-config.schema.json\*](schemas/common/vector-dataset-render-config.schema.json) |

## vectorRenderModeOptions Type

`object` ([Vector render mode options](vector-dataset-render-config-defs-vector-render-mode-options.md))

# vectorRenderModeOptions Properties

| Property                                      | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                              |
| :-------------------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [defaultColorProperty](#defaultcolorproperty) | `string`  | Optional | cannot be null | [Vector dataset render config](vector-dataset-render-config-defs-vector-render-mode-options-properties-default-color-property-id.md) |
| [optimizeSpeed](#optimizespeed)               | `boolean` | Optional | cannot be null | [Vector dataset render config](vector-dataset-render-config-defs-vector-render-mode-options-properties-optimize-speed.md)                   |
| [clustering](#clustering)                     | `object`  | Optional | cannot be null | [Vector dataset render config](vector-dataset-render-config-defs-vector-render-mode-options-properties-clustering-options.md)                  |
| [labelAttributes](#labelattributes)           | `array`   | Optional | cannot be null | [Vector dataset render config](vector-dataset-render-config-defs-vector-render-mode-options-properties-label-attributes.md)               |
| [forceLocalFiltering](#forcelocalfiltering)   | `boolean` | Optional | cannot be null | [Vector dataset render config](vector-dataset-render-config-defs-vector-render-mode-options-properties-force-local-filtering.md)      |
| [iconUrl](#iconurl)                           | `string`  | Optional | cannot be null | [Vector dataset render config](vector-dataset-render-config-defs-vector-render-mode-options-properties-feature-icon-url.md)                       |

## defaultColorProperty

The attribute to use by default (on layer initialization) for class coloring (shall be of 'enum' type)

`defaultColorProperty`

* is optional

* Type: `string` ([Default color property id](vector-dataset-render-config-defs-vector-render-mode-options-properties-default-color-property-id.md))

* cannot be null

* defined in: [Vector dataset render config](vector-dataset-render-config-defs-vector-render-mode-options-properties-default-color-property-id.md)

### defaultColorProperty Type

`string` ([Default color property id](vector-dataset-render-config-defs-vector-render-mode-options-properties-default-color-property-id.md))

## optimizeSpeed

When set layer will rendere to optimize speed rather than interactivity

`optimizeSpeed`

* is optional

* Type: `boolean` ([Optimize speed](vector-dataset-render-config-defs-vector-render-mode-options-properties-optimize-speed.md))

* cannot be null

* defined in: [Vector dataset render config](vector-dataset-render-config-defs-vector-render-mode-options-properties-optimize-speed.md)

### optimizeSpeed Type

`boolean` ([Optimize speed](vector-dataset-render-config-defs-vector-render-mode-options-properties-optimize-speed.md))

## clustering

Feature clustering options

`clustering`

* is optional

* Type: `object` ([Clustering options](vector-dataset-render-config-defs-vector-render-mode-options-properties-clustering-options.md))

* cannot be null

* defined in: [Vector dataset render config](vector-dataset-render-config-defs-vector-render-mode-options-properties-clustering-options.md)

### clustering Type

`object` ([Clustering options](vector-dataset-render-config-defs-vector-render-mode-options-properties-clustering-options.md))

## labelAttributes

The attributes to use for map feature labeling

`labelAttributes`

* is optional

* Type: `string[]`

* cannot be null

* defined in: [Vector dataset render config](vector-dataset-render-config-defs-vector-render-mode-options-properties-label-attributes.md)

### labelAttributes Type

`string[]`

## forceLocalFiltering

Prevent using WFS filters for feature filtering

`forceLocalFiltering`

* is optional

* Type: `boolean` ([Force local filtering](vector-dataset-render-config-defs-vector-render-mode-options-properties-force-local-filtering.md))

* cannot be null

* defined in: [Vector dataset render config](vector-dataset-render-config-defs-vector-render-mode-options-properties-force-local-filtering.md)

### forceLocalFiltering Type

`boolean` ([Force local filtering](vector-dataset-render-config-defs-vector-render-mode-options-properties-force-local-filtering.md))

## iconUrl

The map feature icon representation

`iconUrl`

* is optional

* Type: `string` ([Feature icon URL](vector-dataset-render-config-defs-vector-render-mode-options-properties-feature-icon-url.md))

* cannot be null

* defined in: [Vector dataset render config](vector-dataset-render-config-defs-vector-render-mode-options-properties-feature-icon-url.md)

### iconUrl Type

`string` ([Feature icon URL](vector-dataset-render-config-defs-vector-render-mode-options-properties-feature-icon-url.md))
