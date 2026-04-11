Explanation for csv-data files: 
idx_of_duration_[x]/axis_shift_vs_delay_exp_arr: 1d array, axis shift measured from intra-quadrature distortion characterization experiment as a function of delay between pulses for a pulse duration corresponding to index x. (units: degree)
idx_of_duration_[x]/delay_exp_arr: 1d array, delay between consecutive pulses in the intra-quadrature distortion experiment. (units: s)
idx_of_duration_[x]/pulse_duration: 1-element array containing the used pulse duration for the given index x. (units: s)
idx_of_duration_[x]/axis_shift_vs_delay_fit_arr: 1d array, exponential fit to the axis shift as a function of delay. (units: degree)
idx_of_duration_[x]/delay_fit_arr: 1d array, delay between consecutive pulses for the fit. (units: s)


Here, we used an in-phase envelope with cosine-shaped rise and fall. The rise and fall had a fixed duration of 6.25 ns each. The quadrature envelope was derived using DRAG-P. The pulse duration was altered by changing the duration of the flat part. In SFig 6(a), We present data for 4 different pulse durations (x={0, 4, 10, 16}) corresponding to 13.3 ns, 17.1 ns, 23.8 ns, and 32.1 ns. 