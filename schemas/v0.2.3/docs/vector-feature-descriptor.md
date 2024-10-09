# Vector feature descriptor Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-descriptor.schema.json
```

Metadata of a vector data source

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-feature-descriptor.schema.json](schemas/common/vector-feature-descriptor.schema.json"open original schema") |

## Vector feature descriptor Type

`object` ([Vector feature descriptor](vector-feature-descriptor.md))

# Vector feature descriptor Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                      |
| :---------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [title](#title)               | `string` | Optional | cannot be null | [Vector feature descriptor](vector-feature-descriptor-properties-title.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-descriptor.schema.json#/properties/title")                   |
| [description](#description)   | `string` | Optional | cannot be null | [Vector feature descriptor](vector-feature-descriptor-properties-description.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-descriptor.schema.json#/properties/description")       |
| [geometryType](#geometrytype) | `string` | Optional | cannot be null | [Vector feature descriptor](vector-feature-descriptor-properties-geometrytype.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-descriptor.schema.json#/properties/geometryType")     |
| [geometryName](#geometryname) | `string` | Optional | cannot be null | [Vector feature descriptor](vector-feature-descriptor-properties-geometryname.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-descriptor.schema.json#/properties/geometryName")     |
| [properties](#properties)     | `array`  | Required | cannot be null | [Vector feature descriptor](vector-feature-descriptor-properties-feature-attributes.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-descriptor.schema.json#/properties/properties") |

## title

The title of the feature

`title`

* is optional

* Type: `string`

* cannot be null

* defined in: [Vector feature descriptor](vector-feature-descriptor-properties-title.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-descriptor.schema.json#/properties/title")

### title Type

`string`

## description

A description for the feature

`description`

* is optional

* Type: `string`

* cannot be null

* defined in: [Vector feature descriptor](vector-feature-descriptor-properties-description.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-descriptor.schema.json#/properties/description")

### description Type

`string`

## geometryType

The feature geometry type, if common across all features

`geometryType`

* is optional

* Type: `string`

* cannot be null

* defined in: [Vector feature descriptor](vector-feature-descriptor-properties-geometrytype.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-descriptor.schema.json#/properties/geometryType")

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

* Type: `string`

* cannot be null

* defined in: [Vector feature descriptor](vector-feature-descriptor-properties-geometryname.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-descriptor.schema.json#/properties/geometryName")

### geometryName Type

`string`

## properties

The feature attributes definitions

`properties`

* is required

* Type: an array of merged types ([Vector feature property](vector-feature-property.md))

* cannot be null

* defined in: [Vector feature descriptor](vector-feature-descriptor-properties-feature-attributes.md"https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-descriptor.schema.json#/properties/properties")

### properties Type

an array of merged types ([Vector feature property](vector-feature-property.md))
