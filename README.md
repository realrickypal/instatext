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
- test: [unit tests](https://realpython.com/python-testing/)

### Setting up dataset
Instructions for creating local instance of dataset, or connecting to cloud computing ...

### Running package
1. Navigate to root of repo
2. Run script with `python instatext/run.py`

## Contributing
### Adding package requirements
1. Activate your virtual environment.
2. Use `pip install` to add required packages.
3. `pip freeze > requirements.txt`

### Formatting
4. Run `ruff check` and resolve formatting before pushing.

### Pushing
5. Add modified files or all files `git add --all` 
6. Commit changes with message `git commit -m "your comment"`
7. Push changes `git push origin main`

## Used Technologies
optical character recognition

## Authors
Diksha Bidikar
Sarah Gao
Ricky Palacios
Jayant Thomas

## License
...