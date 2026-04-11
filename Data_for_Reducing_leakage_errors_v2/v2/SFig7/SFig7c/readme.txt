Explanation for csv-data files: 
[name]/gate_error_exp_arr: 1d array, mean error per gate measured from RB experiments as a function of gate duration. Error per gate = Error per Clifford / 2.208 since Cliffords are decomposed using the gate set {I, R_X(+-pi/2), R_Y(+-pi/2)}.
[name]/gate_error_exp_uncertainty_arr: 1d array, 1 sigma uncertainty of the mean error per gate vs duration
[name]/leakage_error_exp_arr: 1d array, mean leakage per gate measured from leakage RB experiments as a function of gate duration. Leakage per gate = Leakage per Clifford / 2.208 since Cliffords are decomposed using the gate set {I, R_X(+-pi/2), R_Y(+-pi/2)}.
[name]/leakage_error_exp_uncertainty_arr: 1d array, 1 sigma uncertainty of the mean leakage error per gate vs duration
[name]/duration_exp_arr: 1d array of tested gate durations. Here, gate duration includes the pulse duration AND zero padding of 0.41 ns. (units: s)
[name]/gate_error_sim_arr: 1d array, simulated gate error of the R_X(pi/2) gate as a function of gate duration
[name]/leakage_error_sim_arr: 1d array, simulated leakage error of the R_X(pi/2) gate as a function of gate duration
[name]/duration_sim_arr: 1d array, gate durations used in simulations (units: s)

Here, the name is the pulse name from the set {Gaussian_DRAG-P_tp=4sigma_discont, Gaussian_DRAG-P_tp=4sigma_cont, Gaussian_DRAG-P_tp=5sigma_cont, Gaussian_DRAG-P_tp=6sigma_cont}. Gaussian_DRAG-P_tp=xsigma means that the pulse duration is x times the standard deviation of the Gaussian. The postfix cont means that the in-phase envelope is continuous as a result of subtracting away the discontinuity at the beginning and end of the pulse. The postfix discont indicates that the discontinuity has NOT been subtracted and is therefore present.