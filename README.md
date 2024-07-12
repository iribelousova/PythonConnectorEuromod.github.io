# *Euromod Connector*

![python](https://img.shields.io/pypi/pyversions/euromod)
![Static Badge](https://img.shields.io/badge/0.1.20a-blu?label=euromod&color=blu)
[![Documentation Status](https://readthedocs.org/projects/pythonconnectoreuromod/badge/?version=latest)](https://pythonconnectoreuromod.readthedocs.io/en/latest/?badge=latest)

## What is _Euromod_?

The Euromod Connector for Python is built to facilitate and simplify the usage of the [EUROMOD](https://euromod-web.jrc.ec.europa.eu "https://euromod-web.jrc.ec.europa.eu") microsimulation model for research and analysis purposes. 

EUROMOD is a tax-benefit microsimulation model for the European Union that enables researchers and policy analysts to calculate, in a comparable manner, the effects of taxes and benefits on household incomes and work incentives for the population of each country and for the EU as a whole. It is a static microsimulation model that applies user-defined tax and benefit policy rules to harmonised microdata on individuals and households, calculates the effects of these rules on household income. 


## Installation 
Python Connector for EUROMOD is available as a source release on [GitHub][gh-release] and 
from the [Python Package Index][pypi]. 

### Requirements
The Euromod Connector requires two EUROMOD components: 1) the model (coded policy rules) , and 2) the input microdata with the variables that respect the EUROMOD naming conventions.
For more information, please, read the sections "Model" and "Input microdata" on the [Download Euromod](https://euromod-web.jrc.ec.europa.eu/download-euromod "https://euromod-web.jrc.ec.europa.eu/download-euromod") web page.


## Documentation

Documentation for Python Connector for EUROMOD is available here:
- [Documentation for Python Connector][doc]
    - [Get started][doc-getstarted]
    - [Simulation examples][doc-simulations]


## License

&copy; Copyright 2024 European Commission. EUROMOD is licensed under the [EUPL, Version 1.2](https://joinup.ec.europa.eu/software/page/eupl). See the
[documentation](http://pythonconnectoreuromod.readthedocs.io/) for details.


[gh-release]: https://github.com/iribelousova/PythonConnectorEuromod/tree/main

[pypi]: https://pypi.org/project/euromod/0.1.20a0/

[doc]: https://github.com/iribelousova/PythonConnectorEuromod

[doc-getstarted]:  https://github.com/iribelousova/PythonConnectorEuromod.github.io/getstarted.html

[doc-simulations]: https://github.com/iribelousova/PythonConnectorEuromod.github.io/example.html

