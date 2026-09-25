# Motorsport Engineering Project Ideas
**For:** Aerospace Engineering student (K.N. Toosi) aiming at high-performance motorsport (aero/CFD, vehicle performance, WEC/F1 pathway)  
**Tools focus:** Ansys (Fluent, Mechanical, Discovery, Motion), SolidWorks, Python  
**Goal:** Build a strong, documentable portfolio for future motorsport roles.

---

# 1. Aerodynamics & CFD

## 1.1 Simplified Formula Student Front Wing CFD Study
### Description
Design a basic multi-element front wing in SolidWorks following simplified Formula Student aerodynamic constraints. Run a series of Ansys Fluent simulations at different angles of attack and ride heights. Analyse downforce, drag, efficiency (L/D), and key flow features (vortices, separation).
### Tools needed
- SolidWorks (geometry)
- Ansys Fluent or Ansys Discovery
- Python (optional post-processing)
### Skills needed/acquired
- CAD for aerodynamic surfaces
- Meshing strategy for external aero
- RANS turbulence modelling
- Force reporting and flow visualisation
- Basic design of experiments
### Definition of done
- Clean geometry + mesh independence check
- At least 6–8 meaningful operating points simulated
- Clear plots of Cl, Cd, L/D vs AoA / ride height
- Short technical report (8–12 pages) with discussion of flow physics
### How to present
GitHub repository with geometry, key result images, and PDF report. LinkedIn carousel or post showing geometry → mesh → pressure/velocity contours → performance graphs. Mention in Master’s motivation letter as evidence of practical CFD skills.

## 1.2 Diffuser & Ground-Effect Study
### Description
Create a simplified underfloor + diffuser geometry. Investigate the effect of ride height, diffuser angle, and rake on downforce generation and flow structures using Ansys Fluent.
### Tools needed
- SolidWorks
- Ansys Fluent
- Python (data analysis)
### Skills needed/acquired
- Ground-effect aerodynamics
- Boundary layer and vortex management
- Parametric studies
- Interpretation of underbody flow
### Definition of done
- Parametric study with at least 3 ride heights and 3 diffuser angles
- Visualisation of underbody vortices and pressure distribution
- Performance maps (downforce vs ride height)
- Written discussion of real-world motorsport relevance
### How to present
Technical report + GitHub. Strong LinkedIn post comparing different configurations with annotated images.

## 1.3 Wheel and Wheel-Arch Aerodynamics
### Description
Model a rotating wheel (or simplified non-rotating first) and basic wheel arch. Study drag contribution, wake structure, and interaction with the body side.
### Tools needed
- SolidWorks
- Ansys Fluent (MRF or sliding mesh if possible)
### Skills needed/acquired
- Rotating reference frames / moving walls
- Bluff-body wake analysis
- Drag breakdown
### Definition of done
- Comparison of stationary vs rotating wheel
- Clear wake visualisation
- Quantitative drag values and discussion
### How to present
Side-by-side comparison images and short report. Excellent for showing understanding of real open-wheel challenges.

## 1.4 Sidepod / Cooling Inlet Trade-off Study
### Description
Design a simple sidepod with cooling inlet and radiator face. Quantify the external aerodynamic penalty versus internal mass-flow / cooling performance.
### Tools needed
- SolidWorks
- Ansys Fluent
### Skills needed/acquired
- Internal + external flow coupling
- Pressure drop vs mass flow
- Aero-cooling trade-off thinking
### Definition of done
- At least two inlet geometries compared
- Mass-flow and Cd results
- Discussion of motorsport cooling philosophy
### How to present
Report focused on the engineering trade-off. Good portfolio piece showing systems-level thinking.

