##########
Change Log
##########

All notable changes to this project are documented in this file.


==========
Unreleased
==========

Added
-----
- Add new motifs for 396 TFs that already had at least one motif and
  add motifs for 12 TFs that didn't yet have a motif:

  -``BATF``
  -``BCL11A``
  -``HES1``
  -``HES5``
  -``HSFY2``
  -``MYF5``
  -``NFYC``
  -``PAX8``
  -``SIX5``
  -``TAL1``
  -``TP73``
  -``ZNF20``

Changed
-------

Fixed
-----


================
1.0.0 2018-10-22
================

Added
-----
- Make ``crc`` a callable python function
- Set up testing infrastructure

Changed
-------
- Remove ``_CLIQUES_ALL.txt`` table from the outputs and report only
  the top 100 ranked cliques in the ``_CLIQUE_SCORES_DEGREE.txt`` table

Fix
---
- Remove the deprecated ``_CLIQUE_SCORES_VSA.txt`` table, the creation
  of which was very memory consuming
- Make the ``bam`` input work
- Fix assigning enhancers to missing genes
- Fix identifying gene column in activity file
- Make the ``mask_file`` input work
