# 6D-BO-Pero-in-air

## Author
[Vincent M. Le Corre](https://github.com/VMLC-PV)  

## Institution
Institute Materials for Electronics and Energy Technology (i-MEET)  
University of Erlangen-Nuremberg (FAU)  
Erlangen, Germany  

Forschungszentrum Jülich GmbH, Helmholtz-Institute Erlangen-Nürnberg (HI ERN), Department of High
Throughput Methods in Photovoltaics
Erlangen, Germany

## Description
This repository contains all the data and code accompanying the publication:  
"Autonomous Optimization of Air-Processed Perovskite Solar Cell in a 6D Parameter Space"  
by Jiyun Zhang, Vincent M. Le Corre, Jianchang Wu, Tian Du, Tobias Osterrieder, Kaicheng Zhang, Handan Zhang, Larry Lüer, Jens Hauch, and Christoph J. Brabec. The publication is currently under review.

## Installation

```
    conda create --name pero
    conda install python==3.12 
    pip install -r requirements.txt
```

Note that this code is based on the [BOAR](https://github.com/i-MEET/boar) package but is kept separate to avoid conflicts with the future development of the BOAR package and make it easy to run the same code as the one used in the publication.