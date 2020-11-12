---
description: 11/11/20
---

# STAR Interviewing Method + Graphs

## Shine Like a STAR

_Using the STAR Method in Behavioral Interviews_

### Behavioral Question

Non-technical interview questions to evaluate leadership, team collaboration, and ability to deliver

### STAR Method

Situation Task Action Result pattern of how to answer behavioral questions

### Situation

* What was your role?
* Where were you working?
* What type of project were you on?

### Task

* What were you asked to do?
* What goal were you trying to reach?
* What were you trying to accomplish?

### Action

* What approach did you take to solve the problem?
* How did you reach the goal?
* What action did you take?

### Result

* Was the original problem solved?
* Were the results as expected?
* Did you learn anything from the experience?

## An Ode to Node

_Graph Data Structures and Algorithms_

### What Are Graphs?

#### Nodes or Vertices \(Vertex\)

Nodes: Data; Vertices: Math

* Can have a value

#### Edges

Edges — Lines

* Can have an arrow or not
* Can have a value

### Graphs Represent Relationships

#### Undirected

* No arrows
* Everything can go two ways
* Usually talking about edges

#### Directed

* Has arrows
* Can only go one way
* Usually talking about a graph

Must be one or the other; cannot mix undirected edges in a directed graph

* Fix this by creating a bidirectional edge

### Node

A node is a neighbor of another node if...

### Graphs

How do we represent graphs?

#### Adjacency List

**Undirected**

* List each Node's neighbors
* Must have a symmetrical relationship between key, value pairs

**Directed**

* Consider graph traversal in this one
* Symmetry is no longer there
  * Symmetrical relationship is possible for bidirected edges

#### Adjacency Matrix

**Undirected**

* Fill graph with 1, 0, and -1 to represent null
* Has a symmetrical relationship in that you can fold the graph diagonally

**Directed**

* Have to fill in the complete matrix because there is no symmetrical relationship

Connectivity -- highly connected = more neighbors

### List or Matrix?

#### Adjacency List

* Easy to change number of nodes
* Can be stored in different locations \(distributed\)
* Requires more space
* Takes more time to look up if nodes are neighbors

#### Adjacency Matrix

* Compact
* Quick lookup time to see if two nodes are neighbors
* Difficult to change the number of nodes
* All stored in one place
* Good for serialization

Most often go with an adjacency list

### Why Use Graphs?

* Trees
  * Trie — structures used for predictive search

### Graph Traversal

#### Breadth First Search

* Inspect nodes closest to starting node before inspecting nodes further
* "Shortest path" --&gt; ASAP
* Optimal, but not faster
  * Has to traverse through more nodes to get to the solution

#### Depth First Search

* Inspect nodes further from the starting node first before closer nodes
* "Any path"
* Often faster, but not optimal
  * Goes "further" to get to the node but doesn't bother with needless searching

### Implementation



