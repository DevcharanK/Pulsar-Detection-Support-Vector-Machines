# Pulsar-Detection-Support-Vector-Machines

Pulsars are a rare type of Neutron star that produces radio emissions detectable here on Earth.
They are of considerable scientific interest as probes of space-time, the inter-stellar medium,
and states of matter. Machine learning tools are now being used to automatically label pulsar
candidates to facilitate rapid analysis. The key task is to Predict if a star is a pulsar start or not.
Each candidate is described by 8 continuous variables and a single class variable. The first four
are simple statistics obtained from the integrated pulse profile (folded profile). This is an array of
continuous variables that describe a longitude-resolved version of the signal that has been
averaged in both time and frequency. The remaining four variables are similarly obtained from
the DM-SNR curve. 

The dataset is contained in pulsar_data_train.csv and pulsar_data_test.csv
