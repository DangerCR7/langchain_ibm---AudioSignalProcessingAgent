# Audio Signal Processing Agent – LangChain IBM

![IBM WatsonX](https://raw.githubusercontent.com/IBM/watson-machine-learning-samples/master/cloud/notebooks/headers/watsonx-Prompt_Lab-Notebook.png)

## Overview

**AudioSignalProcessingAgent** is an agent-based Python project that demonstrates how to leverage IBM's watsonx.ai Agent Lab with LangChain and LangGraph to build and interact with audio signal processing agents. The repository includes a Jupyter notebook designed to guide users through authentication, agent setup, and invoking language-based models for audio processing tasks.

## Features

- **IBM watsonx.ai Integration:** Connects to IBM watsonx.ai Agent Lab for agent orchestration.
- **LangChain & LangGraph:** Uses LangChain for language model interaction and LangGraph for agent workflow.
- **Python API Examples:** Step-by-step guides and code for authentication, agent invocation, and response handling.
- **Audio Signal Processing:** Designed as a template for processing and analyzing audio signals using AI agents.
- **Jupyter Notebook:** Interactive notebook (`audioAgent_NB.ipynb`) with explanations and runnable code cells.
- **Educational Focus:** Suitable for learners and developers exploring agent-based AI workflows in Python.

## Notebook Goals

- Define Python functions for audio signal processing tasks.
- Authenticate and interact with IBM watsonx.ai services.
- Build and invoke LangGraph agents with chat models.
- Run and understand the results of agent processing workflows.
- Learn best practices for saving and modifying agent workflows as notebooks.

## Getting Started

### Prerequisites

- Python 3.11+
- IBM watsonx.ai account (API key required)
- Jupyter Notebook

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DangerCR7/langchain_ibm---AudioSignalProcessingAgent.git
   cd langchain_ibm---AudioSignalProcessingAgent
   ```

2. **Install dependencies** (use your preferred dependency manager):
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook audioAgent_NB.ipynb
   ```

### Usage

- Open and follow the steps in `audioAgent_NB.ipynb`.
- Authenticate using your IBM watsonx.ai API key.
- Run cells sequentially to set up and invoke agents for audio signal processing.
- Modify functions and workflow as needed, but note that changes outside the recommended flow may affect reproducibility.

## License

This project is licensed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0). See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## Acknowledgements

- IBM watsonx.ai Agent Lab
- LangChain and LangGraph open-source projects

## Contact

For questions or support, open an issue in this repository.
