

# Slot: path


_Path to a file._





URI: [https://w3id.org/cetmd/entities/:path](https://w3id.org/cetmd/entities/:path)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MovieStack](MovieStack.md) | A stack of movie frames |  no  |
| [PointMatrixSet2D](PointMatrixSet2D.md) | A set of 2D points with an associated rotation matrix |  no  |
| [ParticleMap](ParticleMap.md) | A 3D particle density map |  no  |
| [SegmentationMask2D](SegmentationMask2D.md) | An annotation image with categorical labels |  no  |
| [Tomogram](Tomogram.md) | A 3D tomogram |  no  |
| [TiltSeries](TiltSeries.md) | A stack of projection images |  no  |
| [Annotation](Annotation.md) | A primitive annotation |  no  |
| [PointMatrixSet3D](PointMatrixSet3D.md) | A set of 3D points with an associated rotation matrix |  no  |
| [GainFile](GainFile.md) | A gain reference file |  no  |
| [TriMesh](TriMesh.md) | A mesh annotation |  no  |
| [SegmentationMask3D](SegmentationMask3D.md) | An annotation volume with categorical labels |  no  |
| [ProbabilityMap3D](ProbabilityMap3D.md) | An annotation volume with real-valued labels |  no  |
| [DefectFile](DefectFile.md) | A detector defect file |  no  |
| [ProbabilityMap2D](ProbabilityMap2D.md) | An annotation image with real-valued labels |  no  |
| [SubProjectionImage](SubProjectionImage.md) | A croppecd projection image |  no  |
| [PointSet2D](PointSet2D.md) | A set of 2D point annotations |  no  |
| [PointVectorSet3D](PointVectorSet3D.md) | A set of 3D points with an associated direction vector |  no  |
| [MovieFrame](MovieFrame.md) | An individual movie frame |  no  |
| [PointVectorSet2D](PointVectorSet2D.md) | A set of 2D points with an associated direction vector |  no  |
| [ProjectionImage](ProjectionImage.md) | A projection image |  no  |
| [PointSet3D](PointSet3D.md) | A set of 3D point annotations |  no  |







## Properties

* Range: [String](String.md)





## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/cetmd/entities




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | https://w3id.org/cetmd/entities/:path |
| native | https://w3id.org/cetmd/entities/:path |




## LinkML Source

<details>
```yaml
name: path
description: Path to a file.
from_schema: https://w3id.org/cetmd/entities
rank: 1000
alias: path
domain_of:
- GainFile
- DefectFile
- MovieFrame
- MovieStack
- ProjectionImage
- TiltSeries
- Tomogram
- ParticleMap
- Annotation
range: string

```
</details>