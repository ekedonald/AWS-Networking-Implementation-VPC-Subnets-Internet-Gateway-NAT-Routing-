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

### Benefits of VPC Peering

### Benefits of VPN Connections