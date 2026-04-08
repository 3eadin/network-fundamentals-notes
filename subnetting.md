# Subnetting

## What is Subnetting?

Subnetting is the process of dividing a network into smaller networks (subnets).

## Why Subnetting is Important

* Improves network efficiency
* Enhances security
* Reduces broadcast traffic

## Subnet Mask

A subnet mask defines how many bits are used for the network and host.

Example:

* /24 → 255.255.255.0
* /28 → smaller subnets

## Subnetting Formula

Number of subnets:
2^n (where n = borrowed bits)

Example:
/24 → /28
28 - 24 = 4 bits
2^4 = 16 subnets

## Hosts per Subnet

Formula:
2^h - 2 (where h = host bits)

## Example

/28 → 16 total addresses → 14 usable hosts

## What I Learned

Subnetting helps organize networks efficiently and is essential for routing.


## Example

Network: 192.168.1.0/24  
Subnet mask: 255.255.255.0  

Range:
192.168.1.1 - 192.168.1.254  

Broadcast:
192.168.1.255
