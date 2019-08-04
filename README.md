# 3D-to-1D End-to-End MR Fingerprinting Reconstruction
Reconstruct tissue parameter maps from magnetic resonance fingerprinting (MRF) scans using a deep learning model. It addresses the fundamental 2D image aliasing problem in MRF as well as the time-series pattern matching in one end-to-end model. Detailed neural network structure will not be disclosed at this moment.

### Introduction
Without futher confusion, MRI is analogous to a clear picture taken on a tripod whereas MRF is like a short film of a subject taken by a shaking camera and you want to find out the underlying properties about the subject. MRF signal is a 3D data. The pixel-wise time-series signal forms a unique pattern or a 'fingerprint' that is later used for pattern matching. However, the MRF signal is contaminated by the aliasing artifact in each frame

The objective of this work is to replace the 2D de-aliasing and time-series pattern matching with one neural network model. 
