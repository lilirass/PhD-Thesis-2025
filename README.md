# PhD-Thesis-2025
Supplementary data and input files related to the following papers are available here.
•	Rassouli, L.; Dupuis, M. Electronic Structure of Excitons in Hematite Fe2O3. J. Phys. Chem. C 2024, 128, 743–758.
•	Rassouli, L.; Shakiba, M.; Akimov, A. V.; Ma, X.; Dupuis, M. Excitons in Hematite Fe2O3: Short-Time Dynamics from TD-DFT and Non-Adiabatic Dynamics Theories. J. Phys. Chem. C 2024, 128, 13681-13693.
•	Rassouli, L.; Rosso, K.; Dupuis, M. Electronic Structure of Excitons in Hematite-Water Slab, In preparation for J. Phys. Chem. C.

Bulk Hematite (221) – Folder: 221-bulk-hematite
•	221-cell-opt-u-on-Fe-O.xyz: XYZ file of the optimized 2×2×1 hematite cell using the +U correction applied to both Fe and O atoms.
•	ex1-geo.xyz: Optimized geometry of the first excited state.
•	CP2K input file examples:
o	Fe2O3_cell-opt.inp: Input for cell optimization of the ground state.
o	Fe2O3_1st_Ex_geo_opt.inp: Input for geometry optimization of the first excited state.
o	Fe2O3_scf.inp: Single-point SCF calculation with TD-DFT.
o	MD_Fe2O3.inp: Example of an ab initio molecular dynamics (AIMD) input file.
Hematite–Water Slab (221-single) – Folder: 221-hematite-water-slab
•	1-water_box_from_materials_studio.xyz: Water box containing 97 water molecules, created in Materials Studio.
•	1-water-MD-TIP3P.inp: Classical MD input using the TIP3P force field to equilibrate the water box.
•	2-hematite-water-MD-FlxSPC-ClayFF.inp: Classical MD input using FlxSPC and ClayFF force fields for the hematite–water system.
•	3-hematite-water-geo-DFT.inp: Geometry optimization of the hematite–water slab using DFT.
•	4-MD_Fe2O3-water-DFT.inp: Ab initio MD input for the hematite–water slab using DFT.
•	4-221-single-MD-frames.xyz: Sample XYZ file containing MD frames for which single-point SCF energy calculations were performed.
•	5-scf-diag.inp and 5-scf-ot.inp: Single-point SCF input files using the diagonalization and OT methods in CP2K, with DFT+U and TD-DFT. Calculations were first performed using OT, and the resulting wavefunction was used as input for diagonalization.
Additional Materials
•	The PowerPoint presentation used for the thesis defense is also included in the repository, providing further details on the methodology and simulation workflow.