## 1.5 Turbulence Model & Mesh Sensitivity Study
### Description
Take one baseline geometry (e.g. wing or diffuser) and systematically compare different turbulence models (k-ε, k-ω SST, etc.) and mesh densities in Ansys Fluent.
### Tools needed
- Ansys Fluent
- Python (for plotting comparisons)
### Skills needed/acquired
- CFD verification & validation mindset
- Understanding model limitations
- Mesh independence
### Definition of done
- Clear comparison tables/plots of forces and key flow features
- Recommendation of best practice for the case
- Discussion of computational cost vs accuracy
### How to present
Methodology-focused report. Shows maturity beyond “I ran a simulation”.

## 1.6 Public Race Car Aero Concept Reverse-Engineering
### Description
Using publicly available photos or regulations, create a simplified geometry of a modern WEC Hypercar or F1-inspired concept and run comparative CFD.
### Tools needed
- SolidWorks
- Ansys Fluent
### Skills needed/acquired
- Geometry idealisation from images
- Competitive analysis mindset
### Definition of done
- Recognisable simplified model
- Basic force and flow results
- Commentary on design intent
### How to present
Visually attractive LinkedIn posts + report. Great for networking.

---

# 2. Vehicle Dynamics & Control

## 2.1 Double-Wishbone Suspension Kinematics Study
### Description
Model a double-wishbone (or pushrod) suspension in Ansys Motion or equivalent. Analyse camber gain, roll-centre migration, scrub radius, and anti-dive/anti-squat characteristics across the travel range.
### Tools needed
- SolidWorks (geometry)
- Ansys Motion (or Mechanical with kinematic constraints)
- Python/Excel (data processing)
### Skills needed/acquired
- Suspension kinematics
- Hardpoint sensitivity
- Motorsport setup philosophy
### Definition of done
- Full travel sweep with key kinematic plots
- At least one sensitivity study (e.g. changing a hardpoint)
- Clear explanation of performance implications
### How to present
Report with animated GIFs or sequential images of suspension travel. Strong for vehicle-dynamics interest.

## 2.2 GPU-Accelerated / Efficient Suspension Simulator (User Idea Expanded)
### Description
Build a Python-based or Ansys-coupled suspension solver that can run quickly (explore efficient numerical methods). Simulate response to bump/heave/roll inputs and basic force calculation.
### Tools needed
- Python (NumPy, SciPy)
- Ansys (for validation or multibody)
- Optional: basic GPU libraries later
### Skills needed/acquired
- Numerical methods for dynamics
- Model reduction / efficiency
- Validation against higher-fidelity tools
### Definition of done
- Working simulator with documented equations
- Comparison against Ansys Motion results
- Example manoeuvre results
### How to present
GitHub repo with clean code + Jupyter notebook demonstration + validation report.

## 2.3 Vertical Dynamics & Damper Sensitivity
### Description
Simple quarter-car or half-car model studying the effect of spring rate and damper curves on tyre load variation and body control.
### Tools needed
- Python or Ansys Motion
- Basic optimisation or parameter sweep
### Skills needed/acquired
- Ride/handling trade-off
- Damper curve interpretation
- Frequency response basics
### Definition of done
- Parameter sweeps with clear metrics (e.g. RMS tyre load)
- Discussion of motorsport relevance (kerbs, bumps, aero platform control)
### How to present
Technical note with plots. Links well to aero platform stability.

## 2.4 Basic Vehicle Model with Aero Map Integration
### Description
Create a simple bicycle or 4-DOF vehicle model in Python that accepts an aerodynamic map (from your Fluent work) and shows the effect of downforce on cornering or stability metrics.
### Tools needed
- Python
- Results from previous CFD projects
### Skills needed/acquired
- Vehicle modelling
- Aero-vehicle coupling
- Performance interpretation
### Definition of done
- Working model with documented assumptions
- Example results showing aero influence
- Clear limitations section
### How to present
Combined CFD + dynamics report. Excellent integrated portfolio piece.

