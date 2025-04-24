# Dirty Cafe Jupyter Notebook Project in VS Code

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
   - Clone it to your local machine: using Git Bash if installed 
     ```bash
     git clone <https://github.com/BonganiChauke/Dirty-Cafe.git>
     ```
   - Navigate to the project directory:
     ```bash
     cd <Dirty-Cafe>
     ```

2. **Install Required Libraries**
   - Open cmd in your comptuer or in vs code open the terminal in vs code windows `Ctrl+Shift+'`  or mac `Ctrl+'`
   - Install the required Python libraries:
     ```bash
     pip install pandas
     pip install seaborn
     pip install stats
     ```
3. ** Download The project
   - Download the project from [GitHub]()
   - Click the `Code` button, then select `Download ZIP` to download the project as a ZIP file.
   - Extract the contents of the ZIP file to a directory of your choice you can use any extraction tool.
   - Download and install [WinRar](https://www.win-rar.com/predownload.html?&L=0) to extract the zip folder.

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
