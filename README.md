# vsmo

This repository revives the _Vector Surveillance and Management Ontology_,
sourced from https://code.google.com/archive/p/vector-surveillance-and-management-ontology/downloads
under the BSD-3-Clause License. This ontology was originally published accompanying:

> [**Ontology for Vector Surveillance and Management**](https://pubmed.ncbi.nlm.nih.gov/23427646)
> <br />Saul Lozano-Fuentes, Aritra Bandyopadhyay, Lindsay G Cowell, Albert Goldfain, and Lars Eisen
> <br />[pubmed:23427646](https://pubmed.ncbi.nlm.nih.gov/23427646), [doi:10.1603/ME12169](https://doi.org/10.1603/ME12169)

`vsmo.obo` in this repository corresponds to an updated version of the
[0.0.17 release](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/vector-surveillance-and-management-ontology/vsmo.0.17.obo).
that can now be parsed with ROBOT.

See additional information on the Bioregistry: https://bioregistry.io/vsmo

## Original README Text

Note on changes in the VSMO upper classes from the paper published in the
Journal of Medical Entomology on the VSMO (Lozano-Fuentes et al.. 2013. Ontology
for vector surveillance and management. Journal of Medical Entomology 50: 1-14)

With the addition of the Basic Formal Ontology framework (BFO
1.1; http://www.ifomis.org/bfo) to the VSMO, the location of the upper classes
presented in the 2013 Journal of Medical Entomology publication on the VSMO has
changed (see figure
at "http://vector-surveillance-and-management-ontology.googlecode.com/svn/wiki/bfo_root.png"
for a guide to navigate to these upper classes in the new VSMO structure).

Using the child-parent analogy: Most of the terms in the VSMO are of type "
object", which now, together with "object_aggregate", are children of "
material_entity".

The class "quality" is now a child of "specifically_dependent_continuant".

The classes "disposition", "function" and "role" are now children of "
realizable_entity".

The term "process" is now a child of "processual_entity".

The term "temporal_inteval" is a child of "connected_temporal_region". 
