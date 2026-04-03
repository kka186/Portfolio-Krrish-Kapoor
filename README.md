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
- TypeScript
- Git

**Engineering Tools**
- Multisim
- Granta EduPack
- Arduino
- AutoCAD

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

  Using MATLAB and Simulink with given codes, we gave a step input to OSCAR where a response would be shown on a graph through the software. We took multiple trials using different spring constants and settled with one trial using 1226N/m as the spring constant. We extracted system parameters using the logarthmic decrement method and mapped these parameters to equivalent RLC circuit values. The beam would have its own RLC values creating a parallel circuit with the MSD values. The circuits voltages were measured in a way where CH 1 was the MSD's capacitor voltage and CH 2 was the beam's capacitor voltage. Furthermore, square and sine wave inputs at differing frequencies were used to analyze the amplitudes and phase shifts among the frequency response.   

  <p align="center">
    <img src="images/Electrical Analogies/rlc_conversion.png" width="85%" style="border:1px solid #aaa; padding:4px;" /><br>
    <sub>Mechanical-to-electrical parameter mapping for RLC analog.</sub>
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  The system evidently provided an underdamped response mapping an equivalent RLC circuit shown in the above section. The amplitudes measured from the oscilloscope under sine wave excitations yielded a maximum amplitude of 840mV at 500Hz for Channel 1 and 32.8mV at 7000Hz for Channel 2. The maximum phase shift obtained was 342.2 degrees at 7000Hz.

  <table align="center">
    <tr>
      <td align="center" width="50%">
        <img src="images/Electrical Analogies/amplitude.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Output amplitude of channel 1 and channel 2 versus frequency under a sine wave excitation.</sub>
      </td>
      <td align="center" width="50%">
        <img src="images/Electrical Analogies/phase.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Frequency-dependent phase response across a sine wave excitation.</sub>
      </td>
    </tr>
  </table>
</details>

---

# Verdant - Environmental Monitoring Platform

