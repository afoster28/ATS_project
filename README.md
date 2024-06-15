# ATS_project

Authors: Adam Foster, Maciek Staniszewski

Automatic Transaction Systems project on forecasting Johnson & Johnson equity price and implementing a long-short momentum strategy based on directional and magnitude signals.

### Running the Code

Please make sure you have all usual dependencies installed on your system. The most important ones include `python`, `pip` and `ipykernel`. If you're using _Visual Studio Code_ for development, you should be prompted to install them automatically. Next, follow this process:

1. Create the virtual environment: `python -m venv venv`
2. Enter `venv`: `source venv/bin/activate` on Linux or `venv\Scripts\activate.bat` on Windows
3. Upgrade your `pip`: `pip install --upgrade pip`
4. Install dependencies from the requirements file: `pip install -r requirements.txt`
5. Navigate to the Model directory and open the Jupyter Notebook IDE of your choice. Select the Python version from inside the `venv` you just created when prompted by `ipykernel` package. Suggested command: `python -m notebook`
