## Mini-dictionary of Microelectronics (EN)

List of abbreviations, terms, and concepts used in hardware development and microelectronics research.

**Index**

1. [Semiconductor Fundamentals](#idCMOS)
2. [VLSI](#idVLSI)
3. [VDSM](#idVDSM)
4. [Digital Design](#idDD)
5. [ASICs](#idASIC)

***

<a name="idCMOS"></a>

<details markdown="1">

<summary><b>Semiconductor Fundamentals (MOSFET)</b></summary>

| Acronym/Term | Full Name | Description |
| --- | --- | --- |
|  | Band Gap | Energy difference between the valence band and the conduction band, defining the minimum energy required to free an electron (eV). |
|  | Band Theory | A model used to explain the condition of solids and electron behavior. |
|  | Polycrystalline | Atomic structure of silicon where silicon crystals are fused together. |
|  | Layer | Different material levels stacked on the chip, each with a specific function in device construction and interconnections. |
|  | Mask | Masks used in the lithography and doping process, containing patterns to be transferred to the wafer or another mask. |
|  | Silicon Wafer | A slice of the ingot used as the base for IC manufacturing. |
| _ICs_ | Integrated Circuits | Integrated circuits. |
|  | Ingot | Cylindrical pure silicon ingots, raw material for semiconductors. |
|  | Die | The useful area used by the chip on the Wafer. |
|  | Scribe line | Non-functional spaces between dies, where cutting saws pass through. |
| _TEG_ | Test Element Group | A pattern that reveals the real physical characteristics of a chip (C, L, R, Transistors...) for testing. |
|  | Edge Dies | Dies at the wafer edges, which may be discarded due to expected fabrication failures. |
|  | Flat Zone | Wafer edge that is cut to identify the wafer. |
|  | Foundry | Factories that produce chips for third parties. They buy and integrate equipment from various manufacturers but do not design. Responsible for processes. Example: Samsung, TSMC. |
| _Fabs_ | Fabrication Plants | Factories that produce chips for themselves, designing, manufacturing, and selling. IDM manufacturers. Example: Intel. |
| _Fabless_ | Fabless Chip Companies | Companies that create their designs (may also use IPs) using EDA and manufacture their projects in foundries, potentially selling them or using them exclusively. Example: Apple, Qualcomm, AMD, Nvidia. |
| _IDMs_ | Integrated Device Manufacturers | They design, manufacture, and sell their own chips. Example: Micron, Intel, Analog Devices. |
| _WFE_ | Wafer Fab Equipment | Machines that manufacture chips. Examples: Applied Materials, KLA, LAM, Tokyo Electron, and ASML. |
| _OSAT_ | Outsourced Semiconductor Assembly and Test | Factories that package and test chips from foundries. |
| _DH_ | Design House | Companies specialized in some stage of VLSI, operating within Fabs or as Fabless. Basically, they design for other companies, not for themselves, acting as an outsourced service. |
|  | Layout | The IC floorplan. |
|  | Reticles | Tool containing a pattern image that needs to be repeated in steps to expose the entire wafer or mask. |
|  | Mask Layer | Mask layers, generally represented by different colors. Example: Metal, poly, n+diff, Contact, etc. |
|  | Mask Data | The final file describing all chip masks, usually in OASIS or GDSII format. |
| _DRC_ | Design Rules Check | Manufacturing rules of the used technology that the Layout must obey, including cell checking, signoff, routing, structures, names, maps. |
| _PUN_ | Pull-Up | PMOS transistors connected in parallel to VDD, located at the top to avoid short circuits in the CMOS connection. |
| _PDN_ | Pull-Down | NMOS transistors connected in series to GROUND, located at the bottom to avoid short circuits in the CMOS connection. |
| _MOSFETs_ | Metal-Oxide-Semiconductor Field-Effect Transistor | Transistor used for switching and amplification in integrated circuits. |
| _CMOS_ | Complementary Metal-Oxide-Semiconductor | Technology that uses NMOS and PMOS for low power consumption. |
| _PMOS_ | P-channel Metal-Oxide-Semiconductor | Transistor that conducts when the gate voltage is low. |
| _NMOS_ | N-channel Metal-Oxide-Semiconductor | Transistor that conducts when the gate voltage is high. |
|  | SPICE MODEL | Mathematical representation of a device's electrical behavior. |
| _FinFET_ | Fin Field-Effect Transistor | 3D transistor with a fin-shaped channel, offering better electrostatic control and lower leakage. |
| _FDSOI_ | Fully Depleted Silicon-On-Insulator | Transistor technology with a fully depleted channel over an insulator, reducing leakage and improving electrostatic control. |
| _VDD_ | Voltage Drain Drain | "High-voltage" signal, connected to the power source. |
| _VSS_ | Voltage Source Source | "Low-voltage" signal, connected to ground. |
| _VTC_ | Voltage Transfer Characteristics | Curve showing the relationship between input and output voltage of a circuit (e.g., CMOS inverter). |
| _Tphl_ | Propagation Delay Time High-to-Low | Time for the output to fall 1→0 after an input change. |
| _Tplh_ | Propagation Delay Time Low-to-High | Time for the output to rise 0→1 after an input change. |
| _TG_ | Transmission Gate | Bidirectional switch formed by NMOS and PMOS in parallel, used to pass signals without degradation. |
|  | Fan-in | Number of inputs to a gate, affects resistance. Lower fan-in, lower delay. |
|  | Fan-out | Number of outputs from a gate, affects capacitance. Higher fan-out, higher load and delay. |
|  | Metastable | Data subject to metastability, may have an uncertain value, could be previous or current data. |
| _NORA_ | NO-RAce Logic | Dynamic logic technique that avoids race conditions between stages. |
| _OTP_ | One-time programmable | Memory programmable only once, used for permanent configuration. |
| _SRAM_ | Static Random Access Memory | Fast memory based on flip-flops, no refresh needed. |
| _DRAM_ | Dynamic Random Access Memory | Dense memory that stores data in capacitors and needs refresh. |
| _RAM_ | Random Access Memory | Volatile, fast-access memory for reading and writing. |
| _ROM_ | Read-Only Memory | Non-volatile memory used to store fixed data. |
| _PROM_ | Programmable read-only memory | Type of ROM that can be programmed once by the user. |
| _DFM_ | Design for Manufacturability | Rules and guidelines to be followed during the manufacturing stage. |
| _CAD_ | Computer-Aided Design | Software for designing, drawing, and verifying systems for integrated circuit (IC) design. |
| _PDK_ | Process Design Kit | Technology provided by the foundry consisting of a set of files characterized by it. |
***

</details>

<a name="idVLSI"></a>

<details markdown="1">

<summary><b>VLSI</b></summary>

| Acronym | Full Name | Description |
| --- | --- | --- |
| _VLSI_ | Very Large-Scale Integration | The entire sequence of steps to transform an RTL description into fabrication. |
| _EDA_ | Electronic Design Automation | The set of tools/software used throughout the IC development flow. |
| _GTECH_ | Generic Technology | Standard library of generic EDA cells used in the intermediate synthesis stage. |
| _NLDM_ | Non-Linear Delay Model | Older model (less accurate), non-linear model. |
| _CCS_ | Composite Current Source | More accurate model than NLDM. |
| _NLPM_ | Natural language programming linter | Library containing power modeling data. |
| _STA_ | Static Timing Analysis | Technique to verify digital circuit timing (passed or not?), fast and exhaustive. |
| _DTA_ | Dynamic Timing Analysis | Technique to analyze circuit timing using test vectors, specific tests, slower. |
| _HDL_ | Hardware Description Language | Programming language paradigm for describing digital circuit behavior and hardware structures. |
| _LVF_ | Liberty Variation Format | Extension of the Liberty format that models statistical variations (process, voltage, temperature) for more precise timing analysis. |
| _TLF_ | Timing Library Format | File describing timing characteristics of standard cells. |
| _LEF_ | Library Exchange Format | Describes simplified cell geometry for use in place & route. |
| _DSCL_ | Digital Standard Cell Library | Set of digital standard cells (with logic, layout, and timing). |
| _DEF_ | Design Exchange Format | Describes the physical implementation of the design (placement, routing, and connections). |
| _LIB_ | Liberty Timing File | File (.lib) describing timing, power, and logic function of standard cells. |
| _SDC_ | Synopsys Design Constraints | Standard file format, TCL-based developed by Synopsys, to define PPA constraints, used in the synthesis process. |
| _FRAM_ | "Frame" | Similar to LEF, also describes the physical format of cells. |
| _GDSII_ | Graphic Design System II | Standard file format used to represent physical layout (Current). |
| _GDSI_ | Graphic Design System I | Standard file format used to represent physical layout (Old/obsolete). |
| _OASIS_ | Open Artwork System Interchange Standard | Another format type (Open-source) to represent a physical design. |
| _ASCII_ | American Standard Code for Information Interchange | Standard for encoding characters as numeric values. |
| _SCL_ | Standard Cell | Characterized standard cells belonging to the PDK. |
|  | CELL | Any type of "component" or unit of an IC project, can be a mux, transistor, etc. |
|  | BUS | Physical connection medium between blocks, through which signals pass. It is governed by a protocol, the rules of that communication. |
| _PI/PO_ | Pins | Circuit connection points, either input or output. |
| _GRID_ | Grid | Reference mesh used in layout to align and position cells and interconnections. |
| _LVS_ | Layout Versus Schematic | Checks if the physical layout matches the schematic (connectivity and devices). |
| _ESD_ | Electrostatic Discharge | Static electricity discharge (like when you get a shock touching something), which can damage the chip and pins. |
| _UPF_ | Unified Power Format | A format/standard to describe how power can be organized within an IC. |
| _TCL_ | Tool Command Language | Scripting language used to automate and control EDA tools. |
|  | CORE | The heart of the IC, or rather, the brain. Provides the basic functionality of an integrated circuit. |
| _HBM_ | Human Body Model | A simulation using the human model when there is an electrical discharge into the circuit. Can be used on other occasions. |
| _RTL_ | Register Transfer Level | An abstraction level for representing digital designs using HDL in the Design stage. |
|  | SKEW | The data transition speed, the difference between the time the signal leaves and arrives. |
| _DUTY CYCLE_ | Duty Cycle | Ratio between the high-level time and the total period of a periodic signal (usually in %). Input parameter for timing analysis and clock design. |
| _CTS_ | Clock Tree Synthesis | Physical flow stage that creates and optimizes the clock signal distribution network on the chip. |
| _PPA_ | Power, Performance, and Area | The main metrics we define for an IC project, based on the project specification. |
| _IPs_ | Intellectual Property | Circuit blocks designed, verified, and reusable in projects, where a company owns their design. |
|  | Floorplan | Involves routing vias to be used for power supply to standard cells. Locations, shapes, sizes of chip modules are determined, and chip area, delays, and wire congestion are estimated, thus providing the basis for the layout. |
|  | Placement | Deals with the process of allocating Standard Cells in the proposed design. |
|  | Site | A site is the basic positioning unit (grid) where standard cells can be placed in the layout. |
| _FPGA_ | Field-Programmable Gate Array | Reconfigurable device composed of logic blocks and programmable interconnections. |
| _PLD_ | Programmable Logic Device | Category of programmable digital devices used to implement logic. |
| _MPGA_ | Mask Programmable Gate Array | Device programmed by mask during manufacturing, with interconnections defined at the foundry. |
| _CPLD_ | Complex Programmable Logic Device | PLD with multiple logic blocks and predictable interconnections, good for control. |
| _SPLD_ | Simple Programmable Logic Device | Simple PLD with few resources, used for basic logic. |
|  | Budget | A project constraint, where we define our development path, whether timing, power, or area. |
***

</details>

<a name="idVDSM"></a>

<details markdown="1">

<summary><b>VDSM</b></summary>

| Acronym | Full Name | Description |
| --- | --- | --- |
| _VDSM_ | Very deep submicron | A VLSI category for technologies below 0.25µm. |
| _SoCs_ | System-on-Chip | Chip that integrates several components/cores/blocks into a single integrated circuit. |
| _Hard Block_ | Hard Block | Physical block already ready inside the chip, optimized for high performance and lower energy consumption. |
| _Soft Block_ | Soft Block | Block described in code (HDL), which can be configured and adapted according to the project. |
| _TDD_ | Time Driven Design | Time-oriented design methodology, ensures the design and timing meet requirements. Used in ASICs. |
| _BBD_ | Block based Design | Block-oriented design methodology. You can design blocks in isolation, aiding clock closure. Used in complex ASICs and IPs. |
| _PBD_ | Platform based Design | Platform-oriented design methodology. A higher abstraction level, widely used in SoCs and Plug. |
| _DVT_ | Design Validation Test | Project validation stage to verify if the circuit works correctly before manufacturing or final delivery. |
| _DSM_ | Deep submicron | Refers to manufacturing technologies with dimensions well below 1 micrometer. |
| _tp_ | Timing Path | A point-to-point path. |
|  | Clock group | Group of different paths of/for clock signals. |
|  | Slack | Difference between required time and arrival time (negative = violation). |
|  | Net timing arcs | The real path delay, the sum of net and cell delays. |
|  | Net delay | Total time required to charge or discharge all parasitic data of the net. |
|  | Cell Delay | The delay for data to pass from cell input to output. |
|  | Transparent latch | Memory circuit that lets the signal pass directly while the clock is active. |
| _FF_ | flip-flop | Sequential circuit triggered by the clock edge that stores 1 bit of information, the smallest unit forming memory. |
|  | Pulse width | Pulse width, time the data remains active and inactive. |
| _tsu_ | Setup time | Time interval before the clock edge during which data must remain stable to avoid metastability. |
| _thd_ | Hold time | Time interval after the clock edge during which data must remain stable to avoid metastability. |
|  | Signal slew | Time required for a transition to occur. |
|  | Pulse Width | Time between the active and inactive state of the clock. |
|  | Clock latency | Difference between skew and slew. |
| _HVT_ | High Threshold Voltage | Transistors with high threshold voltage, consume less energy but are slower. Located in Standard Cells. |
| _RVT_ | Regular Threshold Voltage | Transistors with standard threshold voltage, balance performance and energy consumption. Located in Standard Cells. |
|  | Clock slew | The time difference in clock arrival at different parts of a digital circuit. |
|  | Clock jitter | Variation of skew over time. It varies the Skew. |
|  | Recovery time | Minimum time the reset must be deactivated before the clock edge (Asynchronous). |
|  | Removal time | Minimum time the asynchronous signal, usually reset, must remain active after the clock edge. |
|  | Data path | The data path from the input port to FF, memory, latch, gate... |
|  | Clock path | The path from the clock/memory pin to the sequential clock pin/memory/cell. |
|  | Clock gating path | Clock input port -> Clock gating cell. |
|  | Asynchronous path | Project input port to sequential cell set/reset. |
|  | Critical path | The slowest path of the circuit, used to determine the maximum circuit frequency. |
|  | False path | Existing but non-functional path. |
|  | Single cycle path | Circuit path that takes less than one cycle. |
|  | Multi Cycle path | Project timing path where the signal can take more than one cycle to propagate. |
|  | Launch path | Clock path used at the start point of a register-to-register path. |
|  | Capture path | Clock path used at the end point of a register-to-register path. |
|  | Shortest path | The path with the smallest delay, the best case. |
|  | Capacitive Crosstalk | Interference between two nearby signals, caused by parasitic capacitance between traces/wires in the circuit. |
|  | Resistive Parasitics | Parasitic resistance related to power supply distribution. |
|  | IR Drop | Voltage drop caused by trace resistance when electric current passes through the chip's power supply. |
| _IR Noise_ | IR Noise | Undesired voltage variation or drop caused by the resistance of the chip's power supply network. |
| _I/O_ | Input/Output | Interface responsible for input and output of signals between the chip and the external environment. |
| _PDN_ | Power Distribution Network | Power distribution network responsible for delivering electrical supply to all parts of the chip. |
| _P&R_ | Place and Route | Physical design stage that positions cells on the chip and makes connections between them. |
| _DET_ | Double Edge Triggered | Technique where the flip-flop captures data on both clock edges (rising and falling). |
| _GAL_ | Globally Asynchronous Logic | Architecture where different blocks operate asynchronously with each other. |
| _By-Pass Capacitor_ | Bypass Capacitor | Capacitor used to filter noise and stabilize the circuit's electrical supply. |
| _CDC_ | Clock Domain Crossing | Transfer of a signal between different clock domains in the circuit. |
|  | Metastability | Signal instability in sequential circuits when data changes very close to the clock edge. |
| _PVT_ | Process Voltage Temperature | Represents physical and operational variations affecting integrated circuit behavior, characterized in the PDK. Process (Fast/Slow), Voltage (VDD High/VDD Low), Temperature (High, Slow). |
| _Corners_ | PVT Corners | Specific combinations of PVT (Process, Voltage, Temperature) used to analyze circuit behavior under extreme conditions (worst and best case). |
| _OCV_ | On-Chip Variation | Variation of electrical characteristics within the chip itself caused by process, voltage, and temperature. |
|  | Electromigration | Gradual displacement of metal atoms in a conductor due to high electron movement colliding with them, resulting in high current flow that can cause short or open circuits. |
| _MTTF_ | Mean time to failure | The average time to failure, an indication of IC lifespan. |
|  | Void | The electromigration effect reduces ion density at some interconnection points causing a void, leading to an open circuit. |
|  | Hillock | Protrusion: Widening of the metallic interconnection between metal layers resulting in a short circuit. |
| _NDR_ | Non-default rules | Proper sizing of nets with non-standard rules. |
| _Nets_ | Nets | Electrical connections that interconnect cells and components within the digital circuit. |
| _BJT_ | Bipolar Junction Transistor | Transistor that uses electrons and holes to amplify or switch electrical signals. |
| _PNPN_ | PNPN Junction | Four-layer semiconductor structure used in switching devices, such as thyristors. |
| _SOI_ | Silicon on Insulator | Manufacturing technology where the transistor is built over an insulating layer to reduce electrical losses. |
| _FEOL_ | Front-End of Line | Manufacturing stage where transistors and active devices are built on the wafer. |
| _BEOL_ | Back-End of Line | Manufacturing stage responsible for the metallic interconnections between chip devices. |
| _DIBL_ | Drain Induced Barrier Lowering | Effect in transistors where the drain voltage lowers the channel barrier, increasing leakage. |
| _GIBL_ | Gate Induced Barrier Lowering | Effect where the gate electric field lowers the transistor barrier, causing leakage current. |
|  | antenna effect | A manufacturing problem in integrated circuits where electrical charges accumulated during the process (plasma) build up on metallic interconnections and can damage the transistor gate oxide. |
| _CMP_ | Chemical mechanical planarization | Chemical-mechanical process that causes erosion/recess during manufacturing. |
| _QoR_ | Quality of Results | Metric used to evaluate project quality in performance, area, power, and timing. |
| _QoS_ | Quality of Silicon | Final quality of the manufactured chip considering performance, reliability, and consumption. |
| _Tie_ | Tie cell | Standard cells used for logic constants (1/VDD or 0/GND). |
| _TIEHI_ | Tie-high | Cells with fixed signal at 1/VDD. |
| _TIELO_ | Tie-low | Cells with fixed signal at 0/GND. |
***

</details>

<a name="idDD"></a>

<details markdown="1">

<summary><b>Digital Design Fundamentals</b></summary>

| Acronym | Name | Description |
| --- | --- | --- |
| _BCD_ | Binary-Coded Decimal | Decimal encoding into 4 binary bits. |
| _MSB_ | Most Significant Bit | Most significant bit, located furthest left. |
| _LSB_ | Least Significant Bit | Least significant bit, located furthest right. |
| _Little Endian_ | Little Endian | Format where the least significant byte is stored first in memory. Example: RISC-V. |
| _Big Endian_ | Big Endian | Format where the most significant byte is stored first in memory. Example: MIPS. |
| _Sign and Magnitude_ | Sign and Magnitude | Binary representation where one bit indicates the sign and the remaining bits represent the magnitude. |
| _One's Complement_ | One's Complement | Representation of negative numbers obtained by inverting all bits of the positive number. |
| _Two's Complement_ | Two's Complement | Most widely used binary representation for negative numbers, inverting bits and adding 1. |
| _Quantization_ | Quantization | Conversion of analog values into discrete digital levels. |
| _Encoding_ | Encoding | Process of assigning a digital word to each quantized value. |
| _FP_ | Floating Point | Numerical representation using sign, exponent, and mantissa to represent real numbers. |
| _IEEE 754_ | IEEE 754 | Most widely used standard for floating-point number representation in digital hardware. |
| _FP32_ | Single Precision | 32-bit format with 1 sign bit, 8 exponent bits, and 23 mantissa bits. |
| _FP64_ | Double Precision | 64-bit format with higher precision and numerical range. |
| _FP16_ | Half Precision | 16-bit format used to reduce area, memory, and consumption. |
| _BF16_ | bfloat16 | Reduced format widely used in AI, keeping large exponent and smaller mantissa. |
| _Gray_ | Gray Code | Binary encoding where only one bit changes between consecutive values. |
| _K-Map_ | Karnaugh map | Graphical method used to simplify Boolean expressions and logic circuits. |
| _SOM_ | Sum of Minterms | Canonical Boolean form where the function is represented by the sum of minterms. |
| _POM_ | Product of Maxterms | Canonical Boolean form where the function is represented by the product of maxterms. |
| _mi_ | Minterm | Product that includes all input variables. |
| _Mi_ | Maxterm | Sum of all input variables. |
| _SOP_ | Sum of Products | A function written as an OR of several ANDs. |
| _POS_ | Product of Sums | A function written as an AND of several ORs. |
| _Cut Vertex_ | Articulation Point | Vertex whose removal increases the number of connected components of the graph. |
| _Cut Edge_ | Bridge Edge | Edge whose removal disconnects parts of the graph. |
| _BDD_ | Binary Decision Diagram | Graphical structure used to represent and manipulate Boolean functions. |
| _OBDD_ | Ordered Binary Decision Diagram | BDD where variables follow a fixed order on all paths. |
| _DAG_ | Directed Acyclic Graph | Directed graph without cycles used to represent dependencies and logical decisions. |
| _ROBDD_ | Reduced Ordered Binary Decision Diagram | OBDD optimized by removing redundant nodes and equivalent subtrees. |
| _Quine-McCluskey Approach_ | Quine-McCluskey Method | Tabular method used to simplify Boolean expressions. |
| _LE_ | Logical Effort | Method used to estimate delay and optimize speed in logic gates. |
| _Block Diagram_ | Block Diagram | Graphical representation of a system using functional blocks and their connections. |
| _Bit_ | Binary Digit | Smallest unit of digital information, can be 0 or 1. |
| _Byte_ | Byte | Set of 8 bits used to represent digital data and characters. |
| _X'_ | Don't Care | Condition where the logic value can be 0 or 1 without affecting circuit operation. |
| _Hi-Z_ | High Impedance | State where the circuit output is electrically disconnected from the line. |
| _State_ | State | Set of information stored at a given instant that defines the future behavior of the system. |
| _Stage_ | Stage | Step or processing level within a digital circuit or pipeline. |
| _Storage_ | Storage | Capacity or mechanism used to store digital data and information. |
| _Sequential Logic Circuits_ | Sequential Logic Circuits | Logic circuits whose output depends on current inputs and the previous state. |
| _Combinational Logic Circuits_ | Combinational Logic Circuits | Logic circuits whose output depends only on current inputs. |
|  | edge | The edge, the signal transition period (transient). |
|  | edge triggered | Sensitive to the edge. |
| _FSM_ | Finite State Machine | Sequential logic model based on states and transitions. |
| _Mealy Model_ | Mealy Machine | State machine where the output depends on the current state and inputs. |
| _Moore Model_ | Moore Machine | State machine where the output depends only on the current state. |
| _CU_ | Control Unit | Unit responsible for controlling and coordinating digital system operations. |
| _PU_ | Processing Unit | Unit responsible for processing and executing data operations. |
|  | Clock gating | Technique used in digital circuits to save power by turning off the clock signal to parts of the circuit. |
| _ICG_ | Integrated Clock Gating | A standard cell used in microelectronics to implement clock gating safely and without glitches. |
| _Minimum Clock_ | Minimum Clock Period | Smallest clock period allowed for the circuit to operate correctly without timing violations. |
| _Maximum Clock_ | Maximum Clock Frequency | Highest clock frequency supported by the circuit without timing errors. |
| _tpcq_ | Propagation delay (clock to Q) | Time after the clock edge during which the FF output is guaranteed stable. |
| _ta_ | Aperture time | Time around the clock edge during which data must remain stable. Tsetup + Thold. |
| _tccq_ | Contamination Delay | Time after the clock edge during which the FF output may be unstable. |
| _Path Delay_ | Path Delay | Total time taken by a signal to travel through a circuit path. |
***

</details>

<a name="idASIC"></a>

<details markdown="1">

<summary><b>ASIC Designs</b></summary>

| Acronym | Name | Description |
| --- | --- | --- |
| _ASIC_ | Application-Specific Integrated Circuit | IC designed for a specific purpose. |
| _Package_ | IC Package | Physical chip encapsulation responsible for protecting the die and connecting the circuit to the external environment. |
|  | Pads | Chip edges used to connect input/output signals, VDD/GND, communications, etc. |
|  | Netlist | The product of the transformation performed by an EDA tool from an RTL, using project constraints and the provided technology (GTECH/PDK). |
|  | Gate level | Digital representation level where the circuit is described using logic gates and their connections. |
| _VHSIC_ | Very High-Speed Integrated Circuit | Integrated circuit developed to operate at high speed. |
| _VHDL_ | VHSIC Hardware Description Language | Hardware description language used to model and design digital circuits. |
|  | ports | The interface of a module. |
|  | architecture | What the programmer sees, i.e., what the processor does. ISA, registers, data types... |
| _ISA_ | Instruction Set Architecture | Set of instructions implemented by a computer architecture. |
|  | microarchitecture | How the architecture is implemented, i.e., how the processor does it. Pipeline, ALU, Control unit... |
| _DUT_ | Device Under Test | Circuit or system being tested and verified during simulation or validation. |
| _Stimulus_ | Stimulus | Set of signals or inputs applied to the circuit during testing and simulation. |
| _Assertions_ | Assertions | Checks used to ensure the circuit obeys expected conditions and behaviors during simulation. |
| _Semaphore_ | Semaphore | Synchronization mechanism used to control access to shared resources between processes. |
| _Mailbox_ | Mailbox | Structure used for message exchange between processes, functioning as a FIFO queue. |
|  | Event | An event is a zero-time action. That is, an instantaneous change occurring at a specific point. |
|  | Constraints | Specifications defined by the project budget, may include timing, power, etc. |
| _TBs_ | Testbenchs (wrappers) | Verification environment that encapsulates the design to apply tests, stimuli, and validate circuit functionality. |
| _DUV_ | Device Under Verification | Circuit or system being verified during the functional validation process. |
| _CBS_ | Cycle-Based Simulators | Simulators that execute the circuit cycle by cycle, focusing on performance for large designs. |
| _EBS_ | Event-Based Simulators | Simulators that process signal changes and events over time in the circuit. |
| _DSP_ | Digital Signal Processing | Digital signal processing used to manipulate audio, video, and digital data. |
| _OVI_ | Open Verilog International | Organization responsible for the initial standardization of the Verilog language. |
| _TVM_ | Test Vector Memory | Memory that stores test vectors, used alongside ATPG and BIST. |
| _ICE_ | In-Circuit Emulator | A device that can emulate the system processor. Can execute code from memory or custom code. Generally integrated into the core. |
| _LRM_ | Language Reference Manual | Official document defining rules, syntax, and behavior of a hardware language. |
| _PLI_ | Programming Language Interface | Interface that allows integrating external programming languages with Verilog simulators. |
| _VCD_ | Value Change Dump | File used to store signal changes during digital simulation. |
| _ABV_ | Assertion-Based Verification | Verification method that uses assertions to validate behaviors and rules of the digital design. |
| _FIFO_ | First In First Out | Data structure where the first element to enter is the first to exit. |
| _OVL_ | Open Verification Library | Library of reusable assertions used for digital design verification. |
| _VCs_ | Virtual Cores | Reusable IP blocks used in verification and integration of ASIC/SoC projects. |
| _BFM_ | Bus Functional Model | Model used in verification to simulate the functional behavior of interfaces and buses. |
| _GUI_ | Graphical User Interface | Graphical interface that allows visual interaction with software and digital systems. |
| _DVE_ | Discovery Visualization Environment | Synopsys tool used for debugging and analyzing RTL simulations. |
| _SDF_ | Standard Delay Format | Output data structure containing the actual circuit delay. |
| _PDEF_ | Physical Definition File | Input/output file containing physical project information, such as dimensions, pins, and chip placement. |
| _TLU_ | Table Lookup Plus File | Files used in physical analysis to model resistance and capacitance of chip interconnections. |
| _DFT_ | Design for Test | Scan test is a design for testability technique, where scan FFs are inserted during synthesis to optimize synthesis, timing, and physically check the project. |
| _PI_ | Primary Input | Primary signal input to a digital circuit. |
| _PO_ | Primary Output | Primary signal output of a digital circuit. |
| _IDD Test_ | IDD Test | Test that measures the electric current consumed by the circuit to detect manufacturing faults or defects. |
|  | Scan Chain | Basically the insertion of a FF + MUX in the DFT process. |
| _LSSD_ | Level-Sensitive Scan Design | DFT technique based on level-sensitive latches to improve circuit testability. |
| _BIST_ | Built-In Self-Test | Technique where the circuit itself performs internal tests automatically. |
| _LFSR_ | Linear Feedback Shift Register | Shift register with feedback used to generate pseudo-random patterns. |
| _BILBO_ | Built-In Logic Block Observer | Test structure used for pattern generation and response analysis in BIST. |
| _JTAG_ | Joint Test Action Group | Boundary scan standard used for testing and debugging chips and boards. |
| _TAP_ | Test Access Port | Interface used by JTAG to access circuit test functions. |
| _ATPG_ | Automatic Test Pattern Generation | Automatic process of generating test vectors to detect faults in the circuit. |
| _ERC_ | Electrical Rule Check | Electrical verification performed during the physical verification stage to detect electrical violations in the layout. |
| _Signoff_ | Signoff | Final verification and approval stage of the project before chip manufacturing. |
| _LPE_ | Layout Parasitic Extraction | Stage of extracting electrical parasites from the layout after chip physical routing. |
| _GDSOUT_ | GDSII Output | Final physical layout file format sent for manufacturing. |
| _PDV_ | Physical Design Verification | Physical layout verification stage to validate rules, connectivity, and chip integrity before signoff. |
| _DDC_ | Design Compiler Database | Physical Design input file generated during logic synthesis by the Design Compiler. |
| _DB_ | Database Library | Input file containing standard cell libraries used during synthesis and physical implementation. |
| _.map_ | TLU+ Mapping File | Input file used in the physical stage to map technology layers to TLU+ parasitic models. |
| _TF_ | Technology File | Physical Design stage input file containing manufacturing technology rules and information. |
| _SPEF_ | Standard Parasitic Exchange Format | Physical Design output file containing extracted resistance and capacitance parasites. |
| _NDM_ | New Data Model | Physical database input used by IC Compiler II during Place & Route. |
***

</details>
