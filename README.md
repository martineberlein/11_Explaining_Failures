# 11th Lab Assignment: Explaining Failures

## Getting Started

We recommend using one *virtual environment* per lab assignment.
To follow our instructions, you need a `python3` executable in your `PATH`; we tested the setup with Python 3.10.

1. Create the virtual environment.
   In the `Lab_11` directory, type
   
   ```shell
   python3 -m venv venv
   ```
2. Source the virtual environment. Instead of `activate`, there are also specialized scripts for other shells (e.g., `activate.fish`).
   
   ```shell
   source venv/bin/activate
   ```
3. Install the requirements.
   
   ```shell
   pip install -r requirements.txt
   ```
4. Add the environment to Jupyter.

   ```shell
   python -m ipykernel install --user --name=SBTD_Lab_11
   ```
5. Start Jupyter Lab.

   ```shell
   jupyter lab .
   ```
   
   The above command should automatically open Jupyter Lab in your default browser.
   If this does not work, search the console output for any error messages or otherwise a URL (such as `http://localhost:8888?token=...`) that you can manually paste into a browser window.
6. Open "Lab_11.ipynb" in Jupyter Lab, and choose the kernel "SBTD_Lab_11" by selecting it in the `Kernel > Change Kernel...` dialog.

The installed "kernel spec" `SBTD_Lab_11` can be removed again from Jupyter by running `jupyter kernelspec uninstall SBTD_Lab_11` inside the virtual environment.

