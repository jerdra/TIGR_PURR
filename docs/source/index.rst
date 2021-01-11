.. tigrlab_nextflow documentation master file, created by
   sphinx-quickstart on Mon Jul  8 12:26:36 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

------------------------------------------------------------
TIGRLab Pipelines: Utterly Reproducible Research (TIGR-PURR)
------------------------------------------------------------


Welcome to the documentation page for TIGR-PURR.
This is where you'll find information about how to run the lab's supported pipelines yourself as well as the various configuration options available to you. 

TIGR-PURR is a pipeline system based off a combination of `Nextflow <https://www.nextflow.io>`_ and `Boutiques <https://www.boutiques.github.io>`_ which allow us to seamlessly run a variety of `BIDS Applications <https://bids.neuroimaging.io>`_ based pipelines easily with only a little bit of configuration work. 

Currently, TIGR-PURR is set up to natively support the following cluster configurations:

* The local Kimel-Lab Cluster
* CAMH's SCC Cluster
* Scinet's Niagara Cluster (soon)!
* Your local computer

However, TIGR-PURR can be configured to run *on any cluster set-up with just small tweaks to configuration!*. 


Guides
=======

Kimel Lab Guides
################

If you're a Kimel Lab member at CAMH, then the standard configuration packaged with TIGR_PURR will be sufficient for your use-case. See the following guides to get started:

- :ref:`kimel_getting_started`
- :ref:`kimel_quickstart_tutorial`
- :ref:`kimel_quick_reference`

General User Guide
##################

The following documentation is non-specific towards compute infrastructure and provides information on general configuration and set-up.

- :ref:`minimal_setup`
- :ref:`setup_guide`


.. toctree::
   :maxdepth: 2
   :caption: Contents 

   setup_walkthrough
   install_and_configure
   kimel_getting_started
   kimel_quickstart_tutorial
   kimel_quick_reference
   not_bids
