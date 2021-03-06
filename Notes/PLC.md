# Industrial PLC

Industrial automation began long before PLCs. In the early to mid 1900s, automation was usually done using complicated electromechanical relay circuits. However, the amount of relays, wires and space needed to create even simple automation was problematic. Thousands of relays could be necessary to automate a simple factory process! And if something in the logical circuit needed to be changed, it was a very difficult task.

In 1968 the first programmable logic controller came along to replace complicated relay circuitry in industrial plants. The PLC was designed to be easily programmable by plant engineers and technicians that were already familiar with relay logic and control schematics. Since the beginning PLCs have been programmable using ladder logic which was designed to mimic control circuit schematics. The ladder diagrams look like control circuits where power is flowing from left to right through closed contacts to energize a relay coil.

## 1. Introduction to PLCs
PLC stands for programmable logic controller, and can loosely be defined as *a solid-state computer that monitors both inputs and outputs of automated processes in a manufacture chain, making logic-based decisions based on inputs received.*

The PLC performs the logic functions of relays, timers, counters and sequencers. It has the following advantages:

Programming the PLC is easier than wiring the relay control panel.

1. The PLC can be reprogrammed. Conventional controls must be rewired and are often scrapped instead.
2. PLCs take less floor space then relay control panels.
3. Maintenance of the PLC is easier, and reliability is greater.
4. The PLC can be connected to the plant computer systems more easily than relays can.

![](images/PLC2.jpg)


### Process Control
Process control is the manipulation of process variables (e.g., feed, speed, depth-of-cut) to regulate the processes. Machine
tool operators perform on-line and off-line process control by adjusting feeds and speeds to suppress chatter, initiating an emergency stop in response to a tool breakage event, rewriting a part program to increase the depth-of-cut in order to minimize burr formation and many more. 

But PLCs are required in process control in modern industries. Process control is used in continuous production ??? in manufacturing and in other fields and industries where some kind of material is produced without any kind of interruption ??? as well as in ???batch processing.??? It is used to automatically control the conditions in which a product is made ??? ensuring better quality and efficiency. ???Wastewater management, for example, involves the continuous and unceasing treatment of greywater and sewage, without any interruptions ??? so this is a field in which process control is used.

Process control uses specialised, often custom-built industrial control systems. These systems control the flow, output, mixture, and other such aspects of a continuous production process, based on feedback from sensors, data monitoring systems and more. 

Process control systems operate on a much more refined, powerful level than a system that is purely controlled by humans. For example, consider what would offer better results when pasteurising milk ??? a single individual taking a temperature reading manually, then shutting off the heat when the milk reaches the right temperature ??? or a sensor in a pasteurisation tank that automatically senses when the milk has been pasteurised properly, and then automatically empties the machine, and moves the product onto the next step.

Essentially then, process control is all about eliminating human feedback ??? and allowing the advanced, automated systems of an industrial plant to handle minor adjustments automatically, without intervention beyond human monitoring of each system.

### Manufacturing Process Monitoring
*Process monitoring is the manipulation of sensor measurements (e.g., force, vision, temperature) in determining the state of the processes.* A machine tool operator performs routine monitoring tasks; for example, visually detects missing and broken tools as well as chatter from the characteristic sound it generates. Unmanned monitoring algorithms utilize filtered sensor measurements which, along with operator inputs, determine the process state. The states of complex processes are monitored by a sophisticated signal processing of sensor measurements.

PLCs monitor and collect data from connected inputs and machinery. Because of this, *software programs, such as SCADA and Machine Monitoring systems, can connect to PLCs to process collected machine data and display useful information*, such as production reports, live-trends, alarm notifications, OEE metrics, cycle or batch status, and more.

### Need for PLCs:

1. *PLCs are easy to program.* They???re as easy for a technician to work with as a consumer. You can also extend a PLC system by programming it to follow a set of instructions if certain conditions are true.
2. *PLCs Can Offer A Unified Programming Environment*. PLCs work well with PCs, PACs (programmable automation controllers), motion control devices, and HMIs.
3. *PLCs Collect Robust Data*. The number of inputs you set on a PLC system is up to the user. This means that there is no limit to the number of data sources, nor the amount of data streaming in. Measuring devices, sensors, and motion controls can pick up on several parameters, so it???s up to the user to delineate how this data is collected and how the output displays.
4. *PLCs Can Be Used For Predictive Maintenance*. Predictive maintenance starts with preventative maintenance. If particular equipment reaches a pre-programmed threshold, a sensor goes off that tells the technician that the equipment needs maintenance or replacement. Enough of these reports are then collected as data points themselves to communicate to the system about which factors predict wear and tear or an impending issue. PLCs would interact with a SCADA to display maintenance schedules or allow the flexible configuration of new maintenance rules.
5. PLCs have high reliability
6. Compared to relay contactor logic this technology is for better then previous outdated Technology here less wiring required means less maintenance.
7. PLCs constantly monitor the state of the systems through input devices and generate the control actions according to the logic given in the user program.


