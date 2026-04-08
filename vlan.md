# VLAN (Virtual LAN)

## What is a VLAN?

A VLAN is a logical separation of a network into smaller broadcast domains.

## Why VLANs are Used

* Improve security
* Reduce broadcast traffic
* Organize network logically

## Types of Ports

### Access Port

* Belongs to one VLAN
* Untagged traffic

### Trunk Port

* Carries multiple VLANs
* Uses 802.1Q tagging

## Native VLAN

* Frames are NOT tagged
* Default is VLAN 1

## Example

PC1 → VLAN 10
PC2 → VLAN 20
They cannot communicate without routing

## What I Learned

VLANs separate networks logically even if devices are physically connected.
