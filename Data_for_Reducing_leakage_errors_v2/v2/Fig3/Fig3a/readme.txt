Explanation for csv-data files: 
[name]/gate_error_exp_arr: 1d array, mean error per gate measured from RB experiments as a function of gate duration. Error per gate = Error per Clifford / 2.208 since Cliffords are decomposed using the gate set {I, R_X(+-pi/2), R_Y(+-pi/2)}.
[name]/gate_error_exp_uncertainty_arr: 1d array, 1 sigma uncertainty of the mean error per gate vs duration
[name]/T1_mean_exp_arr: 1d array, mean of T1 measured as a function of gate duration. (units: s)
[name]/T1_uncertainty_exp_arr: 1d array, 1 sigma uncertainty of T1 measured as a function of gate duration. (units: s)
[name]/T2Echo_mean_exp_arr: 1d array, mean of T2 echo measured as a function of gate duration. (units: s)
[name]/T2Echo_uncertainty_exp_arr: 1d array, 1 sigma uncertainty T2 echo measured as a function of gate duration. (units: s)
[name]/duration_exp_arr: 1d array of tested gate durations. Here, gate duration includes the pulse duration AND zero padding of 0.41 ns. (units: s)
[name]/gate_error_sim_arr: 1d array, simulated gate error of the R_X(pi/2) gate as a function of gate duration
[name]/duration_sim_arr: 1d array, gate durations used in simulations (units: s)

Here, the [name] is the pulse name from the set {FAST_DRAG-L, HD_DRAG-L, Cosine_DRAG-L, Cosine_DRAG-P}. Note that T1 and T2 echo were measured after gate calibration for each pulse duration to observe if there are any time-dependent fluctuations of coherence that could affect the measured gate error. 

The data for FAST DRAG-L and Cosine DRAG-L was measured in an interleaved fashion as follows: For a given pulse duration, the FAST DRAG-L pulse was calibrated and benchmarked. Subsequently, the Cosine DRAG-L pulse was calibrated and benchmarked. After benchmarking both pulses for a given pulse duration, the pulse duration was incremented and the same process was repeated. This data collection procedure for FAST DRAG-L and Cosine DRAG-L was further repeated on three separate days to collect more statistics and reduce the effect of potential coherence fluctuations. The data for HD_DRAG-L and Cosine_DRAG-P was collected on seperate days. 