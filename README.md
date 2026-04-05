# Pathfinding-Agent
Assignment for CMPT 310 - Introduction to Artificial Intelligence

This project implements a cleaning robot agent in a grid environment. The robot navigates from cell to cell, cleaning dirty cells while avoiding walls. The project practices the design and implementation of uninformed (DFS, BFS, UCS) and informed (Greedy, A) search algorithms*, as well as reflex-style movement.


## Table of Contents
1. [Navigation Guide](#1-navigation-guide)
2. [Installation](#install)
3. [Getting Started](#start)
4. [Features](#features)



<a name="navigation"></a>

## 1. Navigation Guide

```bash
repository
├── agents.py           ## environment logic
├── search.py           ## search algorithm implementations
├── vacuum_search.py    ## main application script
├── utils.py            ## helper functions
```



<a name="install"></a>

## 2. Installation

This project requires using Python and the following Python libraries are used:
- pygame
- numpy

You can install the required libraries using the following command::
```bash
pip install pygame numpy
```


<a name="start"></a>

## 3. Getting Started

Suggestion: Use PyCharm to efficiently switch between algorithms.

#### 3.1. Clone and Navigate
```bash
# 1. Clone this repo to your local machine
git clone $THISREPO
# 2. Navigate into the repository directory
cd $THISREPO
```

#### 3.2. Run project
1. Open _vacuum_search.py_ file (Make sure you are in the repository directory)
2. (opitonal) Select an algorithm
3. Click the run button



<a name="features"></a>

## 4. Features
This Pathfinding Agent supports five different algorithms:
- BFS: Breadth-First Search
- DFS: Depth-First Search
- UCS: Uniform-Cost Search
- Greedy: Manhattan distance
- A*: A star search

