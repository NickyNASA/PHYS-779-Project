Explanation for csv-data files: 
axis_shift_for_zero_delay_arr: 1d array, axis shift measured from I-distortion characterization experiment as a function of pulse duration (and hence pulse amplitude). Here, we used zero delay between pulses in the I-distortion characterization experiment (units: degree)
pulse_amplitude_arr: 1d array, amplitude of the in-phase component. (units: V)
pulse_duration_arr: 1d array, pulse durations used in the experiment. (units: s)

Here, we used an in-phase envelope with cosine-shaped rise and fall. The rise and fall had a fixed duration of 6.25 ns each. The quadrature envelope was derived using DRAG-P. To sweep the pulse duration, the duration of the flat part of the envelope was altered. Pulse amplitude was recalibrated for each pulse duration.