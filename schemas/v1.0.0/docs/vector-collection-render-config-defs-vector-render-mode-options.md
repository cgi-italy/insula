# Vector render mode options Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.0.0/common/vector-collection-render-config.schema.json#/$defs/vectorRenderModeOptions
```

The vector render mode rendering options

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-collection-render-config.schema.json\*](schemas/common/vector-collection-render-config.schema.json) |

## vectorRenderModeOptions Type

`object` ([Vector render mode options](vector-collection-render-config-defs-vector-render-mode-options.md))

# vectorRenderModeOptions Properties

| Property                                      | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                       |
| :-------------------------------------------- | :------------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [defaultColorProperty](#defaultcolorproperty) | `string`      | Optional | cannot be null | [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-options-properties-default-color-property-id.md) |
| [optimizeSpeed](#optimizespeed)               | Not specified | Optional | cannot be null | [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-options-properties-optimize-speed.md)                   |

## defaultColorProperty

The attribute to use by default (on layer initialization) for class coloring (shall be of 'enum' type)

`defaultColorProperty`

* is optional

* Type: `string` ([Default color property id](vector-collection-render-config-defs-vector-render-mode-options-properties-default-color-property-id.md))

* cannot be null

* defined in: [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-options-properties-default-color-property-id.md)

### defaultColorProperty Type

`string` ([Default color property id](vector-collection-render-config-defs-vector-render-mode-options-properties-default-color-property-id.md))

## optimizeSpeed

When set layer will rendere to optimize speed rather than interactivity

`optimizeSpeed`

* is optional

* Type: unknown ([Optimize speed](vector-collection-render-config-defs-vector-render-mode-options-properties-optimize-speed.md))

* cannot be null

* defined in: [Vector collection render config](vector-collection-render-config-defs-vector-render-mode-options-properties-optimize-speed.md)

### optimizeSpeed Type

unknown ([Optimize speed](vector-collection-render-config-defs-vector-render-mode-options-properties-optimize-speed.md))
