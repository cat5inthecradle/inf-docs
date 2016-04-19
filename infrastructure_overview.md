Infrastructure Overview:

Company Name
============

Date:

Document Owner:

### Table of Contents

* Infrastructure Overview
* Network Platforms
  * Switch Topology – Layer 2
  * Routing Topology – Layer 3
* Physical Server Infrastructure
  * Server Room / CAB Layout
* Virtual Infrastructure
  * Cluster details
  * Virtual Hosts
  * Virtual Networking
  * Virtual Datastores
  * Virtual Disks (VMDK/VHD)
  * Virtual Snapshots
  * Virtual Guest Resources
* Storage Platforms
  * SAN
  * NAS
* Active Directory & Windows Server Environment
  * DCs / FMSO Roles / GCs / Sites
  * DHCP
  * DNS
  * Group Policy
  * Remote Access
  * Third Party Software / Line of Business Applications
* Backup Provision & Disaster Recovery
* Internet Connectivity / WAN
  * Firewalls
  * IPS
  * Proxy
  * Published Services
* Credentials & Access Requirements

Infrastructure Overview
-----------------------

A summary of the infrastructure, such as. 

“This document relates to the VMware VDI infrastructure used for client based access by students of the college internally and externally.”

And then on to explain the top-level hardware in use, how its split across areas, what model is employed? (I.e for switching, Cisco’s Core, Distribution, Access)

You might provide a diagram overview; here is an example for VDI (Source: http://www.pocs.nl/pocs/en/tyechnical/vmware/106-vmware-vdi-pocs.html) 


Network Platforms
-----------------

### Switch Topology – Layer 2

Example diagram
(Source: http://www.netbraintech.com/images/diagram/L2_Map_Example.jpg)


### Routing Topology – Layer 3

Example Diagram
(Source: http://www.netbraintech.com/images/diagram/L3_Map_Example.jpg) 


Mainly this would be diagrams of the topologies, and links to where copies of the configurations are held. And a separate document listing the IP addressing scheme, including devices with static IPs. Don’t forget Public IP addresses in use as well.

Physical Server Infrastructure
------------------------------

### Server Room / CAB Layout

Another diagram of what is where in the Server Room and Comms room racks. Probably an appendix with some actual photos of the rooms as well.

Virtual Infrastructure
----------------------

### Cluster details

### Virtual Hosts

### Virtual Networking

### Virtual Datastores

### Virtual Disks (VMDK/VHD)

### Virtual Snapshots

If they are present on any system and why

### Virtual Guest Resources

How hardware resources for VMs are allocated

Once again this is more of an overview, and a reference a separate document which goes into more detail about the systems.

Storage Platforms
-----------------

### SAN

### NAS

Backup Provision & Disaster Recovery
------------------------------------

Which software is used, which systems it backs up and to which location

Active Directory & Windows Server Environment
---------------------------------------------

### DCs / FMSO Roles / GCs / Sites
### DHCP
### DNS
### Group Policy
### Remote Access
### Third Party Software / Line of Business Applications
### Another subject which will more than likely require its own document.

Backup Provision & Disaster Recovery
------------------------------------

This should reference any DR you have in place, and which document to see in regards to failing over to the DR.

Internet Connectivity / WAN
---------------------------

### Firewalls
### IPS
### Proxy
### Published Services
Some more diagrams needed, explaining traffic flow to the outside, etc. And a table listing the mappings of internal resources for access from the outside. (NATs and PATs).

Credentials & Access Requirements
---------------------------------

A secure document or application should be used for the containment of passwords, but you can link to this option, and list things like security groups in AD used for access to things, I.E VMware vCenter access linked to an AD group.
