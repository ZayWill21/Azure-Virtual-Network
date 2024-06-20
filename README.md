Virtual Architecture Environment with Azure Cloud using Terraform
Welcome to my repository! This project demonstrates how to use Terraform to create a virtual architecture environment in Azure Cloud. The primary goal is to showcase the power of Infrastructure as Code (IaC) and how Terraform can be leveraged to automate the deployment and management of cloud infrastructure.

Project Overview
In this project, we use Terraform to set up a virtual network architecture on Azure, including various network components such as subnets, network interfaces, public IP addresses, and virtual machines. The configuration files are written in HCL (HashiCorp Configuration Language) and can be easily customized to fit different requirements.

Features
Virtual Network: Creates a virtual network with specified address space.
Subnets: Configures subnets within the virtual network.
Network Interfaces: Sets up network interfaces and associates them with public IP addresses.
Public IP Addresses: Creates and manages public IP addresses for network interfaces.
Virtual Machines: Deploys virtual machines within the network.
Security Groups: Manages security groups to control inbound and outbound traffic.
Prerequisites
Before you begin, ensure you have the following installed:

Terraform
Azure CLI
An Azure account with appropriate permissions to create resources
