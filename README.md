# Data Structure and Graph Performance Analyzer

## Project Information

- **Module:** CIT300 – Data Structures and Algorithms
- **Assignment:** Graded Practical Assignment 2 (Week 12)
- **Scope:** Weeks 1–11
- **Programming Language:** Java
- **Application Type:** Console-Based System

## Project Description

This project is a Java console application that demonstrates data structures, searching algorithms, graph traversal and performance comparisons.

Users can perform operations through menus, view results and compare algorithm performance. The project demonstrates object-oriented programming, input validation and GitHub collaboration.

## Team Members

| Full Name | Student ID | Assigned Responsibility |
|---|---|---|
| N M Imthath | 23da2-0578 | Team leader, array, searching, input handling and integration |
| M S M Sabreen | 23da2-0733 | Stack and queue |
| A M D R Adhikari | 23da2-0965 | Graph and performance comparison |
| M L F lafra | 23da2-1118 | Linked list |

## Individual Contributions

### Member 1 – Imthath (Team Leader)

**Assigned files:**
- `ArrayOperations.java`
- `SearchingAlgorithms.java`
- `InputHandler.java`
- `Main.java`

**Assigned responsibilities:**
- Array insertion, deletion, searching and display.
- Linear search and binary search.
- User input handling and validation.
- Main menu and component integration.
- Coordination and review of the complete application.

**Actual implementation and testing completed:**
[Describe the work personally completed and the tests performed.]

### Member 2 – Sabreen

**Assigned files:**
- `StackOperations.java`
- `QueueOperations.java`

**Assigned responsibilities:**
- Stack push, pop, peek and display.
- Queue enqueue, dequeue, front and display.
- Empty-stack and empty-queue handling.
- Demonstration of LIFO and FIFO behaviour.

**Actual implementation and testing completed:**
[Describe the work personally completed and the tests performed.]

### Member 3 – Darshani

**Assigned files:**
- `GraphOperations.java`
- `PerformanceAnalyzer.java`

**Assigned responsibilities:**
- Graph representation, vertex and edge operations.
- Graph display.
- Breadth-First Search (BFS).
- Depth-First Search (DFS).
- Performance comparison and reporting.

**Actual implementation and testing completed:**
[Describe the work personally completed and the tests performed.]

### Member 4 – Lafra

**Assigned file:**
- `LinkedListOperations.java`

**Assigned responsibilities:**
- Linked list insertion, deletion, searching and display.
- Empty-list and missing-value handling.
- Testing linked list operations.

**Actual implementation and testing completed:**
[Describe the work personally completed and the tests performed.]

## Main Features

- Array operations.
- Stack operations.
- Queue operations.
- Linked list operations.
- Linear and binary searching.
- Graph vertex and edge operations.
- BFS and DFS traversals.
- Performance comparison.
- Integrated console menus.
- Input validation and invalid-operation handling.

## Project Structure

```text
-Assignment-2/
├── src/
│   ├── ArrayOperations.java
│   ├── GraphOperations.java
│   ├── InputHandler.java
│   ├── LinkedListOperations.java
│   ├── Main.java
│   ├── PerformanceAnalyzer.java
│   ├── QueueOperations.java
│   ├── SearchingAlgorithms.java
│   └── StackOperations.java
├── LICENSE
└── README.md
```

## Technologies Used

- Java Development Kit (JDK)
- Visual Studio Code
- Git
- GitHub

**Java version used:** [Enter the output of java -version]

## How to Run

The following commands assume that the Java files have no package declarations.

### 1. Clone the repository

```bash
git clone https://github.com/imthEric/-Assignment-2.git
cd ./-Assignment-2
```

### 2. Compile the application

Run from the project root folder:

```bash
javac -d out src/*.java
```

### 3. Start the application

```bash
java -cp out Main
```

Follow the console prompts to select a component and perform operations.

## Searching and Complexity

### Linear Search

Linear search checks elements one by one until the target is found or all elements have been checked.

- Best-case time complexity: O(1)
- Worst-case time complexity: O(n)

### Binary Search

Binary search repeatedly halves the search range.

- Requires sorted data.
- Best-case time complexity: O(1)
- Worst-case time complexity: O(log n)

Sorting, if required, adds a separate cost and should be explained when comparing the two algorithms.

## Graph Traversal and Complexity

### Breadth-First Search (BFS)

BFS uses a queue to explore vertices level by level.

### Depth-First Search (DFS)

DFS explores a path before backtracking, using recursion or an explicit stack.

For an adjacency-list representation, both traversals take O(V + E) time when traversing the full graph, where:

- V is the number of vertices.
- E is the number of edges.

For an adjacency-matrix representation, full traversal generally takes O(V²).

**Representation used in this project:** [Enter the actual representation]

A traversal from one starting vertex visits only the vertices reachable from it unless the program also processes disconnected components.

## Performance Comparison

**Measurements recorded by the application:**
[Specify the actual measurements, such as element comparisons, vertex visits, edge examinations or execution time.]

**Definition of one step or operation:**
[Explain exactly what each counter measures.]

**Example results:**
[Add actual results from running the program. Do not invent measurements.]

Step counts depend on input size, target position, graph structure and the counting method. Execution times can also vary because of JVM warm-up and other activity on the computer.

## Testing Checklist

Mark an item complete only after testing it.

- [ ] Array insertion, deletion, search and display.
- [ ] Stack push, pop, peek and display.
- [ ] Empty-stack handling.
- [ ] Queue enqueue, dequeue, front and display.
- [ ] FIFO processing order.
- [ ] Empty-queue handling.
- [ ] Linked list insertion, deletion, search and display.
- [ ] Empty-list and missing-value handling.
- [ ] Linear search: found and not found.
- [ ] Binary search: found, not found and sorted-input handling.
- [ ] Graph vertex and edge operations.
- [ ] BFS and DFS traversal.
- [ ] Graph cycles and disconnected vertices.
- [ ] Invalid input handling.
- [ ] Performance measurements.
- [ ] Complete application compilation and execution.

## GitHub Collaboration

| Member | Branch |
|---|---|
| Imthath | `Imthath-array-search` |
| Sabreen | `sabreen-stack-queue` |
| Darshani | `Darshani-graph-performance` |
| Lafra | `lafra-linked-list` |

Each member's contribution is documented through their actual commits and pull requests. Changes are reviewed and integrated into the `main` branch.

### Pull Request Evidence

- Imthath: [Add pull request URL]
- Sabreen: [Add pull request URL]
- Darshani: [Add pull request URL]
- Lafra: [Add pull request URL]

## Demonstration Video

**Video link:** [Add the final merged video link]

The final video must be less than 15 minutes. Each member must:

- Introduce themselves with their name and student ID.
- Explain their own contribution.
- Show the relevant code.
- Demonstrate the functionality.
- Explain the data structure, algorithm and complexity.
- Keep their face clearly visible throughout their presentation.
