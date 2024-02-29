This dataset presents the baseband LoRa physical layer (PHY) waveforms captured in the form of discrete complex IQ sequences.

The dataset is primarily used for evaluating the feasibility of achieving authentication of LoRa transmitters through radio frequency fingerprinting (RFF). All the data are in MATLAB .mat file format, with the file name of each file indicating the timestamp of the capture of that specific transmission.

Note that only minimal pre-processing is done to the captured LoRa PHY waveform to keep most of the physical layer imperfection effects within the transmissions. The processing includes 1) downconversion from bandpass to baseband and 2) energy detection to locate the actual transmission within the receiver frame.

For more details on the metadata and parameters of the waveform and the hardware, please refer to the PDF data description file.
