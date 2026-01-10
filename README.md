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

> Tip: Put your images in `/images/` and reference them like `images/filename.png`.
/images/
cad_model_of_wing.png
material_properties.png
wing_fbd_front.png
wing_fbd_beam.png
bending_moment.png
shear_force.png

---

# ✈️ Mechanical Analysis of a Cessna 172 Aircraft Wing

<details>
  <summary><b>What?</b> (click to expand)</summary>
  <br>

  The objective of this project was to analyze the structural integrity of a Cessna 172 wing spar under a conservative loading case (⅓ maximum takeoff weight). The goal was to determine whether the wing could safely withstand bending and shear stresses and to identify the critical section governing failure.

  <p align="center">
    <img src="images/wing_cad.png" width="48%" />
    <img src="images/material_properties.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> CAD model of the wing geometry &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> Material property comparison (2024-T3 Aluminum vs Fibreglass)</sub>
  </p>
</details>

<details>
  <summary><b>How?</b> (click to expand)</summary>
  <br>

  The wing was simplified into a beam with pinned–strut support to represent realistic load transfer. Reaction forces were solved using equilibrium and compatibility equations, followed by shear force and bending moment derivations using Macaulay’s method. Internal stresses were evaluated at the critical section using Mohr’s Circle and Tresca/Von Mises failure criteria.

  <p align="center">
    <img src="images/wing_fbd_front.png" width="48%" />
    <img src="images/wing_fbd_beam.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> Free-body diagram of wing loading &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> Equivalent beam model with forces and moments</sub>
  </p>
</details>

<details>
  <summary><b>Result</b> (click to expand)</summary>
  <br>

  The baseline design was found to have a factor of safety below acceptable limits, indicating yielding risk under the applied loading. Design improvements involving material substitution and geometric changes were proposed, targeting a factor of safety of 1.5 while maintaining acceptable deflection and load distribution.

  <p align="center">
    <img src="images/bending_moment.png" width="48%" />
    <img src="images/shear_force.png" width="48%" />
  </p>

  <p align="center">
    <sub><b>Left:</b> Bending moment distribution along the wing span &nbsp;&nbsp;|&nbsp;&nbsp; <b>Right:</b> Shear force distribution along the wing</sub>
  </p>
</details>



---

## 🚀 Interests & Focus Areas

- Mechatronic system design
- Mechanical–electrical system modeling
- Dynamic systems and vibrations
- Embedded and hardware-interfacing projects
- Engineering analysis backed by experimentation

I enjoy projects where theory, simulation, and real-world behavior come together.

---

## 📫 Contact & Links

- 💼 LinkedIn: *(add link)*
- 📧 Email: kka186@sfu.ca

---

⭐ *Thanks for visiting my GitHub. I’m always open to learning, collaborating, and improving my engineering skills.*
