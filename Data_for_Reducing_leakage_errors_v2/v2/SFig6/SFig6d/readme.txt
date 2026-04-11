Explanation for csv-data files: 
idx_of_a1_[x]/axis_shift_vs_delay_arr: 1d array, axis shift measured from I-distortion characterization experiment as a function of delay between pulses. The envelope pulses have been predistorted using an inverse exponential IIR filter, the a1-parameter of which has been set to a1_value. (units: degree)
idx_of_a1_[x]/delay_arr: 1d array, delay between consecutive pulses in I-distortion characterization experiment (units: s)
idx_of_a1_[x]/a1_value: 1-element array containing the value of the a1-parameter used for the predistortion with the current index x.

Here, we used a predistorted FAST DRAG-P pulse with a pulse duration of 9.6 ns. We swept the a1-parameter of the exponential IIR filter model. The decay time tau_1 of the exponential IIR filter model has been fixed to 8 ns based on prior measurements.