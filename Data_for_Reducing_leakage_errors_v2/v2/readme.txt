This dataset contains the experimental data used in the figures of the paper "Reducing leakage of single-qubit gates for superconducting quantum processors using analytical control pulse envelopes" by E. Hyyppä, A. Vepsäläinen, ..., and J. Heinsoo published in PRX Quantum 5, 030353 (2024): https://doi.org/10.1103/PRXQuantum.5.030353.

The data is stored mostly as csv-files, the contents of which are explained in the readme-files. Each subfolder corresponds to one figure of the paper and also contains a Jupyter Notebook for plotting the data. The subfolders S1-S10 correspond to the supplementary figures, i.e., figures 6-15 in the Appendix of the paper.

Furthermore, we provide a Jupyter notebook in the folder Code_to_plot_FAST_and_HD_DRAG_pulses/ that provides Python functions for evaluating and plotting the proposed FAST DRAG and HD DRAG pulses in time domain and frequency domain. Please cite our paper if you use the Python code for your published research.

The notebooks have been tested using the following Python package versions
Python                    3.11
scipy                     1.14.1
numpy                     2.1.0
matplotlib                3.9.2