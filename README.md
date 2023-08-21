# Exchange-Notebooks
Jupyter Notebooks with example usage of GEMS Exchange APIs

## Setup
### Create Python3 Environment
1. Create a virtual environment in the notebooks folder.

   ```foo@bar:~/Exchange-Notebooks$ python3 -m venv exchange-nbs```
2. Activate the environment.

   ```foo@bar:~/Exchange-Notebooks$ source exchange-nbs/bin/activate```
3. Install requirements with pip.
   ```foo@bar:~/Exchange-Notebooks$ pip install -r requirements.txt```
### Configure API Key
The notebooks load your API key from the `api_key.py` file. You can obtain your API key from the [API Documentation](https://exchange-1.gems.msi.umn.edu/portal/home). You can create the `api_key.py` file like this, replace [REPLACE ME] with your key:

```foo@bar:~/Exchange-Notebooks$ echo "key = '[REPLACE ME]'" > api_key.py```
## To run
1. Run jupyter lab
   
   ```foo@bar:~/Exchange-Notebooks$ jupyter lab```
2. Go to http://localhost:8888/lab in your browser.
### Links
[API Documentation](https://exchange-1.gems.msi.umn.edu/portal/home)
### Contacts
gemssupport@umn.edu