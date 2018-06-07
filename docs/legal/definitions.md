# Concept

## ThreeFold (TF)

The concept for creating a new internet by means of a new digital token.

All the ideas and content created for this concept are opensource and stored in this repository. 
A group of volunteers maintain these repositories.

Look at the [website](https://threefoldtoken.com/) which is also stored in a [github repository](https://github.com/threefoldtoken/website).


## ThreeFold Foundation (TFF)

The group of volonteers who contribute to the ThreeFold concept.
Meet them at https://threefoldtoken.com/team/

## ThreeFold Grid (TFG)

The ThreeFold Grid is a new, global neutral and sustainable network of IT infrastructure. On this Grid, IT capacity is indexed registered on the TF Chain for easy discovery by purchasers.

This Internet capacity is produced and allocated locally - similar to the way electricity and other utilities are purchased today. This allows any digital service or application provider to host their services and applications in proximity to the end user leading to significantly greater performance, a lower price point and better margins. This is both more cost effective and green.

## IT Capacity

- IT = Information Technology.
- IT Capacity is resource availability for running any IT Workloads
- Examples of IT Workloads which can run on the TFG are
	- web applications
	- archiving of data
	- generic storage (e.g. using the S3 storage interface)
	- container workloads (e.g. using the Kubernetes interface)
	- artificial intelligence workloads
	- big data workloads (processing of data)
	- gaming servers
	- content delivery
	- test workloads for developers

## ThreeFold Token (TFT)

The ThreeFold Token is a digital Token which allows anyone to buy and sell IT Capacity on the TF Grid. This token only gets issued by the TF Chain if a TF Pool gets connected to the TF Grid.

The TF Chain can issue a maximum of 100 billion tokens.

## TF Chain (TFC)

The blockchain technology as used by the ThreeFold Grid.
This blockchain technology is used to

- let you store & trade your TFTs
- buy/sell capacity on the TFG
- register capacity of the TFG
- provision IT workloads on the TFG
- ...

see the following [github repos](https://github.com/rivine)

## TF Operating System 

The ThreeFold Operating system is the software which makes it possible to convert any pool of hardware to become an ultra efficient pool of resource for the ThreeFold Grid.

Based on 

- [Zero-OS](https://github.com/zero-os) = Ultra Efficient Stateless Operating System
- [Jumpscale](https://github.com/Jumpscale/) = Automation Framework (self healing, ...)

## user (User)

- is the person/organization/company who buys capacity from the TF Grid
- capacity can only be bought by means of TFTs

# ThreeFold Farming

## ThreeFold Farming Pool (FP)

A Pool of storage & compute hardware which allows to provision IT Capacity.

Each Farming Pool runs the TF Operating System and TF Blockchain Software (TF Chain) which allows anyone in the world to use this IT capacity to host their IT workloads (storage apps, archive capacity, web applications, artificial intelligence, iOT, docker containers, etc). To use this IT Capacity, through the TF Grid, people need to own ThreeFold Tokens (“TFTs”) as they are the only possible mechanism to purchase this capacity on the TF Grid. As such, TFTs represent a true utility. 


## ThreeFold Farmer

A ThreeFold Farmer is any organization or person who invests in a ThreeFold Farming Pool and connects this capacity to the ThreeFold Grid.

As a result of Farming, i.e. creating additional capacity, ThreeFold Tokens are automatically created by the ThreeFold Chain. 

Farmers can cultivate both managed and/or unmanaged capacity.

## Unmanaged Capacity

Unmanaged capacity can exist everywhere; in people’s home, in mobile telephone masts, in utility cabinets, next to railways or motorways, anywhere where internet lines meet electrical outlets. This capacity is deployed to the TF Grid and has no people involved to manage its operations (apart from the physical and network aspects).  Farmers have no access to the TF Nodes purchased. They can only use the capacity produced in the exact same way as any other user, i.e. through the TF Chain, in a secure private and neutral way, equally applicable to all.

## Managed capacity

Managed capacity is capacity that sits in a datacenter or other controlled environment where people operate and maintain supervision of the capacity connected to the TF Grid and published in the TF Directory. SLA (Service Level Agreements) are provided on this capacity like uptime, guaranteed bandwidth, response times, ...

# ThreeFold Resource Pools

![https://docs.google.com/drawings/d/1K1LuYRkD12QwIoZ-AduV-X_RxT1J5nUVt3D5vmerUUk/edit](https://docs.google.com/drawings/d/e/2PACX-1vT-dPplNVaQ1-3oWxrjvVsOjoDrdDZrb2t05BQ0WpFU02PucD_TC4cX5-lcdfxzodDJwwcjPgjYGyyP/pub?w=1440&h=810)

## Resource Pool (RP)

Is available capacity in a ThreeFold Farming Pool.
There are typically more than 1 Resource Pool in a Farming Pool and Resource Pools can span multiple Farming Pools.

A Resource Pool is linked to a User, a User is paying tokens for using the IT Capacity.
A Farming Pool is linked to a Farmer, the Farmer receives tokens for providing the IT Capacity.

## Resource Units (RU)

Units of IT capacity as used in a RP, starting from hardware level. More info see [here](https://github.com/threefoldtoken/info/blob/master/concepts/resource_units.md).

## Cloud Units

Units of IT capacity as sold from the TF Grid to Users.
More info see [here](https://github.com/threefoldtoken/info/blob/master/concepts/cloud_units.md)


## TF Node

- is a compute/storage server which provides capacity for Resource Units
- a TF Node is part of a Farming Pool
- TF Nodes are owned by Farmers.
- a TF Node can be virtual e.g. a virtual machine (only for Managed Capacity)

## Resource Bundle (always per TF Node) (Bundle)

- is x number of resource units bundled
- a Resource Bundle is always per TF Node
- e.g. resource bundel type A = 1 cpu unit + 2 mem unit + 3 hd unit + 1 ssd unit
- the resource bundles are defined by the Farmers, its basically a unit of capacity sold. Users cannot buy individual Resource Units, Users buy Resource Bundles by transfering TFT.

## Resource Reservation (Reservation)

- a reservation for X nr of Resource Bundles
- a reservation is the contract between the User and the Farmer
- has a starting date / end date
- has a price linked to it
- a Resource Pool is made up out of X nr of Resource Bundles.

## TF Robots

- There are 3 types of ThreeFold Robots see []()

# Legal

## The Product

The Product is the ThreeFold Token or any service on the ThreeFold Grid which can be bought by The Purchaser.

## The Company

The company or organization who is selling a service on the ThreeFold Grid or ThreeFold Tokens (TFTs).

## The Purchaser

Is the person or company or organization who buys The Product from The Company


