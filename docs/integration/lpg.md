# Integrating Labeled Property Graphs into Your PKG

Labeled Property Graphs (LPGs) differ from RDF databases in that by default, every relationship has both a type and any number of attributes.  Attributes are key-value pairs that can be optionally indexed for fast performance at scale.

In this section, we will describe the process of moving data from a PKG into an LPG or from an LPG into your PKG.  We will discuss the differences in the data model and some ways to preserve information as it moves between these formats.

## Two Types of LPGs: Fixed and Flexible Schemas

There are two main types of LPG.

1. **Fixed Schema** - these LPGs require uniform schema representations for all vertices and edges.