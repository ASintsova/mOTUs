.. mOTUs documentation master file, created by
   sphinx-quickstart on Fri Feb 18 11:49:40 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

mOTUs
======
|Build| |Conda| |License| |Downloads|

.. |Build| image:: https://ci.appveyor.com/api/projects/status/0x4veuuoabm6018v/branch/master?svg=true
   :target: https://ci.appveyor.com/project/AlessioMilanese/motus-v2/branch/master

.. |Conda| image:: https://anaconda.org/bioconda/motus/badges/installer/conda.svg
   :target: https://anaconda.org/bioconda/motus

.. |License| image:: https://anaconda.org/bioconda/motus/badges/license.svg
   :target: https://github.com/motu-tool/mOTUs_v2/blob/master/LICENSE

.. |Downloads| image:: https://img.shields.io/conda/dn/bioconda/motus.svg?style=flat
   :target: https://github.com/motu-tool/mOTUs_v2/blob/master/LICENSE






Overview
--------

Phylogenetic markers are genes that can be used to reconstruct the evolutionary history of organisms and to profile the taxonomic composition of environmental samples. Efforts to find a good set of protein-coding phylogenetic marker genes led to the identification of 40 universal marker genes (MGs) [1,2]. These 40 MGs occur in single copy in the vast majority of known organisms and they have been used to delineate prokaryotic organisms at the species level [3].
We developed the mOTU profiler as a successor of the original version described in [4]. It uses 10 of the 40 MGs to taxonomically profile shotgun metagenomes, to quantify metabolically active members in metatranscriptomics and to quantify differences between strain populations using single nucleotide variation (SNV) profiles. We extracted the MGs from ~86,000 prokaryotic reference genomes and more than 3,100 publicly available metagenomes (from major human body sites, gut microbiome samples from disease association studies, and ocean water samples). Clustering of MGs led to the generation of a database of MG-based operational taxonomic units (mOTUs) containing 2,297 metagenomic mOTUs (meta-mOTUs) and 11,915 reference mOTUs (ref-mOTUs). For the most recent version (2.6) we extended the database by 19.358 (ext-mOTUs) using MGs from ~600,000 metagenome assembled genomes from 23 environments (mouse, cat, dog, pig, freshwater, wastewater, air, ...). Alignments against this database are then used to taxonomically classify reads, to identify metabolically active members and to profile sub-species level SNVs.



Quickstart
----------

Setup
^^^^^

Profiling
^^^^^^^^^

Output
^^^^^^

Reference
---------

Feedback
--------

Contact
^^^^^^^

Contributing
^^^^^^^^^^^^

Documentation
-------------

.. toctree::
   :maxdepth: 1

    Installation <documentation/install>
    Data Preprocessing <documentation/preprocessing>
    Profiling <documentation/profile>
    Advanced Options <documentation/advanced>
    Tutorial <documentation/tutorial>


