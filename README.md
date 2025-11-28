# I2G – Image To Graph With Gemini

> Draw a graph by hand → take a picture → let an AI turn it into a real `networkx` graph.

This project is a small experiment:  
I take a **hand-drawn graph image** (from my tablet), send it to **Google Gemini** (Vision API), and convert the result into:

- a `networkx` graph  
- an adjacency list  
- a coloring  
- a matplotlib visualization with the n-colors

The main logic currently lives in a Jupyter notebook.

---

## Project Structure

```text
.
├─ images/
│  └─ graph_test.jpg      # hand-drawn graph
├─ src/
│  └─ main.ipynb          # notebook with the whole pipeline
├─ LICENSE                # MIT
└─ README.md
