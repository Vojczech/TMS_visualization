# TMS visualization
App for fast plots based on temperature and moisture data from [TMS dataloggers](https://tomst.com/web/en/systems/tms/tms-3/).

To visualize data just upload raw **.csv** file with prefix **data_** downloaded from TMS datalogger. Temperature and moisture data can be easily filtered by date.

There is option to plot data from different combinations of sensors.

#### Combined temperature and moisture data ####
<img src="/data_94174102_0_combined.png" width="600">

#### Temperature data only ####
<img src="/data_94174102_0_temperature.png" width="600">

---
Try it on [labenvmicro.shinyapps.io](https://labenvmicro.shinyapps.io/TMS_app/) or start **R** and type:
```
install.packages(c("shiny", "shinythemes", "readr", "tidyverse", "Rmisc", "tools", "gridExtra", "grid", "shinycssloaders"))
library(shiny)
runGitHub("TMS_visualization", "Vojczech") 
```
---