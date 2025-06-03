# [Chroma]Morph

**A Mesh Agent System Based on Color Similarity for Image Style Transfer**

**Tech Stack:** Rhino/Grasshopper Python Scripting, Agent-Based Modeling-ABxM.Core library                                                  
**Teammate:** Joyce Wu  

[Chroma]Morph explores how agent-based modeling can be used to transfer image styles through localized, color-driven interactions within a mesh environment. Inspired by wet-on-wet painting techniques, the system simulates how colors dynamically evolve across a mesh as agents interact with their surroundings.

---

## 💡 Concept

This project implements a **similarity-based agent system** where:

- Each **mesh face** serves as a potential agent in either a passive or active state.
- **Active agents** seek out other similarly colored agents and influence the mesh faces they traverse.
- A **decay rate** defines how much color influence is transferred.
- The simulation halts once all mesh faces reach an "active threshold" based on cumulative agent interactions.

---

## 🛠 Features

- 🎨 **Agent-based image style transfer** based on color similarity.
- 🧩 **Localized transformations** of mesh faces within a simulated environment.
- 🔄 Real-time visualization of the propagation and blending process.

---

## 📁 Repository Structure
/src              → Core Grasshopper and Python scripts
/assets           → Sample images and mesh inputs
/README.md        → Project overview

---

## 🚧 Notes

This project is an early-stage exploration that combines visual computing and agent-based simulation. It aims to simulate painterly style transfer effects by mimicking physical dynamics within digital media.

---

