# Industrial Digital Twin for Predictive Maintenance

## 🛠 Executive Summary
A mobile-edge utility designed for the shop floor to bridge the gap between material physics and real-time data logging. The app simulates tool degradation and calculates machining parameters with industrially verified accuracy.

## 🎥 Project Demo
<p align="center">
  <video src="machinist_app.mp4" width="100%" controls></video>
</p>

## 🚀 Core Technical Pillars

* **Physics-Informed Wear Engine**: Developed a modular `MachiningEngine` using Taylor’s Tool Life equations to predict Remaining Useful Life (RUL).
* **Edge Visualization**: Integrated high-performance time-series charting via `fl_chart` to visualize degradation trends in real-time.
* **Sensor Fusion Simulation**: Built a responsive UI for simulating G-force vibration inputs, providing immediate visual feedback on machine health.
* **Data Pipeline**: Engineered a CSV export system to sync time-series logs to cloud storage (Google Drive), creating labeled datasets for future PINN training.
* **Industrial Verification**: Established a 100% success rate for core physics calculations via automated Unit Testing.

## 🧪 Industrial Verification (Unit Tests)
The core logic is verified through a dedicated test suite located in `/test/physics_engine_test.dart`.
* **RPM/IPM Accuracy**: Verified against standard machining constants.
* **Material-Specific Logic**: Confirmed accelerated wear models for high-toughness materials like Titanium.

---
*Developed as a bridge between 18 years of Precision Engineering and modern AI-driven Smart Manufacturing.*
