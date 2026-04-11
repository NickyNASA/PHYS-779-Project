Explanation for csv-data files: 
single_shot_i_voltage_vs_state_and_rep: 2d array, I-component of readout voltage for single shot readout events. The ith row corresponds to preparing the qubit to the ith state, whereas
the columns correspond to different repetitions. (units: V)
single_shot_q_voltage_vs_state_and_rep: 2d array, Q-component of readout voltage for single shot readout events. The ith row corresponds to preparing the qubit to the ith state, whereas
the columns correspond to different repetitions. (units: V)
assigned_states_for_each_shot: 2d array, assigned state of each shot based on our classifier. The ith row corresponds to preparing the qubit to the ith state, whereas
the columns correspond to different repetitions. 
state_assignment_mat: 2d array, probability of assigning the qubit to the jth state after preparing to the ith state. Here, i is the column, and j is the row. 
