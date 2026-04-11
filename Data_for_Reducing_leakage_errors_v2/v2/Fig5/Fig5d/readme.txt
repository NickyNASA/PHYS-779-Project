Explanation for csv-data files: 
[pulse_name]/axis_shift_vs_delay_exp_arr: 1d array, axis shift measured from intra-quadrature distortion characterization experiment as a function of delay between pulses. (units: degree)
[pulse_name]/axis_shift_uncertainty_vs_delay_exp_arr: 1d array, 1 sigma uncertainty of the axis shift (units: degree)
[pulse_name]/delay_exp_arr: 1d array of delays used in the sweep. (units: s)
[pulse_name]/pulse_duration: 1-element array containing the used pulse duration (without zero padding). (units: s)
FAST_DRAG-P_no_predistortion/axis_shift_vs_delay_fit_arr: 1d array, exponential fit to axis shift as a function of delay. (units: degree)
FAST_DRAG-P_no_predistortion/delay_fit_arr: 1d array of delays used for the fit. (units: s)


Here, the pulse name is from the set {FAST_DRAG-P_no_predistostion, FAST_DRAG-P_with_predistostion} indicating whether envelope predistortion has been applied for the FAst DRAG-P pulse. 