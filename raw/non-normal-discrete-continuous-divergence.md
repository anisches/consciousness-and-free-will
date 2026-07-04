# Discrete-Continuous Divergence in Non-normal Spectral Theory

In the study of random recurrent dynamics, non-normal synaptic weight matrices (where $W W^T \neq W^T W$) present unique analytical challenges for determining stationary covariance.

A key finding by [[zavatone-veth-nonnormal-rnn-covariance]] is that discrete-time and continuous-time formulations of these dynamics are not analytically equivalent at the spectral limit.

### Key Contrast:
- **Discrete-time**: The limiting stationary covariance spectrum is characterized by a closed functional equation for the moment generating function.
- **Continuous-time**: Analogous dynamics result in an infinite hierarchy of [[schwinger-dyson-equations]], failing to yield a closed scalar equation.

This divergence has implications for the use of discrete-time models as proxies for continuous-time neural processes. If the analytical properties (like tail eigenvalue behavior) differ fundamentally, discrete-time simulations may introduce artifacts or possess symmetries not present in the underlying biology.

[[non-normal-dynamics]] [[schwinger-dyson-equations]] [[discrete-time-dynamics]] [[recurrent-neural-networks]]
