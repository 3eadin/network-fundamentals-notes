# Spanning Tree Protocol (STP)

## What is STP?

STP prevents loops in a Layer 2 network.

## Why Loops are Dangerous

* Broadcast storms
* MAC table instability
* Network crashes

## Key Concepts

### Root Bridge

* The main switch in the network
* Lowest Bridge ID wins

### Root Port

* Best path to the root bridge

### Designated Port

* Forwarding port for a segment

### Blocking Port

* Disabled to prevent loops

## Port States (Classic STP)

* Blocking
* Listening
* Learning
* Forwarding

## RSTP (802.1w)

* Faster convergence (~1 second)

## What I Learned

STP is essential to keep networks stable and prevent loops.
