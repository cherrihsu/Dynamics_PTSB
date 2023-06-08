# Dynamics_PTSB
Programs and datasets for the work "Efficient Machine-learning-Aided Dynamics for Reactions with Post-Transition-State Bifurcation"
1. The Python programs for training the KRR models were placed in the KRRmodels.zip
2. Coulomb matrices, relative potential energies, and atomic forces for each dataset were placed in the datasets.zip
3. The KRR_traj folder contains the modified Progdyn for generating KRR trajectories.
4. Most of the file structure follow the same one as described in XXX. The files prefixed with KRR are programs for KRR trajectories
5. The progdynstarterHP_sampingOnly is used in KRR trajectories instead of the original progdynstarterHP (AIMD). The codes have to be modified corresponding to the conditions of the machine.
6. The conditions for the KRR trajectory calculations can be modified in KRR_ML_Predicting_Verlet_multimodel.py
7. The conditions for Progdyn can be found and modified in progdyn.conf. This would affect how the initial geometry, velocity are sampled.
