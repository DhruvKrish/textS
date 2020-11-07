# textS

A place to get the summary of a research paper.
Intend to use the text summarization domain of Natural Language Processing.

## Backend Cleaning Activities
1. extractArchive.py<br>
Extracts research papers from the arXiv dataset based on the cs.DC taxonomy 
(Distributed, Parallel, and Cluster Computing). 
2. convertPDF.py
Converts an input pdf to text and then converts the texts into sentences that 
our model requires.

## Backend: Dev Guide

1. We plan to use virtual environment to keep track of this project
```bash
$ pip3 install virtualenv
```

2. Create a virtual environment
```bash
$ virtualenv venv
```

3. To activate virtual environment
```bash
$ source venv/bin/activate
```

4. Install the below libraries
```bash
$ pip3 install pdfminer
```

5. To deactivate virtual enviroment
```bash
$ deactivate
```
### Frontend: Dev Guide

1. Install npm and then
```bash
$ npm run build
```

2. Change Dir to frontend
```bash
$ npm start
```