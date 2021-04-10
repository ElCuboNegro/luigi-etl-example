============
luigi_basics
============

A short example of Luigi using sqlite3

Description
===========

We have a very simple scenario just to demonstrate the combination of those libraries to create the ETL,
we have two different databases db1 and db2, db1 has a table called “names” and has the id, first name
and last name of our employees, and db2 has a table named “salaries” with an id and the salary,
the task is to get all data from “names” and “salaries” and create a CSV with the two tables
merged with the unique id.


Preparation
===========

run this line for prepare the code.

``bash
pip3 install -r requirements.txt
``

.. _pyscaffold-notes:

Note
====

This project has been set up using PyScaffold 4.0.1. For details and usage
information on PyScaffold see https://pyscaffold.org/.
