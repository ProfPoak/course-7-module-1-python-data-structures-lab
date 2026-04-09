# Student Data Management System

A Python lab project that demonstrates core data structure concepts — lists, tuples, sets, comprehensions, and generators — through a simple student records system.

## What It Does

- **Filter students by major** — returns a list of matching students using a list comprehension
- **Format and display student records** — formats each student tuple into a readable string and prints all records
- **Find unique majors** — extracts a deduplicated set of majors from the student list using a set comprehension
- **Generate students lazily** — yields matching students one at a time using a generator expression for memory efficiency

## Project Structure

```
lib/
  student_data.py      # Student records as a list of tuples
  filters.py           # filter_students_by_major()
  data_processing.py   # format_student_data(), display_students()
  set_operations.py    # unique_majors()
  data_generator.py    # student_generator()
testing/               # pytest test suite
```

## Setup

**1. Clone the repo**
```sh
git clone <repo-url>
cd course-7-module-1-python-data-structures-lab
```

**2. Install dependencies**
```sh
pipenv install
```

**3. Activate the virtual environment**
```sh
pipenv shell
```

## Usage

Run the test suite:
```sh
pytest -x
```

## Student Record Format

Each student is stored as a tuple: `(ID, Name, Major)`

```python
(101, "Alice Johnson", "Computer Science")
```
