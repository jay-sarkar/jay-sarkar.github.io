---
layout: page
title: Partially Censored Posterior
description: with S.J. Koopman and L. Hoogerheide
img: /assets/img/pcp.jpg
---
	
<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>

With <a href="http://sjkoopman.net/" title="SJK">Siem Jan Koopman</a> and <a href="https://research.vu.nl/en/persons/lennart-hoogerheide" title="LH">Lennart F. Hoogerheide</a>. 

> A novel estimation method  providing a more accurate inference for a specific region of the predictive density  in case of misspecification. Based on the censored likelihood, where the observations outside the region of interest are censored (i.e. for them only the probability of being outside the region of interest matters). 

PDF: <a class="page-link" href="{{ '/research/Borowska, Hoogerheide, Koopman - Partially censored posterior for accurate left tail density prediction.pdf' | prepend: site.baseurl | prepend: site.url }}">Partially Censored Posterior for Accurate Left Tail Density Prediction</a>

<a href="javascript:showhide('pcp')">_Abstract_</a>
<div id="pcp" style="display:none;">
<p>  <span style="font-size:0.85em;"> 
A novel approach to inference for a specific region of the predictive distribution is introduced. An important domain of application is accurate prediction of financial risk measures, where the area of interest is the left tail of the predictive posterior density of (log)returns. It originates from the Bayesian approach to parameter estimation and time series forecasting, however it provides a more accurate estimation of the density in the region of interest in case of misspecification. In the proposed concept of the Partially Censored Posterior the set of parameters is partitioned into two subsets: the first, for which we consider the standard marginal posterior, and the second, for which we consider a censored conditional posterior. The censoring means that observations outside the region of interest are censored: for those observations only the probability of being outside the region of interest matters. In the second subset we choose parameters that are expected to benefit from censoring. This approach yields more precise parameter estimation than a fully censored posterior for all parameters, and has more focus on the region of interest than a standard approach. Finally,  novel ways of time-varying censoring is developed, beneficial from the tail prediction perspective. Extensive simulation and empirical studies show the ability of the introduced method to outperform standard approaches.  </span> </p>
</div>

Code: <a class="github-button" href="https://github.com/aborowska/PCP" data-size="large" aria-label="Follow @aborowska/PCP on GitHub">Follow @aborowska/PCP</a>