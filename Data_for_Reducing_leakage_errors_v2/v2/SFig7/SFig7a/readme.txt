Explanation for csv-data files: 
[name]/gate_error_exp_arr: 1d array, mean error per gate measured from RB experiments as a function of gate duration. Error per gate = Error per Clifford / 2.208 since Cliffords are decomposed using the gate set {I, R_X(+-pi/2), R_Y(+-pi/2)}.
[name]/gate_error_exp_uncertainty_arr: 1d array, 1 sigma uncertainty of the mean error per gate vs duration
[name]/leakage_error_exp_arr: 1d array, mean leakage per gate measured from leakage RB experiments as a function of gate duration. Leakage per gate = Leakage per Clifford / 2.208 since Cliffords are decomposed using the gate set {I, R_X(+-pi/2), R_Y(+-pi/2)}.
[name]/leakage_error_exp_uncertainty_arr: 1d array, 1 sigma uncertainty of the mean leakage error per gate vs duration
[name]/pulse_amplitude_arr: 1d array, pulse amplitude for the R_X(pi/2)-gate as a function of pulse duration (units: V)
[name]/duration_exp_arr: 1d array of tested gate durations. Here, gate duration includes the pulse duration AND zero padding of 0.41 ns. (units: s)
[name]/gate_error_sim_arr: 1d array, simulated gate error of the R_X(pi/2) gate as a function of gate duration
[name]/leakage_error_sim_arr: 1d array, simulated leakage error of the R_X(pi/2) gate as a function of gate duration
[name]/duration_sim_arr: 1d array, gate durations used in simulations (units: s)

Here, the name is the pulse name from the set {FAST_DRAG-L/P, HD_DRAG-L/P, Cosine_DRAG-L/P, Slepian_DRAG-L/P, Gaussian_DRAG-L/P}. Envelope predistortion has been applied to all pulses.

For FAST DRAG-L, we used hyperparameters: N=4, [f_{l,1}, f_{h,1}] = [194, 214] MHz, [f_{l,2}, f_{h,2}] = [450, 1000] MHz, w_1/w_2 = 5.
For FAST DRAG-P, we used hyperparameters: N=5, [f_{l,1}, f_{h,1}] = [194, 214] MHz, [f_{l,2}, f_{h,2}] = [450, 1000] MHz, w_1/w_2 = 100.
For Slepian_DRAG-L/P, we used hyperparameters: N=4, [f_{l,1}, f_{h,1}] = [185, 1000] MHz
For Gaussian_DRAG-L/P, we used pulse_duration/sigma=5 and subtracted the discontinuity of the in-phase envelope.