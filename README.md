# Diploma-Project-
Demo and presentation
# Spatial Query System

## Overview
This project implements a **high-performance Spatial Query System** developed as a bachelor diploma project at the **National Polytechnic University of Armenia**.

The system is designed to efficiently process spatial data and execute different types of spatial queries using computational geometry techniques and spatial indexing.

The application includes a **graphical user interface (GUI)** for interactive spatial data visualization and query execution.

---

## Project Information

**University:** National Polytechnic University of Armenia  
**Student:** Anna Mezhlumyan  
**Supervisor:** Davit Revazyan  

---

## Features

- Spatial object representation:
  - Point
  - Line
  - Polygon

- Spatial queries:
  - Intersection Query
  - Range Query
  - Within Query
  - Nearest Neighbor / Radius Queries

- High-performance spatial indexing using **R-Tree**

- Interactive **GUI visualization**

- Efficient spatial predicate evaluation using computational geometry algorithms

---

## System Architecture

The system is organized into several modules:

- **Spatial Data Module**
  - Spatial object representation
  - Geometry operations

- **Indexing Module**
  - R-Tree spatial index
  - Efficient search structures

- **Query Engine**
  - Spatial predicate evaluation
  - Query processing logic

- **Visualization Module**
  - GUI for data visualization
  - Query interaction

---

## Technologies Used

- **C++**
- **Qt (GUI)**
- **STL**
- **Boost**


---

## Algorithm Workflow

1. Load spatial input data  
2. Construct spatial objects  
3. Perform spatial data analysis  
4. Build spatial index (R-Tree)  
5. Execute selected spatial query  
6. Display results in GUI  

---

## Complexity

Average query complexity: O(log(N) + M * C)

Where:

- **N** — number of spatial objects  
- **M** — candidate results  
- **C** — geometric predicate cost  

---

## Demo Video

Watch how the system works:

[Demo Video](https://drive.google.com/file/d/1ceaXbeMKnb9xCwvvDnWaJ6t1gb1dZ0X0/view?usp=sharing)

---

## Presentation

View the project presentation:

[Project Presentation](https://drive.google.com/file/d/1SBKKMX2OV1qdLwUPJxE-MoQTv2ekRo8l/view?usp=sharing)
---

## Results

Experiments were performed using datasets of different sizes to evaluate:

- Query execution time
- Index construction time
- System performance

The **R-Tree indexing structure** demonstrated the most stable and efficient performance for spatial queries.

---

## Conclusion

The developed system provides:

- High performance
- Accurate spatial query processing
- Efficient spatial indexing
- User-friendly graphical interface

The tool demonstrates practical applicability for spatial data processing and analysis.

---