### Parts of a PLC

![](images/PLC.png)

There are 5 major components, the 6th being the external programming device:
1. CPU (Central processing unit) - which is the brain of the device
2. Memory
3. Input module
4. Output Module
5. Power Supply
6. External Programming Device

The components are housed in a suitable cabinet designed for the industrial environment.

The input module and output module are the connections to the industrial process that need to be controlled. The inputs to the controller are signals from *limit switches, push-buttons, sensors, and
other on-off devices.* In addition, larger PLCs are capable of accepting signals from analogue devices of the type modelled. The outputs from the controller are *on-off signals* to operate motors, valves, and other devices required to actuate the process.

The processor is the central processing unit (CPU) of the programmable controller. It executes the various logic and sequencing functions described in previous Sections by operating on the PLC INPUTS TO DETERMINE THE APPROPRIATE OUTPUT SIGNALS. The processor is normally a 16 or 32-bit a microprocessor.

Tied to the CPU is the PLC memory, which contains the program of logic, sequencing, and other input/output operations. The memory for a programmable logic controller is specified in the same way as for a computer, and may range from 1k to over 48k of storage capacity.

A power supply is specially used to drive the PLC even though the components of the industrial process that are regulated may have a higher voltage and power rating than the controller itself.

The PLC is programmed by means of a programming device. The programming device (sometimes referred to as a programmer) is usually detachable from the PLC cabinet so that it can be shared between different controllers.

### Common Uses of a PLC
1. Industrial automation
2. Prepaid electricity meters
3. Washing machines
4. Elevators
5. Traffic signals

### How PLCs work
The PLC takes inputs, performs logic on the inputs in the CPU and then turns on or off outputs based on that logic. Think of it like this:

1. The CPU monitors the status of the inputs (ex. switch on, proximity sensor off, valve 40% open, etc.)
2. The CPU takes the information that it gets from the inputs, performs logic on the inputs
3. The CPU operates the outputs logic (ex. turn off motor, open valve, etc.)

## Types of Industrial Control Systems

1. Programmable Logic Controllers (PLCs)
2. Intelligent Electronic Devices (IEDs)
3. Supervisory Control and Data Acquisition (SCADA)
4. Programmable Automation Controllers (PACs)
5. Human-Machine Interface (HMI)
6. Industrial Automation and Control Systems (IACS)
7. Remote Terminal Units (RTUs)
8. Distributed Control Systems

## Types of Industrial Software Systems

Industrial software is a collection of application programs, processes, methods and functions that can aid in collection, manipulation and management of information on an industrial scale. Sectors that make use of industrial software include operations, manufacturing, designing, construction, mining, textile mills, chemicals, food processing and service providers.

### 1. Graphical User Interface (SCADA)
SCADA systems include hardware and software components. The hardware gathers and feeds data into field controller systems, which forward the data to other systems that process and present it to a human-machine interface (HMI) in a timely manner. SCADA systems also record and log all events for reporting process status and issues. SCADA applications warn when conditions become hazardous by sounding alarms.

*HMI software* provides a system that consolidates and presents data from SCADA field devices and enables operators to understand and, if needed, modify the status of SCADA-controlled processes.

### 2. PLC Programming Software
PLC programming software is the collective term referring to the data and instructions provided to a PLC (programmable logic controller) via various types of programming languages. These instructions are executed by the PLC to operate, monitor and control machinery and equipment.

### 3. Configuration Software
Calibration is the activity of checking, by comparison with a standard, the accuracy of a measuring instrument of any type.  It may also include adjustment of the instrument to bring it into alignment with the standard.

In the process industries, a critical part of asset management strategy of a company is the calibration of the process instru-ments  and  other  devices.  Often  companies invest  millions of  dollars  on  instruments  and  they  find  that  uncalibrated instruments  provide misinformation that can cost the  com-panies extra millions of dollars. Also, instruments drift from calibrated  status  under  operational  conditions  resulting  in misleading readings too. Process plants such as pharmaceu-ticals, chemicals, nuclear, metal processing, paper, food and beverage, power, oil  and gas  industries  need to  make  sure that  their  instrumentation in  the plant such  as  temperature sensors, pressure transducers, flow meters, and  the like  are performing as expected and measuring within the specified tolerances.

In process industry, calibration of devices ensures that the processes are well controlled and the products meet expected specifications.

### 4. Calibration Management Software
Calibration management software is a type of quality control software that keeps schedules of the calibration and preventative maintenance service of measurement equipment in manufacturing settings. Calibration software is an automated quality management system that oversees calibration scheduling, optimizes calibration frequency, performs measurement systems analysis, and generates reports and calibration certificates.


