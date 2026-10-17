<h1 align="center">Aditya Kaul</h1>

<p align="center">
  <strong>Applied Mathematics · Computational Physics · Research</strong>
</p>

<p align="center">
  Modeling complex systems. Asking better questions.
</p>

<p align="center">
  <a href="#about">About</a> &nbsp; / &nbsp;
  <a href="#selected-research">Research</a> &nbsp; / &nbsp;
  <a href="#research-archive">Archive</a> &nbsp; / &nbsp;
  <a href="#leadership-and-debate">Debate</a> &nbsp; / &nbsp;
  <a href="#contact">Contact</a>
</p>

---

<!--
EDITING GUIDE — this comment will not appear on the page.

1. Replace the [Add ...] and [Insert ...] placeholders.
2. Use [Link label](https://your-link-here) to add a link.
3. To add an image, upload it to the repository and use:
   ![A description of the image](assets/your-image.png)
4. Leave the image examples below commented out until you upload images.
5. Add exact manuscript titles, authorship, dates, and current status.
6. Remove any project or section you do not want to feature.
-->

## About

I'm **Aditya Kaul**, a student at Washington High School interested in the intersection of **mathematics, physics, and computation**.

Through ASDRP, I work on computational physics and numerical methods. My interests extend from modeling fluids and plasmas to studying satellite observations through NASA SEES and astrophysical energy extraction through Horizon.

I like questions that need both a mathematical explanation and a careful test. Outside research, I'm a parliamentary debater and team captain, a math tutor, and a tennis player.

| Area | Work |
| :--- | :--- |
| **Numerical methods** | ASDRP researcher and group lead; AEGIS development and computational physics |
| **Earth observation** | NASA SEES; satellite data, land cover, and ground observations |
| **Astrophysics** | Horizon Academic Research Program; active galactic nuclei and energy extraction |
| **Leadership** | Captain of Washington High School's parliamentary debate team |

<!-- Optional: add a short personal paragraph about what motivates your work. -->

---

## Selected Research

### 01 / AEGIS

**Adaptive Edge-Guided Interface Scheme**  
*ASDRP · Numerical methods · Computational fluid dynamics*

A numerical method designed around a central challenge: preserving accuracy in smooth flow while remaining stable near shocks.

**The question**

How can a solver retain high-order accuracy without producing unstable behavior around sharp discontinuities?

**The approach**

AEGIS adaptively blends fifth-order and low-order numerical fluxes according to local flow smoothness. A modified Jameson–Schmidt–Turkel discontinuity sensor and a Weibull mapping determine the interface weights.

**My contribution**

[Add the components you designed, implemented, tested, and wrote. Identify collaborators and their contributions where appropriate.]

**Results**

- [Add a benchmark, comparison method, grid resolution, and measured result.]
- [Add an accuracy, stability, or computational-cost finding with its test conditions.]
- [Add a limitation or next step.]

**Figure**

[Add a convergence plot or shock-tube comparison. Explain the axes and the main takeaway.]

<!--
![AEGIS comparison showing the reference solution and numerical results](assets/aegis-results.png)
-->

**Materials:** [Add manuscript link] · [Add code link] · [Add poster link]

---

### 02 / Extending AEGIS to Ideal MHD

**Adaptive methods for magnetized flows**  
*ASDRP · Magnetohydrodynamics · 1D3V*

Extending the AEGIS framework to a system where fluid motion and magnetic fields evolve together.

**The question**

Can adaptive edge-guided flux blending resolve the interacting wave families of ideal magnetohydrodynamics?

**The approach**

Extend the method to the one-dimensional, three-component-velocity ideal-MHD equations. Evaluate the high-order/low-order balance in smooth regions and near strong discontinuities.

**My contribution**

[Add your role in developing the extension, implementing the solver, verifying results, and preparing the presentation.]

**Results**

- [Add the MHD test problem and reference solution.]
- [Add your main observation and a quantitative comparison where available.]
- [Add limitations or unresolved behavior.]

**Figure**

[Add a density, pressure, velocity, or magnetic-field comparison and explain what it demonstrates.]

<!--
![Ideal-MHD results compared with a reference solution](assets/mhd-results.png)
-->

**Materials:** [Add manuscript link] · [Add code link] · [Add URTC poster link]

---

### 03 / Computational Propulsion

**Modeling electric-propulsion systems**  
*ASDRP · Plasma dynamics · Simulation*

Using computational models to investigate the physics of electric propulsion.

**The question**

[Add the precise Hall-thruster or propulsion question investigated.]

**The approach**

[Describe the physical model, assumptions, numerical method, and validation process.]

**My contribution**

[Explain what you independently implemented, analyzed, or wrote, with appropriate collaborator credit.]

**Results**

- [Add the main simulation result and its physical interpretation.]
- [Add a validation comparison or measured trend.]
- [Add a limitation or next research question.]

**Figure**

[Add a simulation image or result plot with units and a descriptive caption.]

<!--
![Propulsion simulation showing the quantity discussed in the results](assets/propulsion-results.png)
-->

**Materials:** [Add paper link] · [Add code link] · [Add presentation link]

---

### 04 / Ground Truth

**Satellite observations, checked on Earth**  
*NASA SEES · Remote sensing · Land-cover analysis*

Comparing satellite-derived land-cover information with field observations to understand where classifications diverge.

**The question**

Where do satellite classifications and observations on the ground disagree, and what might explain the discrepancies?

**The approach**

Compare NASA satellite data with ground observations, investigate classification errors, and consider potential ways to improve the interpretation of remote-sensing products.

[Add the exact dataset, study region, sampling process, and analytical method.]

**My contribution**

Satellite-data analysis and writing on remote-sensing errors and potential solutions.

[Add your exact role, collaborators, and scope of work.]

**Results**

- [Add a specific land-cover finding and the size of the analyzed sample.]
- [Add an error pattern or discrepancy supported by your analysis.]
- [Add a proposed explanation, recommendation, or limitation.]

**Figure**

[Add a study-area map, comparison plot, or confusion matrix. Identify the dataset and source.]

<!--
![Comparison of satellite land-cover classifications and ground observations](assets/sees-results.png)
-->

**Materials:** [Add manuscript link] · [Add poster link] · [Add project materials]

---

### 05 / Astrophysical Energy Extraction

**Investigating the power behind active galactic nuclei**  
*Horizon Academic Research Program · Astrophysical plasma dynamics*

Studying mechanisms that help explain some of the universe's most energetic outflows.

**The question**

How do black-hole energy-extraction mechanisms help explain the power of active galactic nuclei and their jets?

**The approach**

Investigate Blandford–Znajek energy extraction and magnetic reconnection in the context of astrophysical plasma dynamics.

[Specify whether your paper is a literature review, theoretical analysis, or computational study, and describe the scope.]

**My contribution**

Research and manuscript writing through Horizon.

[Add the precise work you completed independently and your advisor's role.]

**Findings**

- [Add the central conclusion and the evidence supporting it.]
- [Add an important distinction between the mechanisms.]
- [Add a limitation or open question.]

**Figure**

[Add a schematic or comparison. Credit any adapted figure and its original source.]

<!--
![Schematic illustrating the energy-extraction mechanisms discussed in the paper](assets/agn-figure.png)
-->

**Materials:** [Add manuscript link] · [Add supporting materials]

---

### 06 / Independent Numerical Solvers

**Computational experiments in applied mathematics**  
*Independent projects · Differential equations · Mathematical modeling*

Exploring how differential equations connect problems in thermodynamics, chemistry, and economics.

**Featured problem**

[Choose one solver and state the real-world question its equation models.]

**Implementation**

[Name the equation, solver, initial or boundary conditions, and the method used to check the implementation.]

**Results**

- [Add a computed result and compare it with an analytical or reference solution.]
- [Add a finding about step size, error, convergence, or model behavior.]

<!--
![Numerical solution and error comparison](assets/solver-results.png)
-->

**Materials:** [Add repository link] · [Add notebook link] · [Add write-up]

---

## Research Archive

Manuscripts, posters, and presentations associated with my research.

| Work | Year | Venue / Format | Current Status | Materials |
| :--- | :--- | :--- | :--- | :--- |
| **AEGIS** — [Insert exact manuscript title] | 2026 | IEEE ICRAMI / [Add details] | [Add current status] | [Add link] |
| **Ideal-MHD extension** — [Insert exact poster title] | 2026 | MIT URTC / Virtual poster | [Add date and status] | [Add link] |
| **Computational propulsion** — [Insert exact paper title] | 2025 | [Add exact venue] | [Add publication status / DOI] | [Add link] |
| **NASA SEES** — [Insert exact manuscript title] | 2026 | [Add journal / conference / archive] | [Add current status] | [Add link] |
| **Astrophysical jets** — [Insert exact manuscript title] | [Year] | [Add journal / archive] | [Add current status] | [Add link] |

<!--
Add complete author lists and formal citations below if desired.
Keep submitted, accepted, presented, preprint, and published statuses precise.
-->

---

## Leadership and Debate

**Captain · Washington High School Parliamentary Debate**

I compete in parliamentary debate and serve as captain of my school's team. Debate gives me another setting for analytical thinking: responding quickly, examining assumptions, and making complicated arguments clear.

In research and debate alike, I care about what happens when an idea meets a difficult question.

### Selected Results

| Result | Tournament | Year |
| :--- | :--- | :--- |
| **Winner** — team | Ryan Mills SVUDL Tournament | 2026 |
| **#1 Speaker** — individual | NYPDL September Online Invitational | 2025 |
| **#7 Speaker** — individual | UC Berkeley Cal Parli Invitational | 2025 |
| **Finalist** — team | Stephen Stewart Memorial Invitational | 2025 |

### Team Leadership

[Add what you do as captain: training, practice coordination, mentoring, preparation, or team-building. Include specific examples.]

---

## Beyond Research

### Teaching

I tutor SAT Math through **Schoolhouse.world**. Explaining a problem clearly is its own test of understanding.

[Add a teaching story, tutoring impact, or profile link.]

### Tennis

Tennis gives me a different kind of feedback loop: prepare, adapt, and stay with the point in front of me.

[Add your team, role, or a personal detail.]

### Other Interests

Cricket conversations, Quiz Bowl, and questions that refuse to stay inside one subject.

[Add the interests or personal details you most want people to know.]

---

## Contact

For questions about a project, research conversations, or a good mathematical puzzle:

- **Email:** [Add your email]
- **Personal GitHub:** [Add your personal profile link]
- **Research GitHub:** [Add your research profile link]
- **ORCID:** [Add your ORCID link]
- **Résumé / CV:** [Add a PDF link]

<!--
For clickable links, replace the relevant placeholder with:

[Email me](mailto:your-email@example.com)
[Personal GitHub](https://github.com/YOUR-USERNAME)
[Research GitHub](https://github.com/YOUR-RESEARCH-USERNAME)
[Résumé / CV](assets/resume.pdf)
-->

---

<p align="center">
  <sub>Aditya Kaul · Research / Mathematics / Physics</sub>
</p>
