Note: This repository is a fresh copy of a different repo because I had problems with the last one, which is why there are so few commits on this one. In the last repo, eah exercice was done on its own branch, merged into main, but there were some bugs so I asked AI to fix the bugs and it told me to create a new fresh copy repo.

AI: > I used an AI assistant to help debug parts of the code.


# OOP & Design Patterns in Python

My exercises for the OOP & Design Patterns in Python course.

- `01-git`: Git workflow
- `02-bash`: bash script to set up a Python environment
- `03-oop`: operator overloading, inheritance, abstract classes
- `04-uml`: UML exercises (hospital system and ABCD Records)
- `05-design-patterns`: Factory, Builder, Singleton, Adapter, Decorator, Strategy, Template Method
- `06-testing`: unit tests, integration tests and mocking

Each folder has its own README and a `tests` folder.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate   # on Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Run the tests

```bash
pytest
```

Each exercise was done on its own branch and then merged into `main`.
