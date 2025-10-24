🌐 Azure Virtual WAN - Contoso Network Connectivity Lab

📘 Overview

This project demonstrates how to create and configure an Azure Virtual WAN to connect multiple regional networks securely and efficiently. The lab simulates Contoso’s network architecture, connecting resources across West US and Southeast Asia regions.



Traffic Flow:
Traffic between the Research VNet in Southeast Asia and the Virtual WAN Hub in West US is routed securely through Azure’s global backbone.

🧠 Learning Objectives

By completing this lab, you will learn how to:

Create a Virtual WAN

Deploy a Virtual Hub using the Azure Portal

Connect a VNet to a Virtual Hub

🛠️ Steps Summary
Task 1: Create a Virtual WAN

Navigate to the Azure Portal.

Create a Virtual WAN in West US.

Assign it to ContosoResourceGroup.

Task 2: Create a Virtual Hub

Inside the WAN, create a Virtual Hub.

Set the address space to 10.60.0.0/24.

Deploy in the West US region.

Task 3: Connect a VNet to the Hub

Create a VNet named ResearchVnet in Southeast Asia.

Add a subnet named ResearchSystemSubnet.

Use the VNet connection option to link it to the WAN Hub.

🧹 Clean Up

To avoid unnecessary costs, delete all created resources after verifying connectivity:

Virtual WAN

Virtual Hub

VNets and subnets

Resource Group (optional)


🧰 Tools & Services Used

Azure Virtual WAN

Azure Virtual Hub

Azure VNet and Subnet

Azure Portal

📄 Key Takeaways

Azure Virtual WAN simplifies large-scale network connectivity.

Centralized hub management improves visibility and performance.

Connecting VNets across regions enhances scalability and security.
