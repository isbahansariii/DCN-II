# Project Title: Configuring a Small Enterprise Network

# Objective:
Design and configure a small enterprise network using Cisco Packet Tracer. The network should include multiple VLANs, routing between VLANs, DHCP, and basic security using Access Control Lists (ACLs).

# Requirements:
 # Network Layout:
     + 3 departments (Sales, HR, IT) connected via a switch.
     + Separate VLANs for each department.
     + A router for inter-VLAN routing.
     + DHCP configuration for automatic IP addressing.
     + Implement a wireless network for guest access.
 # Devices:
    + PCs (4 per department)
    + Switches (Layer 2)
    + Router (Layer 3)
    + Access Point (Wireless)
    + DHCP Server
    + DNS Server (optional)
 # VLAN Configuration:
   + VLAN 10: Sales Department
   + VLAN 20: HR Department
   + VLAN 30: IT Department
   + Ensure that each department is on a separate VLAN with proper IP addressing.
 # Inter-VLAN Routing:
  + Configure routing on the Layer 3 router to allow communication between VLANs.
 # DHCP:
  + Set up a DHCP server to assign IP addresses dynamically to each department.
  + Ensure each department gets addresses from different subnets.
 # Access Control Lists (ACLs):
  + Implement an ACL to block HR VLAN from accessing IT VLAN resources.
  + Allow Sales VLAN to access only specific services (e.g., HTTP) on the IT VLAN.
 # Wireless Setup:
  + Configure an access point for guest users.
  + Use WPA2 security for the wireless network
