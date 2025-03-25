

# Slot: width


_The width of the image (x-axis) in pixels_





URI: [https://w3id.org/cetmd/entities/:width](https://w3id.org/cetmd/entities/:width)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SegmentationMask3D](SegmentationMask3D.md) | An annotation volume with categorical labels |  no  |
| [ProjectionImage](ProjectionImage.md) | A projection image |  no  |
| [Tomogram](Tomogram.md) | A 3D tomogram |  no  |
| [SegmentationMask2D](SegmentationMask2D.md) | An annotation image with categorical labels |  no  |
| [ProbabilityMap3D](ProbabilityMap3D.md) | An annotation volume with real-valued labels |  no  |
| [MovieFrame](MovieFrame.md) | An individual movie frame |  no  |
| [Image2D](Image2D.md) | A 2D image |  no  |
| [Image3D](Image3D.md) | A 3D image |  no  |
| [GainFile](GainFile.md) | A gain reference file |  no  |
| [DefectFile](DefectFile.md) | A detector defect file |  no  |
| [ProbabilityMap2D](ProbabilityMap2D.md) | An annotation image with real-valued labels |  no  |
| [SubProjectionImage](SubProjectionImage.md) | A croppecd projection image |  no  |
| [ParticleMap](ParticleMap.md) | A 3D particle density map |  no  |







## Properties

* Range: [Integer](Integer.md)





## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/cetmd/entities




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | https://w3id.org/cetmd/entities/:width |
| native | https://w3id.org/cetmd/entities/:width |




## LinkML Source

<details>
```yaml
name: width
description: The width of the image (x-axis) in pixels
from_schema: https://w3id.org/cetmd/entities
rank: 1000
alias: width
domain_of:
- Image2D
- Image3D
range: integer

```
</details>