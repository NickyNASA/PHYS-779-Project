Explanation for csv-data files: 
axis_shift_[name]_arr: 1d array, axis shift measured from intra-quadrature distortion characterization experiments as a function of gate duration. (units: degree)
axis_shift_uncertainty_[name]_arr: 1d array, 1 sigma uncertainty of the axis shift (units: degree)
duration_[name]_arr: 1d array of tested gate durations. Here, gate duration includes the pulse duration AND zero padding of 0.41 ns. (units: s)

Here, the name is the pulse name from the set {FAST_DRAG-L, FAST_DRAG-P, FAST_DRAG-L_no_predistortion, FAST_DRAG-P_no_predistortion}. The envelope predistortion has been performed for FAST_DRAG-L and FAST_DRAG-P, but not for FAST_DRAG-L_no_predistortion, and FAST_DRAG-P_no_predistortion.