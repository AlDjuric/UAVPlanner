# UAVPlanner

# Flight Route Planning Tool

## Overview

This project is a **QML-based UAV flight route planning tool** that allows users to:

- Select and modify **waypoints** on an interactive map.
- Define **altitude and speed** for each waypoint.
- Mark **no-fly zones** to avoid restricted areas.
- Export flight paths in **MAVLink, CSV, or GeoJSON** format.

## Technologies Used

- **QML (Qt Quick)** – UI development
- **QtLocation** – Mapping functionality
- **C++ (Qt Framework)** – Backend logic
- **GeoJSON / SQLite** – Data handling
- **MAVLink / CSV Export** – Drone autopilot integration

---

## Roadmap

### **Phase 1: Basic UI (QML Setup)**

- [ ] Display an **interactive map** using **QtLocation**.
- [ ] Allow users to **add waypoints** by clicking on the map.
- [ ] Show a **list of waypoints** in a side panel.
- [ ] Allow users to **delete waypoints**.

### **Phase 2: Flight Path Management**

- [ ] Add **altitude & speed selection** per waypoint.
- [ ] Implement **drag-and-drop editing** of waypoints.
- [ ] Display **total flight distance & estimated time**.

### **Phase 3: No-Fly Zones & Obstacles**

- [ ] Allow users to **draw no-fly zones**.
- [ ] Prevent waypoints from being placed inside **restricted areas**.
- [ ] Display warnings for **prohibited flight paths**.

### **Phase 4: Data Export & Integration**

- [ ] Export flight paths in **CSV, GeoJSON, or MAVLink** format.
- [ ] Integrate with **drone autopilot systems**.

---

## Installation & Setup

### **1. Install Qt and QML**

Ensure you have **Qt 6** installed:

```bash
sudo pacman -S qt6-base qt6-declarative qt6-location
```

Or, download Qt from [Qt Official Website](https://www.qt.io/download).

### **2. Clone the Project**

```bash
git clone https://github.com/yourusername/flight-planner-qml.git
cd flight-planner-qml
```

### **3. Build & Run**

```bash
qtcreator .
```

Or manually:

```bash
mkdir build && cd build
qmake ../
make
./flight-planner
```

---

## Contribution

If you want to contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit changes and push (`git push origin feature-name`).
4. Submit a Pull Request.

---

## License

MIT License - Feel free to use and modify!