## 2. Industrial Communication Network

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
CAT5 cable is made up of four twisted pairs of copper wire. Can handle up to 10/100 Mbps at a 100 MHz bandwidth.

A CAT6 cable is similar to a Cat5 ethernet cable ??? it consists of four pairs of twisted copper wire. However, it provides much more functionality. A Cat6 cable has a bandwidth capacity of 250 MHz, for example, and it offers speeds of up to 10 Gbps. 


#### Fiber Networks

![](images/fiber-optic-cabling.webp)
Fiber-Optic cabling is a glass cabling media that sends network signals using light. Fiber-optic cabling has higher bandwidth capacity than copper cabling.

Fiber-optic cabling consists of a signal-carrying glass core of 5 to 100 microns in diameter (a sheet of paper is about 25 microns thick and a human hair about 75 microns thick), surrounded by a layer of pure silica called cladding, which prevents light from escaping.

Surrounding the cladding are protective layers of acrylic plastic coating, Kevlar fibers for additional strength, and a PVC (polyvinyl chloride) jacket.

Network components use LED or laser diodes to convert electrical signals into light pulses for transmission on fiber-optic cables. An optical detector is used to convert the light pulses back into electrical signals.

There are two types of fiber-optic cabling:

1. Single-mode fiber-optic cabling: 
Has a narrow core (5 or 10 microns in diameter) and allows only one signal to be sent or received at a time over very long distances (up to 50 times farther than multimode fiber-optic cabling). Single-mode fiber-optic cabling uses laser-emitting diodes to introduce signals into the fiber and can transmit only one signal (light beam) at a time. Signal transmission is clear for approximately 30 miles (50 kilometers) before dispersion will distort signals, which means that single-mode fiber is ideal for long cable runs. 

2. Multimode fiber-optic cabling: 
Has a thicker core (50, 62.5, or 100 microns in diameter) and has sufficient bandwidth to allow multiple signals to be simultaneously transmitted or received; each signal follows a different path or mode through the fiber. Light-emitting diodes are used instead of laser-emitting diodes to introduce signals into multimode fiber. Signal transmission is clear for approximately 3000 feet, but longer cable runs can distort signals through modal dispersion. 

There are two types of multimode fiber: 
1. Step-index multimode fiber: The less costly variety of multimode fiber, it uses a wide core with a uniform index of refraction, causing the light beams to reflect in mirror fashion off the inside surface of the core by the process of total internal reflection. Because light can take many different paths down the cable and each path takes a different amount of time, signal distortion can result when step-index fiber is used for long cable runs.
2. Graded-index multimode fiber: The more expensive type of multimode fiber, it uses a core made of multiple concentric layers of glass, each having a lower index of refraction than the layer it contains. In graded-index fiber, light beams follow curved paths and all rays reach the end of the fiber simultaneously, reducing the signal distortion that occurs in step-index fiber when long cable runs are used. 


### Transmission Mode
Transmission mode means transferring data between two devices. It is also known as a communication mode. Buses and networks are designed to allow communication to occur between individual devices that are interconnected. There are three types of transmission mode:- 

#### 1. Simplex (Simple Mode)
![](images/simplex.png)
In Simplex mode, the communication is unidirectional. Only one of the two devices on a link can transmit, the other can only receive. The simplex mode can use the entire capacity of the channel to send data in one direction. 
Example: Keyboard and traditional monitors. The keyboard can only introduce input, the monitor can only give the output. 

#### 2. Half Duplex
![](images/halfduplex.png)
Half-duplex devices can only transmit in one direction at one time. With half-duplex mode, data can move in two directions, but not at the same time.

#### 3. Full Duplex
![](images/fullduplex.png)
The term full-duplex describes simultaneous data transmission and receptions over one channel. A full-duplex device is capable of bi-directional network data transmissions at the same time.



### Network Design
let students refer to class notes.

#### Topology
#### Ring
#### Star
#### Bus

### Protocols

#### Ethernet
Ethernet protocol is a typical LAN technology. Standard Ethernet-based local area networks transmit data at speed up to 10 Mbps. New Ethernet cards known as Fast Ethernet represent high-speed LAN technology as it can provide data transfer rates as high as 100 Mbps.


### Serial Communication
In telecommunication, the process of sending data sequentially over a computer bus is called as serial communication, which means the data will be transmitted bit by bit. While in parallel communication the data is transmitted in a byte (8 bit) or character on several data lines or buses at a time. Serial communication is slower than parallel communication but used for long data transmission due to lower cost and practical reasons.

Serial communication
![](images/Serial-communication.png)


Parallel communication
![](images/Parallel-communication.png)


**Modes of Data Transfer in Serial Communication:**

