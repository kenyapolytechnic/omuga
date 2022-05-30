# Industrial PLC



## Industrial Communication Network

### Networks
Communication networks may be used in control systems to pass data between (1) field devices and PLCs, (2) between different PLCs, or (3) between PLCs and personal computers used for operator interface, data processing and storage, or management information.

Although a communications circuit can involve only two pieces of equipment with a circuit between them, the term network typically refers to connecting many devices together to permit the sharing of data between devices over a single (or redundant) circuits.


Data is transmitted over a network using serial communication, in which words of data called bytes consisting of individual logical zeros and ones (bits) are transmitted sequentially from one device to another.

The collection of data in a single transmission is often called a packet. The rate at which data can be transmitted over a network is defined in bits-per-second or bps, but typically expressed in thousands (Kbps) or millions (Mbps).

### Industrial Networks

In large SCADA systems, there is usually a communications network of some type connecting the individual PLCs to the operator interface equipment at the central control room.

#### Typical Networks
Two terms that are commonly used with respect to management information systems communication are local area network (LAN) and wide area network (WAN). 

#### LAN (Local Area Network)
A LAN consists of all of the devices, typically PCs and servers within a particular industrial facility or site.


#### WAN (Wide Area Network)
A WAN is created by providing a connection between LANs, typically over a long geographic distance using telecommunications industrial facilities. 

#### Network Physical Layer Wiring
All communications networks utilize one of two media to transmit data signals between devices: 

(1) Electrical conductors such as copper wire or 
(2) optical conductors such as fiber optic cable 

Wireless communication via radio or microwave radiation does not require an intervening medium


The point on a device at which the circuit is connected is referred to as a communications port; the physical and electrical characteristics of the communications port must match the media to be used for the network.


#### Copper Cables
Copper media will support either (1) point-to-point or (2) tapped network configurations. Copper-based networks may be used between devices and PLCs or between PLCs, but should not be installed over long distances, or across an industrial facility boundary. All copper network cables should be of shielded construction.

For copper-based networks, three basic types of copper conductors are used.


#### 1. Shielded Twisted pair (STP)

![Shielded twisted pair](images/shielded-twisted-pair-cable-stp.jpg)
Shielded twisted pair (STP), in which individual pairs of insulated conductors are twisted together to reduce inductively coupled interference and covered with a continuous metallic foil shield to reduce capacitively coupled interference.

Individual pairs or multiple pairs are then assembled into a cable within an overall jacket that provides environmental protection.

#### 2. Unshielded Twisted pair (UTP)
![Shielded twisted pair](images/Cat5-UTP-Unshielded-Twisted-Pair-Cable.jpg)

Unshielded twisted pair (UTP), have individual pairs of insulated conductors that are twisted together to reduce inductively coupled interference.

Individual pairs or multiple pairs are then assembled into a cable with an overall jacket to provide environmental protection.

#### 3. Co-axial
![Shielded twisted pair](images/networking-coaixal_cable_01.jpg)
![Shielded twisted pair](images/coax.png)
Coaxial cables have concentric layers of electrical conductors and insulating material. This construction ensures signals are enclosed within the cable and prevents electrical noise from interfering with the signal.

Configurations are available with multiple coaxial cables within a common overall jacket; these are often referred to as twin-ax (2 cables) or tri-ax (3 cables). Coaxial cable construction is inherently shielded.


#### CAT5 & CAT6
#### Fiber Networks

#### Half Duplex

#### Full Duplex



### Network Design
#### Topology
#### Ring
#### Star
#### Bus

### Protocols
#### Ethernet
#### RS485
#### RS232
#### Field bus
#### HART
### Physical Industrial Networks
### Network Devices
#### Modems
#### Network Switches
#### Terminal Reflectors
#### Signal Amplifiers
#### Network hubs
#### Network budges

