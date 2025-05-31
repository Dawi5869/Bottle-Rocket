# 🚀 Rocket Lab – Water Rocket Modeling, Design & Launch Optimization

## ✨ Overview
This project was completed for an aerospace dynamics lab, where our team designed, modeled, and tested a **water bottle rocket** with the goal of maximizing its downrange distance. The challenge involved simulating flight dynamics, validating predictions through experimental launches, and iteratively improving our design based on data-driven insights.

Key aspects of the project included:
- Thrust modeling using **static test stand data**
- **MATLAB-based flight simulation**
- Sensitivity analysis of variables like water volume, launch angle, drag, and mass
- Real-world validation through **four physical launches** with varied parameters

---

## 👨‍💻 Personal Contributions (Damien Wilson)

- **🚀 MATLAB Simulation**
  - Contributed to the flight model used to simulate rocket trajectory across thrust and ballistic phases.
  - Assisted with integration of time-varying forces including thrust, drag, gravity, and friction during launch rail phase.

- **📊 Sensitivity Analysis**
  - Participated in testing variable influence on performance (launch angle, water volume, mass, fin size, and drag).
  - Helped interpret plots and tune parameters (e.g. optimized water volume to ~600–800 mL and launch angle to 37.5–45°).

- **🧠 Engineering Insights**
  - Contributed to post-flight analysis comparing experimental results with modeled outputs.
  - Provided design input on fin shape and nose cone optimization for reduced drag.
  - Helped summarize key lessons learned and improvements for future rocket designs.

---

## 🧪 Project Breakdown

| Launch # | Water Volume | Launch Angle | Modeled Distance | Actual Distance | Peak Height |
|----------|---------------|---------------|------------------|------------------|-------------|
| 1        | 800 mL        | 45°           | 98.6 m           | 54.5 m           | ~30 m       |
| 2        | 1000 mL       | 40°           | 72.9 m           | 50.2 m           | ~25 m       |
| 3        | 600 mL        | 37.5°         | 93.0 m           | 61.9 m           | ~23 m       |
| 4        | 400 mL        | 32.5°         | 68.6 m           | 58.5 m           | ~16 m       |

- **Modeling discrepancy**: Paint-induced drag, wind variation, and static test thrust limitations contributed to differences between model and reality.

---

## 🛠 Tools & Technologies

- **MATLAB** – Used to simulate rocket trajectory using a two-phase model (thrust & ballistic), solve equations of motion, and run sensitivity analysis.
- **Static Test Stand** – Used to empirically derive thrust values and validate model inputs.
- **Hand Fabrication** – Designed and constructed fins, cone, and payload cage from bottle rocket components.
- **Experimental Launch Testing** – Conducted four physical launches to refine assumptions and collect real data.

---

## 🧠 Lessons Learned

- **Water volume** affects pressure efficiency: Too much water prevents full expulsion, decreasing acceleration and distance.
- **Fin shape and mass distribution** impact center of gravity/stability margin—extra fin weight reduced flight quality.
- **Modeling can only go so far**—real-world testing revealed critical flaws not captured in simulations, like nose cone misalignment and surface drag due to paint.

---

## 📬 Contact
Reach out at dawi5869@colorado.edu
