Multi-agent learning algorithm

Author: Pasquale Roseti

The repository contains a proposal of an algorithm for the learning of causal relationships in Smart Home environments.

The work is inspired by: [1] https://github.com/fkanvaly/causality_detection

Starting from [1], I extended the single-agent case to a multi-agent one.

INSTALLATION:

Python version: 3.8.5

pip install -r requirements.txt


ARCHITECTURE:

- test.py: contains the code for the ONE-agent case relationships learning.
- run.py: contains the code for the TWO-agent case relationships learning.


USAGE:

The algorithm works in combination with the iCasa simulation software http://adeleresearchgroup.github.io/iCasa/snapshot/index.html
where it is possible to create a custom environment made by smart devices.


