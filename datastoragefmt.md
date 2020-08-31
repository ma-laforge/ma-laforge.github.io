---
layout: default
title: "Data Storage Formats"
permalink: /extresouces/datastoragefmt
---

{% include favicon.html %}

# Data Storage Formats

This page collects resources that deal with storing complex, hierarchical/binary data to file.

Alternatively, taking an excerpt from [bsdf.io](http://bsdf.io/):
 > \[...\] data specification for serializing (scientific) data, for the purpose of storage and (inter process) communication.


## Issue
 - Many file formats are designed to store complex hierarchical data in a "human-readable" format.
 - The misnomer is that "human-readable" really means these files can be read/edited with simple text editors.
 - In reality, these formats are error-prone/difficult for humans to edit, and even understand.
 - As dataset complexity increases, simple text editors unavoidably assure the eventuality of errors.
 - What is really needed to ensure "human-readability" is a simple, flexible application to view/edit files.

## Goal
Thus, these data storage formats might as well provide the following components:
 1. A solid, flexible, hierarchical *binary* format.
 1. A simple-to-use editor/reader.

## Analogy: `LaTeX` vs .pdf
 - `TeX`/`LaTeX` documents can be generated using simple text editors.
 - Humans have difficulty reading `TeX`/`LaTeX` documents (not very "human-readable").
 - The Portable Document Format (.pdf files) generate documents that are very much "human-readable".
 - \.pdf documents are written to a binary file format that are not easily deciphered with simple text editors.
 - To enable "human-readability", .pdf viewers are provided.

## Basic info
 - &#x2728;: Recommended by MA
 - &#x1F914;: Looks promising to MA
 - [Comparison of data-serialization formats (Wikipedia) &#x21AA;](https://en.wikipedia.org/wiki/Comparison_of_data-serialization_formatstware)

## Text-based formats
 - CSV: (Not typically hierarchical)
 - JSON
 - YAML
 - XML

## Binary formats
 - [HDF5 &#x21AA;](https://www.hdfgroup.org/solutions/hdf5/): &#x2728; Hierarchical Data Format.
   - Source: The HDF Group; Originally developed @ National Center for Supercomputing Applications.
   - [HDF View &#x21AA;](https://www.hdfgroup.org/downloads/hdfview/): Editor.
 - [NetCDF &#x21AA;](https://www.unidata.ucar.edu/software/netcdf/): &#x2728; Network Common Data Form.
   - Source: [University Corporation for Atmospheric Research](https://en.wikipedia.org/wiki/University_Corporation_for_Atmospheric_Research).
   - (MA) HDF5 appears to be a better alternative.
 - [ASDF &#x21AA;](https://asdf-standard.readthedocs.io): (Advanced Scientific Data Format), pronounced AZ-diff.
   - Source: Space Telescope Science Institute.
 - [BSON &#x21AA;](http://bsonspec.org/): [bee · sahn], short for Binary JSON.
 - [BSDF &#x21AA;](http://bsdf.io/): Strives to be simple, compact and fast.
   - [Comparison with other solutions](http://bsdf.io/comparison.html).
   - Source: Almar Klein.

