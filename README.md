# Pull Along Dog Toy - A Kinematic Study and Simulation

This project presents a detailed kinematic study of a **pull-along dog toy**, combining theoretical analysis with simulation. It involves identifying and modeling the underlying mechanisms, performing kinematic analysis using **Python**, and validating the results through **CAD modeling in SolidWorks** and **dynamic simulation in MSC Adams**. The objective is to map real-world mechanical motion to analytical frameworks and computational tools, showcasing the intersection of mechanical design and simulation.

---

## Background

This project was carried out as part of the *Personal Project* component of the course **ME2220: Kinematics and Dynamics of Machinery** at **IIT Hyderabad**. The task was to:

- Select a mechanical toy
- Identify and analyze the mechanisms involved
- Simulate the toy-based mechanism using Adams

I chose a pull-along dog toy for its interesting multi-link motion and combined front–rear actuation.

---

## Mechanisms Analyzed

The toy incorporates:
- **Four 4-bar linkages**: Simulating the motion of the four legs
- **One slotted link mechanism**: Driving the tail movement

### Mechanism Breakdown:
- **Mechanism 1**: Two 4-bar linkages (front legs)
- **Mechanism 2**: Two 4-bar linkages + slotted link (rear legs and tail)

For a detailed breakdown and diagrams, refer to:
> `Reports/` → `KDM_Phase1.pdf` and `KDM_Phase2.pdf`

---

## Study Phases

All reports and analysis scripts are available in the `Reports/` and `scripts/` folders respectively.

### `KDM_Phase1.pdf`
- Toy selection rationale
- Identification of mechanisms
- Mobility analysis (DOF calculation)

### `KDM_Phase2.pdf`
- Detailed segmentation of mechanisms
- Loop-closure equations
- Displacement, velocity, and acceleration analysis using **Python**
- View corresponding implementation and plots in:
  - `toy_mechanism1.ipynb`
  - `toy_mechanism2.ipynb`

### `KDM_Phase3.pdf`
- CAD modeling in **SolidWorks**
- Simulation in **Adams**
- Motion plots and comparisons with analytical results from Phase 2

---

## Results

The analytical and simulation-based motion studies showed strong agreement, validating the accuracy of the theoretical kinematic analysis. This project demonstrates how mechanical systems can be **modeled computationally** and evaluated prior to **physical prototyping** — a powerful combination of classical mechanics and modern tools.

---

## Repository Structure

```plaintext
├── Reports/
│   ├── KDM_Phase1.pdf
│   ├── KDM_Phase2.pdf
│   └── KDM_Phase3.pdf
├── Result_Plots/
│   ├── [Displacement/Velocity/Acceleration plots]
├── scripts/
│   ├── toy_mech1.py
│   └── toy_mech2.py
├── toy_mechanism1.ipynb
├── toy_mechanism2.ipynb
└── README.md
```

---

## Tools & Libraries Used

### Phase 2 (Analytical):
- **Python Libraries**: `NumPy`, `SciPy`, `Matplotlib`

### Phase 3 (Simulation):
- **CAD Modeling**: SolidWorks
- **Motion Simulation**: MSC Adams

---

## Future Scope: AI/ML Integration

- **Motion Prediction**: Use simulation data to train ML models that predict motion from crank inputs.
- **Inverse Kinematics**: Leverage supervised learning to predict required crank angles for desired outputs.
- **Automated Tuning**: Use optimization algorithms or ML models to fine-tune parameters for ideal motion profiles.

---

## Final Thoughts

This project provided a deep dive into the **computational analysis of mechanical systems**, combining the strengths of **AI/ML tools** (via Python) with industry-standard mechanical design and simulation software. As a student passionate about **both Mechanical Engineering and Machine Learning**, this hands-on experience highlighted the exciting potential of integrating these fields—motivating me to explore further innovations at their intersection.

