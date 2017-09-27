---
layout: page
title: research
permalink: /research/
description: Information about my research activities.
---

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>

### Job Market Paper

Project: <a class="page-link" href="{{ '/projects/1_project/' | prepend: site.baseurl | prepend: site.url }}">Bayesian Risk Evaluation for Long Horizons</a>


### Work in progress
	
* Project: <a class="page-link" href="{{ '/projects/3_project/' | prepend: site.baseurl | prepend: site.url }}">Semi-Complete Data Augmentation</a>

* Project: <a class="page-link" href="{{ '/projects/2_project/' | prepend: site.baseurl | prepend: site.url }}">Partially Censored Posterior for Accurate Left Tail Density Prediction</a>
 
* Project: <a class="page-link" href="{{ '/projects/4_project/' | prepend: site.baseurl | prepend: site.url }}">Bayesian Risk Evaluation in State Space Models</a>

	
### Conferences
* [__8th European Seminar on Bayesian Econometrics__](http://esobe2017.org/) (ESOBE2017),
Maastricht, The Netherlands, 26-27 October 2017
* [__Sequential Monte Carlo 2017 Workshop__](http://www.it.uu.se/conferences/smc2017/) (SMC2017),
Uppsala, Sweden, 30 August - 1 September 2017
* [__1st International Conference on Econometrics and Statistics__](http://cmstatistics.org/EcoSta2017/index.php) (EcoSta2017),
Hong Kong, 15-17 June 2017 
* [__Statistics Seminar Series of the School of Mathematics__](http://www.maths.ed.ac.uk/school-of-mathematics/events/statistics) , 
Edinburgh, The UK, 19 May 2017
* [__10th International Conference on Computational and Financial Econometrics__](http://www.cfenetwork.org/CFE2016/) (CFE2016), 
Seville, Spain, 9-11 December 2016
* [__3rd Bayesian Young Statisticians Meeting__](http://web.mi.imati.cnr.it/conferences/BAYSM2016/) (BAYSM2016), 
Florence, Italy, 20-21 June 2016
* [__11th Netherlands Econometric Study Group Meeting__](https://feb.kuleuven.be/drc/Economics/misc/nesg2016/NESG2016) (NESG2016), 
Leuven, Belgium, 17--18 June 2016
* [__TI Ph.D. Lunch Seminar__](http://www.tinbergen.nl/seminar-serie/phd-lunch-seminars-amsterdam/?show_archive=0), 
Amsterdam, The Netherlands, 24 May 2016
* __Econometrics Brown Bag Seminar__,
Amsterdam, The Netherlands, 21 January 2016
 
### Theses
* <a class="page-link" href="{{ '/research/A.Borowska - Dissertation Abstract.pdf' | prepend: site.baseurl | prepend: site.url }}">Methods for Bayesian Analysis of Time Series</a>, _PhD Thesis Abstract_

* <a class="page-link" href="{{ '/research/A.Borowska - Bayesian Risk Evaluation using Importance Sampling.pdf' | prepend: site.baseurl | prepend: site.url }}">Bayesian Risk Evaluation using Importance Sampling</a>, _MPhil Thesis in Econometrics_

	<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('mphil')">_Abstract_</a>
	<div id="mphil" style="display:none;">
	<p>  <span style="font-size:0.85em; text-align: justify;"> We consider the evaluation of two financial risk measures, Value at Risk and Expected Shortfall. Our analysis is performed in a Bayesian fashion where we adopt a model-based approach. We employ the Quick Evaluation of Risk using Mixture of t approximation algorithm (QERMit) of Hoogerheide and van Dijk (2010) due to its accuracy and efficiency, and we upgrade its basic framework in two ways. First, we replace the originally used posterior approximation algorithm with a superior, flexible technique. We report a substantial gain in the accuracy and the precision of estimates in our empirical application based on the daily S&P 500 returns. Second, we extend the basic QERMit framework to allow for latent variables in the underlying model. In this way, the developed technique can be applied to the class of the parameter driven models. We illustrate the procedure using a series of daily IBM returns. Noticeably, all the employed methods are based on importance sampling, which allows for fast computations and is not subject to convergence problem inherent to the alternative Markov Chain Monte Carlo methods. </span> </p>
	</div>
 
* <a class="page-link" href="{{ '/research/A.Borowska - SMC, Selected Topics.pdf' | prepend: site.baseurl | prepend: site.url }}">Sequential Monte Carlo: Selected topics</a>, _Bachelor Thesis in Mathematics_

	<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('smc')">_Abstract_</a>
	<div id="smc" style="display:none;">
	<p>  <span style="font-size:0.85em; text-align: justify;"> We analyse the problem of inference about a latent signal governing the dynamics of a system given only the observed noisy data. We adopt the discrete-time state space approach due to the wide range of problems it can capture. Because in general no closed-form solution are available in this framework, we discuss the class of methods used for approximating of the posterior state distributions, called Sequential Monte Carlo. These methods are based on the Dirac-measures which stem from the draws (particles) from the distribution constructed in the previous iteration. A special attention is devoted to the filtering problem, where one is interested in the estimation of the current state of the system given the current system measurements. We derive theoretical forms of the particle filters, which we then use to construct algorithms suitable for numerical analysis. We discuss the degeneracy problem, inherent to the sequential importance sampling and selected methods to tackle it. The basic convergence results in the context of particle filters are presents. Finally, we consider three numerical application. </span> </p>
	</div>

* <a class="page-link" href="{{ '/research/A.Borowska - The Application of the DSGE-VAR Model to the Polish Macroeconomic Data.pdf' | prepend: site.baseurl | prepend: site.url }}">The Application of the DSGE-VAR Model to the Polish Macroeconomic Data</a>, _Master Thesis in Economics_
 
	<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('dsge')">_Abstract_</a>
	<div id="dsge" style="display:none;">
	<p>  <span style="font-size:0.85em; text-align: justify;"> The DSGE-VAR approach enables to combine the advantages of the theoretically consistent structural models with those of the empirical ones, characterised by the substantial degree of data fit. Moreover, the Bayesian estimation provides a convenient framework to incorporate initial beliefs about the model parameters into the estimation procedure, which seems to be particularly advantageous in the case of rather short time series for Poland. Finally, the obtained estimates allow to assess the extend of the DSGE model misspecification. </span> </p>
	</div>
 