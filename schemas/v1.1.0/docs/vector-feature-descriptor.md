# Vector feature descriptor Schema

```txt
https://cgi-italy.github.io/insula/schemas/v1.1.0/common/vector-feature-descriptor.schema.json
```

Metadata of a vector data source

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-feature-descriptor.schema.json](schemas/common/vector-feature-descriptor.schema.json) |

## Vector feature descriptor Type

`object` ([Vector feature descriptor](vector-feature-descriptor.md))

# Vector feature descriptor Properties

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                        |
| :------------------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [title](#title)                 | `string` | Optional | cannot be null | [Vector feature descriptor](vector-feature-descriptor-properties-title.md)                     |
| [description](#description)     | `string` | Optional | cannot be null | [Vector feature descriptor](vector-feature-descriptor-properties-description.md)         |
| [geometryType](#geometrytype)   | `string` | Optional | cannot be null | [Vector feature descriptor](vector-feature-descriptor-properties-geometrytype.md)       |
| [geometryName](#geometryname)   | `string` | Optional | cannot be null | [Vector feature descriptor](vector-feature-descriptor-properties-geometry-attribute.md) |
| [titleProperty](#titleproperty) | `string` | Optional | cannot be null | [Vector feature descriptor](vector-feature-descriptor-properties-title-attribute.md)   |
| [properties](#properties)       | `array`  | Required | cannot be null | [Vector feature descriptor](vector-feature-descriptor-properties-feature-attributes.md)   |

## title

The title of the feature

`title`

* is optional

* Type: `string`

* cannot be null

* defined in: [Vector feature descriptor](vector-feature-descriptor-properties-title.md)

### title Type

`string`

## description

A description for the feature

`description`

* is optional

* Type: `string`

* cannot be null

* defined in: [Vector feature descriptor](vector-feature-descriptor-properties-description.md)

### description Type

`string`

## geometryType

The feature geometry type, if common across all features

`geometryType`

* is optional

* Type: `string`

* cannot be null

* defined in: [Vector feature descriptor](vector-feature-descriptor-properties-geometrytype.md)

### geometryType Type

`string`

### geometryType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value               | Explanation |
| :------------------ | :---------- |
| `"Point"`           |             |
| `"MultiPoint"`      |             |
| `"LineString"`      |             |
| `"MultiLineString"` |             |
| `"Polygon"`         |             |
| `"MultiPolygon"`    |             |

## geometryName

The name of the geometry attribute

`geometryName`

* is optional

* Type: `string` ([Geometry attribute](vector-feature-descriptor-properties-geometry-attribute.md))

* cannot be null

* defined in: [Vector feature descriptor](vector-feature-descriptor-properties-geometry-attribute.md)

### geometryName Type

`string` ([Geometry attribute](vector-feature-descriptor-properties-geometry-attribute.md))

## titleProperty

The property to use as feature title

`titleProperty`

* is optional

* Type: `string` ([Title attribute](vector-feature-descriptor-properties-title-attribute.md))

* cannot be null

* defined in: [Vector feature descriptor](vector-feature-descriptor-properties-title-attribute.md)

### titleProperty Type

`string` ([Title attribute](vector-feature-descriptor-properties-title-attribute.md))

## properties

The feature attributes definitions

`properties`

* is required

* Type: an array of merged types ([Vector feature property](vector-feature-property.md))

* cannot be null

* defined in: [Vector feature descriptor](vector-feature-descriptor-properties-feature-attributes.md)

### properties Type

an array of merged types ([Vector feature property](vector-feature-property.md))
