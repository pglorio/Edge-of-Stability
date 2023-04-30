# Edge-of-Stability
Experiments on edge of stability phenomenon in ML

In these notebooks I further investigated some of the experiments in https://openreview.net/forum?id=jh-rTtvkGeM . I was curious to see if the asymptotic value of sharpness (i.e. top eigenvalue of the loss Hessian) satisfies the relationship "asymptotic sharpness ~ 2/(learning rate)" for arbitrarily large learning rate (as far as training is stable). It seems that this is essentially the case, although the sharpness fluctuates more and more in time as the learning rate approaches unstable values.
