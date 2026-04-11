Explanation for csv-data files: 
gate_error_[name]_arr: 1d array, mean error per gate measured from RB experiments as a function of gate duration. Error per gate = Error per Clifford / 2.208 since Cliffords are decomposed using the gate set {I, R_X(+-pi/2), R_Y(+-pi/2)}.
gate_error_uncertainty_[name]_arr: 1d array, 1 sigma uncertainty of the mean error per gate vs duration
leakage_error_[name]_arr: 1d array, mean leakage error per gate measured from leakage RB experiments as a function of gate duration. Leakage per gate = Leakage per Clifford / 2.208 since Cliffords are decomposed using the gate set {I, R_X(+-pi/2), R_Y(+-pi/2)}.
leakage_error_uncertainty_[name]_arr: 1d array, 1 sigma uncertainty of the mean leakage error per gate vs duration
duration_[name]_arr: 1d array of tested gate durations. Here, gate duration includes the pulse duration AND zero padding of 0.41 ns. (units: s)


Here, the name is the pulse name from the set {FAST_DRAG-L, FAST_DRAG-L_no_predistortion}. The envelope predistortion has been performed for FAST_DRAG-L, but not for FAST_DRAG-L_no_predistortion.