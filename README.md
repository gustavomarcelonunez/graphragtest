# GraphRAG - Digitization and Natural Language Querying (CLI Version)

This project uses **GraphRAG** to digitize and structure book information into a knowledge graph. It is a **Command-Line Interface (CLI) application**, meaning all operations are executed from the terminal in a Linux environment. It then allows natural language queries through the terminal in a Linux environment.

## Requirements

- **Operating System:** Ubuntu 22.04
- **Python:** 3.10+
- **GraphRAG:** [Official Documentation](https://microsoft.github.io/graphrag/)
  
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gustavomarcelonunez/oceangraphrag.git
   cd oceangraphrag
   ```

2. Create a virtual environment and install dependencies:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

## Usage

### 1. Book Digitization

This project contains digitized text. If you want to use your own text and generate the new knowledge graph, run:
```bash
graphrag index...
```

### 2. Natural Language Queries

Run:
```bash
graphrag query...
```

## Additional Documentation

For more information on GraphRAG and its commands, visit the [official page](https://microsoft.github.io/graphrag/).

