Lab 02 - VLAN Segmentation

Objective

Implement VLAN segmentation to improve network security and traffic isolation.

Network Design

VLAN 10 - Staff

Purpose:

* Employee devices
* Business applications

VLAN 20 - Guest

Purpose:

* Visitor internet access
* Isolated from internal resources

VLAN 30 - Printers

Purpose:

* Network printers
* Controlled access

Configuration Steps

VLAN Creation

Created VLAN interfaces on FortiGate.

DHCP Configuration

Configured separate DHCP scopes for each VLAN.

Firewall Policies

Implemented policies to:

* Allow Staff to access business resources
* Restrict Guest access to internet only
* Limit Printer VLAN communications

Security Controls

* Inter-VLAN traffic restrictions
* Access control policies
* Logging enabled

Validation

* Devices received correct IP addresses
* Guest network isolated
* Printer access functioning
* Security policies enforced

Skills Demonstrated

* VLAN Segmentation
* Network Security
* Firewall Policies
* DHCP Management
