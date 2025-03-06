# class3D_plot
#Class3D Particle Distribution Plot of RELION job

The Class3D particle distribution plot visualizes the relative abundance of particles assigned to different 3D classes during a classification run in RELION. This plot helps assess how particles are distributed among classes, which can indicate heterogeneity in the dataset and guide selection of the best-resolved structures for further refinement.

Key Features:
Displays particle counts or fractions per class.
Helps identify dominant and minor classes.
Assists in filtering out low-quality reconstructions.
Aids in deciding which classes to refine further.

Plot Generation:
To generate the Class3D plot, use the provided command, which extracts and visualizes the class distribution from RELION's output files.
Inside the Class3D job folder, with command ~class3d_plots job.star
It will plot the distribution.
