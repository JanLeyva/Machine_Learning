# Local Poisson bandwidth

In this work is modified the functions `h.cv.sm.binomial` and `loglik.CV` to obtain a band- width choice method for the *local
Poisson regression* based on the leave-one-out cross-validation (`loo-CV`) estimation of the expected likelihood
of an independent observation. 
After that, the `sm`package are used for fit a *Local Poisson regression* with the bandwidth obtained by loo-CV.
