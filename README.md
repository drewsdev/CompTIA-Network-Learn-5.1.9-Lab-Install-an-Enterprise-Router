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
