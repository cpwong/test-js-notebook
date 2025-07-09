# How to run an Jupyter Notebook with Deno


## Install Deno
Make sure Deno is installed on your system. You can install it using a package manager or the official script:

```sh
curl -fsSL https://deno.land/x/install/install.sh | sh
```

Or, on macOS:

```sh
brew install deno
```
Install Jupyter Notebook or JupyterLab
Ensure you have Python 3.x and pip installed, then install Jupyter:

```sh
pip install jupyterlab notebook
```
Install the Deno Jupyter Kernel
Use the following command to install the Deno kernel:

```sh
deno jupyter --unstable --install
```
This will add the Deno kernel to your Jupyter environment. You should see a confirmation message indicating successful installation.

## Start Jupyter Notebook

Launch the Jupyter Notebook server:

```sh
jupyter notebook
```
or for JupyterLab:

```sh
jupyter lab
```

## Select the Deno Kernel in Your Notebook

Open or create a new notebook (.ipynb file).

In the notebook interface (e.g., JupyterLab, classic Notebook, or VS Code with the Jupyter extension), select the Deno kernel from the kernel selection menu.

You can now run JavaScript and TypeScript code interactively in your notebook cells.

## Enabling Deno Extension on VSCode

You might need to install the following extensions:

* Jupyter 
* Deno