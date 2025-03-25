

# Slot: name


_The name of a given entry_





URI: [https://w3id.org/cetmd/entities/:name](https://w3id.org/cetmd/entities/:name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProjectionAlignment](ProjectionAlignment.md) | The tomographic alignment for a single projection |  no  |
| [Scale](Scale.md) | A scaling transformation |  no  |
| [Identity](Identity.md) | The identity transformation |  no  |
| [Translation](Translation.md) | A translation transformation |  no  |
| [Dataset](Dataset.md) | A dataset |  no  |
| [Affine](Affine.md) | An affine transformation |  no  |
| [MapAxis](MapAxis.md) | Axis permutation transformation |  no  |
| [Sequence](Sequence.md) | A sequence of transformations |  no  |
| [CoordinateTransformation](CoordinateTransformation.md) | A coordinate transformation |  no  |
| [CoordinateSystem](CoordinateSystem.md) | A coordinate system |  no  |
| [Average](Average.md) | A particle averaging experiment |  no  |







## Properties

* Range: [String](String.md)





## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/cetmd/entities




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | https://w3id.org/cetmd/entities/:name |
| native | https://w3id.org/cetmd/entities/:name |




## LinkML Source

<details>
```yaml
name: name
description: The name of a given entry
from_schema: https://w3id.org/cetmd/entities
rank: 1000
alias: name
domain_of:
- Average
- Dataset
- CoordinateSystem
- CoordinateTransformation
range: string

```
</details>