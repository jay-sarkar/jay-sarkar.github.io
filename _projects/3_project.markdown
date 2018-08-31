---
layout: page
title: Semi-Complete Data Augmentation
description: 
img: /assets/img/sv_hmm.jpg
---

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>
   
With [Ruth King](http://www.maths.ed.ac.uk/~rking33/).

> Improving the efficiency of data augmentation for state space models. Combining data augmentation with numerical integration in a Bayesian hybrid approach to reduce a high correlation in the posterior draws, typically leading to poor mixing of the MCMC algorithm.

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('scda')">_Abstract_</a>
<div id="scda" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;">
We present a novel method to improve the efficiency of data augmentation algorithms for state-space models. Data augmentation is a standard approach to perform Bayesian inference, which is able to fit any type of model via imputing all of the unknown states in the complete-data likelihood. However, due to often very high correlation this typically leads to poor mixing of the MCMC algorithm. We propose to circumvent this inefficiency by combining data augmentation with numerical integration in a Bayesian hybrid approach. The underlying idea is to combine the good aspects of both methods but removing the problems that arise. For data augmentation the problem is that of highly correlated unknown states; for numerical integration the problem is that of the curse of dimensionality. To this end, we utilise the structure of the unknown states which can be split into two types: auxiliary variables, which are imputed within the MCMC algorithm using data augmentation; and "integrable" states, which are numerically integrated out within the likelihood expression. The idea is to specify the unknown states in such a way that the algorithm is efficient. The proposed technique can be  applied to different types of problems including  estimation of the stochastic volatility for financial data or abundance estimation for ecological time series. </div> </p>
</div>


<i class="fa fa-download fa-ld" aria-hidden="true"></i> Slides: <a class="page-link" href="{{ '/research/A.Borowska - Semi-Complete Data Augmentation for Efficient State Spcae Models Fitting.pdf' | prepend: site.baseurl | prepend: site.url }}">Semi-Complete Data Augmentation for Efficient State Spcae Models Fitting.pdf</a>

Code: <a class="github-button" href="https://github.com/aborowska/DA_in_SSM" data-size="large" aria-label="Follow @aborowska/DA_in_SSM on GitHub">Follow @aborowska/DA_in_SSM</a>