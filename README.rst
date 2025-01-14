.. -*- mode: rst -*-


.. image:: docs/logos/logo_itmo_fs_itog_colour.jpg
  :scale: 10 %
  :target: https://en.itmo.ru/



ITMO_FS
=======

Feature selection library in Python

Package information: |Python 2.7| |Python 3.6| |License| |Docs| |CodeCov|


Install with

::

   pip install ITMO_FS

Current available algorithms:

+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Supervised filters                           | Unsupervised filters                          | Wrappers                     | Hybrid          | Embedded | Ensembles       |
+==============================================+===============================================+==============================+=================+==========+=================+
| Spearman correlation                         | Trace Ratio (Laplacian)                       | Add Del                      | Filter Wrapper  | MOSNS    | MeLiF           |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Pearson correlation                          | Multi-Cluster Feature Selection               | Backward selection           | IWSSr-SFLA      | MOSS     | Best goes first |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Fit Criterion                                | Unsupervised Discriminative Feature Selection | Sequential Forward Selection |                 | RFE      | Best sum        |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| F ratio                                      |                                               | QPFS                         |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Gini index                                   |                                               | Hill climbing                |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Symmetric Uncertainty                        |                                               | Simulated Annealing          |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Fechner correlation                          |                                               | Recursive Elimination        |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Kendall correlation                          |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Information Gain                             |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| ANOVA                                        |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Chi-squared                                  |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Relief                                       |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| ReliefF                                      |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Laplacian score                              |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Modified T-score                             |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Mutual Information Maximization              |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Minimum Redundancy Maximum Relevance         |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Joint Mutual Information                     |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Conditional Infomax Feature Extraction       |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Mutual Information Feature Selection         |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Conditional Mutual Info Maximization         |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Interaction Capping                          |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Dynamic Change of Selected Feature           |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Composition of Feature Relevancy             |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Max-Relevance and Max-Independence           |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Interaction Weight                           |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Double Input Symmetric Relevance             |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Fast Correlation                             |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Statistical Inference Relief                 |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Trace Ratio (Fisher)                         |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Nonnegative Discriminative Feature Selection |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Robust Feature Selection                     |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| Spectral Feature Selection                   |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| VDM                                          |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| QPFS                                         |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+
| MIMAGA                                       |                                               |                              |                 |          |                 |
+----------------------------------------------+-----------------------------------------------+------------------------------+-----------------+----------+-----------------+

Documentation:

https://itmo-fs.readthedocs.io/en/latest/

.. |Python 2.7| image:: https://img.shields.io/badge/python-2.7-blue.svg
.. |Python 3.6| image:: https://img.shields.io/badge/python-3.6-blue.svg
.. |License| image:: https://img.shields.io/badge/license-BSD%20License-blue.svg
.. |Docs| image:: https://readthedocs.org/projects/itmo-fs/badge/?version=latest
.. |CodeCov| image:: https://codecov.io/gh/ctlab/ITMO_FS/branch/develop/graph/badge.svg?token=WK2MNP5F78
   :target: https://codecov.io/gh/ctlab/ITMO_FS
