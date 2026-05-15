# Conductance of multi-heme proteins



* Experimental STM data from Isma: STC, MtrC
* Solvated DFT models: STC, Cyt b562, NrtB, GSU



* Normalization of the distance decay data:
  * Density of states (STC as a reference)
  * Number of contacts
  * Volume fraction of the protein between the electrode contacts



* No thermal sampling (too expensive... computed data do not have error bars)
* Random structures (last snapshot from MD trajectory... it would be better to take a snapshot corresponding to the average number of contacts)



* Can we take into account different numbers of contacts at the two electrodes?
  $ 1 - \left| \frac{N_R - N_L}{N_R + N_L} \right| $