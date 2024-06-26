This is a C++ implementation of the [Python Robotics](https://github.com/AtsushiSakai/PythonRobotics)


# Table of Contents
- [Table of Contents](#table-of-contents)
- [Requirements](#requirements)
- [Documentation](#documentation)
- [Localization](#localization)
  - [Extended Kalman Filter localization](#extended-kalman-filter-localization)

This is a Python code collection of robotics algorithms.

Features:

1. Easy to read for understanding each algorithm's basic idea.

2. Widely used and practical algorithms are selected.

3. Minimum dependency.

See this paper for more details:

- [\[1808\.10703\] PythonRobotics: a Python code collection of robotics algorithms](https://arxiv.org/abs/1808.10703) ([BibTeX](https://github.com/AtsushiSakai/PythonRoboticsPaper/blob/master/python_robotics.bib))


# Requirements

For running each sample code:

- [Python 3.12.x](https://www.python.org/)
 
- [NumPy](https://numpy.org/)
 
- [SciPy](https://scipy.org/)
 
- [Matplotlib](https://matplotlib.org/)
 
- [cvxpy](https://www.cvxpy.org/) 

For development:
  
- [pytest](https://pytest.org/) (for unit tests)
  
- [pytest-xdist](https://pypi.org/project/pytest-xdist/) (for parallel unit tests)
  
- [mypy](http://mypy-lang.org/) (for type check)
  
- [sphinx](https://www.sphinx-doc.org/) (for document generation)
  
- [pycodestyle](https://pypi.org/project/pycodestyle/) (for code style check)

# Documentation
This README only shows some examples of this projec

# Localization

## Extended Kalman Filter localization

<img src="https://github.com/malwaru/RoboticsInCpp/raw/master/Localization/extended_kalman_filter/animation.gif" width="640" alt="EKF pic">