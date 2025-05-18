# Use of RAG techniques for Q&A on the Long AtR Guide

## Overview

This mini-project's aim is to combine the power of LLMs in conjunction with powerful RAG techniques, to create a system that is able to answer questions on the Long AtR Guide. More specifically, in this project the [***LightRAG***](https://github.com/HKUDS/LightRAG) library is used in order to try to get the outmost from this long document. LightRAG is currently one of the top RAG tools both in terms of efficiency and computational cost, since it manages to achieve very good performance with minimal computational costs.

## Local Setup

In order to run this notebook locally, just follow the steps below:

1. Clone the repository using the following command:
```bash
git clone https://github.com/JohnTanAI/Long-AtR-Guide.git
```

and then navigate to the cloned repository directory.

2. (Recommended) Install the **uv** python project and package manager following the instructions [here](https://docs.astral.sh/uv/getting-started/installation/)

3. Create a virtual environment and activate it:
```bash
uv venv .venv && source .venv/bin/activate
```

4. Install the required packages using the following command:
```bash
uv sync
```

5. Create your [Groq](https://groq.com/groqcloud/) and/or [OpenAI](https://platform.openai.com) API keys and store them in the `.env` file in the root directory of the repository.

6. Since this is a Python Notebook (and not a Python script), you will need to have installed something like the following:

   *  [Jupyter](https://jupyter.org/)

   *  [Marimo](https://marimo.io/)

   *  or if using the VS Code IDE, the [Jupyter Extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

7. Run the **rag.ipynb** file based on the comments in the notebook.