# Python-Package-Tutorial-and-Guidebooks

This package containes starter guides to various cruitial python packages used in the 2026 IIntruction to Artifical Intelligence Course

## Requirements

### Colab

All major requrements are hhandles by both the Google Colab Platform and the install pacakagesin each notebook

### Vscode Extensions

- Jupyter
- Colab
- Python
- ipykernel

## Vscode or Pycharm or Local setup

For a smooth experience I woluld advice setting up virtal environnment that would be used as the kernel for your notebooks. You can do that directly in vscode or using the terminal

### Vscode

- In Vscode you can use `Ctrl+Shif+P` and select Python: Create Environment
- Select the venv tool you pefer be it `venv` or `conda`
- then select the python version you want to use preferable a version above Python 3.12
- Once selected check the `requirements.txt` and click OK

### Terminal

- In the terminal , make sure you re at the package location
- Run the following command to create a virtual environment

```bash
            python -m venv your-environment-name
```

- Activate the virtual environment

  ```bash
            source your-environment-name/bin/activate  # On Unix or MacOS
            your-environment-name\Scripts\activate     # On Windows
  ```

- Install the packages in the requirement file using the command

```bash
            pip install -r requirements.txt
```

### Using the virtual environment

- In vscode, open the command palette `Ctrl+Shift+P` and select Python: Select Interpreter
- Choose the virtual environment you just created as the interpreter for your notebooks
- Alternatively at the top-right corner of your notebook you can click on `select kernel` and select the virtual environment you created

## Packages

- Numpy
- MatPlotLib
- Pandas
- Scikit-Learn `Being worked on`
- Seaborn
- Torch `being worked on`
