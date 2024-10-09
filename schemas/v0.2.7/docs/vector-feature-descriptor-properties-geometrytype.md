# Untitled string in Vector feature descriptor Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.6/common/vector-feature-descriptor.schema.json#/properties/geometryType
```

The feature geometry type, if common across all features

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                             |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [vector-feature-descriptor.schema.json\*](schemas/common/vector-feature-descriptor.schema.json) |

## geometryType Type

`string`

## geometryType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value               | Explanation |
| :------------------ | :---------- |
| `"Point"`           |             |
| `"MultiPoint"`      |             |
| `"LineString"`      |             |
| `"MultiLineString"` |             |
| `"Polygon"`         |             |
| `"MultiPolygon"`    |             |
