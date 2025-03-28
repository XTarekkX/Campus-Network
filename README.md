# Campus-Network
a networking project creating a full campus network with 2 branches and several departments.
divided to 2 branches Faculty of engineering and faculty of health.
faculty of engineering consists of several buildings (ssp, electical engineering, adminstration buildings) each have floors and departments (8 departments across all the buildings).
The departments are seperated using VLAN segmentation each department has different ip network ex: 192.168.1.0 192.168.2.0 192.168.10.0 etc..
faculty of health have only 2 departments staff and student labs.
used RIPV2 for routing along with ROAS for intervlan routing.
the ip are acquired dynamically using router based dhcp server.
A working email server is present.