## 2.5 Roll and Load Transfer Analysis
### Description
Study lateral load transfer, roll stiffness distribution, and their effect on tyre utilisation using a simplified model.
### Tools needed
- Python / Excel / Ansys
### Skills needed/acquired
- Weight transfer fundamentals
- Setup balance thinking
### Definition of done
- Clear calculations and plots for different balance configurations
- Discussion of understeer/oversteer tendencies
### How to present
Concise technical memo. Good foundational dynamics project.

---

# 3. Structural & Lightweight Design

## 3.1 Rulebook-Based Formula Student Upright
### Description
Design an upright (knuckle) that complies with key Formula Student structural and geometric rules. Optimise for stiffness-to-weight using Ansys Mechanical.
### Tools needed
- SolidWorks
- Ansys Mechanical
- FS rules (publicly available)
### Skills needed/acquired
- Rule-constrained design
- Static + modal analysis
- Lightweighting principles
- Factor of safety in motorsport context
### Definition of done
- Geometry compliant with stated rules
- Mesh independence and stress/modal results
- Weight and stiffness summary
- Iteration history (at least 2–3 versions)
### How to present
Design report with rules checklist, FEA results, and manufacturing considerations. Classic FS-style portfolio piece.

## 3.2 Wishbone / Control Arm Structural Design
### Description
Design and analyse a suspension wishbone under braking, cornering, and combined loads.
### Tools needed
- SolidWorks
- Ansys Mechanical
### Skills needed/acquired
- Load case definition
- Beam vs solid modelling decisions
- Buckling / fatigue awareness
### Definition of done
- Multiple load cases analysed
- Clear safety factors and deflection results
- Design justification
### How to present
Structured FEA report. Pairs well with the kinematics project.

## 3.3 Front Wing Mainplane Structural Analysis
### Description
Take an aerodynamic load from a Fluent simulation and apply it to a structural model of the mainplane. Assess deflection and stress.
### Tools needed
- Ansys Fluent + Ansys Mechanical (or one-way FSI)
- SolidWorks
### Skills needed/acquired
- Aero-structural coupling (one-way)
- Understanding of wing stiffness importance
### Definition of done
- Mapped or equivalent aero loads applied
- Deflection and stress results
- Discussion of acceptable deformation for aero performance
### How to present
Integrated aero-structural report. Shows multi-physics awareness.

## 3.4 Topology Optimisation Study (Simple Bracket or Upright Region)
### Description
Use Ansys topology optimisation on a non-critical bracket or simplified upright region to explore load-path-driven design.
### Tools needed
- Ansys Mechanical
### Skills needed/acquired
- Topology optimisation workflow
- Interpretation and redesign for manufacturability
### Definition of done
- Optimised concept + interpreted redesign
- Comparison of mass and stiffness before/after
### How to present
Before/after visuals + short report. Visually impressive for LinkedIn.

## 3.5 Modal Analysis of a Suspension Component
### Description
Perform modal analysis on an upright or wishbone and discuss potential resonance issues with typical road/kerb inputs.
### Tools needed
- Ansys Mechanical
### Skills needed/acquired
- Modal analysis
- Vibration awareness in vehicle components
### Definition of done
- First 5–10 modes with effective mass participation
- Discussion of implications
### How to present
Technical note with mode shape images.

---

# 4. Thermal & Cooling Systems

## 4.1 Radiator Duct Performance Study
### Description
Model a simple cooling duct + radiator face. Evaluate mass flow, pressure drop, and temperature drop for different duct designs.
### Tools needed
- SolidWorks
- Ansys Fluent (with heat transfer)
### Skills needed/acquired
- Internal flow + heat exchanger modelling
- Cooling system trade-offs
### Definition of done
- At least two duct geometries compared
- Mass-flow, ΔP, and heat rejection results
### How to present
Cooling-focused report. Relevant for both ICE and electric powertrains.

## 4.2 Brake Duct Thermal Analysis
### Description
Simple conjugate heat transfer study of a brake disc with cooling duct.
### Tools needed
- Ansys Fluent (CHT)
### Skills needed/acquired
- Conjugate heat transfer
- Thermal management fundamentals
### Definition of done
- Temperature distribution on disc
- Effect of duct design on cooling
### How to present
Visual temperature contours + short report.

