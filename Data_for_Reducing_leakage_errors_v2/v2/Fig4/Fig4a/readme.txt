Explanation for csv-files:
min_tg_with_leakage_below_threshold_mat: 2d array, shortest gate duration that produces a leakage error below 5e-5 for different studied pulse shapes. The duration includes a zero padding of 0.41 ns. 
pulse_shapes_mat: 2d array, names for the studied pulse shapes including FAST DRAG, HD DRAG, Slepian DRAG, Cosine DRAG, and Gaussian DRAG for both variants of DRAG.

See experimental data of Supplementary Fig. 7 that has been used to obtain the shortest gate duration with a leakage rate below the threshold value of 5e-5 for each of the pulses.

For FAST DRAG-L, we used hyperparameters: N=4, [f_{l,1}, f_{h,1}] = [194, 214] MHz, [f_{l,2}, f_{h,2}] = [450, 1000] MHz, w_1/w_2 = 5.
For FAST DRAG-P, we used hyperparameters: N=5, [f_{l,1}, f_{h,1}] = [194, 214] MHz, [f_{l,2}, f_{h,2}] = [450, 1000] MHz, w_1/w_2 = 100.
For Slepian_DRAG-L/P, we used hyperparameters: N=4, [f_{l,1}, f_{h,1}] = [185, 1000] MHz
For Gaussian_DRAG-L/P, we used pulse_duration/sigma=5 and subtracted the discontinuity of the in-phase envelope.