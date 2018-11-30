# Installation

**NOTE:** 
`ROI.plugin.gurobi` was tested on `Debian GNU/Linux 8 (jessie)` with the
`gurobi` versions `6.5` and `7`. The **ROI** plugin for `gurobi` 8
can be found at 
[`https://github.com/FlorianSchwendinger/ROI.plugin.gurobi`](https://github.com/FlorianSchwendinger/ROI.plugin.gurobi).

Before `ROI.plugin.gurobi` can be installed `gurobi` and its corresponding 
**R** package need to be installed. Both can be obtained from
[https://www.gurobi.com](https://www.gurobi.com) 
and more information about the installation can be found in the `Quick Start Guides` at
[https://www.gurobi.com/documentation](https://www.gurobi.com/documentation).    


After `gurobi` and `gurobi` (**R** package) are installed simply use
```r
remotes:::install_github("FlorianSchwendinger/ROI.plugin.gurobi7")
```
to install `ROI.plugin.gurobi`.