## 4.3 Electronics / Battery Cold-Plate Concept
### Description
Basic cold-plate or air-cooled enclosure for electronics or a simplified battery module.
### Tools needed
- Ansys Fluent or Mechanical (thermal)
### Skills needed/acquired
- Thermal design for reliability
- Relevance to hybrid/electric endurance racing
### Definition of done
- Temperature maps under load
- Comparison of cooling strategies
### How to present
Application-focused technical note.

## 4.4 Underhood / Powertrain Cooling Airflow
### Description
Simplified underhood volume with heat sources and exits. Study airflow distribution.
### Tools needed
- Ansys Fluent
### Skills needed/acquired
- Complex internal flow
- Packaging vs cooling trade-off
### Definition of done
- Flow distribution visualisation
- Identification of dead zones
### How to present
Report with streamlines and recommendations.

## 4.5 Thermal-Structural Coupling on a Component
### Description
Apply temperature field from a thermal analysis to a structural model and assess thermal stresses.
### Tools needed
- Ansys Mechanical / Fluent
### Skills needed/acquired
- Thermo-mechanical analysis
### Definition of done
- Combined thermal + structural results
- Discussion of design implications
### How to present
Integrated analysis report.

---

# 5. Integrated, Data & Portfolio Projects

## 5.1 Full (Simplified) Open-Wheel Aero Package
### Description
Combine front wing, floor/diffuser, and rear wing into one model and run a limited set of Fluent cases.
### Tools needed
- SolidWorks
- Ansys Fluent
### Skills needed/acquired
- Full-vehicle aero thinking
- Component interaction awareness
### Definition of done
- Assembled geometry
- Baseline force breakdown (front/rear balance)
- Discussion of interactions
### How to present
Flagship portfolio project. Major LinkedIn showcase opportunity.

## 5.2 Aero Map → Vehicle Performance Study
### Description
Generate a small aero map from CFD and feed it into a simple vehicle dynamics model to show lap-time or cornering sensitivity.
### Tools needed
- Ansys Fluent + Python vehicle model
### Skills needed/acquired
- End-to-end performance thinking
- Sensitivity analysis
### Definition of done
- Documented aero map
- Vehicle model results showing aero influence
### How to present
Combined report. Extremely strong for motivation letters.

## 5.3 Automated CFD Post-Processing Toolbox
### Description
Python scripts that take Fluent exports and automatically generate force plots, comparison charts, and report-ready figures.
### Tools needed
- Python (Pandas, Matplotlib, etc.)
- Ansys Fluent exports
### Skills needed/acquired
- Workflow automation
- Reproducible analysis
### Definition of done
- Working scripts with documentation
- Example output from one of your cases
### How to present
GitHub repository. Shows software maturity.

## 5.4 Statistical / Sensitivity Extension of Your F1 Paper
### Description
Extend your existing statistical paper with a technical sensitivity study (e.g. how much aero or powertrain performance correlates with career outcomes or team budgets — or pure technical sensitivity).
### Tools needed
- Python / Excel
- Your existing research
### Skills needed/acquired
- Data analysis
- Bridging technical & industry understanding
### Definition of done
- Updated or companion paper/technical note
- Clear visualisations
### How to present
ResearchGate / LinkedIn + PDF. Unique differentiator.

## 5.5 Design of Experiments (DoE) on a Key Geometry
### Description
Apply formal Design of Experiments to one of your aero or structural projects (e.g. wing angle + endplate height + ride height).
### Tools needed
- Ansys + Python / Excel
### Skills needed/acquired
- DoE methodology
- Efficient exploration of design space
### Definition of done
- DoE matrix, results, and response surfaces or main-effects plots
- Conclusions on most influential parameters
### How to present
Methodology-strong report. Impressive to admissions tutors and engineers.
