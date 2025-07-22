# Fueler
An AI based full stack application for fuel efficient route optimization that leverages algorithms like Dijkstra and heuristics functions to choose best path in a graph.
# Fuel Optimiser

Fuel Optimiser is a web-based tool that visualizes real-world locations as graph nodes for interactive route planning. It leverages advanced optimization algorithms, including Dijkstra's algorithm, and incorporates elevation data via external APIs to calculate the most fuel-efficient paths. The application uses caching to accelerate computations and features an intuitive interface that closely mimics actual geographic layouts.

## Features
- Visualizes locations as graph nodes for interactive route planning
- Calculates fuel-efficient paths using Dijkstra's algorithm and optimization techniques
- Integrates elevation data from external APIs for more accurate estimations
- Implements caching to speed up route computations
- Intuitive web interface with HTML/CSS

## Tech Stack
- Python
- Flask
- NetworkX
- Dijkstra's Algorithm
- Caching (Pickle)
- HTML/CSS
- Elevation API

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/YOUR-USERNAME/fuel-optimiser.git
   cd fuel-optimiser
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the application:
   ```sh
   python main.py
   ```

## Usage
- Access the web interface in your browser (default: http://localhost:5000)
- Select start and end locations to visualize and optimize your route
- View the most fuel-efficient path and related statistics

