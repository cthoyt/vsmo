# vsmo

Revival of the Vector Surveillance and Management Ontology, sourced
from https://code.google.com/archive/p/vector-surveillance-and-management-ontology/downloads
under the New BSD License.

`vsmo.obo` in this repository corresponds to the 0.0.17 release
at https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/vector-surveillance-and-management-ontology/vsmo.0.17.obo.
It does not currently parse with ROBOT.

## Original README

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
