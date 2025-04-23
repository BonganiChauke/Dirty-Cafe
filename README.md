# Jupyter Notebook Project in VS Code

This README provides instructions for setting up and running a Jupyter Notebook project in Visual Studio Code (VS Code).

---

## Prerequisites

1. **Visual Studio Code**
   - Download and install [VS Code](https://code.visualstudio.com/).

2. **Python**
   - Install Python (version 3.7 or later) from [python.org](https://www.python.org/).
   - Ensure Python is added to your system's PATH.

3. **Jupyter Notebook**
   - Install Jupyter Notebook using pip:
     ```bash
     pip install notebook
     ```

4. **VS Code Extensions**
   - Install the following extensions in VS Code:
     - **Python** (by Microsoft)
     - **Jupyter** (by Microsoft)

---

## Project Setup

1. **Clone the Repository**
   - If the project is stored in a Git repository, clone it to your local machine:
     ```bash
     git clone <repository_url>
     ```
   - Navigate to the project directory:
     ```bash
     cd <project_directory>
     ```

2. **Install Required Libraries**
   - Check if the project includes a `requirements.txt` file.
   - Install the required Python libraries:
     ```bash
     pip install -r requirements.txt
     ```

---

## Running the Project

1. **Open the Project in VS Code**
   - Launch VS Code and open the project folder.

2. **Select the Python Interpreter**
   - Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS) to open the Command Palette.
   - Type `Python: Select Interpreter` and select the Python environment where you installed the required libraries.

3. **Open a Jupyter Notebook**
   - Navigate to the `.ipynb` file in the Explorer.
   - Click on the file to open it in the Notebook Editor.

4. **Run the Notebook**
   - Click on the `Run All` button at the top or execute individual cells using the play button next to each cell.

---

## Troubleshooting

- **Missing Python Libraries**:
  If you encounter a `ModuleNotFoundError`, ensure that all required libraries are installed in the selected Python environment.

- **Jupyter Not Installed**:
  Ensure you have installed Jupyter by running:
  ```bash
  pip install notebook
