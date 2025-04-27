# algokit-python-workshop

This project has been generated using AlgoKit. See below for default getting started instructions.

# Setup

### Pre-requisites

- [Python 3.12](https://www.python.org/downloads/) or later

### Initial Setup

#### 1. Clone the Repository

Start by cloning this repository to your local machine.

#### 3. Bootstrap Your Local Environment

Run the following commands within the project folder:

- **Setup Project**: Execute `algokit project bootstrap all` to install dependencies and setup a Python virtual environment in `.venv`.

### Development Workflow

#### Terminal

Directly manage and interact with your project using AlgoKit commands:

1. **Build Contracts**: `algokit project run build` compiles all smart contracts. You can also specify a specific contract by passing the name of the contract folder as an extra argument.
   For example: `algokit project run build -- hello_world` will only build the `hello_world` contract.
