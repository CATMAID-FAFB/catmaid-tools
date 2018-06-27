# CATMAID tools
Overview of packages and scripts for the analysis of
[CATMAID](http://catmaid.readthedocs.io/en/stable/) data contributed by the
FAFB community.

### Contributing
1. Add scripts/code to the repository or link to external resource
2. Leave brief description in this README. If possible, include maintainer/contact

## R

### [nat](https://github.com/jefferis/nat)
An R package for the (3D) visualisation and analysis of biological image data,
especially tracings of single neurons. **nat** is the core package of a wider
suite of neuroanatomy tools introduced at http://jefferislab.github.io.
*Greg Jefferis, WT UK/Jefferis lab*.

### [rcatmaid](https://github.com/jefferis/rcatmaid)
R package providing API access to the CATMAID web image annotation tool.
Provides interface with nat R package, enabling wide variety of analyses.
*Greg Jefferis, WT UK*.

### [elmr](https://github.com/jefferis/elmr)
Provides tools to move between adult brain EM and light level data,
emphasising the interaction between the CATMAID web application and the R
Neuroanatomy Toolbox package. See also https://github.com/saalfeldlab/elm,
from which this package borrows both a name and uses data. *Greg Jefferis, WT UK*.

### [catnat](https://github.com/alexanderbates/catnat)
R Package for use with rcatmaid and nat. catnat provides some higher level
analysis function for, for example, clustering synapses within a neuron's
tree structure, clustering together neurons by synapse position in 3D space
and splitting a neuron into different compartments
(e.g. axon-dendrite-primary neurite) and visualising these splits and clusters.
*Alexander Bates, Jefferis Lab*.

### [tracerutils](https://github.com/fmlove/tracerutils)
R package with useful functions for EM tracers.  Provides shortcuts for common
tasks like plotting neurons from CATMAID, randomly sampling synapses, and
checking for duplicate connectors. *Fiona Love, WT UK*.

### Scripts
- [Random sampling of pre- or postsynaptic partners](https://gist.github.com/AmeliaES/54dc9342bad1626ca37b475b0e2f8e08). *Amelia Edmondson-Stait, WT UK*.


## Python

### [pymaid](https://github.com/schlegelp/pymaid)
Python 3 package to fetch data from CATMAID server and analyse neuron anatomy
and connectivity. Features include: fetch data from CATMAID, 2D and 3D plotting
of neurons, virtual neuron surgery (cutting, stitching, pruning, rerooting, etc),
R bindings (e.g. for libraries nat, nat.nblast and elmr), interface with
Blender 3D, import/export from/to SWC, load and annotate image data.
*Philipp Schlegel, WT UK*.

### [catbot](https://github.com/flyconnectome/catbot)
Slack chatbot that allows quick queries to a CATMAID server. Most notably it
lets you NBLAST CATMAID neurons against e.g. the
[flycircuit](http://www.flycircuit.tw/) database. *Philipp Schlegel, WT UK*.

### [Blender plugin](https://github.com/schlegelp/CATMAID-to-Blender)
Plugin for [Blender 3D](https://www.blender.org/) that allows fetching data
from CATMAID server for high-quality renderings. *Philipp Schlegel, WT UK*.

### Scripts
- [Neato dendrograms of neurons](https://github.com/CATMAID-FAFB/catmaid-tools/tree/master/Python/Dendrogram_Code). *Markus Pleijzier, WT UK*.
- [Reconstruct a neuron's connectivity history](https://github.com/CATMAID-FAFB/catmaid-tools/tree/master/Python/connectivity_history.ipynb). *Philipp Schlegel, WT UK*
