Explanation for csv-data files: 
[pulse]/[hyperparameter]/idx_of_duration_[x]/leakage_error_exp_arr.csv: 1d array, mean leakage per gate measured from leakage RB experiments as a function of the swept hyperparameter value. Leakage per gate = Leakage per Clifford / 2.208 since Cliffords are decomposed using the gate set {I, R_X(+-pi/2), R_Y(+-pi/2)}.
[pulse]/[hyperparameter]/idx_of_duration_[x]/leakage_error_exp_uncertainty_arr.csv: 1d array, 1 sigma uncertainty of the mean leakage per gate vs hyperparameter value
[pulse]/[hyperparameter]/idx_of_duration_[x]/sweep_parameter_exp_arr.csv: 1d array of swept hyperparameter values in the experiment. For frequencies, the units are Hz.  
[pulse]/[hyperparameter]/idx_of_duration_[x]/leakage_error_sim_arr.csv: 1d array, simulated leakage per gate for R_X(pi/2) vs hyperparameter value
[pulse]/[hyperparameter]/idx_of_duration_[x]/sweep_parameter_sim_arr.csv: 1d array of swept hyperparameter values in the simulation. For frequencies, the units are Hz.  
[pulse]/[hyperparameter]/idx_of_duration_[x]/leakage_error_cosine_DRAG.csv: 1-element array containing the leakage error for Cosine DRAG-L pulse of corresponding duration
[pulse]/[hyperparameter]/idx_of_duration_[x]/gate_duration.csv: 1-element array containing the gate duration. (units: s)
[pulse]/[hyperparameter]/idx_of_duration_[x]/default_parameter_value.csv: 1-element array containing the default value of the hyperparameter used in the main text of the manuscript. Frequencies are in Hz.

Here, the studied pulses are HD DRAG-L (panel (a)) and Slepian DRAG-L (panel b). For HD DRAG-L, the swept hyperparameter is the suppressed frequency. For Slepian DRAG-L, the swept hyperparameter is the cutoff frequency. 
The studied gate durations were 6.2 ns for index of 0, and 7.9 ns for index of 1. Both include zero padding of 0.41 ns.  