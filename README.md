# CompTIA-Network-Learn-5.1.9-Lab-Install-an-Enterprise-Router
## CompTIA CertMaster Learn v9.1

To install the router and complete the connectivity, perform the following tasks.

* Add the router to the rack in the open spot near the top.  
* Install the necessary SFP Transceiver adapters.  
  * Insert an SFP Transceiver (RJ45) in the WAN port on the router.  
  * Insert an SFP Transceiver (LC) in the LAN 1-4 ports on the router.  
* Use the AC power cable with C14 end to connect the router to a critical load bank outlet on one of the UPSs.  
* Select the necessary fiber cable and connect the LAN ports on the router to the appropriate port on the fiber patch panel.  
  * To properly connect to the fiber patch panel, use the color coding on the end of the fiber optic cables to identify which end is Tx and which is Rx.  
    * Connector A (white or red) is Tx.  
    * Connector B (black) is Rx.  
  * The fiber patch panel has the odd ports set as Tx and the Even numbered ports set as Rx.  
  * Make the following connections:  
    * LAN 1 port on the router to ports 1 and 2 on the fiber patch panel  
    * LAN 2 port on the router to ports 3 and 4 on the fiber patch panel  
    * LAN 3 port on the router to ports 5 and 6 on the fiber patch panel  
    * LAN 4 port on the router to ports 7 and 8 on the fiber patch panel  
* Connect the WAN port on the router to a port on the pfSense device at the top of the rack using a Cat6a cable.

![Exhibit](/Screenshot_1.png)  
![Connections](/Screenshot_2.png)

Explanation

Complete this lab as follows:

1. Add the router to the empty slot near the top of the rack.  
  a. Under Shelf, expand Routers.  
  b. Drag the Router to the first open space at the top of the rack in the Workspace.  
2. Insert an SFP Transceiver (RJ45) into the WAN port on the router.  
  a. Under Shelf, expand Adapters.  
	b. Drag the SFP Transceiver (RJ45) to the WAN port on the router.  
3. Insert an SFP Transceiver (LC) into the LAN 1-4 ports.  
	a. Under Shelf, expand Adapters.  
	b. Drag an SFP Transceiver (LC) to each of the LAN 1-4 ports on the router.  
4. Use the AC power cable with C14 end to connect the router to a critical load bank outlet on one of the UPSs.  
	a. Above the rack, select Back to switch to the back view of the rack.  
	b. Under Shelf, expand Cables.  
	c. Select the AC Power Cable with C14 end.  
	d. From the Selected Component pane, drag the AC Power Connector to the router and the AC Power Connector C14 to a critical load bank outlet on a UPS.  
5. Connect the LAN 1 port on the router to ports 1 and 2 on the fiber patch panel using an SC to LC fiber cable.  
	a. Above the rack, select Front to switch to the front view of the rack.  
	b. Select the SC to LC fiber cable.  
	c. From the Selected Component pane:  
			* Drag the Duplex LC Fiber Connector to the LAN 1 port on the router.  
			* Drag the Fiber Optic SC Connector (A) to port 1 on the fiber patch panel.  
			* Drag the Fiber Optic SC Connector (B) to port 2 on the fiber patch panel.  
6. Connect the LAN 2 port on the router to ports 3 and 4 on the fiber patch panel using an SC to LC fiber cable.  
	a. Under Cables on the Shelf, select the SC to LC fiber cable.  
	b. From the Selected Component pane:  
			* Drag the Duplex LC Fiber Connector to the LAN 2 port on the router.  
			* Drag the Fiber Optic SC Connector (A) to port 3 on the fiber patch panel.  
			* Drag the Fiber Optic SC Connector (B) to port 4 on the fiber patch panel.  
7. Connect the LAN 3 port on the router to ports 5 and 6 on the fiber patch panel using an SC to LC fiber cable.  
	a. Under Cables on the Shelf, select the SC to LC fiber cable.  
	b. From the Selected Component pane:  
			* Drag the Duplex LC Fiber Connector to the LAN 3 port on the router.  
			* Drag the Fiber Optic SC Connector (A) to port 5 on the fiber patch panel.  
			* Drag the Fiber Optic SC Connector (B) to port 6 on the fiber patch panel.  
8. Connect the LAN 4 port on the router to ports 7 and 8 on the fiber patch panel using an SC to LC fiber cable.  
	a. Under Cables on the Shelf, select the SC to LC fiber cable.  
	b. From the Selected Component pane:  
			* Drag the Duplex LC Fiber Connector to the LAN 4 port on the router.  
			* Drag the Fiber Optic SC Connector (A) to port 7 on the fiber patch panel.  
			* Drag the Fiber Optic SC Connector (B) to port 8 on the fiber patch panel.  
9. Connect the WAN port on the router to a port on the pfSense device at the top of the rack.  
	a. Under Cables on the Shelf, select the Cat6a Cable.  
	b. From the Selected Component pane, drag one of the RJ45 Shielded Connectors to the WAN port on the router and the other to a port on the pfSense device above the router.
