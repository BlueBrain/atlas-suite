# Atlas Suite
A suite to build, analyze volumetric brain atlases.

- [atlas-densities](#atlas-densities) — Create the volumetric density data files for brain regions.
- [atlas-direction-vectors](#atlas-direction-vectors) — Generation of artificial neuronal trees based on the topology of biological cells and their statistical properties.
- [atlas-placement-hints](#atlas-placement-hints) — Generation of artificial neuronal trees based on the topology of biological cells and their statistical properties.
- [atlas-splitter Workflows](#atlas-splitter) — Generation of artificial neuronal trees based on the topology of biological cells and their statistical properties.
- [atlas-alignment-meter](#atlas-alignment-meter) — Pythonic tool (CLI and library) to measure the slice-to-slice jaggedness of a volumetric dataset (NRRD file only).
- [Deep Atlas Suite](#deep-atlas-suite) — A suite of tools created by the Blue Brain Project to manipulate brain atlas images.


## atlas-densities 

<img alt="Atlas-Densities Banner" src="https://github.com/BlueBrain/atlas-suite/raw/main/images/BBP-Atlas-Densities.jpg" width="600"/>

Useful links:
[GitHub repo](https://github.com/BlueBrain/atlas-densities),
[Documentation](https://github.com/BlueBrain/atlas-densities#readme).

**Create the volumetric density data files for brain regions.**

This project contains the tools to create the volumetric density data files the `BBP Cell Atlas`_ is built on.
For example:
 * combine AIBS annotation files to reinstate missing mouse brain regions
 * combine several AIBS gene marker datasets, to be used as hints for the spatial distribution of glia cells
 * compute cell densities for several cell types including neurons and glia cells in the whole mouse brain


## atlas-direction-vectors

<img alt="Atlas-Direction-Vectors Banner" src="https://github.com/BlueBrain/atlas-suite/raw/main/images/BBP-Atlas-Direction-Vectors.jpg" width="600"/>

Useful links:
[GitHub repo](https://github.com/BlueBrain/atlas-direction-vectors),
[Documentation](https://github.com/BlueBrain/atlas-direction-vectors#readme).

**Generation of artificial neuronal trees based on the topology of biological cells and their statistical properties.**

This project is used to create direction vectors for several brain regions including the cerebellum, the isocortex, and the thalamus of the AIBS P56 mouse brain. Direction vectors are 3D unit vectors associated to voxels of a brain region.
They represent the directions that cross transversely the layers in laminar brain regions.

## atlas-placement-hints

<img alt="Atlas-Placement-Hints Banner" src="https://github.com/BlueBrain/atlas-suite/raw/main/images/BBP-Atlas-Placement-Hints.jpg" width="600"/>

Useful links:
[GitHub repo](https://github.com/BlueBrain/atlas-placement-hints),
[Documentation](https://github.com/BlueBrain/atlas-placement-hints#readme).

**Generation of artificial neuronal trees based on the topology of biological cells and their statistical properties.**

This project contains tools to compute placement hints.
`Placement hints` give approximate distances, per voxel, to different layers within the context of a laminar brain region.

## atlas-splitter

<img alt="Atlas-Splitter Banner" src="https://github.com/BlueBrain/atlas-suite/raw/main/images/BBP-Atlas-Splitter.jpg" width="600"/>

Useful links:
[GitHub repo](https://github.com/BlueBrain/atlas-splitter),
[Documentation](https://github.com/BlueBrain/atlas-splitter#readme).

**Generation of artificial neuronal trees based on the topology of biological cells and their statistical properties.**

This project contains tools to split brain atlas regions and refine annotations accordingly.
For example, this can be used to split the layer 2/3 of the AIBS mouse isocortex and save modified hierarchy and annotation files.
     
## atlas-alignment-meter

<img alt="Atlas-Alignment-Meter Banner" src="https://github.com/BlueBrain/atlas-suite/raw/main/images/BBP-Atlas-Alignment-Meter.jpg" width="600"/>

Useful links:
[GitHub repo](https://github.com/BlueBrain/atlas-alignment-meter),
[Documentation](https://github.com/BlueBrain/atlas-alignment-meter#readme).

** Pythonic tool (CLI and library) to measure the slice-to-slice jaggedness of a volumetric dataset**

Measure the displacement of slices in order to smooth the volumetric dataset.

## Deep Atlas Suite

The [Deep Atlas](https://github.com/BlueBrain/Deep-Atlas) is a suite of tools created by the Blue Brain Project to manipulate brain atlas images.

https://github.com/BlueBrain/Deep-Atlas
