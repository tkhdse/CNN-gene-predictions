### Predicting Gene Mutations Using Convolutional Neural Networks for Neurodegenerative Diseases

Python, PyTorch, Node.js, React.js, Tailwind, Neo4J
Node.js version 8.11.0 and above

### About


### Setup
Set up ```.env``` file in the root directory with the following contents:
```
OMIM_API_key=
NEO4J_USERNAME=
NEO4J_PASSWORD=
NEO4J_URI=
```

### Install Python dependencies (from root directory):

Set up virtual environment:
```
cd src
```

For Mac
```
# make venv
python3 -m venv venv

# activate venv
source venv/bin/activate
```

For Windows
```
# make venv
python -m venv venv

# activate venv
.\venv\Scripts\activate
```


Install dependencies
```
pip3 install -r requirements.txt
```

SSL certificate: Install Certificates.command


To Run Python files
Make sure you are in the ```src``` directory, then you can run the files. 

### To run frontend (from root directory):
```
cd app
npm i
npm start
```

### Run backend:
```
cd src
// activate venv
python3 app.py
```
