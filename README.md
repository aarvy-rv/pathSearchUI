# Path Finding Algorithm

This project implements several path-finding algorithms: **BFS**, **DFS**, **UCS**, and **A\***.  
(If you want C++ implementation(CLI based) : https://github.com/aarvy-rv/Path-Search).

## 🛠️ How to Use

1. **Download the code** to your local machine.
2. Open  index.html in the project directory, which is ready for use.
3. You can upload the input and heuristic files provided in the repository, or use your own files—just make sure they follow the required file format before uploading.


If you are using **A\*** Search, you **must** specify the heuristic file:


## Input File Format

Each line in the **input file** should be in the format:

```
<Source> <Destination> <Path Cost>
```

Example:
```
Chicago Milwaukee 93
Milwaukee Madison 79
Milwaukee DesMoines 269
```

---

## Heuristic File Format (Only for A*)

Each line should contain the city and the estimated cost to the destination:

```
<City> <Heuristic Cost>
```

Example:
```
Chicago 750
Milwaukee 820
Madison 790
```

---

## Supported Algorithms

- **BFS** – Breadth-First Search
- **DFS** – Depth-First Search
- **UCS** – Uniform Cost Search
- **A\*** – A-Star Search (requires heuristic file)

---

## Notes

- Ensure the heuristic file is only used when running A* search.
- File names must match exactly with your local files.
- Cities and search types are case-sensitive.

---
