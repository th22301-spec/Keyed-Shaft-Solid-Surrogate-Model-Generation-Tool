This script is developed as part of ongoing academic research under the ShapeShift framework, which addresses the need for efficient and accessible mechanical evaluation tools for Material Extrusion (MEX) additive manufacturing.

Although MEX enables customizable and cost-effective part production, it suffers from variability in mechanical performance—especially in functional, load-bearing components. Traditional high-fidelity filament-level Finite Element Analysis (FEA) models offer accuracy but are computationally expensive and require significant user expertise.

The objective of this work is to develop a solid surrogate model generation tool that maintains acceptable predictive accuracy while significantly reducing simulation time and complexity. This supports the creation of surrogate datasets for machine learning models, model order reduction, or fast design evaluation in MEX-printed parts.

By automating the generation of a keyed shaft solid model with appropriate boundary conditions, materials, meshing, and loading in Abaqus, this tool contributes to the broader goal of enabling open-access, scalable, and intelligent simulation for additive manufacturing applications.

Features
	•	Research-focused surrogate model generation
	•	Parametric keyed shaft geometry
	•	Automatic material assignment & meshing
	•	Torsional loading via RP coupling
	•	Reduced-cost FE model suitable for surrogate datasets
Requirements
	•	Abaqus/CAE with Python scripting
	•	numpy
How to Run
	1.	Open Abaqus/CAE
	2.	Run the script (File → Run Script)
	3.	Provide input parameters when prompted