<details>
  <summary><b>What?</b></summary>
  <br>

  The objective of this project was to design and develop a climate resilience dashboard that helps companies, city agencies, and urban planners identify urban heat islands and make more informed green infrastructure decisions. Verdant was created to transform environmental and geospatial data into an interactive platform for locating high-risk areas and evaluating where cooling interventions may have the greatest impact.

  By combining urban temperature data, regional comparisons, and map-based visualization, the platform provides decision-makers with a clear view of climate-related conditions across a city. The project focused on making large-scale environmental data accessible and actionable through an interface that supports climate-conscious planning.

  <p align="center">
    <img src="images/Verdant/landing-page.png" width="85%" style="border:1px solid #aaa; padding:4px;" /><br>
    <sub>Verdant landing page introducing the platform’s focus on climate resilience and urban heat analysis.</sub>
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Verdant was developed by combining open-source environmental data, geospatial mapping tools, and an interactive web interface into a single climate analysis platform. Public satellite and sensor APIs from NASA were used to evaluate urban temperature conditions, while 3D map-based visualization displayed heat-risk patterns, hotspot zones, vulnerable areas, and potential green infrastructure opportunities.

  The platform was structured as a web-based dashboard so that complex climate data could be translated into a format that companies, agencies, and planning stakeholders could use effectively. Interactive layers, charts, and recommendation panels were incorporated to help users compare regions, assess projected cooling impacts, and identify where infrastructure investments may provide the greatest benefit.

  <table align="center">
    <tr>
      <td align="center" width="50%">
        <img src="images/Verdant/how-layer-dashboard.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Dashboard view showing map layers, geospatial heat mapping, and hotspot analysis.</sub>
      </td>
      <td align="center" width="50%">
        <img src="images/Verdant/how-3d-dashboard.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>3D visualization used to analyze hotspot zones and infrastructure opportunities.</sub>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  The final outcome of this project was a functional climate resilience dashboard capable of visualizing urban heat patterns, identifying hotspot zones, and presenting green infrastructure recommendations through an interactive interface. Verdant translated raw environmental and geospatial data into a usable planning tool for comparing regions, evaluating vulnerability, and assessing where cooling strategies may provide the greatest benefit.

  The completed platform demonstrated a practical application of environmental data analysis, geospatial visualization, and user-focused dashboard design. Verdant was recognized at XHacks 2026, where it received the **[SFU SURGE] Systems for Scale** award.

  <p align="center">
    <img src="images/Verdant/result-dashboard.png" width="85%" style="border:1px solid #aaa; padding:4px;" /><br>
    <sub>Final Verdant dashboard showing hotspot mapping, environmental metrics, and green infrastructure recommendations.</sub>
  </p>
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
    <sub>Multi-resistor RC circuit schematic with a dependent source.</sub>
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  An applied step excitation to the circuit created in Multisim was used to further analyze the charging behaviour and obtain the time constant of the system. Using voltage and time cursors on the oscilliscope would then yield the effective time constant of the system. To validate theoretical predictions, I compared simulated behavior with hand calculations using equivalent resistance methods.

  <p align="center">
    <img src="images/Transient Response of Multi-Resistor RC Circuits Using Multisim/circuit_schematic.png" width="85%" style="border:1px solid #aaa; padding:4px;" /><br>
    <sub>Multisim circuit schematic with the function generator and oscilloscope connected.</sub>
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  The time constant came out to be 400ms and matched theoretical predictions with zero percent error.

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

  Analyzed the structural integrity of a Cessna 172 wing spar under a conservative loading case (⅓ maximum takeoff weight) to identify the critical section governing bending and shear behavior. We also must evaluate whether our component will fail due to internal stresses during flight and the mode of failure. 

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

  Simplified the wing into an equivalent beam with pinned–strut support, which enabled us to solve reaction forces using equilibrium and compatibility equations. We also assumed drag to be negligible and that the lift force was uniform along the surface of the wing for ease of analysis. We then derived shear force and bending moment distributions using Macaulay’s method and evaluated stresses using Mohr’s Circle and ductile failure criteria. 

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

  We found the critical point where the most bending and shear stress on the wing would be at x=1.7m (just before the wing strut). From our Mohr's circle stress and deformation calculations the wing would fail due to yielding as the component had a factor of safety of 0.66. We proposed design improvements including the usage of carbon fibre, or a higher yield strength of aluminum to prevent failure. 

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

  Selected an optimal material for a commercial aircraft turbine fan blade to minimize weight while meeting safety, durability, cost, thermal, and environmental constraints. 

  <p align="center">
    <img src="images/Aircraft Turbine Fan Blade/blade_cavity.png" width="85%" style="border:1px solid #aaa; padding:4px;" /><br>
    <sub>Simplified fan blade geometry and cavity region considered during material selection.</sub>
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

 Modelled the blade with simplified geometry and screened 5 candidate materials in Granta EduPack 2024 R2 using constraint thresholds (e.g., max service temperature, fracture toughness), property charts (natural frequency vs allowable stress/density), and a weighted multi-criteria score across frequency, fracture toughness, price, density, and service temperature.   

  <p align="center">
    <img src="images/Aircraft Turbine Fan Blade/naturalfreq_tensile_stress.png" width="85%" style="border:1px solid #aaa; padding:4px;" /><br>
    <sub>Material screening chart comparing natural frequency and tensile stress limits.</sub>
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

Identified Nickel-based superalloys as the best overall choice (balanced fatigue/temperature performance and acceptable environmental impact), with tungsten carbide as highest-performing but environmentally costly due to density, and high-carbon steel as a budget option with weaker high-temp/fatigue suitability. 

  <table align="center">
    <tr>
      <td align="center" width="50%">
        <img src="images/Aircraft Turbine Fan Blade/material_table.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Final material property comparison table.</sub>
      </td>
      <td align="center" width="50%">
        <img src="images/Aircraft Turbine Fan Blade/nickelbased_superalloy.png" width="95%" style="border:1px solid #aaa; padding:4px;" /><br>
        <sub>Nickel-based superalloy environmental effects chart.</sub>
      </td>
    </tr>
  </table>
</details>

---

## 📫 Contact & Links

- 💼 LinkedIn: *https://www.linkedin.com/in/krrish-kapoor-957b07310/*
- 📧 Email: kka186@sfu.ca

---


