---
title: "GAP: Forecasting commit activity in git projects"
collection: publications
permalink: /publication/2020-jss-gap
excerpt: 'This paper proposes a practicable probabilistic forecasting model based on the statistical technique of survival analysis based on the commit activity of individuals involved in git repositories.'
date: 2020-01-01
venue: 'Journal of Systems and Software'
#paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0164121220300546'
#citation: 'A. Decan, E. Constantinou, T. Mens, H. Rocha, “GAP: Forecasting commit activity in git projects“, Journal of Systems and Software, Elsevier, Vol. 165, pp. 110573, 2020'
---
<a href='https://www.sciencedirect.com/science/article/abs/pii/S0164121220300546'>Download article</a>

<a href='https://decan.lexpage.net/files/JSS-2020.pdf'>Download pre-print</a>

<a href='https://zenodo.org/record/3666048#.X1Yh8Wf7Q8M'>Replication package</a>

Abandonment of active developers poses a significant risk for many open source software projects. This risk can be reduced by forecasting the future activity of contributors involved in such projects. Focusing on the commit activity of individuals involved in git repositories, this paper proposes a practicable probabilistic forecasting model based on the statistical technique of survival analysis. The model is empirically validated on a wide variety of projects accounting for 7528 git repositories and 5947 active contributors. We found that a model based on the last 20 observed days of commit activity per contributor provides the best concordance. We also found that the predictions provided by the model are generally close to actual observations, with slight underestimations for low probability predictions and slight overestimations for higher probability predictions. This model is implemented as part of an open source tool, called GAP, that predicts future commit activity.
