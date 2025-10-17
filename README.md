# MCS_MEMOP_Code_Model_Data

Repository Structure
1. msc_memop_code
This folder contains the underlying model code and scripts used to implement and run the MCS-MEMOP framework.
It includes: borg_res.py, operators_res.py, algorithms_res.py, init_evaluation.py and SwatInterOptis_MultiSces.py

2. swat_inout
This folder contains the calibrated and directly runnable SWAT model for the Dengsha River Watershed.
It includes:
The full SWAT input/output files after calibration (TxtInOut structure);
Calibrated parameters and setup corresponding to the study’s baseline configuration;
Files ready for direct execution of SWAT simulations.

3. Figure Data (Excel files)
The dataset includes the numerical data used to generate Figures 4–9 in the manuscript.
Figure 4: Data illustrating the performance of MOP, SMOP, and MEMOP solutions, including values for the three objectives and four selected solutions.
Figure 5: Data showing the performance of MOP, SMOP, and MEMOP solutions under epoch-specific constraints.
Figure 6: Data presenting the unit removal costs associated with MOP, SMOP, and MEMOP solutions.
Figure 7: Data showing total cost, TN, and TP loads for MEMOP solutions under each of the 13 climate scenarios (C1–C13).
Figure 8: Data illustrating the performance of MEMOP solutions across multiple climate scenarios, evaluated using robustness metrics.
Figure 9: Data showing the performance of MCS-MEMOP solutions under newly introduced climate conditions.

For detailed explanations of the data and their interpretation, please refer to the relevant sections of the paper.
