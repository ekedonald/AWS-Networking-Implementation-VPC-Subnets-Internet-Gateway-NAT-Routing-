# AWS Networking Implementation (VPC, Subnets, Interet Gateway, NAT & Routing)

## What Is an Amazon VPC?
An Amazon Virtual Private Cloud (VPC) is like your own private section of the Amazon cloud where you can place and manage resources (i.e. servers or databases). You control incoming and outfoing traffic like a gated community.

### The Default VPC
The default VPC is like a starter pack provided by amazon for your cloud resources. It is a pre-configured space in the Amazon cloud where you can immediately start deploying your apllications or services. It has built-in-security and network settings to help you get up and running quickly but you can adjust these as you see fit.

A Default VPC which Amazon provides for you in each region (think of a region as a separate city) is like a pre-built house in that city. This house comes with some defaukt settings to help you move in and start living (or start deploying your applications) immediately but juat like a real house, you can change these settings according to your needs.

### Creating a new VPC

### Creating & Configuring Subnets
#### What are Subnets?
Subnets are like smaller segments within a VPC that help you organize and manage your resources. Subnets are like dividing an office building into smaller sections, where each section represents a department. In this analogy, subents are created to organize and manage the network effectively.

### Understanding Public & Private Subnets in AWS VPC
#### Creating a Public Subnet

#### Creating a Private Subnet

#### Working With Public & Private Subnets

## Internet Gateway & Routing Table

#### Introduction to Internet Gateway & Table

#### What is an Internet Gateway?

#### Public Subnets

## What is a Routing Table?

### Creating & Configuring Routing Tables

## NAT Gateway & Private Subnets
### Introduction to Private Subnets & NAT Gateway

### Understanding NAT Gateway

### Creating a NAT Gateway & Linking it to a Private Subnet

## Security Group & Network ACLs

### Understanding the Differences between Security Groups & Network Access Control Lists

### Network Access Control {NACLs}

## VPC Peering & VPN Connection

### Introduction to VPC Peering
VPC Peering is a networking feature that allows you to connect 2 Virtual Private Clouds (VPCs) within the same cloud provider's network or across different regions. VPC Peering enables direct communicstion between VPCs allowing resources in each VPC to interact with eacg other as if they were on the same network. It provides a secure and private connection without the need for internet access. VPC Peering is commonly used to establish connectivity between VPCs in scenarios such as multi-tier apllications, resouce sharing or data replication.

### Benefits of VPC Peering

### Inroduction to VPN Connections
Virtual Private Network (VPN) connections establish a secure and encrypted communication channel betwen your on-premises network and a cloud provider's network such as a VPC. VPN connections enable secure access to resourcs in the cloud from remote locations or connect on-premuses netwokrs with cloud resources.

There are two primary types of VPN connections which are:

1. **Site-to-Site VPN**: It establishes a secure connetion between your on-premises network and the cloud provider's network. It allows communication between your on-premises resources and resources in the VPC securely and privately. This type of VPN connection is commonly used in Hybrid Cloud Architectures.

2. **AWS Client VPN**: AWS Client VPN provides secure remote acces to the cloud network for individual users or devices. It enables secure connectivity for remote employees, partners or contractors to access resoruces in the VPC securely.

### Benefits of VPN Connections
* **Secure Remote Access**: VPN connections enable secure access to resources in the cloud network for remote users or devices ensuring data privacy and protection.

* **Data Encryption**: VPN connections encrypt the data transmitted between your on-premises network and the cloud network providing a secure channel for data transfer.

* **Flexibility and Mobility**: VPN connections allow authorized users to securely access cloud resources from any location promoting flexibility and mobility in accessing critical applications and data.

* **Hybrid Cloud Connectivity**: VPN connections play a vital role in establishing secure and reliable connectivity between your on-premises network anc cloud resources facilitating hybrid cloud architectures and seamless integration.

