# Hardware Papers
Collection of hardware papers I find interesting/important. Some software papers are included if they are relevant to hardware accelerators.

Organized by topic. Will reorganize as I go. 
    
---

## History and Scaling
- CPU DB [[link]](http://queue.acm.org/detail.cfm?id=2181798)
- Dark Silicon and the End of Multicore Scaling [[link]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.363.8520&rep=rep1&type=pdf)
- Computing's Energy Problem [[link]](http://ieeexplore.ieee.org/document/6757323/)
- Pursue robust indefinite scalability [[link]](http://static.usenix.org/events/hotos11/tech/final_files/Ackley.pdf)

## Architecture
- Architecture Support for Accelerator-Rich CMPs [[link]](http://cadlab.cs.ucla.edu/~cong/papers/saw2011.pdf)
- A Framework for Comparing Models of Computation [[link]](https://inst.eecs.berkeley.edu/~ee249/fa07/discussions/TSM.pdf)
- Compositional System-Level Design Exploration with Planning of High-Level Synthesis [[link]](https://pdfs.semanticscholar.org/5f48/8f513630be40bbd015fd6165cd04703db0fc.pdf)
- Design Perspectives on 22nm CMOS and Beyond [[link]](http://ieeexplore.ieee.org/document/5227192/)
- Discerning the Dominant Out-of-Order Performance Advantage: Is it Speculation or Dynamism [[link]](http://dl.acm.org/citation.cfm?id=2451143)
- Efficient Interaction between OS and Architecture in Heterogeneous Platforms [[link]](http://dl.acm.org/citation.cfm?id=1945032)
- The Discipline of Embedded Systems Design [[link]](http://www-verimag.imag.fr/~sifakis/Computer_ESdiscipline.pdf)
- IBM Power Edge of Network Processor: A Wire-Speed System on a Chip [[link]](http://dl.acm.org/citation.cfm?id=1978281)
- Integrated Anaylsis of Power and Performance for Pipelined Microprocessors [[link]](http://dl.acm.org/citation.cfm?id=2250077)
- The Optimum Pipeline Depth for a Microprocessor [[link]](http://researcher.watson.ibm.com/researcher/files/us-viji/optimum_pipeline.pdf)
- A Case for OS-Friendly Hardware Accelerators [[link]](http://hwacha.org/papers/osaccel-wivosca2013.pdf)
- Petri Nets: Properties, Analysis and Applications [[link]](https://inst.eecs.berkeley.edu/~ee249/fa07/discussions/PetriNets-Murata.pdf)
- The Scalable Commutativity Rule: Designing Scalable Software for Multicore Processors [[link]](http://people.csail.mit.edu/nickolai/papers/clements-sc.pdf)
- Short-Circuiting Memory Traffic in Handheld Platforms [[link]](http://www.cse.psu.edu/hpcl/docs/2014_MICRO_Praveen.pdf)
- Supervised Design Space Exploration of Compositional Approximation of Pareto Sets [[link]](http://www.iliasdiakonikolas.org/papers/dac-pareto.pdf)
- Topology-Based Performance Analysis and Optimization of Latency-Insensitive Systems [[link]](http://www.cs.columbia.edu/~luca/)
- Understanding Sources of Inefficiency in General-Purpose Chips [[link]](http://csl.stanford.edu/~christos/publications/2010.efficiency.isca.pdf)

#### Latency-Insensitive Design
- Coping With Latency in SOC Design [[link]](http://www.cs.columbia.edu/~luca/research/lidMicro02.pdf)
- A Methodology for Correct-by-Construction Latency Insensitive Design [[link]](http://www.cs.columbia.edu/~luca/research/lidICCAD99.pdf)
- Implementing Latency-Insensitive Dataflow Blocks [[link]](http://arcade.cs.columbia.edu/lid-memocode15.pdf)
- The Role of Back-Pressure in Implementing Latency-Insensitive Systems [[link]](http://www.cs.columbia.edu/~luca/research/rbilsENTCS06.pdf)

## Language, Simulation, and Synthesis
- Aladdin: A Pre-RTL, Power-Performance Accelerator Simulator Enabling Large Design Space Exploration of Customized Architectures
- Benchmarking Methodology for Embedded Scalable Platforms
- Darkroom: Compiling High-Level Image Processing Code into Hardware Pipelines
- Simulating DRAM controllers for future system architecture exploration
- FPGA Acceleration by Dynamically-Loaded Hardware Libraries
- Hardware Synthesis from a Recursive Functional Language
- MachSuite: Benchmarks for Accelerator Design and Customized Architectures
- Putting the LID on Haskell: From a Functional Language to Latency-Insensitive Hardware
- Quo Vadis, SLD? Reasoning About the Trends and Challenges of System Level Design
- Synthesis-friendly techniques for tightly-coupled integration of hardware accelerators into shared-memory multi-core clusters

## Accelerators
- A Defect-Tolerant Accelerator for Emerging High-Performance Applications
- Accelerator-Rich CMPs: From Concept to Real Hardware
- Algorithms for High-Throughput Disk-to-Disk Sorting
- Optimizing Parallel Bitonic Sort
- Conservation Cores: Reducing the Energy of Mature Computations
- Hardware Acceleration of Key-Value Stores
- Tagged Up/Down Sorter - A Hardware Priority Queue
- Meet the Walkers: Accelerating Index Traversals for In-Memory Databases
- N Queens on an FPGA: Mathematics, Programming, or Both?
- A Reconfigurable Fabric for Accelerating Large-Scale Datacenter Services 
- Sorting on Architecturally Diverse Computer Systems
- SQRL: Hardware Accelerator for Collecting Software Data Structures
- The Accelerator Store framework for high-performance, low-power accelerator-based systems
- Thin Servers with Smart Pipes: Designing SoC Accelerators for Memcached
- High Throughput and Large Capacity Pipelined Dynamic Search Tree on FPGA
- Q100: The Architecture and Design of a Database Processing Unit
- Navigating Big Data with High-Throughput, Energy-Efficient Data Partitioning
- CortexSuite: A Synthetic Brain Benchmark Suite
- DianNao: A Small-Footprint High-Throughput Accelerator for Ubiquitous Machine-Learning
- A Dynamically Configurable Coprocessor for Convolutional Neural Networks
- A Digital Neurosynaptic Core Using Embedded Crossbar Memory with 45pJ per Spike in 45nm
- Hardware spiking neurons design: analog or digital?
- Low-Power, High-Performance Analog Neural Branch Prediction
- NeuFlow: A Runtime Reconfigurable Dataflow Processor for Vision
- Neural Acceleration for General-Purpose Approximate Programs
- Neural Network Stream Processing Core (NnSP) for Embedded Systems
- Probabilistic synaptic weighting in a reconfigurable network of VLSI integrate-and-fire neurons
- A 201.4 GOPS 496 mW Real-Time Multi-Object Recognition Processor With Bio-Inspired Neural Perception Engine
- Recurrant Neural Networks Hardware Implementation on FPGA
- Silicon Neurons That Compute
- SNNAP: Approximate Computing on Programmable SoCs via Neural Acceleration

## Databases
- A Comprehensive Study of Main-Memory Partitioning and its Application to Large-Scale Comparison- and Radix-Sort
- High Throughput Heavy Hitter Aggregation for Modern SIMD Processors
- Ibex - An Intelligent Storage Enginer with Support for Advanced SQL Off-loading
- Massively Parallel Sort-Merge Joins in Main Memory Multi-Core Database Systems
- Rethinking SIMD Vectorization for In-Memory Databases
- Scalable Aggregation on Multicore Processors
- Vector Extensions for Decision Support DBMS Acceleration

## Memory
- Accelerator Memory Reuse in the Dark Silicon Era
- What Every Programmer Should Know About Memory
- Tardis: Time Traveling Coherence Algorithm for Distributed Shared Memory
- Why On-Chip Cache Coherence Is Here to Stay

## Security
- MAGIC: Malicious Aging in Circuits/Cores
- RSA Key Extraction via Low-Bandwith Acoustic Cryptanalysis
- Stealing Keys from PCs using a Radio: Cheap Electromagnetic Attacks on Windowed Exponentiation

## Other
- The Manchester Prototype Dataflow Computer

