# Vector feature property common attributes Schema

```txt
https://cgi-italy.github.io/insula/schemas/v0.2.0/common/vector-feature-property.schema.json#/$defs/common
```

Definition of vector feature property common attribute

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [vector-feature-property.schema.json\*] (schemas/common/vector-feature-property.schema.json) |

## common Type

`object` ([Vector feature property common attributes](vector-feature-property-defs-vector-feature-property-common-attributes.md))

# common Properties

| Property                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                 |
| :-------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                   | `string`  | Required | cannot be null | [Vector feature property] (vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-identifier.md)             |
| [name](#name)               | `string`  | Required | cannot be null | [Vector feature property] (vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-title.md)                |
| [description](#description) | `string`  | Optional | cannot be null | [Vector feature property] (vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-description.md)   |
| [filterable](#filterable)   | `boolean` | Optional | cannot be null | [Vector feature property] (vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-filtering-flag.md) |
| [sortable](#sortable)       | `boolean` | Optional | cannot be null | [Vector feature property] (vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-sorting-flag.md)     |
| [quantity](#quantity)       | `object`  | Optional | cannot be null | [Vector feature property] (measured-quantity.md)                                                                                                 |

## id

The property id (e.g. column name)

`id`

* is required

* Type: `string` ([Property identifier](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-identifier.md))

* cannot be null

* defined in: [Vector feature property] (vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-identifier.md)

### id Type

`string` ([Property identifier](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-identifier.md))

## name

The property human readable title

`name`

* is required

* Type: `string` ([Property title](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-title.md))

* cannot be null

* defined in: [Vector feature property] (vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-title.md)

### name Type

`string` ([Property title](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-title.md))

## description

The property description

`description`

* is optional

* Type: `string` ([Property description](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-description.md))

* cannot be null

* defined in: [Vector feature property] (vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-description.md)

### description Type

`string` ([Property description](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-description.md))

## filterable

A flag indicating if filtering should be enabled for this property

`filterable`

* is optional

* Type: `boolean` ([Property filtering flag](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-filtering-flag.md))

* cannot be null

* defined in: [Vector feature property] (vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-filtering-flag.md)

### filterable Type

`boolean` ([Property filtering flag](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-filtering-flag.md))

### filterable Default Value

The default value is:

```json
true
```

## sortable

A flag indicating if sorting should be enabled for this property

`sortable`

* is optional

* Type: `boolean` ([Property sorting flag](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-sorting-flag.md))

* cannot be null

* defined in: [Vector feature property] (vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-sorting-flag.md)

### sortable Type

`boolean` ([Property sorting flag](vector-feature-property-defs-vector-feature-property-common-attributes-properties-property-sorting-flag.md))

### sortable Default Value

The default value is:

```json
true
```

## quantity

The quantity measured by a variable

`quantity`

* is optional

* Type: `object` ([Measured quantity](measured-quantity.md))

* cannot be null

* defined in: [Vector feature property] (measured-quantity.md)

### quantity Type

`object` ([Measured quantity](measured-quantity.md))

### quantity Examples

```json
{
  "id": "area_m2",
  "name": "Area",
  "description": "Area in squared meters",
  "units": "m²"
}
```
