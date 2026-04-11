Explanation for csv-data files: 
cost_function_vs_a1_and_tp_mat: 2d array, Cost function, i.e., sum of squared axis shifts, as a function the predistortion parameter a1 and the pulse duration
a1_arr: 1d array, values of a1-parameter used for the predistortion
pulse_duration_arr: 1d array, pulse duration. (units: s)

Here, we used a predistorted FAST DRAG-P pulse. We varied the a1-parameter value used for predistortion as well as the pulse duration to find an optimal value of a1 minimizing the cost function across pulse durations. The decay time of the IIR exponential predistortion model has been set to 8 ns. 