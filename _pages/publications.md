---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% if author.googlescholar %}
  You can find a full list of all my publications on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Selected Conference Publications
 ======
 (\* indicates equal contribution)
 
 **Curth, A.**, & van der Schaar, M. (2023). Understanding the Impact of Competing Events on Heterogeneous Treatment Effect Estimation from Time-to-Event Data. In International Conference on Artificial Intelligence and Statistics 2023. PMLR. _To Appear._
 
 Crabbé, J.\*, **Curth, A.**\*, Bica, I.\*, & van der Schaar, M. (2022). Benchmarking heterogeneous treatment effect models through the lens of interpretability. In Thirty-sixth conference on neural information processing systems datasets and benchmarks track. [Link](https://openreview.net/forum?id=ddPXQt-gM--)

Chan, A., **Curth, A.**, & van der Schaar, M. (2022) Inverse Online Learning: Understanding Non-Stationary and Reactionary Policies. In International Conference on Learning Representations (ICLR). [Link](https://openreview.net/forum?id=DYypjaRdph2)

Jarrett, D., Cebere, B. C., Liu, T., **Curth, A.**, & van der Schaar, M. (2022). Hyperimpute: Generalized iterative imputation with automatic model selection. In International Conference on Machine Learning (pp. 9916-9937). PMLR.[Link](https://proceedings.mlr.press/v162/jarrett22a.html)
 
**Curth, A.**, Svensson, D., Weatherall, J., & van der Schaar, M. (2021). Really doing great at estimating CATE? a critical look at ML benchmarking practices in treatment effect estimation. In Thirty-fifth conference on neural information processing systems datasets and benchmarks track (round 2).[Link](https://openreview.net/forum?id=FQLzQqGEAH)
 
**Curth, A**\*, Lee, C.\*,  & van der Schaar, M. (2021). SurvITE: learning heterogeneous treatment effects from time-to-event data. Advances in Neural Information Processing Systems, 34, 26740-26753. [Link](https://proceedings.neurips.cc/paper/2021/hash/e0eacd983971634327ae1819ea8b6214-Abstract.html)
 
 **Curth, A.**, & van der Schaar, M. (2021). On inductive biases for heterogeneous treatment effect estimation. Advances in Neural Information Processing Systems, 34, 15883-15894. [Link](https://proceedings.neurips.cc/paper/2021/hash/8526e0962a844e4a2f158d831d5fddf7-Abstract.html) _NeurIPS Spotlight Paper._
 
**Curth, A.**, & van der Schaar, M. (2021). Nonparametric estimation of heterogeneous treatment effects: From theory to learning algorithms. In International Conference on Artificial Intelligence and Statistics (pp. 1810-1818). PMLR. [Link](https://proceedings.mlr.press/v130/curth21a.html)

 **Curth, A.**, Thoral, P., van den Wildenberg, W., Bijlstra, P., de Bruin, D., Elbers, P., & Fornasa, M. (2019). Transferring clinical prediction models across hospitals and electronic health record systems. In Machine Learning and Knowledge Discovery in Databases: International Workshops of ECML PKDD 2019, Würzburg, Germany, September 16–20, 2019, Proceedings, Part I (pp. 605-621). Springer International Publishing. [Link](https://www.researchgate.net/profile/Paul-Elbers/publication/337821644_Transferring_Clinical_Prediction_Models_across_Hospitals_and_Electronic_Health_Record_Systems/links/5debf83092851c83646b664d/Transferring-Clinical-Prediction-Models-across-Hospitals-and-Electronic-Health-Record-Systems.pdf)
 

## Selected Preprints
 ======
**Curth, A.**, & van der Schaar, M. (2023). In Search of Insights, Not Magic Bullets: Towards Demystification of the Model Selection Dilemma in Heterogeneous Treatment Effect Estimation. arXiv preprint arXiv:2302.02923. [Link](https://arxiv.org/abs/2302.02923)

**Curth, A.**, Hüyük, A., & van der Schaar, M. (2022). Adaptively Identifying Patient Populations With Treatment Benefit in Clinical Trials. arXiv preprint arXiv:2208.05844. [Link](https://arxiv.org/abs/2208.05844) _Presented as Spotlight Paper at the Workshop on Adaptive Experimental Design and Active Learning in the Real World at ICML 2022._

Hatt, T., Berrevoets, J., **Curth, A.**, Feuerriegel, S., & van der Schaar, M. (2022). Combining observational and randomized data for estimating heterogeneous treatment effects. arXiv preprint arXiv:2202.12891. [Link](https://arxiv.org/abs/2202.12891)

Berrevoets, J., **Curth, A.**, Bica, I., McKinney, E., & van der Schaar, M. (2021). Disentangled counterfactual recurrent networks for treatment effect inference over time. arXiv preprint arXiv:2112.03811. [Link](https://arxiv.org/abs/2112.03811)

**Curth, A.**, Alaa, A. M., & van der Schaar, M. (2020). Estimating structural target functions using machine learning and influence functions. arXiv preprint arXiv:2008.06461. [Link](https://arxiv.org/abs/2008.06461) _MSc Dissertation._



{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
