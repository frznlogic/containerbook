=======================
Introduction to cgroups
=======================

-----------------
What are cgroups?
-----------------

Cgroups is a Linux kernel feature that can be used to create groups of processes
that you wish to control the resource usage of. The name stems from control
groups, commonly abbreviated to cgroups. In other words you group certain
processes together, and then you can limit, account, prioritize and control for
example how much CPU time, memory, or disk io can be used by that group of
processes.

Cgroups are mainly used for: 

* Resource limiting 
* Prioritization
* Accounting 
* Control 

The cgroups subsystem is more flexible and powerful than older already existing
systems such as 'nice' and 'quota'. Cgroups can be created and managed by
regular users. 

At the time of writing cgroups are currently undergoing a major revisions from
what is currently known as cgroups-v1 into cgroups-v2. Some of the design
features are being removed, consistency, usability and a unified hierarchy is
being setup. This document will aim at providing information about cgroups-v2 as
it should have the most relevance for the future. 

Tools for manipulating cgroups
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

There are multiple ways of using and managing cgroups:

* cgroup filesystem
* cgmanager
* libcgroup
* 
