---
layout: page
title: M-Filter for Extended Density Combinations
description: 
img:  
---

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script> 


With [Nalan Baştürk](https://www.maastrichtuniversity.nl/n.basturk), [Stefano Grassi](https://sites.google.com/view/stefanograssi), [Lennart Hoogerheide](https://research.vu.nl/en/persons/lennart-hoogerheide) and [Herman K. van Dijk](https://personal.eur.nl/hkvandijk/)  

> A novel extended time-varying density combination scheme for dynamic asset-allocation based on  mixing of alternative volatility models and alternative portfolio strategies. For computations: a new Student's _t_ mixture based particle filter (M-Filter).


<i class="fa fa-download fa-ld" aria-hidden="true"></i> PDF: <a class="page-link" href="{{ '/research/Basturk, Borowska, Grassi, Hoogerheide, van Dijk - Time-varying Combinations of Bayesian Dynamic Models and Equity Momentum Strategies.pdf' | prepend: site.baseurl | prepend: site.url }}">Time-varying Combinations of Bayesian Dynamic Models and Equity Momentum Strategies</a> 


<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('baysm')">_Abstract_</a>
<div id="baysm" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;"> A novel dynamic asset-allocation approach is proposed where portfolios as well as portfolio strategies are updated at every decision period based on their past performance. A general class of models is specified, combining a dynamic factor model and a vector autoregressive model, where we also allow for stochastic volatility. A Bayesian strategy combination is introduced to combine two model-based strategies, a model momentum strategy based on fitted returns and a residual momentum strategy. This extends the mixture of experts analysis by allowing the strategy weights to be interdependent, time-dependent and incomplete. The presented estimation approach, originating from the forecast combination literature, relies on the implied state space structure of the joint model for the time series and strategy weights. Given the complexity of the resulting non-linear and non-Gaussian structure a novel and efficient particle filter is introduced, based on mixtures of Student's _t_ distributions. Using US industry portfolio returns over almost a century of monthly data, our empirical results indicate that time-varying combinations of flexible models from our developed class with two momentum strategies outperform competing models in terms of mean returns and Sharpe ratios, as well as reduced volatility and the largest loss. The latter result demonstrates the usefulness of the proposed methodology from risk management perspective.
</div> </p>
</div>
