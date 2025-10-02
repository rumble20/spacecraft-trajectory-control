# Autonomous Trajectory Planning and Control

This repository explores the simulation and control of autonomous vehicles (drones or spacecraft) with a focus on **trajectory planning, control strategies, and AI-based methods**.  
The project is structured in **progressive modules**, each addressing a different aspect of aerospace/robotics engineering.

---

## Features (Planned & Implemented)
- ✅ Vehicle dynamics simulation (2D/3D models, disturbances, constraints)  
- 🔄 Classical control: LQR / MPC for stabilization and trajectory tracking  
- 🔄 Trajectory optimization: minimum-fuel or time-optimal missions  
- 🔄 Reinforcement learning: training agents for autonomous guidance  
- 🔄 Perception: computer vision for localization from synthetic imagery  

(*Check roadmap for progress tracking.*)

---

## Usage
Each module will have a dedicated script or notebook.  
Example (Step 1 – vehicle dynamics simulation):
```bash
python dynamics_simulation.py
```

Outputs:  
- Time evolution of vehicle state  
- 2D/3D trajectory plots  
- Comparison between uncontrolled and controlled motion  

---

## Repository Structure
```
autonomous-trajectory-control/
│
├── dynamics_simulation.py       # Step 1: baseline dynamics
├── control_lqr_mpc.py           # Step 2: classical control
├── trajectory_optimization.py   # Step 3: optimal control
├── rl_guidance.py               # Step 4: reinforcement learning
├── vision_navigation.py         # Step 5: computer vision
│
├── plots/                       # Generated plots and results
├── docs/                        # Notes, background, references
└── README.md
```

---

## Goals
- Demonstrate skills in **control theory, optimization, reinforcement learning, and sensor-based navigation**  
- Provide a flexible sandbox for experimenting with **aerospace guidance & navigation concepts**  
- Showcase integration of **classical engineering methods** with **modern AI approaches**  

---

## References
- Bryson, A.E., *Optimal Control Theory for Aerospace Applications*  
- Sutton & Barto, *Reinforcement Learning: An Introduction*  
- Astrom & Murray, *Feedback Systems*  
- Relevant aerospace and robotics research papers (to be added)

---

## Contact
Created by Riccardo Legnini.  
Feel free to connect via LinkedIn or open an issue for discussion!
