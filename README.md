Background / Scenario
We established a new company with four departments , so we want to create different VLANs for each department with enabling inter vlan routing so they can communicate with each other:
HR : VLAN 10 ( 6 users : all PCs)
Sales : VLAN 20 ( 4 users : 2 PCs and 2 Laptops)
IT : VLAN 30 (5 users : all PCs)
PR : VLAN 40 ( 7 users : 3 PCs / 2 laptops / 1 smartphone / 1 tablet)
Available devices to use :
End point devices :16 PCs ,4 laptops ,1 smartphone and 1 tablet
Network devices: 4 L2 switches , 1 L3 switch , 2 routers, 1 WLC , 1 AP , 4 servers ( DNS , DHCP ,AAA and SNMP)
Kindly draw your network topology with only the above devices
Addressing schema :
Our company range is 192.168.0.0/16
Objectives
Part 1: Build the Network and Configure Basic Device Settings ( host names , banner , etc..)
Part 2: Create VLANs and Assign Switch Ports
Part 3: Configure an 802.1Q Trunk between the Switches
Part 4: Configure Inter-VLAN Routing on the Router
Part 5: Verify Inter-VLAN Routing is working
Part 6 : Enable port security on all access ports with maximum 1 MAC and make it sticky
Part 7 : Make the violation mode restrict
Part 8: Enable BPDU guard on access ports
Part 9: Shut down all non used ports
Part 10 : enable DHCP relay and put the DHCP server in another LAN from the HR and Sales departments
Part 11 : Configure 2 WLANs for sales ( WPA2+ PSK )and PR (WPA2 + 802.1X with AAA server through RADIUS)
