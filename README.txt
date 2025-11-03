# Race Telemetry Dashboard

A high-performance Python application built with PyQt6 for visualizing and analyzing simulated race car telemetry data in real-time. This project bridges software development with core motorsport engineering principles, providing an intuitive platform for deep performance analysis.

##  Features

### Real-Time Data Visualization
- Live, interactive graphs for key performance metrics:
  - **Kinematics:** Velocity, G-Force (Lateral/Longitudinal), Slide
  - **Driver Inputs:** Throttle %, Brake %, Steering %
  - **Powertrain:** RPM, Gear
  - **Session Data:** Race Position, Delta Time
- **Precision Data Cursor:** Extract exact values at specific timestamps or distances directly from the graph.

### Advanced Lap Analysis
- **Circuit Mapping:** Generate detailed track maps with:
  - Lap time comparisons
  - Racing line analysis
  - Sector breakdowns
  - Throttle and brake application heatmaps
  - G-force vector visualization
- **Multi-lap Comparison:** Analyze unlimited laps simultaneously with dedicated color-coding (Main, Secondary, Multi).

### Professional-Grade Interface
- Built with **PyQt6** for a smooth, responsive user experience
- Multi-tabbed layout for organized data presentation
- Intuitive controls for complex data manipulation

##  Technologies Used

*   **Backend:** Python 3
*   **GUI Framework:** PyQt6
*   **Data Processing:** Pandas, NumPy
*   **Data Visualization:** pyqtgraph

##  Quick Start

1.  **Clone the repository**
    ```bash
    git clone https://github.com/your-username/race-telemetry-app.git
    cd race-telemetry-app
    ```

2.  **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch the application**
    ```bash
    python main.py
    ```

## 📖 User Guide

### Basic Workflow

1.  **Import Data:** Click the `File` button to load your telemetry data (CSV format required for v1.0)
2.  **Configure X-Axis:** Select your primary dimension (Time/Distance) using the `X-Axis` button
3.  **Customize Graphs:** Use the `Graph` button to:
    - Add/remove data channels from display
    - Compare multiple laps using the color-coded selection system:
      - **Blue:** Primary lap
      - **Red:** Secondary lap  
      - **Multi-color:** Unlimited additional laps

### Advanced Features

- **Data Inspection:** Click `Filler` to pinpoint exact values at any point, synchronized across all graphs and maps
- **Track Mapping:** Generate circuit visualizations with `Create Track Map`
- **Lap Statistics:** Access comprehensive lap data with `Show Lap Stats`

## Project Architecture

This application demonstrates professional data handling patterns used in modern motorsports:

*   **Data Layer:** Ingests and manages telemetry streams
*   **Processing Layer:** Calculates performance metrics and derivatives
*   **Presentation Layer:** Multi-tabbed GUI for comprehensive data visualization

## 💾 Download Standalone Application

[**Download for Windows**] (https://drive.google.com/open?id=1csYc2HC83O8jOls0Tcg4_QbTQDMzAucu&usp=drive_fs) - Pre-compiled executable (v1.0)

### Installation:
1. Download the .zip file above
2. Extract the contents to any folder
3. Run `RaceTelemetry.exe` (found in “dist” folder)
4. *(Windows may show a security warning - this is normal for new applications)*


*No installation required - simply download and run*

---

## Future Enhancements

*   Support for additional data formats (MDF, MOTEC)
*   Real-time telemetry streaming support
*   Advanced aerodynamic analysis tools
*   Predictive lap simulation

**Known Issues:**
- The "Data Cursor" feature is currently labeled "Filler" in the UI. This is purely a cosmetic issue and the functionality works completely. This will be fixed in v1.1, scheduled for late December.


*Developed with passion for motorsport performance engineering.*