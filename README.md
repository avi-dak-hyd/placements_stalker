# Introduction

Need to see which roll numbers belong to which people in the
pdf which can be downloaded from ERP for internships/
placements?

You are at the right place.


## Installation

Setup virtual environment in Python3 using:

```
virtualenv -p python3 .venv/
```

Activate it in a shell using:
```
source .venv/bin/activate
```

**Install Dependencies**

```
pip install -r requirements.txt
```

## Usage

```
python main.py <filename>
```

For testing on sample file ([test.pdf](test.pdf)):

```
python main.py test.pdf
```

