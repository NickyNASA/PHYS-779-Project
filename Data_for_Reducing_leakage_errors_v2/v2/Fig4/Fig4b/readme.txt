Explanation for csv-data files: 
gate_error_vs_time: 1d array, mean error per gate measured from RB experiments as a function of time since gate calibration. Error per gate = Error per Clifford / 2.208 since Cliffords are decomposed using the gate set {I, R_X(+-pi/2), R_Y(+-pi/2)}.
gate_error_uncertainty_vs_time: 1d array, 1 sigma uncertainty of the mean error per gate 
incoherent_error_vs_time: 1d array, mean incoherent error per gate measured from purity RB experiments as a function of time since gate calibration. incoherent error per gate = incoherent error per Clifford / 2.208.
incoherent_error_uncertainty_vs_time: 1d array, 1 sigma uncertainty of the mean incoherent error per gate
leakage_error_vs_time: 1d array, mean leakage per gate measured from leakage RB experiments as a function of time since gate calibration. leakage per gate = leakage per Clifford / 2.208
leakage_error_uncertainty_vs_time: 1d array, 1 sigma uncertainty of the mean leakage per gate 
coherence_limit_estimate_vs_time: 1d array, estimate for the incoherent error computed from T1 and T2 echo measured interleaved with the Rb experiments.
T1_mean_vs_time: 1d array, mean of T1 vs time since calibration. (units: s)
T1_uncertainty_vs_time: 1d array, 1sigma uncertainty of T1 vs time since calibration (units: s)
T2Echo_mean_vs_time: 1d array, mean of T2Echo vs time since calibration. (units: s)
T2Echo_uncertainty_vs_time: 1d array, 1sigma uncertainty of T2Echo vs time since calibration (units: s)
time_arr: 1d array, time since gate calibration. (units: h)

Here, we used a gate duration of 6.67 ns (incl. 0.41 ns padding) and FAST DRAG-L pulse. 