# Azure-Nested-Virtualization-HyperV-IIS-Lab
Deployment of an Azure Virtual Machine with Hyper-V and hosting of a Windows Server virtual machine running IIS to simulate a cloud-based enterprise virtualization environment.

## Environment
> Microsoft Azure
> Azure Virtual Machine (Windows Server 2022)
> Hyper-V Role
> Nested Virtual Machine
> Windows Server 
> Internet Information Services (IIS)
> Isolated cloud lab environment

## Disclaimer
"This lab was conducted in a controlled and authorized environment strictly for educational purposes."

## Lab Setup
1. Deploy an Azure Virtual Machine that supports nested virtualization
2. Configure networking and remote access
3. Install the Hyper-V role on the Azure VM
4. Enable nested virtualization features
5. Create a virtual switch for Hyper-V networking
6. Create a nested Windows Server virtual machine
7. Install Windows Server on the nested VM
8. Install and configure IIS on the nested server

## Tools Used
> Microsoft Azure
> Azure Virtual Machines
> Windows Server
> Hyper-V Manager
> PowerShell
> Internet Information Services (IIS)
> Remote Desktop Protocol (RDP)

## Azure Virtual Machine Configuration
> Deployment of a virtualization-capable Azure VM
> Configuration of virtual networking
> Remote administration through RDP
> Allocation of CPU, memory, and storage resources

## Hyper-V Configuration
> Installation of the Hyper-V role
> Configuration of virtual switches
> Creation and management of nested virtual machines
> Validation of nested virtualization functionality

## IIS Server Configuration
> Installation of the IIS Server role
> Configuration of the Default Web Site
> Deployment of sample web content
> Personalization of the default Web Site 

## Validation
> Verify Hyper-V is operational within the Azure VM
> Confirm the nested Windows Server VM boots successfully
> Validate IIS services are running
> Access the hosted website through the configured network

> Keep Windows Server and IIS updated with the latest security patches
> Limit inbound ports to only required services
> Use isolated virtual networks for lab environments
