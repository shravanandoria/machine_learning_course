# Machine Learning Course

This repository contains a beginner-friendly machine learning course built around Jupyter notebooks and Python examples. It is designed to help learners understand core ML concepts, work with Python libraries, and practice hands-on coding in a structured way.

## Project Overview

The course includes multiple lecture notebooks covering foundational topics such as:

- Python basics and environment setup
- Data handling and preprocessing
- Essential machine learning concepts
- Standard library usage and Python modules
- Practical coding exercises and examples

## Repository Structure

```text
ml_course/
├── README.md
├── python/
│   ├── lect_1.ipynb
│   ├── lect_2.ipynb
│   ├── lect_3.ipynb
│   ├── lect_4.ipynb
│   ├── lect_4.1.ipynb
│   ├── lect_5.ipynb
│   ├── lect_5.1.ipynb
│   ├── lect_5.2.ipynb
│   ├── lect_5.3.ipynb
│   ├── requirements.txt
│   ├── test.py
│   └── modules/
│       ├── destination.txt
│       ├── example.csv
│       ├── source.txt
│       ├── lect_6.ipynb
│       ├── lect_6_standard_lib.ipynb
│       ├── my_package/
│       │   ├── __init__.py
│       │   ├── my_module.py
│       │   └── sub_package/
│       │       ├── __init__.py
│       │       └── sub_module.py
│       └── shravan_dir/
└── .gitignore
```

## Getting Started

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd ml_course
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

On Windows:

```bash
venv\Scripts\activate
```

On macOS/Linux:

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r python/requirements.txt
```

## Running the Notebooks

Open the notebooks in the `python/` folder using Jupyter Notebook or VS Code's notebook support.

```bash
jupyter notebook
```

Then navigate to the relevant lesson notebook and start experimenting.

## Notes

- The project is structured for learning and experimentation.
- Some notebooks focus on Python fundamentals and module/package concepts.
- You can add your own notes, code snippets, and exercises as you progress.

## Learning Path

A suggested order is:

1. Start with the lecture notebooks in `python/`
2. Review Python module concepts in `python/modules/`
3. Practice with `test.py` and experiment with code snippets
4. Extend the examples and build your own mini-projects

## License

This project is intended for educational purposes.
