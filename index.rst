.. title:: Introduction to Nutanix AHV

.. toctree::
  :maxdepth: 2
  :caption: Basic Troubleshooting
  :name: _bas_troub
  :hidden:

  basic_linux/basic_linux
  foundation/Foundation
  cvm/cvm
  ahv/ahv
  poc/poc
  implement/implement

.. toctree::
  :maxdepth: 2
  :caption: Advanced Troubleshooting
  :name: _adv_troub
  :hidden:


.. toctree::
  :maxdepth: 2
  :caption: Appendix
  :name: _appendix
  :hidden:

  appendix/glossary
  appendix/otherstuff

.. _getting_started:

---------------
Getting Started
---------------

This workshop has a presentation that holds all the slides that are discussed before you will runthe workshop. The presentation can be found :download:`here <ppt/presentation.pptx>`

The purpose of this training is to get to a knowledge that common issues can be solved by any help from support or other SEs. This is **not** to get the knowledge of our **SREs** that we have, **nor** to be a starting point of getting **NSS** certified.

What will we discuss?
+++++++++++++++++++++

During the workshop and the presentation we will discuss the following troubleshooting topics:

- Basic Linux commands to are helpfull
- Foundation
- Acropolis (CVM)
- AHV
- PoC
- Implementation

Basic Linux commands
....................

As our Nutanix CVM is running within a CentOS O/S, we can use the default Linux bash commands to look, search and manipulate files. IN this module you will learn the most common and handy commands to use.

- grep
- ls
- cat
- tr
- cut
- sar
- ifconfig
- less
- more
- find
- mv
- rm
- ps
- top
- tail
- df
- ssh

Foundation
..........

This process is the the most important first step to get a cluster installed. Unfortunately, allthough a lot will be automatically solved, there are still issues seen in the field when performing the Foundation process. Think about:

- A
- B
- C
- Network issues

Acropolis (CVM)
...............

Our magic sauce comes from the CVM. As mentioned earlier this is a VM that is based on CentOS, but runs a lot of daemons that have their own purpose, use and specific commandlines tools available. This module will discuss the most common ones like:

- Genesis
- Stargate
- Zookeeper
- Cassandra
- PRISM
- Medusa

AHV
...

Our free of charge HyperVisor is becoming more and more best of breed. More features are becoming available in the CVM that can be used by the HyperVisor. To understand how to solve issues, this module will provide the first line off defense for troubleshooting the NUtanix AHV. The module will discuss the following topics:

- VM management
- Virtual Network management
- C
- D

PoC
...

For PoC purposes you will have to combine a few things of the other modules to get to pinpointing the issue and then solve it, or to find your way in the process of getting a PoC setup and running successful. This module will discuss:

- Pre-Requirements for the PoC
- SFDC process to start a PoC
- Transport process
- Dark Site installations
- E

Implementation
..............

If you need to run an implementation, you may need to combine the former modules. Just as with a PoC. There are some small steps that need to done before handing over the clusert to the customer. This module, allthough not really a troubleshooting module, will discuss the tasks to handover the cluster to the customer in a very smooth manner.

- SFDC process
- Support portal process
- License the cluster
- Dark site installations