1. **Asynchronous Data Transfer** ??? The mode in which the bits of data are not synchronized by a clock pulse. Clock pulse is a signal used for synchronization of operation in an electronic system.
2. **Synchronous Data Transfer** ??? The mode in which the bits of data are synchronized by a clock pulse.


**Characteristics of Serial Communication:**

1. **Baud rate** is used to measure the speed of transmission. It is described as the number of bits passing in one second. For example, if the baud rate is 200 then 200 bits per Sec passed. In telephone lines, the baud rates will be 14400, 28800 and 33600.

In the serial port context, "9600 baud" means that the serial port is capable of transferring a maximum of 9600 bits per second.
2. **Start Bit**: The start bit is used to signal the beginning of a frame.  Both transmitter and receiver assume that the channel is initially idle (i.e. zero volt logical level). The beginning of a frame is then signalled by setting the channel high for a specified length of time and then setting it low again. Transmission of data bits usually commences a specified interval of time after the falling edge of the start bit.
3. **Stop Bits** are used for a single packet to indicate the end of the packet.
4. **Parity Bit** is the simplest form of checking the errors. There are of four kinds, i.e., even odd, marked and spaced. For example, If 011 is a number the parity bit=0, i.e., even parity and the parity=1, i.e., odd parity.

Timing Diagram for Serial protocol
![](images/timingDiagram.png)

#### RS485
RS-485 is an industrial specification that defines the electrical interface and physical layer for point-to-point communication of electrical devices. RS-485 and RS-422 are serial interface standards in which data is sent in a differential pair (two wires, or twisted pair cable), which allows greater distances and higher data rates than non-differential serial schemes such as RS-232

Most electrical signals are single-ended, comprised of a single wire and ground. Differential signals use two wires which are the inverse of each other -- when one swings positive, the other swings negative in equal magnitude. The receiving circuit looks only at the difference between the two, ignoring any common-mode voltage. This "push-pull" arrangement reduces the impact of electrical interference because external noise will affect both wires equally and the common-mode rejection will ignore the noise.


#### RS232
The term RS232 stands for "Recommended Standard 232" and it is a type of serial communication used for transmission of data normally in medium distances.

In telecommunication, the process of sending data sequentially over a computer bus is called as serial communication, which means the data will be transmitted bit by bit. While in parallel communication the data is transmitted in a byte (8 bit) or character on several data lines or buses at a time. Serial communication is slower than parallel communication but used for long data transmission due to lower cost and practical reasons.


#### Field bus
Let students find out about this.

#### HART
Let students find out about this.


### Physical Industrial Networks

### Network Devices
#### Modems
A modem is a computer hardware device that converts data from a digital format into a format suitable for an analog transmission medium such as telephone or radio. A modem transmits data by modulating one or more carrier wave signals to encode digital information, while the receiver demodulates the signal to recreate the original digital information. The goal is to produce a signal that can be transmitted easily and decoded reliably. Modems can be used with almost any means of transmitting analog signals, from light-emitting diodes to radio.

#### Network Switches
![](images/switch.jpg)
A switch is a data link layer device in a computer network that connects other devices together. Multiple data cables are plugged into a switch to enable communication between different networked devices. Switches manage the flow of data across a network by transmitting a received network packet only to the one or more devices for which the packet is intended. Each networked device connected to a switch can be identified by its network address, allowing the switch to direct the flow of traffic maximizing the security and efficiency of the network.

They use MAC addresses to forward data at the data link layer (layer 2) of the OSI model. Some switches can also forward data at the network layer (layer 3) by additionally incorporating routing functionality. 

A switch is more intelligent than an Ethernet hub, which simply retransmits packets out of every port of the hub except the port on which the packet was received, unable to distinguish different recipients, and achieving an overall lower network efficiency.

#### Network hubs
![](images/hub_and_switch.jpg)
A hub is a physical layer networking device which is used to connect multiple devices in a network. They are generally used to connect computers in a LAN. When a data frame arrives at a port, it is broadcast to every other (except the port from which the data is received) port, without considering whether it is destined for a particular destination or not.


#### Network bridges
A network bridge is a computer networking device that creates a single, aggregate network from multiple communication networks or network segments. This function is called network bridging.[1] Bridging is distinct from routing. Routing allows multiple networks to communicate independently and yet remain separate, whereas bridging connects two separate networks as if they were a single network.[2] In the OSI model, bridging is performed in the data link layer (layer 2).[3] If one or more segments of the bridged network are wireless, the device is known as a wireless bridge.

#### Router
A router is a networking device that forwards data packets between computer networks. Routers perform the traffic directing functions on the Internet. Data sent through the internet, such as a web page or email, is in the form of data packets. A packet is typically forwarded from one router to another router through the networks that constitute an internetwork (e.g. the Internet) until it reaches its destination node.


#### Terminal Reflectors
Let students find out about this.

#### Signal Amplifiers
Let students find out about this.
