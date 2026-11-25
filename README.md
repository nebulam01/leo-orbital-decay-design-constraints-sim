# 📉 Orbital Decay Simulator & Satellite Design Constraints

An interactive Low-Earth Orbit (LEO) atmospheric drag and orbital decay simulator I built in Google Colab using `Gradio`, `NumPy`, `Pandas`, and `Matplotlib` to compare altitude decay across multiple starting altitudes and examine the spacecraft design constraints that emerge.

## ✨ Key Features
- **Multi-Altitude Comparison:** Simulate four selectable starting altitudes simultaneously and compare decay trajectories and lifetime estimates.
- **Physical & Environmental Inputs:** Tune spacecraft mass (kg), cross-sectional area (m²), drag coefficient ($C_d$), solar activity level, and simulation horizon (years).
- **Decay & Lifetime Visuals:** Plots altitude vs. time curves down to re-entry (~120 km) alongside a lifetime comparison chart in a dark-mode dashboard.
- **Full-Width Design Constraints & Table:** Explains mission-lifetime vs. altitude trade-offs, solar-array area vs. drag conflicts, and propulsion/orbit-maintenance constraints, paired with a full-width summary table.

## 🛠️ Tech Stack
- **Environment:** Google Colab
- **Simulation, Plotting & UI:** Python, `Gradio`, `NumPy`, `Pandas`, `Matplotlib`

## ⚙️ How to Run the Project
1. **Open in Google Colab:**
   - Upload the notebook or script to Google Colab (`colab.research.google.com`).
2. **Run & Launch:**
   - Run the cell to install `gradio`, `numpy`, `pandas`, and `matplotlib` and launch the dashboard.
3. **Simulate:**
   - Adjust the four altitudes, mass, drag area, drag coefficient, and solar activity level, then click **Simulate Orbital Decay**.

## 📌 Scope & Assumptions
- Built for preliminary mission-design trade studies and educational astrodynamics exploration rather than operational space-surveillance or high-fidelity thermospheric density modeling.
- Uses an exponential scale-height atmospheric density approximation and circularized orbital energy-decay relations.
