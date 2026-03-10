# Force-Directed Graph Visualization with D3.js

Interactive network visualization of board game relationships using D3.js Force Simulation.

## Project Overview
This project implements an interactive force-directed graph to visualize relationships between board games. 
Each node represents a board game and each edge represents the similarity relationship between two games based on categories and gameplay mechanics.

The visualization allows users to explore the network through dragging, pinning nodes, and observing node importance using size and color scaling.

## Features
- Interactive force-directed graph
- Drag nodes to reposition them
- Pin nodes in place
- Double-click to unpin nodes
- Node size based on degree
- Node color based on connectivity

## Edge Styles
- value = 0 → gray solid edge
- value = 1 → green dashed edge

## Technologies
- D3.js v5
- HTML
- CSS
- JavaScript

## Running the Project
Run a local server:

python -m http.server

Then open:
http://localhost:8000/Q2.html
