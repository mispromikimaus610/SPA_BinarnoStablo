# Binary Tree Algorithms Implementation 🌳

This repository contains a comprehensive collection of **Binary Tree** algorithms implemented in Java. The project focuses on leveraging recursion to solve complex data structure problems, developed as part of advanced studies in **Data Structures and Algorithms (DSA)**.

## ✨ Key Features

The implementation includes over 30 specialized methods categorized by:

### 1. Basic Tree Operations
* **Traversals:** In-order (Infix) traversal for data visualization.
* **Tree Metrics:** Calculations for height (depth), total node count, and individual node levels.
* **Existence Checks:** Recursive search to verify if a specific node exists within the structure.

### 2. Statistical & Mathematical Logic
* **Aggregations:** Sum of all nodes, average value calculation, and product of leaf nodes.
* **Conditional Math:** Product of odd nodes, sum of nodes within a specific range, and counting specific node values.
* **Extreme Values:** Finding the maximum element in the tree using recursive comparison.

### 3. Advanced Structural Algorithms
* `zbirNajdubljih`: Calculates the sum of nodes located at the tree's maximum depth.
* `proizvodPredaka`: Computes the product of all common ancestors for two given nodes.
* `najvecizbir`: Identifies the root-to-leaf path with the highest sum.
* `najvecarazlika`: Finds the maximum absolute difference between a parent and its direct children.

## 🏗️ Technologies & Architecture

* **Language:** Java
* **Library Dependency:** This project utilizes the `labis` package (standard academic library) for the `CvorStabla` (Node) and `ABinarnoStablo` (Abstract Tree) definitions.
* **Core Concepts:** Deep Recursion, Exception Handling, and Object-Oriented Logic.

## 📂 Project Structure

The repository is organized as an Eclipse project:
```text
spa_kolokvijum2_1-master/
├── src/
│   └── spa_kolokvijum2_1/
│       ├── Binarno_stablo.java   # Core algorithms
│       └── Test.java             # Entry point for testing
├── Common_2019_Stabla_1.jar      # Required academic library
├── .classpath                    # Eclipse configuration
└── .project                      # Eclipse project file
```

## 🚀 Getting Started

### Prerequisites
* **JDK 11** or higher.
* **IDE:** IntelliJ IDEA, Eclipse, or NetBeans.
* **External Library:** Ensure `labis.jar` is added to your project's classpath to resolve inheritance from `ABinarnoStablo`.

### Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/mispromikimaus610/SPA_BinarnoStablo.git](https://github.com/mispromikimaus610/SPA_BinarnoStablo)
   ```
2. Open the project in your IDE.

3. Run Test.java to execute the algorithms against a generated tree.
Developed as part of academic preparation for Data Structures and Algorithms exams.
