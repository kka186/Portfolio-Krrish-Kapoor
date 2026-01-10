# 👋 Hi, I’m Krrish Kapoor

🎓 **Mechatronic Systems Engineering Student**  
📍 Langley, BC | Simon Fraser University  
🛠️ Mechanical • Electrical • Computational Systems

I’m a Mechatronics Engineering student with a strong interest in modeling, analyzing, and designing multidisciplinary systems that integrate mechanical structures, electrical circuits, and computational tools. My experience spans structural mechanics, dynamic systems, circuit analysis, and experimental validation using both simulation and real-world measurements.

---

## 🔧 Technical Skills

**Programming & Computation**
- Python
- MATLAB

**Engineering Tools**
- Multisim
- Granta EduPack
- Arduino

---

## 📌 Projects

---

# ✈️ Mechanical Analysis of a Cessna 172 Aircraft Wing

<details>
  <summary><b>What?</b> (click to expand)</summary>
  <br>

  I analyzed the structural integrity of a Cessna 172 wing spar under a conservative loading case (⅓ max takeoff weight) to identify the critical section and assess safety under bending and shear.

  <p align="center">
    <img src="images/wing_geometry.png" width="48%" />
    <img src="images/wing_geometry_alt.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> Wing geometry & loading &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> Boundary conditions & constraints</sub>
  </p>
</details>

<details>
  <summary><b>How?</b> (click to expand)</summary>
  <br>

  The wing was simplified into a beam with pinned–strut support. Reaction forces were solved using equilibrium and compatibility equations, followed by shear force and bending moment calculations using Macaulay’s method. Stresses at the critical section were evaluated using Mohr’s Circle and Tresca/Von Mises criteria.

  <p align="center">
    <img src="images/wing_fbd.png" width="48%" />
    <img src="images/mohrs_circle.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> Free-body diagram & reactions &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> Mohr’s Circle stress analysis</sub>
  </p>
</details>

<details>
  <summary><b>Result</b> (click to expand)</summary>
  <br>

  The baseline design did not meet safety margin requirements, prompting design improvements involving material and geometric changes. These modifications achieved a target factor of safety of 1.5 while maintaining small wingtip deflection.

  <p align="center">
    <img src="images/bending_moment.png" width="48%" />
    <img src="images/deflection_plot.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> Bending moment distribution &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> Wing deflection results</sub>
  </p>
</details>

---

# ⚡ Transient Response Analysis of RC & RL Circuits (Lab + Multisim)

<details>
  <summary><b>What?</b> (click to expand)</summary>
  <br>

  This project investigated the transient response of first-order RC and RL circuits subjected to step inputs, focusing on time constants and agreement between theory, simulation, and experiment.

  <p align="center">
    <img src="images/rc_step_setup.png" width="48%" />
    <img src="images/rl_step_setup.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> RC circuit setup &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> RL circuit setup</sub>
  </p>
</details>

<details>
  <summary><b>How?</b> (click to expand)</summary>
  <br>

  Voltage and current responses were measured during step excitation, and time constants were extracted using the 63.2% method. Multisim was used to simulate circuit behavior, and Thevenin equivalents were applied to simplify resistor networks.

  <p align="center">
    <img src="images/multisim_model.png" width="48%" />
    <img src="images/thevenin_equivalent.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> Multisim simulation &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> Thevenin reduction</sub>
  </p>
</details>

<details>
  <summary><b>Result</b> (click to expand)</summary>
  <br>

  Experimental results closely matched theoretical predictions, confirming the validity of first-order models. Small discrepancies were attributed to component tolerances, measurement limitations, and non-ideal behavior.

  <p align="center">
    <img src="images/rc_charging_plot.png" width="48%" />
    <img src="images/rl_current_plot.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> RC charging response &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> RL current response</sub>
  </p>
</details>

---

# 🧠 Modelling of Mechatronic Systems Using Mechanical–Electrical Analogies

<details>
  <summary><b>What?</b> (click to expand)</summary>
  <br>

  I studied the dynamic response of a mass–spring–damper system and a flexible beam under base excitation, then recreated both systems using equivalent RLC circuits to demonstrate mechanical–electrical analogies.

  <p align="center">
    <img src="images/msd_setup.png" width="48%" />
    <img src="images/beam_setup.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> MSD experimental setup &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> Flexible beam setup</sub>
  </p>
</details>

<details>
  <summary><b>How?</b> (click to expand)</summary>
  <br>

  Time- and frequency-domain response data were used to estimate natural frequency and damping ratio. MATLAB models were developed for validation, and mechanical parameters were mapped to equivalent RLC circuit components.

  <p align="center">
    <img src="images/rlc_mapping.png" width="48%" />
    <img src="images/matlab_model.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> Mechanical–electrical mapping &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> MATLAB simulation</sub>
  </p>
</details>

<details>
  <summary><b>Result</b> (click to expand)</summary>
  <br>

  The electrical analog models successfully reproduced key features of the mechanical response, including resonance and damping trends. Differences highlighted the impact of friction and real-world non-idealities.

  <p align="center">
    <img src="images/frequency_response.png" width="48%" />
    <img src="images/phase_response.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> Frequency response &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> Phase response</sub>
  </p>
</details>

---

# 🧱 Materials Selection: Aircraft Turbine Fan Blade (Granta EduPack + Eco Audit)

<details>
  <summary><b>What?</b> (click to expand)</summary>
  <br>

  The objective was to select an optimal material for an aircraft turbine fan blade while balancing performance, cost, and environmental impact.

  <p align="center">
    <img src="images/edupack_overview.png" width="48%" />
    <img src="images/design_constraints.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> EduPack workflow &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> Design constraints</sub>
  </p>
</details>

<details>
  <summary><b>How?</b> (click to expand)</summary>
  <br>

  Candidate materials were screened using mechanical and thermal constraints, ranked using weighted criteria, and evaluated using Eco Audit lifecycle analysis.

  <p align="center">
    <img src="images/material_chart.png" width="48%" />
    <img src="images/weighted_ranking.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> Material selection chart &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> Weighted ranking results</sub>
  </p>
</details>

<details>
  <summary><b>Result</b> (click to expand)</summary>
  <br>

  Nickel-based superalloys ranked highest overall due to their balance of fatigue resistance, temperature capability, cost, and environmental performance. Alternative materials were identified for different design priorities.

  <p align="center">
    <img src="images/eco_audit.png" width="48%" />
    <img src="images/final_comparison.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> Eco-Audit results &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> Final material comparison</sub>
  </p>
</details>


---

## 📫 Contact & Links

- 💼 LinkedIn: *https://www.linkedin.com/in/krrish-kapoor-957b07310/*
- 📧 Email: kka186@sfu.ca

---

⭐ *Thanks for visiting my GitHub. I’m always open to learning, collaborating, and improving my engineering skills.*
