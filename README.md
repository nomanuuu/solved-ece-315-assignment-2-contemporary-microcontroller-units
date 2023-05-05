Download Link: https://assignmentchef.com/product/solved-ece-315-assignment-2-contemporary-microcontroller-units
<br>
<ol>

 <li>Like many other contemporary microcontroller units (MCUs), the MCF54415 provides the ability to enter a lowpower mode, which would be attractive in applications where the system is battery-powered and where one wants to avoid wasting the limited stored energy when the MCU does not need to be running. Consult the on-line reference manual for the MCF54415 and briefly explain how the <em>wait</em>, <em>doze</em> and <em>stop</em> modes save power while preserving different degrees of MCU functionality. How does one cause the MCU to enter each of the three modes? How does one get the MCU to exit from the modes and go back to executing software in normal operation?</li>

 <li>In the lectures we discussed (1) multiple nonpreemptive loops with interrupts, and (2) periodically-scheduled statedriven code. What are the major similarities and differences between these two software architectures?</li>

 <li>What are the major advantages to designing the software in a real-time embedded system using tasks that execute ina multitasking software architecture? When would it be more appropriate to choose a single-threaded bare-metal software architecture instead of a multitasking architecture?</li>

 <li>Briefly explain how a co-operative multitasking software architecture could be implemented in MicroC/OS. Be sureto provide some idle time in your design to provide timing flexibility. You do not have to provide a full implementation in C for your proposed design, but you do need to propose a design that could be readily implemented using the existing features of MicroC/OS.</li>

 <li>In a pre-emptive multitasking system there are typically two systems of priorities: one for the tasks and one for thehardware interrupts. What are the different purposes of the two systems of priorities? In which ways do the two systems of priorities interact?</li>

 <li>Consider the design of an asynchronous serial data connnection that must reliably communicate data packets thatare 1500 bytes long. The nominal bit rate is to be 115200 bits per second. Reliable transport is assumed to be possible only if the sampling time stays within the middle 75% of the bit time. The receiver clock operates at 32 times the frequency of the transmitter clock, and the timing recovery scheme allows the receiver to select the best of 32 possible phases when choosing a divided-down receiver clock to be used to approximate the transmitter clock. How accurate must the transmitter and receiver clock frequencies be, in parts per million, in order to ensure reliable communication of the data packets?</li>

 <li>Consult the documentation of the Micrel KS8721BT PHY and note that Ethernet 10BASE-T uses a Manchester linecode while Ethernet 100BASE-TX uses a 4B5B line code. Using reputable Internet resources determine what the purpose of these codes code is, and provide the tables that define what these codes are. What do you think is the main advantage of using the the 4B5B code instead of the Manchester code?</li>

 <li>Briefly define each of the following terms in computer networking: (a) duplex point-to-point link; (b) fullyconnected topology; (c) collision; (d) cross-over cable; and (e) daisy-chain configuration.</li>

</ol>