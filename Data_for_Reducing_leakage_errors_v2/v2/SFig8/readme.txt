Explanation for csv-data files: 
[hyperparameter]/FAST_DRAG-P_idx_of_duration_[x]/leakage_error_exp_arr.csv: 1d array, mean leakage per gate measured from leakage RB experiments as a function of the swept hyperparameter value. Leakage per gate = Leakage per Clifford / 2.208 since Cliffords are decomposed using the gate set {I, R_X(+-pi/2), R_Y(+-pi/2)}.
[hyperparameter]/FAST_DRAG-P_idx_of_duration_[x]/leakage_error_exp_uncertainty_arr.csv: 1d array, 1 sigma uncertainty of the mean leakage per gate vs hyperparameter value
[hyperparameter]/FAST_DRAG-P_idx_of_duration_[x]/sweep_parameter_exp_arr.csv: 1d array of swept hyperparameter values in the experiment. For frequencies, the units are Hz.  
[hyperparameter]/FAST_DRAG-P_idx_of_duration_[x]/leakage_error_sim_arr.csv: 1d array, simulated leakage per gate for R_X(pi/2) vs hyperparameter value
[hyperparameter]/FAST_DRAG-P_idx_of_duration_[x]/sweep_parameter_sim_arr.csv: 1d array of swept hyperparameter values in the simulation. For frequencies, the units are Hz.  
[hyperparameter]/FAST_DRAG-P_idx_of_duration_[x]/leakage_error_cosine_DRAG.csv: 1-element array containing the leakage error for Cosine DRAG-P pulse of corresponding duration
[hyperparameter]/FAST_DRAG-P_idx_of_duration_[x]/gate_duration.csv: 1-element array containing the gate duration. (units: s)
[hyperparameter]/FAST_DRAG-P_idx_of_duration_[x]/default_parameter_value.csv: 1-element array containing the default value of the hyperparameter used in the main text of the manuscript. Frequencies are in Hz.

Here, the swept hyperparameters of FAST DRAG-P include the number of cosine terms, the cutoff frequency, the center frequency of the frequency interval suppressing the ef-transition, the weight of the frequency interval suppressing the ef-transition, and the width of the frequency interval suppressing the ef-transition. 

The studied gate durations were 7.9 ns for index of 0, and 9.2 ns for index of 1. Both include zero padding of 0.41 ns.  