# Replication of Do They Discuss Design?
This study aims to replicate the findings in [1](#references).

## Environment Setup

### Requirements
1. Python 3.6.0
2. Virtual Environment

### Setup Virtual Environment 
To install the virtual environment run   
`$ python3 -m venv venv`  
To activate this virtual environment run  
`$ source venv/bin/activate`

### Install Requirements
The requirements are defined in requirements.txt with version. To 
install them run  
`$ pip install -r requirements.txt`

### Download `nltk stopwords corpus`
To download the `nltk stopwords corpus` run  
`nltk.download('stopwords')` in the `python interactive console`.

## About Code
The `main.py` contains all the code of this replication.


## About Paper
The paper can be found in this folder names as `paper.pdf`


## About Data
The data file can be found in this folder and named as 
`sentences-classified.csv`


## Run the Replication
To run the replication, simply run the main.py file by  
`$ python main.py`  
Please make sure to be in the directory of the `main.py` file.


## Results
The outputs will be generated in the results folder. Please refer to the
Readme file in the `results` folder for more insights on the results.


## References
1. J. a. Brunet, G. C. Murphy, R. Terra, J. Figueiredo, and D. Serey,
“Do developers discuss design?” in Proceedings of the 11th Working
Conference on Mining Software Repositories, ser. MSR 2014. New
York, NY, USA: ACM, 2014, pp. 340–343.
