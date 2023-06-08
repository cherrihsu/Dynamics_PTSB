# Dynamics_PTSB
Programs and datasets for the work "Efficient Machine-learning-Aided Dynamics for Reactions with Post-Transition-State Bifurcation"
1. The Python programs for training the KRR models were placed in the _KRRmodels.zip_
2. Coulomb matrices, relative potential energies, and atomic forces for each dataset were placed in the _datasets.zip_
3. The _KRR_traj_ folder contains the modified Progdyn for generating KRR trajectories.
4. Most of the file structure follow the same one as described in _JACS_, **2020**, _142_, 12865. The files prefixed with KRR are programs for KRR trajectories
5. The _progdynstarterHP_sampingOnly_ is used in KRR trajectories instead of the original _progdynstarterHP_ (AIMD). The codes have to be modified corresponding to the conditions of the machine.
6. The conditions for the KRR trajectory calculations can be modified in _KRR_ML_Predicting_Verlet_multimodel.py_
7. The conditions for Progdyn can be found and modified in _progdyn.conf_. This would affect how the initial geometry, velocity are sampled.
