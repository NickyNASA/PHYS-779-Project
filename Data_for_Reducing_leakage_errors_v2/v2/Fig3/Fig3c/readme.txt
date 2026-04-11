Explanation for csv-data files: 
[name]/leakage_error_exp_arr: 1d array, mean leakage error per gate measured from leakage RB experiments as a function of gate duration. Leakage per gate = Leakage per Clifford / 2.208 since Cliffords are decomposed using the gate set {I, R_X(+-pi/2), R_Y(+-pi/2)}.
[name]/leakage_error_exp_uncertainty_arr: 1d array, 1 sigma uncertainty of the mean leakage error per gate vs duration
[name]/duration_exp_arr: 1d array of tested gate durations. Here, gate duration includes the pulse duration AND zero padding of 0.41 ns. (units: s)
[name]/leakage_error_sim_arr: 1d array, simulated leakage error of the R_X(pi/2) gate as a function of gate duration
[name]/duration_sim_arr: 1d array, gate durations used in simulations (units: s)

Here, the name is the pulse name from the set {FAST_DRAG-L, HD_DRAG-L, Cosine_DRAG-L, Cosine_DRAG-P}.