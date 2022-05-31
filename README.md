Weather Forecasting with SPARQL
===============================

> Implementing a sliding-window algorithm in SPARQL to compute weather
  forecasts


Abstract
--------

Attention to weather conditions is a common topic of conversation in
our daily lives. The weather indeed plays a role in our choices, and
for specific domains like agriculture, maritime transport, or
environment, awareness of weather forecast is crucial and dictates
their decisions and strategies. Recently, multiple initiatives have
been taken by national weather agencies to release online their
weather data as open data archives. Using an RDF dataset [1] of French
weather data, we show here how SPARQL [2] can be used to quickly
compute forecasts relying on a sliding-window algorithm [3]. We make
our system available and hope it will be combined with other resources
to help weather-dependent actors taking decisions.


How to use these resources?
---------------------------

The repository provides SPARQL 1.1 queries to compute sliding-window
algorithms in order to _predict_ weather conditions using open records
from Meteo France and uplifted to RDF in [1].


Repository files
----------------

This repository contains:

- `README.md` (this file): providing documentation;
- `weather-forecast.rq`: the SPARQL able to compute a prediction for average temperatures based on the structure proposed by [1];
- `LICENSE`.


References
----------

[1] <https://zenodo.org/record/5925413#.YpX0PtZ7lFQ>  
[2] <https://www.w3.org/TR/sparql11-query/>  
[3] <https://downloads.hindawi.com/archive/2013/156540.pdf>  


Authors
-------

Damien Graux <https://dgraux.github.io/>  
Nadia Yacoubi Ayadi <https://orcid.org/0000-0002-6132-8718>  
Inria, France  
2022
