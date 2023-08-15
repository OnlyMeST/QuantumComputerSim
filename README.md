# Quantum Computing Simulator

This is a simple Quantum Computing Simulator application built using the Python library Qiskit and the graphical user interface (GUI) library Tkinter. The simulator allows you to interactively create and visualize quantum circuits composed of various quantum gates. You can also visualize the state of the quantum system using Bloch sphere representation.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Supported Quantum Gates](#supported-quantum-gates)
- [Visualizing the Circuit](#visualizing-the-circuit)
- [Visualizing the State](#visualizing-the-state)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Quantum Computing Simulator is a Python application that provides a simple graphical interface for building and visualizing quantum circuits. It utilizes the Qiskit library for quantum computing and Tkinter for the GUI components.

## Prerequisites

Before using this simulator, ensure you have the following software installed:

- Python (3.6 or later)
- Qiskit library (`pip install qiskit`)
- Tkinter (usually included with Python)

## Installation

1. Clone or download this repository.
2. Navigate to the project directory using the terminal.
3. Run the simulator script using the command: `python quantum_simulator.py`

## Usage

1. Run the script using the provided installation instructions.
2. The simulator GUI window will open.
3. Select quantum gates from the toolbox to build your circuit.
4. Visualize the circuit or state as needed.
5. Experiment with different gate combinations and states.

## Supported Quantum Gates

The following quantum gates are supported in this simulator:

- X Gate
- Y Gate
- Z Gate
- Hadamard Gate
- CNOT Gate
- T Gate
- S Gate
- CX Gate

## Visualizing the Circuit

To visualize the constructed quantum circuit:

1. Click the "Visualize Circuit" button.
2. The circuit will be drawn using the `circuit_drawer` function from Qiskit.

## Visualizing the State

To visualize the quantum state using the Bloch sphere representation:

1. Click the "Visualize State" button.
2. The quantum state will be calculated and displayed using the Bloch sphere visualization.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, make improvements, and submit a pull request. We welcome any contributions that enhance the functionality or user experience of the Quantum Computing Simulator.

## License

This project is licensed under the [MIT License](LICENSE).
