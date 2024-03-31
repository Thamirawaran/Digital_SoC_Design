**Theory Part**

**Routing and Design Rule Check:**
Routing involves the process of determining the physical paths for interconnecting various components in the chip layout.
Design rule check (DRC) ensures that the layout adheres to the manufacturing constraints and design rules specified by the fabrication process.

**Introduction to Maze Routing – Lee’s Algorithm:**
Maze routing, based on Lee's algorithm, is a method used to find optimal paths through a maze-like grid, often employed in automatic routing algorithms for VLSI designs.

**Lee’s Algorithm Conclusion:**
A summary of the advantages and limitations of Lee's algorithm in the context of VLSI routing.

**Design Rule Check(DRC):**
Ensuring that the layout conforms to various design rules specified by the fabrication process, such as minimum feature size, spacing, and overlap requirements.

**Power Distribution Network and Routing:**
The power distribution network (PDN) involves designing the network of power supply lines to ensure stable and uniform power distribution across the chip.
Routing involves determining the paths for power lines to connect power sources to the standard cells and other components.

**Lab Steps to Build Power Distribution Network:**
Step-by-step instructions for building the power distribution network in the chip layout, considering factors like power grid topology and voltage drop constraints.

**Lab Steps from Power Straps to Std Cell Power:**
Detailed instructions for routing power lines from the power straps (main power sources) to the standard cells in the chip layout.

**Basics of Global and Detail Routing and Configure TritonRoute:**
Global routing involves determining high-level interconnection paths, while detail routing involves refining these paths to meet timing, congestion, and other constraints.
TritonRoute is a routing tool used in VLSI design to perform both global and detail routing.

**TritonRoute Features:**
Overview of the features offered by TritonRoute, including its capabilities in handling routing challenges efficiently.

**TritonRoute Feature 1 – Honors Pre-Processed Route Guides:**
TritonRoute can utilize pre-processed route guides to guide the routing process and ensure adherence to design constraints.

**TritonRoute Feature 2 & 3 – Inter-Guide Connectivity and Intra-Layer Routing:**
TritonRoute supports inter-guide connectivity, allowing routes to cross guide boundaries, and intra-layer routing, optimizing routing within each routing layer.

**TritonRoute Method to Handle Connectivity:**
Description of TritonRoute's approach to handling connectivity challenges, ensuring robust and efficient routing solutions.

**Routing Topology Algorithm and Final Files List Post-Route:**
Explanation of the routing topology algorithm used by TritonRoute and the files generated after completing the routing process, such as the routed layout and routing reports.
