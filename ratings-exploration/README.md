# Ratings Exploration

This project contains the code that is described within the blog post []. 

To follow along with the blog post please follow the steps below to install the required dependencies.

### Create a Virtual Environment

It's a good practice to work within a virtual environment to avoid conflicts between dependencies. Here's how you can create and activate a virtual environment using `venv` (built-in to Python 3):

1. Clone this repository and navigate into it:
   
   ```bash
   git clone git@github.com:statistico/statistico-experiments.git
   cd my_project && cd ratings-exploration
   ```

2. Create a virtual environment (replace `env_name` with your preferred name for the environment):

   ```bash
   python3 -m venv env_name
   ```

3. Activate the virtual environment:

   On macOS and Linux:
   ```bash
   source env_name/bin/activate
   ```

   On Windows:
   ```bash
   .\env_name\Scripts\activate
   ```

   Your command prompt should now show the active environment name at the beginning of the prompt.

## Install Required Libraries

Inside your activated virtual environment, install the necessary libraries using pip:

```bash
pip install pandas tabulate matplotlib
```

- `pandas`: A powerful data analysis and manipulation library.
- `tabulate`: Helps in formatting tabular data.
- `matplotlib`: A plotting library for creating visualizations in Python.

These libraries are now installed and ready to be used within your Jupyter Notebook environment.

## Launch Jupyter Notebook

Now that everything is set up, launch Jupyter Notebook to start working:

```bash
jupyter notebook
```

This will open Jupyter in your default web browser. You can create new notebooks or open existing ones to start analyzing data with pandas, visualizing data with matplotlib, and formatting outputs with tabulate.

## Deactivate Virtual Environment

When you're done working in your project, you can deactivate the virtual environment:

```bash
deactivate
```

This will return you to your system's default Python environment.

## Additional Notes

- Make sure to activate your virtual environment (`source env_name/bin/activate`) every time you start working on your project.
- Install additional libraries as needed using `pip install`.
