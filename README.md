# Human Rights First DocDB

Deployed App: [https://a.humanrightsfirstdocdb.dev](https://a.humanrightsfirstdocdb.dev)

Deployed DS API: [https://ds.humanrightsfirstdocdb.dev](https://ds.humanrightsfirstdocdb.dev)


## Contributors

### LABS FT 40
[Alex Lucchesi](https://github.com/lucchesia7) 

[Alyssa Murray](https://github.com/dagtag)  

[Ben Clowe](https://github.com/benclowe29)

[Greg Engelmann](https://github.com/engegreg) 

[Hunter Jordan](https://github.com/Hunter-Jordan)

[Peter Rockwood](https://github.com/prockwood)

[Joshua Aurajo](https://github.com/joshua-aurajo)

[Mark Porath](https://github.com/m-rath)

[Youssef Al-Yakoob](https://github.com/yalyakoob)

[Guy Altman](https://github.com/galtman5)

[Jake Harris](https://github.com/theawesomejaik)

[Jeremy Hebert](https://github.com/jhebert1994)

[Daniel Ferber](https://github.com/Daos21912)

[Jackson Reber](https://github.com/JacksonReber)

[Madina Izimbetova](https://github.com/madina-iz)

[Amadou N'Gom](https://github.com/Amadou23)

[Jacob Smith](https://github.com/fleekz)

[Samuel Egbert](https://github.com/Samuel-Egbert31415)


<br>
<br>

![MIT](https://img.shields.io/packagist/l/doctrine/orm.svg)  

![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square) 

![Python](https://img.shields.io/pypi/pyversions/VS)


### Getting Started
- Clone the repo to install it as your own remote.
  - **note** please [be sure to set your remote](https://help.github.jp/enterprise/2.11/user/articles/changing-a-remote-s-url/) for this repo to point to your Labs Team Repository.
- run: `pip install -r requirements.txt` to download all dependencies.


### Key Features

- computer vision based document searching  
- fast and reliable storage for crucial documents 
- accurate and reliable artifact removal
- built in search algorithms for pulling in necessary information


## Research
Our research into this project stretches far and wide, covering a multitude of libraries. To better consolidate space, you can find our research [here](./assets/research.md)


# Tech Stack

- Logic: Python
- API Framework: FastAPI
- Database: MongoDB
- ML Model: Tesseract
- Visualizations: Plotly

## Architecture

![image info](./assets/DS_structural_diagram_v3.png)
![user_flow_model](./assets/user_flow_diagram.png)

# Installation Instructions

- pip install 
  - FastAPI
  - MongoDB
  - Tesseract
  - Plotly  

## Local Setup
Clone the repo as usual, then cd into the project and create a virtual environment:
```
python -m venv venv
```
On Windows, run:
```
venv\Scripts\activate.bat
```
On Linux, Unix or MacOS, run:
```
source venv/bin/activate
```
Install dependencies:
```
pip install -r requirements.txt
```
Some operating systems refer to python as python3 and pip as pip3.

# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](./CODE_OF_CONDUCT.md). Please follow it in all your interactions with the project.

## Issue/Bug Request

**If you are having an issue with the existing project code, please submit a bug report under the following guidelines:**

- Check first to see if your issue has already been reported.
- Check to see if the issue has recently been fixed by attempting to reproduce the issue using the latest master branch in the repository.
- Create a live example of the problem.
- Submit a detailed bug report including your environment & browser, steps to reproduce the issue, actual and expected outcomes, where you believe the issue is originating from, and any potential solutions you have considered.

### Feature Requests

We would love to hear from you about new features which would improve this app and further the aims of our project. Please provide as much detail and information as possible to show us why you think your new feature should be implemented.

### Pull Requests

If you have developed a patch, bug fix, or new feature that would improve this app, please submit a pull request. It is best to communicate your ideas with the developers first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.

Remember that this project is licensed under the MIT license, and by submitting a pull request, you agree that your work will be, too.

#### Pull Request Guidelines

- Update the README.md with details of changes to the interface.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
