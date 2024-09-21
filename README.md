# Instatext: Image Text Extraction

## Project Description
Capstone project for Rice MDS. Convert image text (text stored as an image) into text (text stored as symbols).

## Installation
1. Clone repo `git clone <repo>`
2. `cd <repo>`
3. `pip install virtualenv`
4. Create virtual environment `virtualenv .venv`
5. Activate virtual environment (varies by OS) `source .venv/Scripts/activate`
2. Install packages ```pip install -r requirements.txt```

## Execution and Usage
### Repo Structure
```
instatext
├───data
├───instatext
│   ├───preprocessing.py
│   ├───processing.py
│   ├───postprocessing.py
│   └───run.py
└───tests
requirements.txt
```
- data: store dataset locally
- instatext: main project folder
- testunit tests](https://realpython.com/python-testing/)

### Setting up dataset
Instructions for creating local instance of dataset, or connecting to cloud computing ...

### Running package
1. Navigate to root of repo
2. Run script with `python instatext/run.py`

## Contributing
### Creating a branch
1. Create checkout `git checkout -b <branch name>`

### Adding package requirements
2. Activate your virtual environment.
3. Use `pip install` to add required packages.
4. `pip freeze > requirements.txt`

### Formatting
5. Run `ruff check` and resolve formatting before pushing.

### Pushing
6. Add modified files or all files `git add --all` 
7. Commit changes
8. Push to remote repo
9. Merge with main branch

## Used Technologies
optical character recognition

## Authors
Diksha Bidikar
Sarah Gao
Ricky Palacios
Jayant Thomas

## License
...