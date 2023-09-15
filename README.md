# danny-amli-testing-grounds
Danny Atherton's testing grounds for edits to jphall663/awesome-machine-learning-interpretability

# awesome-machine-learning-*interpretability* [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated, but probably biased and incomplete, list of awesome machine learning interpretability resources.

If you want to contribute to this list (*and please do!*) read over the [contribution guidelines](contributing.md), send a pull request, or contact me [@jpatrickhall](https://twitter.com/jpatrickhall).

**An incomplete, imperfect blueprint for a more human-centered, lower-risk machine learning.** The resources in this repository can be used to do many of these things today. *The resources in this repository should not be considered legal compliance advice.*

## Table of Contents
### General Resources
* [Comprehensive Software Examples and Tutorials](https://github.com/datherton09/danny-amli-testing-grounds#comprehensive-software-examples-and-tutorials)
* [Books](https://github.com/datherton09/danny-amli-testing-grounds#books)
* [Scholarly Literature on Responsible AI](https://github.com/datherton09/danny-amli-testing-grounds#scholarly-literature-on-responsible-ai)
* [Classes](https://github.com/datherton09/danny-amli-testing-grounds#classes)
* [Glossaries and Dictionaries](https://github.com/datherton09/danny-amli-testing-grounds#glossaries-and-dictionaries)
### Generative AI
### Technical Resources
* [Responsible AI Software Packages](https://github.com/datherton09/danny-amli-testing-grounds#responsible-ai-software-packages)
  * [Browser](https://github.com/datherton09/danny-amli-testing-grounds#browser)
  * [C/C++](https://github.com/datherton09/danny-amli-testing-grounds#cc)
  * [Python](https://github.com/datherton09/danny-amli-testing-grounds#python)
  * [R](https://github.com/datherton09/danny-amli-testing-grounds#r)
* [Machine Learning Environment Management Tools](https://github.com/datherton09/danny-amli-testing-grounds#machine-learning-environment-management-tools)
* [APIs for Responsible AI](https://github.com/datherton09/danny-amli-testing-grounds#apis-for-responsible-ai)
* [Software for Domain-specific Fairness/Explainability](https://github.com/datherton09/danny-amli-testing-grounds#software-for-domain-specific-fairnessexplainability)
### Evaluation and Standards
* [Benchmarks](https://github.com/datherton09/danny-amli-testing-grounds#benchmarks)
* [Datasets for Fairness and Explainability](https://github.com/datherton09/danny-amli-testing-grounds#datasets-for-fairness-and-explainability)
* [Auditing and Evaluation Resources](https://github.com/datherton09/danny-amli-testing-grounds#auditing-and-evaluation-resources)
* [AI Incident Trackers](https://github.com/datherton09/danny-amli-testing-grounds#ai-incident-trackers)
* ### Community and Policy
* [Policy and Regulatory Frameworks](https://github.com/datherton09/danny-amli-testing-grounds#policy-and-regulatory-frameworks)
* [Best Practices](https://github.com/datherton09/danny-amli-testing-grounds#best-practices)
* [Communities and Forums](https://github.com/datherton09/danny-amli-testing-grounds#communities-and-forums)
* [Conferences and Workshops](https://github.com/datherton09/danny-amli-testing-grounds#conferences-and-workshops)
### Additional Resources
* [Challenges and Competitions](https://github.com/datherton09/danny-amli-testing-grounds#challenges-and-competitions)
* [Other Interpretability and Fairness Resources and Lists](https://github.com/datherton09/danny-amli-testing-grounds#other-interpretability-and-fairness-resources-and-lists)
### Curated Bibliographies
* [NIST Playbook_Measure_FullLaunch](https://github.com/datherton09/danny-amli-testing-grounds#nist-playbook-measure-fulllaunch)

## General Resources
### Comprehensive Software Examples and Tutorials
This section is a curated collection of guides and tutorials that simplify responsible AI and machine learning. It spans from basic model interpretability to advanced fairness techniques. Suitable for both novices and experts, the resources cover topics like COMPAS fairness analyses and explainable machine learning via counterfactuals. Notable contributions, such as Dipanjan (DJ) Sarkar's Model Interpretation series, are included. Python and R code examples are provided for easy implementation.
* [COMPAS Analysis Using Aequitas](https://github.com/dssg/aequitas/blob/master/docs/source/examples/compas_demo.ipynb)
* [Explaining Quantitative Measures of Fairness (with SHAP)](https://github.com/slundberg/shap/blob/master/notebooks/overviews/Explaining%20quantitative%20measures%20of%20fairness.ipynb)
* [Getting a Window into your Black Box Model](http://projects.rajivshah.com/inter/ReasonCode_NFL.html)
* [From GLM to GBM Part 1](https://www.h2o.ai/blog/from-glm-to-gbm-part-1/)
* [From GLM to GBM Part 2](https://www.h2o.ai/blog/from-glm-to-gbm-part-2/)
* [IML](https://mybinder.org/v2/gh/christophM/iml/master?filepath=./notebooks/tutorial-intro.ipynb)
* [Interpretable Machine Learning with Python](https://github.com/jphall663/interpretable_machine_learning_with_python)
* [Interpreting Machine Learning Models with the iml Package](http://uc-r.github.io/iml-pkg)
* [Interpretable Machine Learning using Counterfactuals](https://docs.seldon.io/projects/alibi/en/v0.2.0/examples/cf_mnist.html)
* [Machine Learning Explainability by Kaggle Learn](https://www.kaggle.com/learn/machine-learning-explainability)
* [Model Interpretability with DALEX](http://uc-r.github.io/dalex)
* Model Interpretation series by Dipanjan (DJ) Sarkar:
  * [The Importance of Human Interpretable Machine Learning](https://towardsdatascience.com/human-interpretable-machine-learning-part-1-the-need-and-importance-of-model-interpretation-2ed758f5f476)
  * [Model Interpretation Strategies](https://towardsdatascience.com/explainable-artificial-intelligence-part-2-model-interpretation-strategies-75d4afa6b739)
  * [Hands-on Machine Learning Model Interpretation](https://towardsdatascience.com/explainable-artificial-intelligence-part-3-hands-on-machine-learning-model-interpretation-e8ebe5afc608)
  * [Interpreting Deep Learning Models for Computer Vision](https://towardsdatascience.com/explainable-artificial-intelligence-part-3-hands-on-machine-learning-model-interpretation-e8ebe5afc608)
* [Partial Dependence Plots in R](https://journal.r-project.org/archive/2017/RJ-2017-016/)
* [PiML-Toolbox](https://github.com/SelfExplainML/PiML-Toolbox/tree/main/examples)
* [Saliency Maps for Deep Learning](https://medium.com/@thelastalias/saliency-maps-for-deep-learning-part-1-vanilla-gradient-1d0665de3284)
* [Visualizing ML Models with LIME](http://uc-r.github.io/lime)
* [Visualizing and debugging deep convolutional networks](https://rohitghosh.github.io/2018/01/05/visualising-debugging-deep-neural-networks/)
* [What does a CNN see?](https://colab.research.google.com/drive/1xM6UZ9OdpGDnHBljZ0RglHV_kBrZ4e-9)

### Books
This section contains books that are either freely downloadable or links to full Internet Archive scans of books that can be borrowed with a free account.
* [An Introduction to Machine Learning Interpretability](https://www.h2o.ai/wp-content/uploads/2019/08/An-Introduction-to-Machine-Learning-Interpretability-Second-Edition.pdf)
* [Explanatory Model Analysis](https://pbiecek.github.io/ema/)
* [Fairness and Machine Learning](http://fairmlbook.org/)
* [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)
* [Machine Learning for High-Risk Applications: Approaches to Responsible AI](https://pages.dataiku.com/oreilly-responsible-ai)
* [Responsible Machine Learning](https://www.h2o.ai/resources/ebook/responsible-machine-learning/) (requires email for now)
* [Trustworthy Machine Learning](http://www.trustworthymachinelearning.com/)

### Scholarly Literature on Responsible AI
* [50 Years of Test (Un)fairness: Lessons for Machine Learning](https://arxiv.org/pdf/1811.10104.pdf)
* [A Comparative Study of Fairness-Enhancing Interventions in Machine Learning](https://arxiv.org/pdf/1802.04422.pdf)
* [A Survey Of Methods For Explaining Black Box Models](https://arxiv.org/pdf/1802.01933.pdf)
* [A Marauder’s Map of Security and Privacy in Machine Learning](https://arxiv.org/pdf/1811.01134.pdf)
* [Challenges for Transparency](https://arxiv.org/pdf/1708.01870.pdf)
* [Closing the AI Accountability Gap](https://arxiv.org/pdf/2001.00973.pdf)
* [DQI: Measuring Data Quality in NLP](https://arxiv.org/pdf/2005.00816.pdf)
* [Explaining by Removing: A Unified Framework for Model Explanation](https://arxiv.org/abs/2011.14878)
* [Explaining Explanations: An Overview of Interpretability of Machine Learning](https://arxiv.org/pdf/1806.00069.pdf)
* [Explanation in Human-AI Systems: A Literature Meta-Review, Synopsis of Key Ideas and Publications, and Bibliography for Explainable AI](https://arxiv.org/abs/1902.01876v1)
* [Interpretable Machine Learning: Definitions, Methods, and Applications](https://arxiv.org/abs/1901.04592)
* [Limitations of Interpretable Machine Learning](https://compstat-lmu.github.io/iml_methods_limitations/)
* [Machine Learning Explainability in Finance](https://www.bankofengland.co.uk/-/media/boe/files/working-paper/2019/machine-learning-explainability-in-finance-an-application-to-default-risk-analysis)
* [On the Art and Science of Machine Learning Explanations](https://arxiv.org/pdf/1810.02909.pdf)
* [Please Stop Explaining Black Box Models for High-Stakes Decisions](https://arxiv.org/pdf/1811.10154.pdf)
* [Software Engineering for Machine Learning: A Case Study](https://www.microsoft.com/en-us/research/uploads/prod/2019/03/amershi-icse-2019_Software_Engineering_for_Machine_Learning.pdf)
* [The Mythos of Model Interpretability](https://arxiv.org/pdf/1606.03490.pdf)
* [Towards A Rigorous Science of Interpretable Machine Learning](https://arxiv.org/pdf/1702.08608.pdf)
* [Toward Trustworthy AI Development: Mechanisms for Supporting Verifiable Claims](https://arxiv.org/pdf/2004.07213.pdf)
* [The Security of Machine Learning](https://people.eecs.berkeley.edu/~adj/publications/paper-files/SecML-MLJ2010.pdf)
* [Techniques for Interpretable Machine Learning](https://arxiv.org/pdf/1808.00033.pdf)
* [Trends and Trajectories for Explainable, Accountable and Intelligible Systems: An HCI Research Agenda](https://dl.acm.org/citation.cfm?id=3174156)
* [Underspecification Presents Challenges for Credibility in Modern Machine Learning](https://arxiv.org/pdf/2011.03395.pdf)

### Classes
This section features a selection of educational courses focused on ethical considerations and best practices in emerging technologies like AI and machine learning. The classes range from introductory courses on data ethics to specialized training in fairness and trustworthy deep learning.
* [An Introduction to Data Ethics](https://www.scu.edu/ethics/focus-areas/technology-ethics/resources/an-introduction-to-data-ethics/)
* [Certified Ethical Emerging Technologist](https://certnexus.com/certification/ceet/)
* [Fairness in Machine Learning](https://fairmlclass.github.io/)
* [Fast.ai Data Ethics course](http://ethics.fast.ai/syllabus/#lesson-2-bias--fairness)
* [Human-Center Machine Learning](http://courses.mpi-sws.org/hcml-ws18/)
* [Introduction to Responsible Machine Learning](https://jphall663.github.io/GWU_rml/)
* [Trustworthy Deep Learning](https://berkeley-deep-learning.github.io/cs294-131-s19/)

### Glossaries and Dictionaries
This section features a collection of either freely accessible or Internet Archive-accessible glossaries and dictionaries that are in any way geared toward defining terms in artificial intelligence. 
* [The Language of Trustworthy AI: An In-Depth Glossary of Terms (NIST AIRC)) Glossary](https://airc.nist.gov/AI_RMF_Knowledge_Base/Glossary)
* [VAIR (Vocabulary of AI Risks)](https://delaramglp.github.io/vair/)

# Generative AI
* [Andreessen Horowitz (a16z) AI Canon](https://a16z.com/ai-canon/)
* [DAIR Prompt Engineering Guide](https://www.promptingguide.ai/)
 * [DAIR Prompt Engineering Guide GitHub](https://github.com/dair-ai/Prompt-Engineering-Guide)  

# Technical Resources
## Responsible AI Software Packages
### Browser
* [DiscriLens](https://github.com/wangqianwen0418/DiscriLens)
* [manifold](https://github.com/uber/manifold)
* [TensorBoard Projector](http://projector.tensorflow.org)
* [What-if Tool](https://pair-code.github.io/what-if-tool/index.html#about)
### C/C++
* [Born-again Tree Ensembles](https://github.com/vidalt/BA-Trees)
* [Certifiably Optimal RulE ListS](https://github.com/nlarusstone/corels)
### Python
* [acd](https://github.com/csinva/hierarchical_dnn_interpretations)
* [aequitas](https://github.com/dssg/aequitas)
* [AI Fairness 360](http://aif360.mybluemix.net)
* [AI Explainability 360](https://github.com/IBM/AIX360)
* [ALEPython](https://github.com/blent-ai/ALEPython)
* [Aletheia](https://github.com/SelfExplainML/Aletheia)
* [allennlp](https://github.com/allenai/allennlp)
* [algofairness](https://github.com/algofairness)
* [Alibi](https://github.com/SeldonIO/alibi)
* [anchor](https://github.com/marcotcr/anchor)
* [BlackBoxAuditing](https://github.com/algofairness/BlackBoxAuditing)
* [casme](https://github.com/kondiz/casme)
* [Causal Discovery Toolbox](https://github.com/FenTechSolutions/CausalDiscoveryToolbox)
* [captum](https://github.com/pytorch/captum)
* [causalml](https://github.com/uber/causalml)
* [cdt15](https://github.com/cdt15)
* [checklist](https://github.com/marcotcr/checklist)
* [contextual-AI](https://github.com/SAP/contextual-ai)
* [ContrastiveExplanation (Foil Trees)](https://github.com/MarcelRobeer/ContrastiveExplanation)
* [counterfit](https://github.com/Azure/counterfit/)
* [dalex](https://github.com/ModelOriented/DALEX)
* [debiaswe](https://github.com/tolga-b/debiaswe)
* [DeepExplain](https://github.com/marcoancona/DeepExplain)
* [deeplift](https://github.com/kundajelab/deeplift)
* [deepvis](https://github.com/yosinski/deep-visualization-toolbox)
* [DiCE](https://github.com/interpretml/DiCE)
* [DoWhy](https://github.com/microsoft/dowhy)
* [ecco](https://github.com/jalammar/ecco)
* [eli5](https://github.com/TeamHG-Memex/eli5)
* [explainerdashboard](https://github.com/oegedijk/explainerdashboard)
* [fairml](https://github.com/adebayoj/fairml)
* [fairlearn](https://github.com/fairlearn/fairlearn)
* [fairness-comparison](https://github.com/algofairness/fairness-comparison)
* [fairness_measures_code](https://github.com/megantosh/fairness_measures_code)
* [foolbox](https://github.com/bethgelab/foolbox)
* [Grad-CAM](https://github.com/topics/grad-cam) (GitHub topic)
* [gplearn](https://github.com/trevorstephens/gplearn)
* [hate-functional-tests](https://github.com/paul-rottger/hate-functional-tests)
* [imodels](https://github.com/csinva/imodels)
* [iNNvestigate neural nets](https://github.com/albermax/innvestigate)
* [Integrated-Gradients](https://github.com/ankurtaly/Integrated-Gradients)
* [interpret](https://github.com/interpretml/interpret)
* [interpret_with_rules](https://github.com/clips/interpret_with_rules)
* [Keras-vis](https://github.com/raghakot/keras-vis)
* [keract](https://github.com/philipperemy/keract/)
* [L2X](https://github.com/Jianbo-Lab/L2X)
* [lime](https://github.com/marcotcr/lime)
* [LiFT](https://github.com/linkedin/LiFT)
* [lit](https://github.com/pair-code/lit)
* [lofo-importance](https://github.com/aerdem4/lofo-importance)
* [lrp_toolbox](https://github.com/sebastian-lapuschkin/lrp_toolbox)
* [MindsDB](https://github.com/mindsdb/mindsdb)
* [MLextend](http://rasbt.github.io/mlxtend/)
* [ml-fairness-gym](https://github.com/google/ml-fairness-gym)
* [ml_privacy_meter](https://github.com/privacytrustlab/ml_privacy_meter)
* [OptBinning](https://github.com/guillermo-navas-palencia/optbinning)
* [parity-fairness](https://pypi.org/project/parity-fairness/)
* [PDPbox](https://github.com/SauceCat/PDPbox)
* [pyBreakDown](https://github.com/MI2DataLab/pyBreakDown)
* [PyCEbox](https://github.com/AustinRochford/PyCEbox)
* [pyGAM](https://github.com/dswah/pyGAM)
* [pymc3](https://github.com/pymc-devs/pymc3)
* [pytorch-innvestigate](https://github.com/fgxaos/pytorch-innvestigate)
* [rationale](https://github.com/taolei87/rcnn/tree/master/code/rationale)
* [responsibly](https://github.com/ResponsiblyAI/responsibly)
* [revise-tool](https://github.com/princetonvisualai/revise-tool)
* [robustness](https://github.com/MadryLab/robustness)
* [RISE](https://github.com/eclique/RISE)
* [sage](https://github.com/iancovert/sage/)
* [SALib](https://github.com/SALib/SALib)
* [scikit-fairness](https://github.com/koaning/scikit-fairness)
* [scikit-multiflow](https://scikit-multiflow.github.io/)
* [shap](https://github.com/slundberg/shap)
* [shapley](https://github.com/benedekrozemberczki/shapley)
* [Skater](https://github.com/datascienceinc/Skater)
* [tensorfow/cleverhans](https://github.com/tensorflow/cleverhans)
* [tensorflow/lucid](https://github.com/tensorflow/lucid)
* [tensorflow/fairness-indicators](https://github.com/tensorflow/fairness-indicators)
* [tensorflow/model-analysis](https://github.com/tensorflow/model-analysis)
* [tensorflow/model-card-toolkit](https://github.com/tensorflow/model-card-toolkit)
* [tensorflow/model-remediation](https://github.com/tensorflow/model-remediation)
* [tensorflow/privacy](https://github.com/tensorflow/privacy)
* [tensorflow/tcav](https://github.com/tensorflow/tcav)
* [tensorfuzz](https://github.com/brain-research/tensorfuzz)
* [TensorWatch](https://github.com/microsoft/tensorwatch)
* [TextFooler](https://github.com/jind11/TextFooler)
* [tf-explain](https://github.com/sicara/tf-explain)
* [Themis](https://github.com/LASER-UMASS/Themis)
* [themis-ml](https://github.com/cosmicBboy/themis-ml)
* [treeinterpreter](https://github.com/andosa/treeinterpreter)
* [woe](https://github.com/boredbird/woe)
* [xai](https://github.com/EthicalML/xai)
* [xdeep](https://github.com/datamllab/xdeep)
* [yellowbrick](https://github.com/DistrictDataLabs/yellowbrick)
* [Bayesian Case Model](https://users.cs.duke.edu/~cynthia/code/BCM.zip)
* [Bayesian Ors-Of-Ands](https://github.com/wangtongada/BOA)
* [Bayesian Rule List (BRL)](https://users.cs.duke.edu/~cynthia/code/BRL_supplement_code.zip)
* [Explainable Boosting Machine (EBM)/GA2M](https://github.com/interpretml/interpret)
* [fair-classification](https://github.com/mbilalzafar/fair-classification)
* [Falling Rule List (FRL)](https://users.cs.duke.edu/~cynthia/code/falling_rule_list.zip)
* H2O-3
  * [Penalized Generalized Linear Models](http://docs.h2o.ai/h2o/latest-stable/h2o-py/docs/modeling.html#h2ogeneralizedlinearestimator)
  * [Monotonic GBM](http://docs.h2o.ai/h2o/latest-stable/h2o-py/docs/modeling.html#h2ogradientboostingestimator)
  * [Sparse Principal Components (GLRM)](http://docs.h2o.ai/h2o/latest-stable/h2o-py/docs/modeling.html#h2ogeneralizedlowrankestimator)
* [learning-fair-representations](https://github.com/zjelveh/learning-fair-representations)
* [Optimal Sparse Decision Trees](https://github.com/xiyanghu/OSDT)
* [Monotonic](http://xgboost.readthedocs.io/en/latest/tutorials/monotonic.html) [XGBoost](http://xgboost.readthedocs.io/en/latest/)
* [Multilayer Logical Perceptron (MLLP)](https://github.com/12wang3/mllp)
* [pySS3](https://github.com/sergioburdisso/pyss3)
* [Risk-SLIM](https://github.com/ustunb/risk-SLIM)
* Scikit-learn
  * [Decision Trees](http://scikit-learn.org/stable/modules/tree.html)
  * [Generalized Linear Models](http://scikit-learn.org/stable/modules/linear_model.html)
  * [Sparse Principal Components](http://scikit-learn.org/stable/modules/decomposition.html#sparse-principal-components-analysis-sparsepca-and-minibatchsparsepca)
* [sklearn-expertsys](https://github.com/tmadl/sklearn-expertsys)
* [skope-rules](https://github.com/scikit-learn-contrib/skope-rules)
* [Super-sparse Linear Integer models (SLIMs)](https://github.com/ustunb/slim-python)
* [tensorflow/lattice](https://github.com/tensorflow/lattice)
* [This Looks Like That](https://github.com/cfchen-duke/ProtoPNet)
### R
* [aif360](https://cran.r-project.org/web/packages/aif360/index.html)
* [ALEPlot](https://cran.r-project.org/web/packages/ALEPlot/index.html)
* [arules](https://cran.r-project.org/web/packages/arules/index.html)
* [Causal SVM](https://github.com/shangtai/githubcausalsvm)
* [DALEX](https://github.com/ModelOriented/DALEX)
* [DALEXtra](https://cran.r-project.org/web/packages/DALEXtra/index.html)
* [DrWhyAI](https://github.com/ModelOriented/DrWhy)
* [elasticnet](https://cran.r-project.org/web/packages/elasticnet/index.html)
* [ExplainPrediction](https://github.com/rmarko/ExplainPrediction)
* [Explainable Boosting Machine (EBM)/GA2M](https://cran.r-project.org/web/packages/interpret/index.html)
* [fairmodels](https://github.com/ModelOriented/fairmodels)
* [fairness](https://cran.r-project.org/web/packages/fairness/index.html)
* [fastshap](https://github.com/bgreenwell/fastshap)
* [featureImportance](https://github.com/giuseppec/featureImportance)
* [flashlight](https://github.com/mayer79/flashlight)
* [forestmodel](https://cran.r-project.org/web/packages/forestmodel/index.html)
* [fscaret](https://cran.r-project.org/web/packages/fscaret/)
* [gam](https://cran.r-project.org/web/packages/gam/index.html)
* [glm2](https://cran.r-project.org/web/packages/glm2/)
* [glmnet](https://cran.r-project.org/web/packages/glmnet/index.html)
* H2O-3
  * [Penalized Generalized Linear Models](http://docs.h2o.ai/h2o/latest-stable/h2o-r/docs/reference/h2o.glm.html)
  * [Monotonic GBM](http://docs.h2o.ai/h2o/latest-stable/h2o-r/docs/reference/h2o.gbm.html)
  * [Sparse Principal Components (GLRM)](http://docs.h2o.ai/h2o/latest-stable/h2o-r/docs/reference/h2o.glrm.html)
* [iBreakDown](https://github.com/ModelOriented/iBreakDown)
* [ICEbox](https://cran.r-project.org/web/packages/ICEbox/index.html)
* [iml](https://github.com/christophM/iml)
* [ingredients](https://github.com/ModelOriented/ingredients)
* [intepret](https://cran.r-project.org/web/packages/interpret/index.html)
* [lightgbmExplainer](https://github.com/lantanacamara/lightgbmExplainer)
* [lime](https://github.com/thomasp85/lime)
* [live](https://cran.r-project.org/web/packages/live/index.html)
* [mcr](https://github.com/aaronjfisher/mcr)
* [modelDown](https://cran.r-project.org/web/packages/modelDown/index.html)
* [modelOriented](https://github.com/ModelOriented)
* [modelStudio](https://github.com/ModelOriented/modelStudio)
* [Monotonic](http://xgboost.readthedocs.io/en/latest/tutorials/monotonic.html) [XGBoost](http://xgboost.readthedocs.io/en/latest/)
* [pdp](https://bgreenwell.github.io/pdp/index.html)
* [quantreg](https://cran.r-project.org/web/packages/quantreg/index.html)
* [rpart](https://cran.r-project.org/web/packages/rpart/index.html)
* [RuleFit](http://statweb.stanford.edu/~jhf/R_RuleFit.html)
* [Scalable Bayesian Rule Lists (SBRL)](https://users.cs.duke.edu/~cynthia/code/sbrl_1.0.tar.gz)
* [shapFlex](https://github.com/nredell/shapFlex)
* [shapleyR](https://github.com/redichh/ShapleyR)
* [shapper](https://cran.r-project.org/web/packages/shapper/index.html)
* [smbinning](https://cran.r-project.org/web/packages/smbinning/index.html)
* [vip](https://github.com/koalaverse/vip)
* [xgboostExplainer](https://github.com/AppliedDataSciencePartners/xgboostExplainer)

## Machine Learning Environment Management Tools
* [dvc](https://dvc.org/)
* [gigantum](https://github.com/gigantum)
* [mlflow](https://mlflow.org/)
* [mlmd](https://github.com/google/ml-metadata)
* [modeldb](https://github.com/VertaAI/modeldb)
* [whylabs](https://www.rsqrdai.org/)
## APIs for Responsible AI
This section features a selection of APIs designed to enhance interpretability and fairness in machine learning models. These APIs provide a straightforward way to integrate ethical considerations and model transparency into your existing projects. From explainability metrics to fairness audits, these tools offer pre-built functionalities that can assist both novice and experienced practitioners in achieving responsible AI deployment. 
### Interpretability APIs
- [SHAP](https://github.com/slundberg/shap)
- [LIME](https://github.com/marcotcr/lime)
- [Anchor](https://github.com/marcotcr/anchor)
- [Counterfactual Explanations](https://github.com/SeldonIO/alibi)
### Fairness APIs
- [Aequitas](https://github.com/dssg/aequitas)
- [Fairlearn](https://github.com/fairlearn/fairlearn)
- [What-If Tool](https://pair-code.github.io/what-if-tool/)
- [IBM AI Fairness 360](https://github.com/IBM/AIF360)
- [Themis-ML](https://github.com/cosmicBboy/themis-ml)

## Software for Domain-specific Fairness/Explainability
This section curates specialized software tools aimed at fairness and explainability within specific domains, such as in healthcare, finance, or social sciences.

# Evaluation and Standards
## Benchmarks
* [Bias Benchmark for QA dataset (BBQ)](https://github.com/nyu-mll/bbq)

## Common Datasets for Responsible AI
* [Adult income dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)
* [All Lending Club loan data](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
* [Bias Benchmark for QA dataset (BBQ)](https://github.com/nyu-mll/bbq)
* [Census income classification with scikit-learn](https://shap.readthedocs.io/en/latest/example_notebooks/tabular_examples/model_agnostic/Census%20income%20classification%20with%20scikit-learn.html)
* [COMPAS Recidivism Risk Score Data and Analysis](https://www.propublica.org/datastore/dataset/compas-recidivism-risk-score-data-and-analysis)
* [Iris flower dataset](https://archive.ics.uci.edu/dataset/53/iris)
* [MIMIC-III Clinical Database](https://physionet.org/content/mimiciii/1.4/)
* [NYPD Stop, Question and Frisk Data](https://www.nyc.gov/site/nypd/stats/reports-analysis/stopfrisk.page)
* [OpenML Benchmarking Suites](https://openreview.net/forum?id=OCrD8ycKjG)
* [Real Toxicity Prompts (Allen Institute for AI)](https://allenai.org/data/real-toxicity-prompts)
* [Statlog (German Credit Data)](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)
* [TruthfulQA](https://github.com/sylinrl/TruthfulQA)
* [Wikipedia Talk Labels: Personal Attacks](https://www.kaggle.com/datasets/jigsaw-team/wikipedia-talk-labels-personal-attacks)
* [Winogender Schemas](https://github.com/rudinger/winogender-schemas)

## Auditing and Evaluation Resources
* [De-risking Language Models for Adoption](https://docs.google.com/presentation/d/1m0p1KcYw-HM6U0hr_8egH2-7v4SlQhJq/edit#slide=id.p17)
* [IQT Labs AI Assurance Audit of RoBERTa, an Open source, Pretrained Large Language Model](https://assets.iqt.org/pdfs/IQTLabs_RoBERTaAudit_Dec2022_final.pdf/web/viewer.html)

## AI Incident Trackers
* [AI Incident Database (Responsible AI Collaborative)](https://incidentdatabase.ai/)
* [AI Vulnerability Database (AVID)](https://avidml.org/)
* [AIAAIC](https://www.aiaaic.org/)
* [George Washington University Law School's AI Litigation Database](https://blogs.gwu.edu/law-eti/ai-litigation-database/)
* [Verica Open Incident Database (VOID)](https://www.thevoid.community/)

# Community and Policy
## Policy and Regulatory Frameworks
This section serves as a repository for policy documents, regulations, guidelines, and recommendations that govern the ethical and responsible use of artificial intelligence and machine learning technologies. From international legal frameworks to specific national laws, the resources cover a broad spectrum of topics such as fairness, privacy, ethics, and governance. 
* [12 CFR Part 1002 - Equal Credit Opportunity Act (Regulation B)](https://www.consumerfinance.gov/policy-compliance/rulemaking/regulations/1002/)
* [A Regulatory Framework for AI: Recommendations for PIPEDA Reform](https://www.priv.gc.ca/en/about-the-opc/what-we-do/consultations/completed-consultations/consultation-ai/reg-fw_202011/)
* [AI Principles: Recommendations on the Ethical Use of Artificial Intelligence by the Department of Defense](https://media.defense.gov/2019/Oct/31/2002204458/-1/-1/0/DIB_AI_PRINCIPLES_PRIMARY_DOCUMENT.PDF)
* [THE AIM INITIATIVE](https://www.dni.gov/files/ODNI/documents/AIM-Strategy.pdf)
* [Aiming for truth, fairness, and equity in your company’s use of AI](https://www.ftc.gov/news-events/blogs/business-blog/2021/04/aiming-truth-fairness-equity-your-companys-use-ai)
* [Algorithmic Accountability Act of 2019](https://www.wyden.senate.gov/imo/media/doc/Algorithmic%20Accountability%20Act%20of%202019%20Bill%20Text.pdf)
* [ALGORITHM CHARTER FOR AOTEAROA NEW ZEALAND](https://data.govt.nz/assets/data-ethics/algorithm/Algorithm-Charter-2020_Final-English-1.pdf)
* [Artificial Intelligence (AI) in the Securities Industry](https://www.finra.org/sites/default/files/2020-06/ai-report-061020.pdf)
* [Article 22 EU GDPR](https://www.privacy-regulation.eu/en/article-22-automated-individual-decision-making-including-profiling-GDPR.htm)
* [Assessment List for Trustworthy Artificial Intelligence (ALTAI) for self-assessment - Shaping Europe’s digital future - European Commission](https://ec.europa.eu/digital-single-market/en/news/assessment-list-trustworthy-artificial-intelligence-altai-self-assessment)
* [Audit of Governance and Protection of Department of Defense Artificial Intelligence Data and Technology](https://media.defense.gov/2020/Jul/01/2002347967/-1/-1/1/DODIG-2020-098.PDF)
* [A Primer on Artificial Intelligence in Securities Markets](https://www.cftc.gov/media/2846/LabCFTC_PrimerArtificialIntelligence102119/download)
* [Biometric Information Privacy Act](https://www.ilga.gov/legislation/ilcs/ilcs3.asp?ActID=3004&ChapterID=57)
* [Booker Wyden Health Care Letters](https://www.scribd.com/document/437954989/Booker-Wyden-Health-Care-Letters#download)
* [California Consumer Privacy Act (CCPA)](https://oag.ca.gov/privacy/ccpa)
* [California Privacy Rights Act (CPRA)](https://www.oag.ca.gov/system/files/initiatives/pdfs/19-0021A1%20%28Consumer%20Privacy%20-%20Version%203%29_1.pdf)
* [Consultation on the OPC’s Proposals for ensuring appropriate regulation of artificial intelligence](https://www.priv.gc.ca/en/about-the-opc/what-we-do/consultations/consultation-ai/pos_ai_202001/)
* [Civil liability regime for artificial intelligence](https://www.europarl.europa.eu/doceo/document/TA-9-2020-0276_EN.pdf)
* [Data Ethics Framework](https://strategy-staging.data.gov/assets/docs/data-ethics-framework-action-14-draft-2020-sep-2.pdf)
* [DEVELOPING FINANCIAL SECTOR RESILIENCE IN A DIGITAL WORLD: SELECTED THEMES IN TECHNOLOGY AND RELATED RISKS](https://www.osfi-bsif.gc.ca/Eng/Docs/tchrsk.pdf)
* [Directive on Automated Decision Making](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=32592)
* [Executive Order on Promoting the Use of Trustworthy Artificial Intelligence in the Federal Government](https://www.whitehouse.gov/presidential-actions/executive-order-promoting-use-trustworthy-artificial-intelligence-federal-government/)
* [EEOC Letter (from U.S. senators re: hiring software)](https://www.bennet.senate.gov/public/_cache/files/0/a/0a439d4b-e373-4451-84ed-ba333ce6d1dd/672D2E4304D63A04CC3465C3C8BF1D21.letter-to-chair-dhillon.pdf)
* [Facial Recognition and Biometric Technology Moratorium Act of 2020](https://drive.google.com/file/d/1gkTcjFtieMQdsQ01dmDa49B6HY9ZyKr8/view)
* [Four Principles of Explainable Artificial Intelligence ](https://www.nist.gov/system/files/documents/2020/08/17/NIST%20Explainable%20AI%20Draft%20NISTIR8312%20%281%29.pdf)
* [General principles for the use of Artificial Intelligence in the financial sector](https://www.dnb.nl/media/jkbip2jc/general-principles-for-the-use-of-artificial-intelligence-in-the-financial-sector.pdf)
* [Gouvernance des algorithmes d’intelligence artificielle dans le secteur financier (French)](https://acpr.banque-france.fr/sites/default/files/medias/documents/20200612_gouvernance_evaluation_ia.pdf)
* [Innovation spotlight: Providing adverse action notices when using AI/ML models](https://www.consumerfinance.gov/about-us/blog/innovation-spotlight-providing-adverse-action-notices-when-using-ai-ml-models/)
* [Meta AI's Responsible Use Guide](https://ai.meta.com/llama/responsible-use-guide/)
* [Office of Management and Budget Guidance for Regulation of Artificial Intelligence Applications](https://www.whitehouse.gov/wp-content/uploads/2020/11/M-21-06.pdf) (Finalized Nov. 2020)
* [On Artificial Intelligence - A European approach to excellence and trust](https://ec.europa.eu/info/sites/info/files/commission-white-paper-artificial-intelligence-feb2020_en.pdf)
* [Opinion of the German Data Ethics Commission](https://www.bmjv.de/SharedDocs/Downloads/DE/Themen/Fokusthemen/Gutachten_DEK_EN.pdf?__blob=publicationFile&v=2)
* [NIST AI 100-1 Artificial Intelligence Risk Management Framework (NIST AI RMF 1.0)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf)
* [PAI's Responsible Practices for Synthetic Media: A Framework for Collective Action (Partnership on AI)](https://syntheticmedia.partnershiponai.org/)
* [Principles of Artificial Intelligence Ethics for the Intelligence Community](https://www.intel.gov/principles-of-artificial-intelligence-ethics-for-the-intelligence-community)
* [Proposal for a Regulation laying down harmonised rules on artificial intelligence (Artificial Intelligence Act)](https://digital-strategy.ec.europa.eu/en/library/proposal-regulation-laying-down-harmonised-rules-artificial-intelligence-artificial-intelligence)
* [Psychological Foundations of Explainability and Interpretability in Artificial Intelligence](https://nvlpubs.nist.gov/nistpubs/ir/2021/NIST.IR.8367.pdf)
* [Questions and Answers to Clarify and Provide a Common Interpretation of the Uniform Guidelines on Employee Selection Procedures](https://www.eeoc.gov/laws/guidance/questions-and-answers-clarify-and-provide-common-interpretation-uniform-guidelines)
* [Questions from the Commission on Protecting Privacy and Preventing Discrimination](https://auditor.utah.gov/wp-content/uploads/sites/6/2021/02/Office-of-the-State-Auditor-Questions-to-help-Procuring-Agencies-_-Entities-with-Software-Procurement-Feb-1-2021-Final.pdf)
* [RE: Use of External Consumer Data and Information Sources in Underwriting for Life Insurance](https://www.dfs.ny.gov/industry_guidance/circular_letters/cl2019_01)
* [Singapore Personal Data Protection Commission (PDPC) Model Artificial Intelligence Governance Framework](https://www.pdpc.gov.sg/Help-and-Resources/2020/01/Model-AI-Governance-Framework)
* [SUPERVISORY GUIDANCE ON MODEL RISK MANAGEMENT](https://www.federalreserve.gov/supervisionreg/srletters/sr1107a1.pdf)
* [U.K. Information Commissioner's Office (ICO) AI Audting Framework (overview series)](https://ico.org.uk/about-the-ico/news-and-events/ai-blog-an-overview-of-the-auditing-framework-for-artificial-intelligence-and-its-core-components/)
* [Artificial Intelligence/Machine Learning (AI/ML)-Based: Software as a Medical Device (SaMD) Action Plan](https://www.fda.gov/media/145022/download) (Updated Jan. 2021)
* [U.S. House of Representatives Resolution on AI Strategy](https://hurd.house.gov/sites/hurd.house.gov/files/HURDTX_AI%20Res.pdf)
* [Using Artificial Intelligence and Algorithms](https://www.ftc.gov/news-events/blogs/business-blog/2020/04/using-artificial-intelligence-algorithms)

## Best Practices

## Communities and Forums

## Conferences and Workshops
* [FAT/ML (Fairness, Accountability, and Transparency in Machine Learning)](https://www.fatml.org/)
* [AIES (AAAI/ACM Conference on AI, Ethics, and Society)](https://www.aies-conference.com/)
* [NeurIPS Workshop on Ethical, Social and Governance Issues in AI](https://nips.cc/Conferences/)
* [ICML Workshop on Fairness, Accountability, and Transparency in Machine Learning](https://icml.cc/)
* [ACM FAccT (Fairness, Accountability, and Transparency)](https://facctconference.org/)

# Additional Resources

## Challenges and Competitions
* [FICO Explainable Machine Learning Challenge](https://community.fico.com/s/explainable-machine-learning-challenge)
* [National Fair Housing Alliance Hackathon](https://nationalfairhousing.org/hackathon2023/)
* [Twitter Algorithmic Bias](https://hackerone.com/twitter-algorithmic-bias?type=team)

## Other Interpretability and Fairness Resources and Lists
* [8 Principles of Responsible ML](https://ethical.institute/principles.html)
* [ACM FAT* 2019 Youtube Playlist](https://www.youtube.com/playlist?list=PLXA0IWa3BpHk7fE8IH6wXNEfAZyr3A5Yb)
* [Adversarial ML Threat Matrix](https://github.com/mitre/advmlthreatmatrix)
* [AI Tools and Platforms](https://docs.google.com/spreadsheets/u/2/d/10pPQYmyNnYb6zshOKxBjJ704E0XUj2vJ9HCDfoZxAoA/htmlview#)
* [AI Ethics Guidelines Global Inventory](https://algorithmwatch.org/en/project/ai-ethics-guidelines-global-inventory/)
* [AI Incident Database](http://aiid.partnershiponai.org/)
* [AllenNLP Interpret: A Framework for Explaining Predictions of NLP Models](http://sameersingh.org/files/papers/allennlp-interpret-demo-emnlp19.pdf)
* [Algorithms and prejudice](https://www.thesaturdaypaper.com.au/news/politics/2019/12/07/algorithms-and-prejudice/15756372009195)
* [Awesome interpretable machine learning](https://github.com/lopusz/awesome-interpretable-machine-learning) ;)
* [Awesome machine learning operations](https://github.com/EthicalML/awesome-machine-learning-operations)
* [Awful AI](https://github.com/daviddao/awful-ai)
* [algoaware](https://www.algoaware.eu/)
* [BIML Interactive Machine Learning Risk Framework](https://berryvilleiml.com/interactive/)
* [Beyond Explainability: A Practical Guide to Managing Risk in Machine Learning Models](https://go.immuta.com/beyond-explainability-white-paper)
* [criticalML](https://github.com/rockita/criticalML)
* [Data Feminism](https://mitpress.mit.edu/books/data-feminism)
* [Dealing with Bias and Fairness in AI/ML/Data Science Systems](https://docs.google.com/presentation/d/17o_NzplYua5fcJFuGcy1V1-5GFAHk7oHAF4dN44NkUE)
* [Debugging Machine Learning Models (ICLR workshop proceedings)](https://debug-ml-iclr2019.github.io/)
* [Decision Points in AI Governance](https://cltc.berkeley.edu/wp-content/uploads/2020/05/Decision_Points_AI_Governance.pdf)
* [De-identification Tools](https://www.nist.gov/itl/applied-cybersecurity/privacy-engineering/collaboration-space/focus-areas/de-id/tools)
* [Deep Insights into Explainability and Interpretability of Machine Learning Algorithms and Applications to Risk Management](https://ww2.amstat.org/meetings/jsm/2019/onlineprogram/AbstractDetails.cfm?abstractid=303053)
* [Distill](https://distill.pub)
* [Faces in the Wild Benchmark Data](https://github.com/visionjo/facerec-bias-bfw)
* [Fairness, Accountability, and Transparency in Machine Learning (FAT/ML) Scholarship](https://www.fatml.org/resources/relevant-scholarship)
* [From Principles to Practice: An interdisciplinary framework to operationalise AI ethics](https://www.ai-ethics-impact.org/resource/blob/1961130/c6db9894ee73aefa489d6249f5ee2b9f/aieig---report---download-hb-data.pdf)
* [How will the GDPR impact machine learning?](https://www.oreilly.com/radar/how-will-the-gdpr-impact-machine-learning/)
* [Machine Learning Ethics References](https://github.com/radames/Machine-Learning-Ethics-References)
* [Machine Learning Interpretability Resources](https://github.com/h2oai/mli-resources)
* [Machine Learning: Considerations for fairly and transparently expanding access to credit](http://info.h2o.ai/rs/644-PKX-778/images/Machine%20Learning%20-%20Considerations%20for%20Fairly%20and%20Transparently%20Expanding%20Access%20to%20Credit.pdf)
* [MIT AI Ethics Reading Group](https://mitaiethics.github.io/)
* [On the Responsibility of Technologists: A Prologue and Primer](https://algo-stats.info/2018/04/15/on-the-responsibility-of-technologists-a-prologue-and-primer/)
* [private-ai-resources](https://github.com/OpenMined/private-ai-resources)
* [Problems with Shapley-value-based explanations as feature importance measures](https://arxiv.org/pdf/2002.11097v1.pdf)
* [Real-World Model Debugging Strategies](https://medium.com/@jphall_22520/strategies-for-model-debugging-aa822f1097ce)
* [ResponsibleAI](https://romanlutz.github.io/ResponsibleAI/)
* [Robust ML](https://www.robust-ml.org/)
* [Safe and Reliable Machine Learning](https://www.dropbox.com/s/sdu26h96bc0f4l7/FAT19-AI-Reliability-Final.pdf?dl=0)
* [Sample AI Incident Response Checklist](https://bnh-ai.github.io/resources/)
* [Ten Questions on AI Risk](https://fpf.org/wp-content/uploads/2020/06/Ten-Questions-on-AI-Risk-FPF.pdf)
* [Testing and Debugging in Machine Learning](https://developers.google.com/machine-learning/testing-debugging)
* [Troubleshooting Deep Neural Networks](http://josh-tobin.com/assets/pdf/troubleshooting-deep-neural-networks-01-19.pdf)
* [Warning Signs: The Future of Privacy and Security in an Age of Machine Learning](https://fpf.org/wp-content/uploads/2019/09/FPF_WarningSigns_Report.pdf)
* [When Not to Trust Your Explanations](https://docs.google.com/presentation/d/10a0PNKwoV3a1XChzvY-T1mWudtzUIZi3sCMzVwGSYfM/edit)
* [XAI Resources](https://github.com/pbiecek/xai_resources)
* [You Created A Machine Learning Application Now Make Sure It's Secure](https://www.oreilly.com/ideas/you-created-a-machine-learning-application-now-make-sure-its-secure)

# Curated Bibliographies
## NIST Playbook Measure FullLaunch
* Abebe, Rediet, and Kira Goldner. "Mechanism Design for Social Good." *AI Matters* 4, no. 3 (October 2018): 27--34. https://doi.org/10.1145/3284751.3284761.
* Barocas, Solon, Anhong Guo, Ece Kamar, Jacquelyn Krones, Meredith Ringel Morris, Jennifer Wortman Vaughan, W. Duncan Wadsworth, and Hanna Wallach. "Designing Disaggregated Evaluations of AI Systems: Choices, Considerations, and Tradeoffs." *Proceedings of the 2021 AAAI/ACM Conference on AI, Ethics, and Society*, July 2021, 368--78. https://doi.org/10.1145/3461702.3462610.
* Barredo Arrieta, Alejandro, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, et al. "Explainable Artificial Intelligence (XAI): Concepts, Taxonomies, Opportunities, and Challenges Toward Responsible AI." *Information Fusion* 58 (June 2020): 82--115. https://doi.org/10.1016/j.inffus.2019.12.012.
* Barrett, Matthew P. "Framework for Improving Critical Infrastructure Cybersecurity Version 1.1." *National Institute of Standards and Technology (NIST)*, April 16, 2018. https://doi.org/10.6028/nist.cswp.04162018.
* Bender, Emily M., and Batya Friedman. "Data Statements for Natural Language Processing: Toward Mitigating System Bias and Enabling Better Science." *Transactions of the Association for Computational Linguistics* 6 (2018): 587--604. https://doi.org/10.1162/tacl_a_00041.
* Benthall, Sebastian, Seda Gürses, and Helen Nissenbaum. "Contextual Integrity through the Lens of Computer Science." *Foundations and Trends in Privacy and Security* 2, no. 1 (December 22, 2017): 1--69. https://doi.org/10.1561/3300000016.
* Bhattacharyya, Asit, and Lorne Cummings. "Measuring Corporate Environmental Performance -* Stakeholder Engagement Evaluation." *Business Strategy and the Environment* 24, no. 5 (2013): 309--25. https://doi.org/10.1002/bse.1819.
* Bishop, Christopher M. *Pattern Recognition and Machine Learning*. New York City, New York: Springer, 2006.
* Boyd, Karen. "Designing Up with Value-Sensitive Design: Building a Field Guide for Ethical ML Development." *FAccT '22: 2022 ACM Conference on Fairness, Accountability, and Transparency*, June 20, 2022, 2069--82. https://doi.org/10.1145/3531146.3534626.
* Brown, Shea, Ryan Carrier, Merve Hickok, and Adam Leon Smith. "Bias Mitigation in Data Sets." *SocArXiv*, July 8, 2021. https://doi.org/10.31235/osf.io/z8qrb.
* Buolamwini, Joy, and Timnit Gebru. "Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification." *Proceedings of the 1st Conference on Fairness, Accountability and Transparency in PMLR* 81 (2018): 77--91. https://doi.org/https://proceedings.mlr.press/v81/buolamwini18a.html.
* Buçinca, Zana, Phoebe Lin, Krzysztof Z. Gajos, and Elena L. Glassman. "Proxy Tasks and Subjective Measures Can Be Misleading in Evaluating Explainable AI Systems." *IUI '20: Proceedings of the 25th International Conference on Intelligent User Interfaces*, March 17, 2020, 454--64. https://doi.org/10.1145/3377325.3377498.
* Caliskan, Aylin, Joanna J. Bryson, and Arvind Narayanan. "Semantics Derived Automatically from Language Corpora Contain Human-Like Biases." *Science* 356, no. 6334 (April 14, 2017): 183--86. https://doi.org/10.1126/science.aal4230.
* Chouldechova, Alexandra. "Fair Prediction with Disparate Impact: A Study of Bias in Recidivism Prediction Instruments." *Big Data* 5, no. 2 (June 1, 2017): 153--63. https://doi.org/10.1089/big.2016.0047.
* Cobbe, Jennifer, Michelle Seng Lee, and Jatinder Singh. "Reviewable Automated Decision-Making: A Framework for Accountable Algorithmic Systems." *FAccT '21: Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency*, March 1, 2021, 598--609. https://doi.org/10.1145/3442188.3445921.
* Costanza-Chock, Sasha. *Design Justice: Community-Led Practices to Build the Worlds We Need*. Cambridge: The MIT Press, 2020.
* Davis, Janet, and Lisa P. Nathan. "Value Sensitive Design: Applications, Adaptations, and Critiques." Edited by Jeroen van den Hoven, Pieter E. Vermaas, and Ibo van de Poel. *Handbook of Ethics, Values, and Technological Design*, January 1, 2015, 11--40. https://doi.org/10.1007/978-94-007-6970-0_3.
* Dcass, Microsoft. "Community Jury." Microsoft Learn's Azure Application Architecture Guide, 2023. https://learn.microsoft.com/en-us/azure/architecture/guide/responsible-innovation/community-jury/.
* Dobbe, Roel, Thomas Krendl Gilbert, and Yonatan Mintz. "Hard Choices in Artificial Intelligence." *Artificial Intelligence* 300 (November 2021). https://doi.org/10.1016/j.artint.2021.103555.
* Dwork, Cynthia. "Differential Privacy." *Automata, Languages and Programming*, 2006, 1--12. https://doi.org/10.1007/11787006_1.
* Fairlearn. "Fairness in Machine Learning." Fairlearn 0.8.0 Documentation, n.d. https://fairlearn.org/v0.8/user_guide/fairness_in_machine_learning.html#.
* Fazelpour, Sina, and Maria De-Arteaga. "Diversity in Sociotechnical Machine Learning Systems." *Big Data and Society* 9, no. 1 (2022). https://doi.org/10.1177/20539517221082027.
* Fazelpour, Sina, and Zachary C. Lipton. "Algorithmic Fairness from a Non-Ideal Perspective." *AIES '20: Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society*, February 7, 2020, 57--63. https://doi.org/10.1145/3375627.3375828.
* Franklin, Jade S., Karan Bhanot, Mohamed Ghalwash, Kristin P. Bennett, Jamie McCusker, and Deborah L. McGuinness. "An Ontology for Fairness Metrics." *AIES '22: Proceedings of the 2022 AAAI/ACM Conference on AI, Ethics, and Society*, July 2022, 265--75. https://doi.org/10.1145/3514094.3534137.
* Friedman, Batya, and David G. Hendry. *Value Sensitive Design: Shaping Technology with Moral Imagination*. Cambridge, MA: The MIT Press, 2019.
* Friedman, Batya, David G. Hendry, and Alan Borning. "A Survey of Value Sensitive Design Methods." *Foundations and Trends in Human-Computer Interaction* 11, no. 2 (November 22, 2017): 63--125. https://doi.org/10.1561/1100000015.
* Fry, Hannah. *Hello World: Being Human in the Age of Algorithms*. New York: W.W. Norton & Company, 2018.
* Givens, Alexandra Reeve, and Meredith Ringel Morris. "Centering Disability Perspectives in Algorithmic Fairness, Accountability, & Transparency." *FAT* '20: Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency*, January 27, 2020, 684--684. https://doi.org/10.1145/3351095.3375686.
* Google Developers. "Overview of Debugging ML Models." Google Developers Machine Learning Foundational Courses, n.d. https://developers.google.com/machine-learning/testing-debugging/common/overview.
* Green, Ben. "Escaping the Impossibility of Fairness: From Formal to Substantive Algorithmic Fairness." *Philosophy and Technology* 35, no. 90 (October 8, 2022). https://doi.org/10.1007/s13347-022-00584-6.
* Hall, Patrick. "Strategies for Model Debugging." Towards Data Science, November 8, 2019. https://towardsdatascience.com/strategies-for-model-debugging-aa822f1097ce.
* Hart, Diane, Gabi Diercks-O'Brien, and Adrian Powell. "Exploring Stakeholder Engagement in Impact Evaluation Planning in Educational Development Work." *Evaluation* 15, no. 3 (2009): 285--306. https://doi.org/10.1177/1356389009105882.
* Harvard University Privacy Tools Project. "Differential Privacy." Harvard University, n.d. https://privacytools.seas.harvard.edu/differential-privacy.
* Hasan, Ali, Shea Brown, Jovana Davidovic, Benjamin Lange, and Mitt Regan. "Algorithmic Bias and Risk Assessments: Lessons from Practice." *Digital Society* 1 (2022). https://doi.org/10.1007/s44206-022-00017-z.
* Hastie, Trevor, Robert Tibshirani, and Jerome Friedman. *The Elements of Statistical Learning: Data Mining, Inference, and Prediction*. 2nd ed. Springer-Verlag, 2009.
* Hendricks, Sharief, Nailah Conrad, Tania S. Douglas, and Tinashe Mutsvangwa. "A Modified Stakeholder Participation Assessment Framework for Design Thinking in Health Innovation." *Healthcare* 6, no. 3 (September 2018): 191--96. https://doi.org/10.1016/j.hjdsi.2018.06.003.
* Hutson, Matthew. "Measuring AI's Carbon Footprint: New Tools Track and Reduce Emissions from Machine Learning." IEEE Spectrum, November 22, 2022. https://spectrum.ieee.org/ai-carbon-footprint.
* IBM. "IBM's Principles of Chaos Engineering." IBM, n.d. https://www.ibm.com/cloud/architecture/architecture/practices/chaos-engineering-principles/.
* IEEE Computer Society. "Software Engineering Body of Knowledge Version 3: IEEE Computer Society." IEEE Computer Society. Accessed January 21, 2023. https://www.computer.org/education/bodies-of-knowledge/software-engineering/v3.
* "ISO/IEC TR 24027:2021." ISO, November 2021. https://www.iso.org/standard/77607.html.
* Jacobs, Abigail Z., and Hanna Wallach. "Measurement and Fairness." *FAccT '21: Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency*, March 2021, 375--85. https://doi.org/10.1145/3442188.3445901.
* Jo, Eun Seo, and Timnit Gebru. "Lessons from Archives: Strategies for Collecting Sociocultural Data in Machine Learning." *FAT* '20: Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency*, January 2020, 306--16. https://doi.org/10.1145/3351095.3372829.
* Jordan, Sara R. "Designing Artificial Intelligence Review Boards: Creating Risk Metrics for Review of AI." *2019 IEEE International Symposium on Technology and Society (ISTAS)*, 2019. https://doi.org/10.1109/istas48451.2019.8937942.
* Kay, Matthew, Cynthia Matuszek, and Sean A. Munson. "Unequal Representation and Gender Stereotypes in Image Search Results for Occupations." *CHI '15: Proceedings of the 33rd Annual ACM Conference on Human Factors in Computing Systems*, April 18, 2015, 3819--28. https://doi.org/10.1145/2702123.2702520.
* Kroll, Joshua A. "Outlining Traceability: A Principle for Operationalizing Accountability in Computing Systems." *FAccT '21: Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency*, March 1, 2021, 758--71. https://doi.org/10.1145/3442188.3445937.
* Lamba, Hemank, Kit T. Rodolfa, and Rayid Ghani. "An Empirical Comparison of Bias Reduction Methods on Real-World Problems in High-Stakes Policy Settings." *ACM SIGKDD Explorations Newsletter* 23, no. 1 (May 29, 2021): 69--85. https://doi.org/10.1145/3468507.3468518.
* Landers, Richard N., and Tara S. Behrend. "Auditing the AI Auditors: A Framework for Evaluating Fairness and Bias in High Stakes AI Predictive Models." *American Psychologist* 78, no. 1 (2023): 36--49. https://doi.org/10.1037/amp0000972.
* Loi, Michele, and Christoph Heitz. "Is Calibration a Fairness Requirement?" *FAccT '22: 2022 ACM Conference on Fairness, Accountability, and Transparency*, June 2022, 2026--34. https://doi.org/10.1145/3531146.3533245.
* Machanavajjhala, Ashwin, Johannes Gehrke, Daniel Kifer, and Muthuramakrishnan Venkitasubramaniam. "L-Diversity: Privacy beyond K-Anonymity." *22nd International Conference on Data Engineering (ICDE'06)*, 2006. https://doi.org/10.1109/icde.2006.1.
* Margetis, George, Stavroula Ntoa, Margherita Antona, and Constantine Stephanidis. "Human-Centered Design of Artificial Intelligence." Essay. In *Handbook of Human Factors and Ergonomics*, edited by Gavriel Salvendy and Waldemar Karwowski, 5th ed., 1085--1106. S: John Wiley & Sons, 2021.
* MathWorks. "Explore Fairness Metrics for Credit Scoring Model." MATLAB & Simulink, 2023. https://www.mathworks.com/help/risk/explore-fairness-metrics-for-credit-scoring-model.html.
* McGraw, Gary, Harold Figueroa, Victor Shepardson, and Richie Bonett. "BIML Interactive Machine Learning Risk Framework." Berryville Institute of Machine Learning (BIML), 2022. https://berryvilleiml.com/interactive/.
* Mehrabi, Ninareh, Fred Morstatter, Nripsuta Saxena, Kristina Lerman, and Aram Galstyan. "A Survey on Bias and Fairness in Machine Learning." *ACM Computing Surveys* 54, no. 6 (July 2021): 1--35. https://doi.org/10.1145/3457607.
* Metcalf, Jacob, and Kate Crawford. "Where Are Human Subjects in Big Data Research? The Emerging Ethics Divide." *Big Data and Society* 3, no. 1 (Spring 2016). https://doi.org/10.1177/2053951716650211.
* Microsoft Research. "AI Fairness Checklist." Microsoft, February 7, 2022. https://www.microsoft.com/en-us/research/project/ai-fairness-checklist/.
* Mitchell, Margaret, Simone Wu, Andrew Zaldivar, Parker Barnes, Lucy Vasserman, Ben Hutchinson, Elena Spitzer, Inioluwa Deborah Raji, and Timnit Gebru. "Model Cards for Model Reporting." *FAT *19: Proceedings of the Conference on Fairness, Accountability, and Transparency*, January 2019, 220--29. https://doi.org/10.1145/3287560.3287596.
* Mitre, Mitre Corporation. "Mitre/Advmlthreatmatrix: Adversarial Threat Landscape for AI Systems." GitHub, n.d. https://github.com/mitre/advmlthreatmatrix.
* Moss, Emanuel, Elizabeth Watkins, Ranjit Singh, Madeleine Clare Elish, and Jacob Metcalf. "Assembling Accountability: Algorithmic Impact Assessment for the Public Interest." *SSRN*, July 8, 2021. https://doi.org/10.2139/ssrn.3877437.
* Narayanan, Arvind. "Tl;DS * 21 Fairness Definition and Their Politics by Arvind Narayanan." Dora's world, July 19, 2019. https://shubhamjain0594.github.io/post/tlds-arvind-fairness-definitions/.
* National Institute of Standards and Technology (NIST). "Cybersecurity Framework." NIST, 2023. https://www.nist.gov/cyberframework.
* National Institutes of Health. "Definition of Human Subjects Research." NIH Central Resource for Grants and Funding Information, January 13, 2020. https://grants.nih.gov/policy/humansubjects/research.htm.
* Noble, Safiya Umoja. *Algorithms of Oppression: How Search Engines Reinforce Racism*. New York, NY: New York University Press, 2018.
* Obermeyer, Ziad, Brian Powers, Christine Vogeli, and Sendhil Mullainathan. "Dissecting Racial Bias in an Algorithm Used to Manage the Health of Populations." *Science* 366, no. 6464 (October 25, 2019): 447--53. https://doi.org/10.1126/science.aax2342.
* Office for Human Research Protections (OHRP). "45 CFR 46." United States Department of Health and Human Services Office for Human Research Protections, March 10, 2021. https://www.hhs.gov/ohrp/regulations-and-policy/regulations/45-cfr-46/index.html.
* Passi, Samir, and Solon Barocas. "Problem Formulation and Fairness." *FAT* '19: Proceedings of the Conference on Fairness, Accountability, and Transparency*, January 2019, 39--48. https://doi.org/10.1145/3287560.3287567.
* Patton, Jeff, Peter Economy, Martin Fowler, Alan Cooper, and Marty Cagan. *User Story Mapping: Discover the Whole Story, Build the Right Product*. O'Reilly, 2014.
* Paulk, Mark C., Bill Curtis, Mary Beth Chrissis, and Charles V. Weber. "Capability Maturity Model, Version 1.1." *IEEE Software* 10, no. 4 (1993): 18--27. https://doi.org/10.1109/52.219617.
* Paullada, Amandalynne, Inioluwa Deborah Raji, Emily M. Bender, Emily Denton, and Alex Hanna. "Data and Its (Dis)Contents: A Survey of Dataset Development and Use in Machine Learning Research." *Patterns* 2, no. 11 (2021): 100336. https://doi.org/10.1016/j.patter.2021.100336.
* Piano, Luca, Fabio Garcea, Valentina Gatteschi, Fabrizio Lamberti, and Lia Morra. "Detecting Drift in Deep Learning: A Methodology Primer." *IT Professional* 24, no. 5 (2022): 53--60. https://doi.org/10.1109/mitp.2022.3191318.
* Raji, Inioluwa Deborah, I. Elizabeth Kumar, Aaron Horowitz, and Andrew Selbst. "The Fallacy of AI Functionality." *FAccT '22: 2022 ACM Conference on Fairness, Accountability, and Transparency*, June 2022, 959--72. https://doi.org/10.1145/3531146.3533158.
* Robinson, David G. *Voices in the Code: A Story About People, Their Values, and the Algorithm They Made*. New York: Russell Sage Foundation, 2022.
* Saxena, Devansh, Karla Badillo-Urquiola, Pamela J. Wisniewski, and Shion Guha. "A Human-Centered Review of Algorithms Used within the U.S. Child Welfare System." *CHI '20: Proceedings of the 2020 CHI Conference on Human Factors in Computing Systems*, April 23, 2020, 1--15. https://doi.org/10.1145/3313831.3376229.
* Schiff, Daniel, Aladdin Ayesh, Laura Musikanski, and John C. Havens. "IEEE 7010: A New Standard for Assessing the Well-Being Implications of Artificial Intelligence." *2020 IEEE International Conference on Systems, Man, and Cybernetics (SMC)*, 2020. https://doi.org/10.1109/smc42975.2020.9283454.
* Schmidt, Victor, Alexandra Luccioni, Alexandre Lacoste, and Thomas Dandres. "Machine Learning CO2 Impact Calculator." ML CO2 Impact, n.d. https://mlco2.github.io/impact/.
* Schwartz, Roy, Jesse Dodge, Noah A. Smith, and Oren Etzioni. "Green AI." *Communications of the ACM* 63, no. 12 (December 2020): 54--63. https://doi.org/10.1145/3381831.
* Selbst, Andrew D., Danah Boyd, Sorelle A. Friedler, Suresh Venkatasubramanian, and Janet Vertesi. "Fairness and Abstraction in Sociotechnical Systems." *FAT* '19: Proceedings of the Conference on Fairness, Accountability, and Transparency*, January 29, 2019, 59--68. https://doi.org/10.1145/3287560.3287598.
* Shneiderman, Ben. *Human-Centered AI*. Oxford: Oxford University Press, 2022.
* Shneiderman, Ben. "Human-Centered AI." *Issues in Science and Technology* 37, no. 2 (Winter 2021): 56--61. https://doi.org/https://issues.org/human-centered-ai/.
* Shneiderman, Ben. "Tutorial: Human-Centered AI: Reliable, Safe and Trustworthy." *IUI '21 Companion: 26th International Conference on Intelligent User Interfaces * Companion*, April 14, 2021, 7--8. https://doi.org/10.1145/3397482.3453994.
* Slack, Dylan, Sophie Hilgard, Emily Jia, Sameer Singh, and Himabindu Lakkaraju. "Fooling LIME and SHAP: Adversarial Attacks on Post Hoc Explanation Methods." *AIES '20: Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society*, February 7, 2020, 180--86. https://doi.org/10.1145/3375627.3375830.
* Sloane, Mona, Emanuel Moss, Olaitan Awomolo, and Laura Forlano. "Participation Is Not a Design Fix for Machine Learning." *Equity and Access in Algorithms, Mechanisms, and Optimization*, October 2022. https://doi.org/10.1145/3551624.3555285.
* "Statement on Principles for Responsible Algorithmic Systems." *Association for Computing Machinery (ACM)*, October 26, 2022. ACM Technology Policy Council. https://www.acm.org/binaries/content/assets/public-policy/final-joint-ai-statement-update.pdf.
* Suresh, Harini, and John Guttag. "A Framework for Understanding Sources of Harm Throughout the Machine Learning Life Cycle." *Equity and Access in Algorithms, Mechanisms, and Optimization*, October 2021. https://doi.org/10.1145/3465416.3483305.
* Sweeney, Latanya. "K-Anonymity: A Model for Protecting Privacy." *International Journal of Uncertainty, Fuzziness and Knowledge-Based Systems* 10, no. 5 (2002): 557--70. https://doi.org/10.1142/s0218488502001648.
* Thomas, Rachel L., and David Uminsky. "Reliance on Metrics Is a Fundamental Challenge for AI." *Patterns* 3, no. 5 (May 13, 2022): 100476. https://doi.org/10.1016/j.patter.2022.100476.
* Thompson, Caitlin. "Who's Homeless Enough for Housing? In San Francisco, an Algorithm Decides." Coda, September 21, 2021. https://www.codastory.com/authoritarian-tech/san-francisco-homeless-algorithm/.
* Umbrello, Steven, and Ibo van de Poel. "Mapping Value Sensitive Design onto AI for Social Good Principles." *AI and Ethics* 1, no. 3 (February 1, 2021): 283--96. https://doi.org/10.1007/s43681-021-00038-3.
* Visengeriyeva, Larysa. "Visenger * Overview." GitHub, n.d. https://github.com/visenger.
* Winter, Jenifer Sunrise, and Elizabeth Davidson. "Big Data Governance of Personal Health Information and Challenges to Contextual Integrity." *The Information Society: An International Journal* 35, no. 1 (2019): 36--51. https://doi.org/10.1080/01972243.2018.1542648.
* Yang, Ke, Julia Stoyanovich, Abolfazl Asudeh, Bill Howe, HV Jagadish, and Gerome Miklau. "A Nutritional Label for Rankings." *SIGMOD '18: Proceedings of the 2018 International Conference on Management of Data*, May 27, 2018, 1773--76. https://doi.org/10.1145/3183713.3193568.
* Zerilli, John, Alistair Knott, James Maclaurin, and Colin Gavaghan. "Algorithmic Decision-Making and the Control Problem." *Minds and Machines* 29, no. 4 (December 11, 2019): 555--78. https://doi.org/10.1007/s11023-019-09513-7. 
