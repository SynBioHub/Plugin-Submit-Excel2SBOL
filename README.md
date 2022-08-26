# Plugin-Submit-Test
A submit plugin based on the [Excel2SBOL python library](https://pypi.org/project/excel2sbol/)

# Install
## Docker
Run `docker run --publish 8098:5000 --detach --name submit-plug synbiohub/plugin-submit-excel2sbol:snapshot`
Check it is up using http://localhost:8098/status.

## Using Python
Clone the repository using `git clone https://github.com/SynBioHub/Plugin-Submit-Excel2SBOL.git` followed by `cd ./Plugin-Submit-Excel2SBOL`.
Then run `pip install -r requirements.txt` to install the requirements. Then run `FLASK_APP=app python -m flask run`. A flask module will run at http://localhost:5000/status.
