# Wallace Tree Multiplier

This repository contains the implementation of a Wallace Tree Multiplier, an efficient multiplier architecture used in digital circuits for fast binary multiplication. The Wallace Tree Multiplier reduces the number of partial products through a combination of carry-save addition and compression, leading to faster computation.

## Repository Structure

- `verilog/`: Contains the Verilog source code for the Wallace Tree Multiplier implementation.
- `presentation/`: PowerPoint presentation providing an overview of the Wallace Tree Multiplier and its implementation.
- `logisim/`: Logisim circuit file showcasing the Wallace Tree Multiplier in a digital circuit simulation.

## Usage

### 1. Clone the Repository
Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/your-username/wallace-tree-multiplier.git
```

### 2. Verilog Implementation

- Navigate to the `verilog/` directory and use a Verilog simulator (e.g., ModelSim, Vivado, or Icarus Verilog) or a synthesis tool to analyze and simulate the `wallace_tree_multiplier.v` file. This file contains the Verilog code for the Wallace Tree Multiplier.
  
```bash
cd verilog
```

- To run the simulation, follow the instructions of the simulator tool you are using.

### 3. Presentation

- To understand the architecture and working of the Wallace Tree Multiplier, open the `presentation/WallaceTreeMultiplier.pptx` file.
  
  You can view it using Microsoft PowerPoint or any compatible software.

- Feel free to modify the slides to tailor them to your needs.
  

### 4. Logisim Circuit Simulation

- The Wallace Tree Multiplier circuit can also be viewed and simulated in Logisim.

- Open the `logisim/WallaceTreeMultiplier.circ` file in Logisim, a digital logic simulator.

- You can explore the circuit, provide inputs, and observe the outputs to understand how the Wallace Tree Multiplier operates.
- 

## License

This project is open-source and available under the [MIT License](LICENSE).
