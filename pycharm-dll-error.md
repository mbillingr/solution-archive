# DLL error in Pycharm

## Description
Sometimes running Python code from Pycharm in Windows causes DLL load errors, while running the same code from the terminal works correctly.
These errors occur in various modules (I have seen them in scipy, sqlite, and others).

## Workaround
Running Pycharm from within the same (conda) environment seems to prevent the problem.

## Solution
Updating the affected Python package sometims solved the issue.
It's not always easy to tell which package needs to be updated.

## Solution
Matlab installations sometimes interfere with Python's scientific packages.
Uninstalling Matlab has resolved this problem in at least two cases.
(I don't remember if the terminal was affected too when Matlab was the problem.)
