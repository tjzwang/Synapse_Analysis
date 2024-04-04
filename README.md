The code was created and used for the following publication. If you use this code or modify this code and use it for any purposes, please cite:
Gillani, R. L., Kironde, E. N., Whiteman, S., Zwang, T. J. & Bacskai, B. J. Instability of excitatory synapses in experimental autoimmune encephalomyelitis and the outcome for excitatory circuit inputs to individual cortical neurons. Brain, Behav., Immun. (2024) doi:10.1016/j.bbi.2024.03.039

# Synapse_Analysis
Matlab code for analysis of synapse data in Gillani et al manuscript (to be updated with citation once published).
To run first create an excel spreadsheet with information in the following columns/format
%"Neuron ID" = 1
%"Treatment (Healthy = 0, EAE =1)" = 2
%"Segment ID" = 3
%"Synapse Type (Stable =0, Dynamic =1)" = 4
% "Segment length (microns)" = 5
% "Distance along segment (microns)" = 6
%"Distance from cell body (microns)" = 7
%"Apical/Basilar (Apical = 0, Basilar = 1)" = 8

Modify the matlab code to include the location of the excel spreadsheet by changing the information in '...' to the correct path on your computer
%SynapseInfo = xlsread('C:...xlsx');

Code runs one neuron at a time. Change value on line 12, n = #, to run different neurons.
