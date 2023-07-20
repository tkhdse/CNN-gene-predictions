### Predicting Gene Mutations Using Convolutional Neural Networks for Neurodegenerative Diseases

Python, Tensorflow, Scikit-learn, Node.js, React.js, Tailwind, C++,
Node.js version 8.11.0 and above

### About


### Setup
Set up ```.env``` file in the root directory with the following contents:
```
API_USER=
API_PW=
API_key=
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

To Run Python files
Make sure you are in the ```src``` directory, then you can run the files. 


### Run C++:
```
mkdir build
cd build
cmake ..

make; ./bin/exec
```

### To run frontend (from root directory):
```
cd app
npm i
npm start
```
