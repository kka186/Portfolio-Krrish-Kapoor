# 👋 Hi, I’m Krrish Kapoor

🎓 **Mechatronic Systems Engineering Student**  
📍 Langley, BC | Simon Fraser University  
 Mechanical • Electrical • Computational Systems

I’m a Mechatronics Engineering student with a strong interest in modeling, analyzing, and designing multidisciplinary systems that integrate mechanical structures, electrical circuits, and computational tools. My experience spans structural mechanics, dynamic systems, circuit analysis, and experimental validation using both simulation and real-world measurements.

---

## Technical Skills

**Programming & Computation**
- Python
- MATLAB

**Engineering Tools**
- Multisim
- Granta EduPack
- Arduino

---

## Projects

---

# Mechanical Analysis of a Cessna 172 Aircraft Wing

<details>
  <summary><b>What?</b></summary>
  <br>

  Analyzed the structural integrity of a Cessna 172 wing spar under a conservative loading case (⅓ maximum takeoff weight) to identify the critical section governing bending and shear behavior.

  <p align="center">
    <img src="images/Cessna 172 Wing/wing_model.png" width="48%" />
    <img src="images/Cessna 172 Wing/wing_properties.png" width="48%" />
  </p>
  <p align="center">
    <sub>Overall wing geometry (left) and material properties used in analysis (right).</sub>
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Simplified the wing into an equivalent beam with pinned–strut support. Solved reaction forces using equilibrium and compatibility, then derived shear force and bending moment distributions using Macaulay’s method. Evaluated stresses using Mohr’s Circle and ductile failure criteria.

  <p align="center">
    <img src="images/Cessna 172 Wing/fbd_front.png" width="48%" />
    <img src="images/Cessna 172 Wing/fbd_forces.PNG" width="48%" />
  </p>
  <p align="center">
    <sub>Free-body diagram of wing loading (left) and internal force breakdown for beam model (right).</sub>
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  Identified insufficient safety margin in the baseline design and justified design improvements. Final outputs highlight the governing load region and internal force distribution.

  <p align="center">
    <img src="images/Cessna 172 Wing/bending.png" width="48%" />
    <img src="images/Cessna 172 Wing/shear.png" width="48%" />
  </p>
  <p align="center">
    <sub>Bending moment distribution (left) and shear force distribution along the wing span (right).</sub>
  </p>
</details>

---

# Transient Response of RC Circuits (Experimental)

<details>
  <summary><b>What?</b></summary>
  <br>

  Experimentally measured the transient response of first-order RC circuits subjected to step inputs to determine time constants and compare real behavior with theoretical models.

  <p align="center">
    <img src="images/Transient Response of RC Circuits/circuit_schematic.png" width="85%" />
  </p>
  <p align="center">
    <sub>Physical RC circuit used for step-response testing.</sub>
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Applied step excitation to the circuit and recorded voltage response. Extracted time constants using exponential response landmarks and compared results to predicted values.

  <p align="center">
    <img src="images/Transient Response of RC Circuits/time_constant.png" width="85%" />
  </p>
  <p align="center">
    <sub>Measured charging curve with extracted time constant.</sub>
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  Verified first-order transient behavior in hardware and quantified deviations caused by component tolerances and measurement limitations.
</details>

---

# Transient Response of Multi-Resistor RC Circuits Using Multisim

<details>
  <summary><b>What?</b></summary>
  <br>

  Investigated how resistor network topology affects the transient response of an RC circuit by analyzing a multi-resistor configuration.

  <p align="center">
    <img src="images/Transient Response of Multi-Resistor RC Circuits Using Multisim/multisim_circuit.png" width="85%" />
  </p>
  <p align="center">
    <sub>Multisim schematic of the multi-resistor RC circuit.</sub>
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Applied step excitation within Multisim and analyzed voltage response. Compared simulated behavior with hand calculations using equivalent resistance methods.

  <p align="center">
    <img src="images/Transient Response of Multi-Resistor RC Circuits Using Multisim/circuit_schematic.png" width="85%" />
  </p>
  <p align="center">
    <sub> Simplified circuit representation used for analytical modeling.</sub>
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  Extracted an effective time constant from simulation and demonstrated how network topology alters transient response.

  <p align="center">
    <img src="images/Transient Response of Multi-Resistor RC Circuits Using Multisim/time_constant.png" width="85%" />
  </p>
  <p align="center">
    <sub> Simulated step-response curve with effective time constant.</sub>
  </p>
</details>

---

# Modelling of Mechatronic Systems Using Mechanical–Electrical Analogies

<details>
  <summary><b>What?</b></summary>
  <br>

  Modeled the dynamics of a mass–spring–damper system and represented it using an equivalent RLC electrical circuit.

  <p align="center">
    <img src="images/Electrical Analogies/oscar.png" width="48%" />
    <img src="images/Electrical Analogies/FBD_MSD.png" width="48%" />
  </p>
  <p align="center">
    <sub>Physical MSD setup (left) and corresponding free-body diagram (right).</sub>
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Identified natural frequency and damping from response trends, then mapped mechanical parameters to electrical components.

  <p align="center">
    <img src="images/Electrical Analogies/rlc_conversion.png" width="85%" />
  </p>
  <p align="center">
    <sub>Mechanical-to-electrical parameter mapping for RLC analog.</sub>
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  Electrical analog reproduced resonance and phase behavior observed in the mechanical system.

  <p align="center">
    <img src="images/Electrical Analogies/magnitude_freq.png" width="48%" />
    <img src="images/Electrical Analogies/phase_freq.png" width="48%" />
  </p>
  <p align="center">
    <sub>Frequency-response magnitude (left) and phase plot (right).</sub>
  </p>
</details>

---

# Materials Selection: Aircraft Turbine Fan Blade

<details>
  <summary><b>What?</b></summary>
  <br>

  Selected a turbine fan blade material by balancing mechanical performance, cost, and environmental impact.

  <p align="center">
    <img src="images/Aircraft Turbine Fan Blade/blade_cavity.png" width="85%" />
  </p>
  <p align="center">
    <sub>Fan blade geometry and cavity region considered in material selection.</sub>
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Screened materials using engineering constraints and ranked finalists using material charts and Eco Audit lifecycle analysis.

  <p align="center">
    <img src="images/Aircraft Turbine Fan Blade/naturalfreq_tensile_stress.png" width="85%" />
  </p>
  <p align="center">
    <sub>Material screening chart comparing natural frequency and tensile stress limits.</sub> 
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  Identified a top-ranked material and justified the selection using combined performance and sustainability metrics.

  <p align="center">
    <img src="images/Aircraft Turbine Fan Blade/material_table.png" width="48%" />
    <img src="images/Aircraft Turbine Fan Blade/nickelbased_superalloy.png" width="48%" />
  </p>
  <p align="center">
    <sub>Final material property comparison table (left) and selected nickel-based superalloy (right).</sub>
  </p>
</details>


---

## 📫 Contact & Links

- 💼 LinkedIn: *https://www.linkedin.com/in/krrish-kapoor-957b07310/*
- 📧 Email: kka186@sfu.ca

---


