Explanation for csv-data files: 
[name]/pf_vs_N_cliffords_and_idx_mat: 2d array, f-state probability after an RB sequence as a function of the number of random Clifford gates in the sequence (columns) and the index of the random sequence (rows). We used 25 different random sequences for each sequence length. 
[name]/N_cliffords_arr: 1d array, number of Clifford gates used in RB
[name]/pf_fit_vs_N_cliffords: 1d array, exponential fit to the f-state probability as a function of the number of Clifford gates
[name]/N_cliffords_arr_for_fit: number of Clifford gates for the fit
[name]/leakage_per_gate_and_uncertainty: fitted leakage error and 1sigma uncertainty as a 2-element 1d array

Here, the name is the pulse name from the set {FAST_DRAG-L, Cosine_DRAG-L}. Envelope predistortion has been applied to all pulses. 

The gate duration was 6.25 ns including 0.41 ns zero padding.
