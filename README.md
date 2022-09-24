# Spike Detection

Spike detection is an important step in Brain-Computer Interfaces (BCI) as it allows the temporal location of the action potentials (or spikes) to be found within the raw data. A BCI can then sort the spikes and extract features, and from there machine learning algorithms can be run on the features. This experiment is two-fold: the first major step to investigate is the pre-processing phase, wherein several different filtering and transform methods are applied. From there, the pre-processed data will be evaluated by several different detection algorithms, and the results will be compared. It is the goal of this experiment to find a pre-procesing and detection algorithm combination that can both reliably detect action potentials and do so with minimal computation cost.

## References

Dataset: [Click here](https://crcns.org/data-sets/hc)

Readings:
* *Statistical Signal Processing for Neuroscience and Neurotechnology*, Edited by Karim Oweiss
