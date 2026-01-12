# 👋 Hi, I’m Krrish Kapoor

🎓 **Mechatronic Systems Engineering Student**  
📍  Langley, BC | Simon Fraser University  
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

# Modelling of Mechatronic Systems Using Mechanical–Electrical Analogies

<details>
  <summary><b>What?</b></summary>
  <br>

 The objective of this project was to model and predict the dynamic response of a coupled mechanical system subjected to base excitation, and to demonstrate that its behavior can be accurately represented using an equivalent electrical circuit.

A mass–spring–damper (MSD) system and a flexible vertical beam were experimentally and numerically characterized to extract key system parameters such as natural frequency and damping ratio. These mechanical systems were then converted into equivalent RLC circuits, allowing the same dynamic behavior to be analyzed in the electrical domain. The final goal was to validate that the combined MSD–beam system and its electrical analog exhibit consistent transient and frequency-response characteristics under base excitation.

  <table align="center">
    <tr>
      <td align="center" width="50%">
        <img src="images/Electrical Analogies/oscar.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Physical mass–spring–damper system (OSCAR) experimental setup.</sub>
      </td>
      <td align="center" width="50%">
        <img src="images/Electrical Analogies/FBD_MSD.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Free-body diagram of the beam and OSCAR (one spring) used for dynamic modeling.</sub>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Using MATLAB and Simulink with given codes, we gave a step input to OSCAR where a response would be shown on a graph through the software. We took multiple trials using different spring constants and settled with one trial using 1226N/m as the spring constant. We extracted system parameters using the logarthmic decrement method and mapped these parameters to equivalent RLC circuit values. The beam would have its own RLC values creating a parallel circuit with the MSD values. The circuits voltages were measured where CH 1 was the MSD's capacitor voltage and CH 2 was the beam's capacitor voltage and square and sine wave inputs at differing frequencies were used to analyze the amplitudes and phase shifts among the frequency response.   

  <p align="center">
    <img src="images/Electrical Analogies/rlc_conversion.png" width="85%" style="border:1px solid #aaa; padding:4px;" /><br>
    <sub>Mechanical-to-electrical parameter mapping for RLC analog.</sub>
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  Electrical analog reproduced resonance and phase behavior observed in the mechanical system.

  <table align="center">
    <tr>
      <td align="center" width="50%">
        <img src="images/Electrical Analogies/magnitude_freq.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Frequency-response magnitude.</sub>
      </td>
      <td align="center" width="50%">
        <img src="images/Electrical Analogies/phase_freq.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Phase response across excitation frequency.</sub>
      </td>
    </tr>
  </table>
</details>

---

# Transient Response of Multi-Resistor RC Circuits Using Multisim

<details>
  <summary><b>What?</b></summary>
  <br>

The objective was to examine the first-order transient response of a multi-resistor circuit containing a dependent source by utilizing Thevenin’s theory to
measure the time constant. The circuit topology included a switch where I must validate discharging and charging behaviour of the system. 
  <p align="center">
    <img src="images/Transient Response of Multi-Resistor RC Circuits Using Multisim/multisim_circuit.png" width="85%" style="border:1px solid #aaa; padding:4px;" /><br>
    <sub>Multisim schematic of the multi-resistor RC circuit.</sub>
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  An applied step excitation to the circuit created in Multisim was used to further analyze the charging behaviour and obtain the time constant of the system. Using voltage and time cursors on the oscilliscope would then yield the effective time constant of the system. To validate theoretical predictions, I compared simulated behavior with hand calculations using equivalent resistance methods.

  <p align="center">
    <img src="images/Transient Response of Multi-Resistor RC Circuits Using Multisim/circuit_schematic.png" width="85%" style="border:1px solid #aaa; padding:4px;" /><br>
    <sub>Simplified circuit representation used for analytical modeling.</sub>
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  The time constant came out to be 400ms and matched theoretical predictions with zero error.

  <p align="center">
    <img src="images/Transient Response of Multi-Resistor RC Circuits Using Multisim/time_constant.png" width="85%" style="border:1px solid #aaa; padding:4px;" /><br>
    <sub>Simulated step-response curve with effective time constant.</sub>
  </p>
</details>

---

# Mechanical Analysis of a Cessna 172 Aircraft Wing

<details>
  <summary><b>What?</b></summary>
  <br>

  Analyzed the structural integrity of a Cessna 172 wing spar under a conservative loading case (⅓ maximum takeoff weight) to identify the critical section governing bending and shear behavior.

  <table align="center">
    <tr>
      <td align="center" width="50%">
        <img src="images/Cessna 172 Wing/wing_model.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Overall wing geometry used for structural modeling.</sub>
      </td>
      <td align="center" width="50%">
        <img src="images/Cessna 172 Wing/wing_properties.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Material properties used in stress and deflection analysis.</sub>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Simplified the wing into an equivalent beam with pinned–strut support. Solved reaction forces using equilibrium and compatibility, then derived shear force and bending moment distributions using Macaulay’s method. Evaluated stresses using Mohr’s Circle and ductile failure criteria.

  <table align="center">
    <tr>
      <td align="center" width="50%">
        <img src="images/Cessna 172 Wing/fbd_front.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Free-body diagram showing applied loads and supports.</sub>
      </td>
      <td align="center" width="50%">
        <img src="images/Cessna 172 Wing/fbd_forces.PNG" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Internal force resolution for the equivalent beam model.</sub>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  Identified insufficient safety margin in the baseline design and justified design improvements. Final outputs highlight the governing load region and internal force distribution.

  <table align="center">
    <tr>
      <td align="center" width="50%">
        <img src="images/Cessna 172 Wing/bending.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Bending moment distribution along the wing span.</sub>
      </td>
      <td align="center" width="50%">
        <img src="images/Cessna 172 Wing/shear.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Shear force distribution along the wing span.</sub>
      </td>
    </tr>
  </table>
</details>

---

# Materials Selection: Aircraft Turbine Fan Blade

<details>
  <summary><b>What?</b></summary>
  <br>

  Selected a turbine fan blade material by balancing mechanical performance, cost, and environmental impact.

  <p align="center">
    <img src="images/Aircraft Turbine Fan Blade/blade_cavity.png" width="85%" style="border:1px solid #aaa; padding:4px;" /><br>
    <sub>Fan blade geometry and cavity region considered during material selection.</sub>
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Screened materials using engineering constraints and ranked finalists using material charts and Eco Audit lifecycle analysis.

  <p align="center">
    <img src="images/Aircraft Turbine Fan Blade/naturalfreq_tensile_stress.png" width="85%" style="border:1px solid #aaa; padding:4px;" /><br>
    <sub>Material screening chart comparing natural frequency and tensile stress limits.</sub>
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  Identified a top-ranked material and justified the selection using combined performance and sustainability metrics.

  <table align="center">
    <tr>
      <td align="center" width="50%">
        <img src="images/Aircraft Turbine Fan Blade/material_table.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Final material property comparison table.</sub>
      </td>
      <td align="center" width="50%">
        <img src="images/Aircraft Turbine Fan Blade/nickelbased_superalloy.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Selected nickel-based superalloy candidate.</sub>
      </td>
    </tr>
  </table>
</details>

---

## 📫 Contact & Links

- 💼 LinkedIn: *https://www.linkedin.com/in/krrish-kapoor-957b07310/*
- 📧 Email: kka186@sfu.ca

---


