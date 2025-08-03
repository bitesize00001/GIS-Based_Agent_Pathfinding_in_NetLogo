# GIS-Based_Agent_Pathfinding_in_NetLogo

## 🧭 Overview

This NetLogo model simulates agent-based pathfinding within an urban environment. Agents are programmed to navigate toward buildings while avoiding bus stops, using spatial constraints derived from a GIS-based map layout.

## 🗺️ Model Objective

- Demonstrate basic spatial navigation using NetLogo’s GIS capabilities.
- Allow agents to find shortest or optimal paths to buildings.
- Exclude bus stops as target destinations and/or avoid them as obstacles.

## 🔧 Features

- **GIS Layer Integration:** Import of spatial layers (buildings, roads, bus stops).
- **Agent Navigation:** Rule-based pathfinding logic.
- **Selective Pathfinding:** Agents only navigate to buildings, not bus stops.
- **Visual Output:** Animated agent movement, destination highlighting.

## 🚀 How It Works

1. **Setup**
   - Load GIS layers (e.g., shapefiles/raster).
   - Initialize patches as either walkable, building, or bus stop.

2. **Agent Creation**
   - Agents spawn at defined locations.
   - Each agent is assigned a target (building).

3. **Pathfinding Logic**
   - Agents find a path using distance-based or heuristic navigation.
   - Bus stops are flagged and avoided during routing.

4. **Simulation Loop (`go`)**
   - Agents move step-by-step toward the nearest building.
   - Routes adjust dynamically if blocked.

## 🧠 Technologies

- **NetLogo** (ABM platform)
- **GIS Extension** (for spatial data handling)

## 📁 File

- `2019 GIS+PATH_+PATH_FINDING_1 只走到建築不走到公車站.nlogo` – Main model file.

## 📌 Notes

- Designed for research or teaching purposes.
- Can be extended to multi-modal navigation, accessibility simulation, or emergency evacuation modeling.

## 👩‍💻 Author

Dr.-Ing. Hsiao-Hui Chen  
Urban & Health Informatics | Data Science | NetLogo Modeling

---

## 💼 Use Case

Ideal for portfolios targeting:
- Urban Planning & Transport Simulation
- Agent-Based Modeling Roles
- GIS + ABM Research Projects
