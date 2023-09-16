
# awesome-machine-learning-*interpretability* [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated, but biased and incomplete, list of awesome responsible machine learning resources.

If you want to contribute to this list (*and please do!*) read over the [contribution guidelines](contributing.md), send a [pull request](https://github.com/jphall663/awesome-machine-learning-interpretability/compare), or file an [issue](https://github.com/jphall663/awesome-machine-learning-interpretability/issues/new).

## Table of Contents

### General Resources
* [Comprehensive Software Examples and Tutorials](https://github.com/jphall663/awesome-machine-learning-interpretability#comprehensive-software-examples-and-tutorials)
* [Free-ish Books](https://github.com/jphall663/awesome-machine-learning-interpretability#books)
* [Open-ish Classes](https://github.com/jphall663/awesome-machine-learning-interpretability#classes)
* [Glossaries and Dictionaries](https://github.com/jphall663/awesome-machine-learning-interpretability#glossaries-and-dictionaries)
  
### Generative AI

### Technical Resources

* [Open Source/Access Responsible AI Software Packages](https://github.com/jphall663/awesome-machine-learning-interpretability#responsible-ai-software-packages)
  * [Browser](https://github.com/jphall663/awesome-machine-learning-interpretability#browser)
  * [C/C++](https://github.com/jphall663/awesome-machine-learning-interpretability#cc)
  * [Python](https://github.com/jphall663/awesome-machine-learning-interpretability#python)
  * [R](https://github.com/jphall663/awesome-machine-learning-interpretability#r) 
* [Machine Learning Environment Management Tools](https://github.com/jphall663/awesome-machine-learning-interpretability#machine-learning-environment-management-tools)
* [Domain-specific Software]()

### Evaluation and Standards

* [Benchmarks](https://github.com/jphall663/awesome-machine-learning-interpretability#benchmarks)
* [Best Practices]()
* [Common or Useful Datasets](https://github.com/jphall663/awesome-machine-learning-interpretability#datasets-for-fairness-and-explainability)
* [Auditing and Evaluation Resources](https://github.com/jphall663/awesome-machine-learning-interpretability#auditing-and-evaluation-resources)
* [AI Incident Trackers](https://github.com/jphall663/awesome-machine-learning-interpretability#ai-incident-trackers)
  
### Community and Policy

* [Policy and Regulatory Frameworks](https://github.com/jphall663/awesome-machine-learning-interpretability#policy-and-regulatory-frameworks)
* [Best Practices](https://github.com/jphall663/awesome-machine-learning-interpretability#best-practices)
* [Communities and Forums](https://github.com/jphall663/awesome-machine-learning-interpretability#communities-and-forums)

### Additional Resources
* [Challenges and Competitions](https://github.com/jphall663/awesome-machine-learning-interpretability#challenges-and-competitions)
* [List-of-Lists](https://github.com/jphall663/awesome-machine-learning-interpretability#other-interpretability-and-fairness-resources-and-lists)

### Curated Bibliographies
* [NIST Playbook_Measure_FullLaunch](https://github.com/jphall663/awesome-machine-learning-interpretability#nist-playbook-measure-fulllaunch)

## General Resources

### Comprehensive Software Examples and Tutorials

This section is a curated collection of guides and tutorials that simplify responsible AI and machine learning. It spans from basic model interpretability to advanced fairness techniques. Suitable for both novices and experts, the resources cover topics like COMPAS fairness analyses and explainable machine learning via counterfactuals. 

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

### Free-ish Books

This section contains books that are either freely downloadable or links to full Internet Archive scans of books that can be borrowed with a free account.

* [An Introduction to Machine Learning Interpretability](https://www.h2o.ai/wp-content/uploads/2019/08/An-Introduction-to-Machine-Learning-Interpretability-Second-Edition.pdf)
* [Explanatory Model Analysis](https://pbiecek.github.io/ema/)
* [Fairness and Machine Learning](http://fairmlbook.org/)
* [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)
* [Machine Learning for High-Risk Applications: Approaches to Responsible AI](https://pages.dataiku.com/oreilly-responsible-ai)
* [Responsible Machine Learning](https://www.h2o.ai/resources/ebook/responsible-machine-learning/) (requires email for now)
* [Trustworthy Machine Learning](http://www.trustworthymachinelearning.com/)

### Open-ish Classes

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

## Generative AI

This section contains information related to the responsible use of generative AI.
* [Andreessen Horowitz (a16z) AI Canon](https://a16z.com/ai-canon/)
* [DAIR Prompt Engineering Guide](https://www.promptingguide.ai/)
 * [DAIR Prompt Engineering Guide GitHub](https://github.com/dair-ai/Prompt-Engineering-Guide)  

## Technical Resources

### Open Source/Access Responsible AI Software Packages

#### Browser

* [DiscriLens](https://github.com/wangqianwen0418/DiscriLens)
* [manifold](https://github.com/uber/manifold)
* [TensorBoard Projector](http://projector.tensorflow.org)
* [What-if Tool](https://pair-code.github.io/what-if-tool/index.html#about)

#### C/C++

* [Born-again Tree Ensembles](https://github.com/vidalt/BA-Trees)
* [Certifiably Optimal RulE ListS](https://github.com/nlarusstone/corels)

#### Python

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

#### R

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

### Machine Learning Environment Management Tools

* [dvc](https://dvc.org/)
* [gigantum](https://github.com/gigantum)
* [mlflow](https://mlflow.org/)
* [mlmd](https://github.com/google/ml-metadata)
* [modeldb](https://github.com/VertaAI/modeldb)
* [whylabs](https://www.rsqrdai.org/)

### Domain-specific Software
This section curates specialized software tools aimed at fairness and explainability within specific domains, such as in healthcare, finance, or social sciences.

## Evaluation and Standards

### Benchmarks
* [Bias Benchmark for QA dataset (BBQ)](https://github.com/nyu-mll/bbq)
* [TruthfulQA](https://github.com/sylinrl/TruthfulQA)
* [OpenML Benchmarking Suites](https://openreview.net/forum?id=OCrD8ycKjG)
* [Winogender Schemas](https://github.com/rudinger/winogender-schemas)
* [Real Toxicity Prompts (Allen Institute for AI)](https://allenai.org/data/real-toxicity-prompts)

### Best Practices
  
### Common Datasets for Responsible AI

* [Adult income dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)
* [All Lending Club loan data](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
* [Census income classification with scikit-learn](https://shap.readthedocs.io/en/latest/example_notebooks/tabular_examples/model_agnostic/Census%20income%20classification%20with%20scikit-learn.html)
* [COMPAS Recidivism Risk Score Data and Analysis](https://www.propublica.org/datastore/dataset/compas-recidivism-risk-score-data-and-analysis)
* [MIMIC-III Clinical Database](https://physionet.org/content/mimiciii/1.4/)
* [NYPD Stop, Question and Frisk Data](https://www.nyc.gov/site/nypd/stats/reports-analysis/stopfrisk.page)
* [Statlog (German Credit Data)](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)
* [Wikipedia Talk Labels: Personal Attacks](https://www.kaggle.com/datasets/jigsaw-team/wikipedia-talk-labels-personal-attacks)

### Auditing and Evaluation Resources

### AI Incident Trackers
* [AI Incident Database (Responsible AI Collaborative)](https://incidentdatabase.ai/)
* [AI Vulnerability Database (AVID)](https://avidml.org/)
* [AIAAIC](https://www.aiaaic.org/)
* [George Washington University Law School's AI Litigation Database](https://blogs.gwu.edu/law-eti/ai-litigation-database/)
* [Verica Open Incident Database (VOID)](https://www.thevoid.community/)

## Community and Policy

### Policy and Regulatory Frameworks
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

### Communities and Forums

### Conferences and Workshops

* [AIES (AAAI/ACM Conference on AI, Ethics, and Society)](https://www.aies-conference.com/)
* [NeurIPS Workshop on Ethical, Social and Governance Issues in AI](https://nips.cc/Conferences/)
* [ICML Workshop on Fairness, Accountability, and Transparency in Machine Learning](https://icml.cc/)
* [ACM FAccT (Fairness, Accountability, and Transparency)](https://facctconference.org/)
  * * [FAT/ML (Fairness, Accountability, and Transparency in Machine Learning)](https://www.fatml.org/)

## Additional Resources

### Challenges and Competitions
* [FICO Explainable Machine Learning Challenge](https://community.fico.com/s/explainable-machine-learning-challenge)
* [National Fair Housing Alliance Hackathon](https://nationalfairhousing.org/hackathon2023/)
* [Twitter Algorithmic Bias](https://hackerone.com/twitter-algorithmic-bias?type=team)

### Other Interpretability and Fairness Resources and Lists
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
