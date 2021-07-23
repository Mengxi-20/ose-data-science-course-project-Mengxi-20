# Student project: Replication of Chen et. al. (2020) 

This is the final project of the OSE data science course summerterm 2021 by Mengxi Wang.

## Project overview

This repository contains my replication of the main results from [Chen, T., Kung, J. K. S., & Ma, C. (2020)](https://doi.org/10.1093/ej/ueaa043). Long Live Keju! The Persistent Effects of China’s Civil Examination System. The Economic Journal, 130(631), 2030–2064.

Chen et al. (2020) offered an ingenious design and an interesting application of instrumental variables. This observation of a strong, positive relationship between prefectures with a strong historical tradition of exam success and current years of schooling enabled Chen et al. (2020) to contribute important insights to the persistent impact of a remarkably long-lived institution — imperial China’s civil service examination system — methods of selecting candidates or current educational attainment. Moreover, Chen et al. (2020) further demonstrated that this relationship is causal by using the average river distance to a prefecture’s nearest pine and bamboo forests as an instrument, which produced the main tools for printing.

This notebook successfully replicates Chen et al. (2020)’s main results. A causal relationship between the keju and current methods of selecting candidates has been verified. The main results were precisely reproduced in Section 4. In addition, the notebook contains a test of weak instruments and an examination of keju's impacts on populations with distinct levels of educational achievement in 2010 as an extension of Chen et al. (2020)’s findings in Section 5.


<a href="https://nbviewer.jupyter.org/github/OpenSourceEconomics/ose-data-science-course-project-Mengxi-20/blob/master/replication-notebook-mengxi.ipynb"
   target="_parent">
   <img align="center"
  src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.png"
      width="109" height="20">
</a>
<a href="https://mybinder.org/v2/gh/OpenSourceEconomics/ose-data-science-course-project-Mengxi-20/master?filepath=replication-notebook-mengxi.ipynb"
    target="_parent">
    <img align="center"
       src="https://mybinder.org/badge_logo.svg"
       width="109" height="20">
</a>

## Reproducibility

To ensure the reproducibility of the project, the repository is supported by a GitHub Actions Continuos Integration (CI). The state of my workflow can be found here:

</a>
<a href="https://github.com/OpenSourceEconomics/ose-data-science-course-project-Mengxi-20/actions/workflows/ci.yml"
    target="_parent">
    <img align="center"
       src="https://github.com/OpenSourceEconomics/ose-data-science-course-project-Mengxi-20/actions/workflows/ci.yml/badge.svg"
       width="200" height="20">
</a>


## Sources

* Chen, T., Kung, J. K. S., & Ma, C. (2020). Long Live Keju! The Persistent Effects of China’s Civil Examination System. *The Economic Journal*, 130(631), 2030–2064. https://doi.org/10.1093/ej/ueaa043

* Jeffrey M Wooldridge. Econometric analysis of cross section and panel data. MIT press, 2010.

* Jing, X., & Liu, L. (2019). The Equity of Gaokao (National University/College Entrance Examination) in China. *Review of Educational Theory*, 2(3), 29. https://doi.org/10.30564/ret.v2i3.881

* Kuaishou DA Ecology. FixedEffectModel: A Python Package for Linear Model with High Dimensional Fixed Effects.https://github.com/ksecology/FixedEffectModel,2020.Version 0.x

* Semykina & Wooldridge (2010). Estimating panel data models in the presence of endogeneity and selection. *Journal of Econometrics*, 157(2): pp. 375-380. https://doi.org/10.1016/j.jeconom.2010.03.039

