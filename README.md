# HiC Normalization
This project is useful in finding normalized HiC matrices and use those normalized matrix to create lampps data file.
Files description:

Text_File_changing_for_hic_in_score_format.ipynb: To convert the HiC raw text file (n*n matrix format) to score format useful for "Pre" command in juicer tools.

HiC Normalization.ipynb: The code is to convert the raw HiC matrix to explicitely normalized matrix which takes into account the bias due to chromatin accessibility of the restriction endonucleases.

contact_freq_to_contact_prob.ipyb: To convert the normalized HiC contact reads to data file for lammps input to create 3D structure of the matrix.

heat_plot.ipynb: To plot HiC contact map using seaborn and matplotlib.

multiple_bar_plot.ipynb: To plot composite bar plots for available data.
