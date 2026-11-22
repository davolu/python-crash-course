# Python Crash Course: Beginner to Advanced

A free, one-hour Colab walkthrough by **David Oluyale | Agentic AI Hub**.

Go from your first `print("Hello, world!")` to classes, generators, decorators and a small project.
Every concept uses a simple everyday example: coffee orders, pets, shopping lists, playlists, the weather.

## Open the notebook

- **Colab:** [Open in Colab](https://colab.research.google.com/github/davolu/python-crash-course/blob/main/Python_Crash_Course.ipynb)
- `Python_Crash_Course.ipynb`: the course notebook (no outputs).
- `Python_Crash_Course_EXECUTED.ipynb`: the same notebook with the outputs from our recorded run.

No API keys or accounts needed. Pure Python. The only internet use is `%pip install tabulate` (Part 7),
and downloading `data/expenses.csv` on Colab for the mini-project.

## What you will learn

1. **Basics**: print, variables, types, strings, f-strings, numbers, input (simulated).
2. **Collections**: lists, tuples, dictionaries, sets.
3. **Control flow**: if / elif / else, for and while loops, comprehensions.
4. **Functions**: defaults, `*args`, `**kwargs`, return values, scope.
5. **Errors**: try / except / else / finally, raise.
6. **Files**: text, CSV, JSON.
7. **Modules and pip**: math, random, datetime, collections, installing packages.
8. **Classes**: methods, inheritance, dunder methods, dataclasses.
9. **Advanced tools**: iterators, generators, lambda, map / filter / sorted, decorators, context managers.
10. **Type hints and testing** with `assert`.
11. **Mini-project**: an expense tracker that reads `data/expenses.csv` and writes `report.md`.

## Run locally

```bash
pip install -r requirements.txt jupyter
jupyter notebook Python_Crash_Course.ipynb
```

`data/expenses.csv` is a made-up month of 18 expenses, used for practice.
