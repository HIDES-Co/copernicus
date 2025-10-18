# OpenEO Project

This project is a starting point for working with the openEO platform. It includes a basic Python script and a Jupyter notebook to get you started.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Python 3.12 or higher and `uv` installed on your system. You can install `uv` by following the official instructions: [https://github.com/astral-sh/uv](https://github.com/astral-sh/uv)

### Installation

1.  **Create a virtual environment:**
    ```bash
    uv venv
    ```
2.  **Activate the virtual environment:**
    ```bash
    source .venv/bin/activate
    ```
    For Windows, use:
    
    ```bash
    .venv\Scripts\activate
    ```
3.  **Install the dependencies:**
    ```bash
    uv pip install -e .[dev]
    ```
    This will install all the necessary packages for the project from `pyproject.toml`, including the development dependencies.

## Usage

To run the main script, execute the following command:

```bash
python main.py
```

## Development with VS Code and Jupyter Notebooks

This project is set up to work with Jupyter notebooks inside VS Code.

1.  **Open the project in VS Code.**
2.  **Install the recommended extensions.** VS Code will likely prompt you to install the Python and Jupyter extensions if you don't have them already.
3.  **Select the Python interpreter.** Open the command palette (`Ctrl+Shift+P` or `Cmd+Shift+P`) and type "Python: Select Interpreter". Choose the interpreter from your `.venv` directory.
4.  **Open the `prube.ipynb` file.** You can now run the cells in the notebook and interact with the openEO platform.
