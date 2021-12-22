# SinteringTrajectory
Prediction of Sintering deformation based on Grain Size, Porosity, and Surface Area. This code can also applying the amount of shrinkage that occurs to STL files. This can be used a presintering scale up method for additive manufacturing components that require sintering.

The Sint_Traj_SA only simulates data for the relationship between surface area and fractional density

Final_plot_gen will create various plots that relate surface area, density, porosity, and grain size.
The parameters may be varied (K, a, b, theta, and more) to become case specific

GSE is the code for the grain size measurement and plot generation. This code will vary the standard deviation in grain size and calculate the parameter K over time t. The average error over 10000 cases will be recorded. Different K and GS_o can be implemented in this code
