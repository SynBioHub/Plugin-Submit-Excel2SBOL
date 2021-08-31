# Plugin-Submit-Test
A submit plugin based on the Excel2SBOL python library

# Install
## Docker
Run `docker run --publish 8098:5000 --detach --name submit-plug synbiohub/plugin-submit-excel2sbol:snapshot`
Check it is up using http://localhost:8098/status.

## Using Python
Run pip install -r requirements.txt to install the requirements. Then run `FLASK_APP=app python -m flask run`. A flask module will run at http://localhost:5000/.
