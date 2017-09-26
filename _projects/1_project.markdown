---
layout: page
title: Long Run Risk Evaluation
description: Job Market Paper
img: /assets/img/qermit.jpg
---

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>
  
> Precise forecasts of the tail of the distribution of returns for very long horizons, even one-month and one-year ahead (not barely for the 10-days-ahead horizon required by the Basel Committee). An importance sampling based approach where the importance densities are constructed sequentially to "guide" the draws into the tail.
>
> > _Why do we care?_ Check: [Long Run Value at Risk (VaR)](https://vlab.stern.nyu.edu/doc/4?topic=apps) analysed by [NYU Stern VLAB](https://vlab.stern.nyu.edu/)!  

PDF: <a class="page-link" href="{{ '/research/A.Borowska - Bayesian Risk Evaluation for Long Horizons.pdf' | prepend: site.baseurl | prepend: site.url }}">Long Run Risk Evaluation</a>

 
<a href="javascript:showhide('longrun')">_Abstract_</a>
<div id="longrun" style="display:none;">
<p>  <span style="font-size:0.85em;"> We present an  accurate and efficient approach to Bayesian estimation of two financial risk measures, Value at Risk and Expected Shortfall, for a given volatility model. We obtain precise forecasts of the tail of the distribution of returns not only for the 10-days-ahead horizon required by the Basel Committee but even for  long horizons, like one-month or one-year ahead. The latter has recently attracted a considerable attention due to a different character of the short term risk and the long run one. Long  horizon forecasts can also be useful e.g. for option pricing. The key insight behind our proposed importance sampling based approach is the construction of the importance densities sequentially, with conditioning of the  properties of the current conditional density on the marginal density and the previous conditional densities. For robustness, the partial candidate densities  are efficiently constructed as mixtures of Student's t densities. By oversampling the extreme negative scenarios and punishing them by lower importance weights, we achieve a much higher precision in characterising the properties of the left tail. We report substantial accuracy gains for all the considered horizons in  empirical studies on two datasets of daily financial returns, including a highly volatile period of the recent financial crisis. We analyse two workhorse models used by financial practitioners, GARCH(1,1)-t and GAS(1,1)-t. To illustrate the flexibility of the proposed construction method, we present how it can be adjusted to the frequentist case, for which we provide  counterparts of both Bayesian applications.</span> </p>
</div>



Code: <a class="github-button" href="https://github.com/aborowska/QERMit" data-size="large" aria-label="Follow @aborowska/QERMit on GitHub">Follow @aborowska/QERMit</a>