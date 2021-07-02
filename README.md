Code for FORCE-inspired RNN training for the modeling of β-LFP oscillations.

**force_architectures** - basic network training using FORCE procedure introduced in Sussillo & Abbott, 2009 (single readout on a periodic function), followed by extensions to train: 
- single internal current on periodic function 
- several internal currents on several functions  
- all internal currents on a set of functions 

**positive_sigmoid_single** - training on a single trial of LFP data in network with positive sigmoid nonlinearity. N (number of neurons) = N^T (number of targets).

**positive_sigmoid_multiple** - training on multiple trials of LFP data in network with positive sigmoid nonlinearity. N = N^T.

**duplicates_single** - training using duplicate method on single trial of LFP data. N = 2N^T.

**duplicates_multiple** - training using duplicate method on multipe trials of LFP data. N = 2N^T.
