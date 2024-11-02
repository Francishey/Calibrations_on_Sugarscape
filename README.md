auxiliary_plot_generation.ipynb -- generate all the plots in this paper

main_loop_for_the_whole_project.ipynb -- generate all analysis including HM, PMR, ABC base, SMC and SA, also produce the data stored in the folder 'alldata'

alldata folder: 

1. six folders include histories of calibrated parameters, for different methods
2. non_implausible_space.npy -- numpy file storing the filtered subspace after HM is applied to the full parameter space
3. pmr_with_abc.npy -- storing parameters after abc base calibration after PMR adjustment, with HM applied
4. pmr_without_abc.npy -- all same as above except from the condition that HM is not applied
5. summary_multi_dim_observation.npy -- storing 10-dim summary statistics for sugarscape simulations, ready for PMR application
6. total_uncertainty.npy -- sum of model discrepancy and ensemble variance, used for calculating the implausibility score of parameter x in HM
