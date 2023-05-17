# Surface-wave-dispersion-using-CWT
Extracts seismic surface wave group velocity dispersion curves using continuous wavelet transform (CWT)
Pre-requisit: Python-3.8 and Obspy-1.2.2
This code extracts group velocity dispersion curve for the earthquake data as well as for the empirical Green's functions obtained between two stations.
It is required to specify minimum and maximum frequency range to obtain dispersion curve.
Also, specify the number of filters to obtain dispersion as scales of CWT. It is required to call scales from CWT function of obspy.signal.tf_misfit.
'test_syn.sac' or 'AAM_CBN.sac' can be used as a sample data file for extracting group velocity dispersion curve.
