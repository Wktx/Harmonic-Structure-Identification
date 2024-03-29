# Harmonic-Structure-Identification

Classified chord type (Major, Minor, Diminished) with supervised ML model. Recorded and labeled chords using MIDI. Applied Fast Fourier Transform and Cumulative Distribution Transform on audio signals. 

Harmonic structure identification is a complex problem examining the relationship between perceived sound and the sound's frequency content across time. Harmony depends on consistent relationships in the frequency domain, but the variation in musical analysis presents a significant issue in decoding the harmony based on peak frequencies in a spectral transform. Complicating factors include recording noise, temporal and spectral variation, and resonance variations between instruments. The cumulative distribution transform offers an attractive paradigm for signal matching, where difficult derivations of signal domain mapping functions for positive, normalized signals become trivial optimization problems in the transform domain. The result is a mechanism for signal comparison that is light-weight while maintaining or improving accuracy against typical signal metrics like Euclidean distance. Here, the harmonic identification problem is considered using the cumulative distribution transform paradigm and two classifiers are presented, based on the CDT-nearest subspace and linear discriminant analysis methods.

Authors: William Ashe, William Xiao
