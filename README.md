
# Awesome Machine Learning Interpretability [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A maintained and curated list of practical and awesome responsible machine learning resources.

If you want to contribute to this list (*and please do!*), read over the [contribution guidelines](contributing.md), send a [pull request](https://github.com/jphall663/awesome-machine-learning-interpretability/compare), or file an [issue](https://github.com/jphall663/awesome-machine-learning-interpretability/issues/new). 

If something you contributed or found here is missing after our September 2023 redeux, please check the [archive](https://github.com/jphall663/awesome-machine-learning-interpretability/blob/master/archive/README.md.bak).

## Contents

* **Community and Official Guidance Resources** 
  * [Community Frameworks and Guidance](#community-frameworks-and-guidance)
    * [Infographics and Cheat Sheets](#infographics-and-cheat-sheets)
    * [LLM Red Teaming Resources](#llm-red-teaming-resources)
  * [Conferences and Workshops](#conferences-and-workshops)
  * [Official Policy, Frameworks, and Guidance](#official-policy-frameworks-and-guidance)

* **Education Resources**
  * [Comprehensive Software Examples and Tutorials](#comprehensive-software-examples-and-tutorials)
  * [Free-ish Books](#free-ish-books)
  * [Glossaries and Dictionaries](#glossaries-and-dictionaries)
  * [Open-ish Classes](#open-ish-classes)

* **Miscellaneous Resources**
  * [AI Incident Information Sharing Resources](#ai-incident-information-sharing-resources)
  * [Challenges and Competitions](#challenges-and-competitions)
  * [Curated Bibliographies](#curated-bibliographies)
  * [List of Lists](#list-of-lists)

* **Technical Resources**
  * [Benchmarks](#benchmarks)
  * [Common or Useful Datasets](#common-or-useful-datasets)
  * [Domain-specific Software](#domain-specific-software)
  * [Machine Learning Environment Management Tools](#machine-learning-environment-management-tools)
  * [Open Source/Access Responsible AI Software Packages](#open-sourceaccess-responsible-ai-software-packages)
    * [Browser](#browser)
    * [C/C++](#cc)
    * [JavaScript](#javascript)
    * [Python](#python)
    * [R](#r)
   
* **Citing Awesome Machine Learning Interpretability**
  * [ACM, APA, Chicago, and MLA](#acm-apa-chicago-and-mla)

## Community and Official Guidance Resources

### Community Frameworks and Guidance 

This section is for responsible ML guidance put forward by organizations or individuals, not for official government guidance.

* [8 Principles of Responsible ML](https://ethical.institute/principles.html)
* [A Brief Overview of AI Governance for Responsible Machine Learning Systems](https://arxiv.org/pdf/2211.13130.pdf)
* [Adversarial ML Threat Matrix](https://github.com/mitre/advmlthreatmatrix)![](https://img.shields.io/github/stars/mitre/advmlthreatmatrix?style=social)
* [AI Verify](https://aiverifyfoundation.sg/what-is-ai-verify/):
  * [AI Verify Foundation](https://aiverifyfoundation.sg/what-is-ai-verify/)
  * [AI Verify Foundation, Cataloguing LLM Evaluations](https://aiverifyfoundation.sg/downloads/Cataloguing_LLM_Evaluations.pdf)
  * [AI Verify Foundation, Generative AI: Implications for Trust and Governance](https://aiverifyfoundation.sg/downloads/Discussion_Paper.pdf) 
* [AI Snake Oil](https://www.aisnakeoil.com/)
* [AllenNLP Interpret: A Framework for Explaining Predictions of NLP Models](http://sameersingh.org/files/papers/allennlp-interpret-demo-emnlp19.pdf)
* [Andreessen Horowitz (a16z) AI Canon](https://a16z.com/ai-canon/)
* [Anthropic's Responsible Scaling Policy](https://www-files.anthropic.com/production/files/responsible-scaling-policy-1.0.pdf)
* [AuditBoard: 5 AI Auditing Frameworks to Encourage Accountability](https://www.auditboard.com/blog/ai-auditing-frameworks/)
* [Auditing machine learning algorithms: A white paper for public auditors](https://www.auditingalgorithms.net/index.html)
* [AWS Data Privacy FAQ](https://aws.amazon.com/compliance/data-privacy-faq/)
* [AWS Privacy Notice](https://aws.amazon.com/privacy/)
* [AWS, What is Data Governance?](https://aws.amazon.com/what-is/data-governance/)
* [Berryville Institute of Machine Learning, Architectural Risk Analysis of Large Language Models (requires free account login)](https://berryvilleiml.com/results/BIML-LLM24.pdf)
* [Brendan Bycroft's LLM Visualization](https://bbycroft.net/llm) 
* [BIML Interactive Machine Learning Risk Framework](https://berryvilleiml.com/interactive/)
* Center for Security and Emerging Technology (CSET):
  * [CSET's Harm Taxonomy for the AI Incident Database](https://github.com/georgetown-cset/CSET-AIID-harm-taxonomy)![](https://img.shields.io/github/stars/georgetown-cset/CSET-AIID-harm-taxonomy?style=social)
  * [CSET Publications](https://cset.georgetown.edu/publications/)
  * [Adding Structure to AI Harm: An Introduction to CSET's AI Harm Framework](https://cset.georgetown.edu/publication/adding-structure-to-ai-harm/)
  * [AI Incident Collection: An Observational Study of the Great AI Experiment](https://cset.georgetown.edu/publication/ai-incident-collection-an-observational-study-of-the-great-ai-experiment/)
  * [Repurposing the Wheel: Lessons for AI Standards](https://cset.georgetown.edu/publication/repurposing-the-wheel/)
  * [Translating AI Risk Management Into Practice](https://cset.georgetown.edu/article/translating-ai-risk-management-into-practice/)
  * [Understanding AI Harms: An Overview](https://cset.georgetown.edu/article/understanding-ai-harms-an-overview/)
* [Censius: AI Audit](https://censius.ai/wiki/ai-audit)
* [CivAI, GenAI Toolkit for the NIST AI Risk Management Framework: Thinking Through the Risks of a GenAI Chatbot](https://www.civai.org/genai-toolkit-pdf)
* [Coalition for Content Provenance and Authenticity (C2PA)](https://c2pa.org/)
* [Crowe LLP: Internal auditor's AI safety checklist](https://www.crowe.com/insights/asset/i/internal-auditors-ai-safety-checklist)
* [Data Provenance Explorer](https://www.dataprovenance.org/)
* [Data & Society, AI Red-Teaming Is Not a One-Stop Solution to AI Harms: Recommendations for Using Red-Teaming for AI Accountability](https://datasociety.net/wp-content/uploads/2023/10/Recommendations-for-Using-Red-Teaming-for-AI-Accountability-PolicyBrief.pdf)
* [Dealing with Bias and Fairness in AI/ML/Data Science Systems](https://docs.google.com/presentation/d/17o_NzplYua5fcJFuGcy1V1-5GFAHk7oHAF4dN44NkUE)
* [Debugging Machine Learning Models (ICLR workshop proceedings)](https://debug-ml-iclr2019.github.io/)
* [Decision Points in AI Governance](https://cltc.berkeley.edu/wp-content/uploads/2020/05/Decision_Points_AI_Governance.pdf)
* [Distill](https://distill.pub)
* [Dominique Shelton Leipzig, Countries With Draft AI Legislation or Frameworks](https://dominiquesheltonleipzig.com/country-legislation-frameworks/)
* [Ethical and social risks of harm from Language Models](https://www.deepmind.com/publications/ethical-and-social-risks-of-harm-from-language-models)
* [Evaluating LLMs is a minefield](https://www.cs.princeton.edu/~arvindn/talks/evaluating_llms_minefield/)
* [Fairly's Global AI Regulations Map](https://github.com/fairlyAI/global-ai-regulations-map/blob/dev/README.md)![](https://img.shields.io/github/stars/fairlyAI/global-ai-regulations-map?style=social)
* [FATML Principles and Best Practices](https://www.fatml.org/resources/principles-and-best-practices)
* [ForHumanity Body of Knowledge (BOK)](https://forhumanity.center/bok/)
* [The Foundation Model Transparency Index](https://crfm.stanford.edu/fmti/)
* [From Principles to Practice: An interdisciplinary framework to operationalise AI ethics](https://www.ai-ethics-impact.org/resource/blob/1961130/c6db9894ee73aefa489d6249f5ee2b9f/aieig---report---download-hb-data.pdf)
* [Gage Repeatability and Reproducibility](https://asq.org/quality-resources/gage-repeatability)
* [Georgetown University Library's Artificial Intelligence (Generative) Resources](https://guides.library.georgetown.edu/ai)
* Google:
  * [Closing the AI accountability gap: defining an end-to-end framework for internal algorithmic auditing](https://dl.acm.org/doi/abs/10.1145/3351095.3372873)
  * [The Data Cards Playbook](https://sites.research.google/datacardsplaybook/)
  * [Data governance in the cloud - part 1 - People and processes](https://cloud.google.com/blog/products/data-analytics/data-governance-and-operating-model-for-analytics-pt1)
  * [Data Governance in the Cloud - part 2 - Tools](https://cloud.google.com/blog/products/data-analytics/data-governance-in-the-cloud-part-2-tools)
  * [Evaluating social and ethical risks from generative AI](https://deepmind.google/discover/blog/evaluating-social-and-ethical-risks-from-generative-ai/)
  * [Generative AI Prohibited Use Policy](https://policies.google.com/terms/generative-ai/use-policy)
  * [Principles and best practices for data governance in the cloud](https://services.google.com/fh/files/misc/principles_best_practices_for_data-governance.pdf)
  * [Responsible AI Framework](https://cloud.google.com/responsible-ai)
  * [Responsible AI practices](https://ai.google/responsibility/responsible-ai-practices/)
  * [Testing and Debugging in Machine Learning](https://developers.google.com/machine-learning/testing-debugging)
* [H2O.ai Algorithms](https://github.com/h2oai/h2o-tutorials/blob/master/training/h2o_algos/h2o_algos_cheat_sheet_04_25_17.pdf)![](https://img.shields.io/github/stars/h2oai/h2o-tutorials?style=social)
* [HackerOne Blog](https://www.hackerone.com/vulnerability-and-security-testing-blog)
* [Haptic Networks: How to Perform an AI Audit for UK Organisations](https://www.haptic-networks.com/cyber-security/how-to-perform-an-ai-audit/)
* [Hogan Lovells, The AI Act is coming: EU reaches political agreement on comprehensive regulation of artificial intelligence](https://www.engage.hoganlovells.com/knowledgeservices/news/the-ai-act-is-coming-eu-reaches-political-agreement-on-comprehensive-regulation-of-artificial-intelligence?nav=FRbANEucS95NMLRN47z%2BeeOgEFCt8EGQ71hKXzqW2Ec%3D&key=BcJlhLtdCv6%2FJTDZxvL23TQa3JHL2AIGr93BnQjo2SkGJpG9xDX7S2thDpAQsCconWHAwe6cJTmX%2FZxLGrXbZz2L%2BEiiz68X&uid=iZAX%2FROFT6Q%3D)
* [Hugging Face, The Landscape of ML Documentation Tools](https://huggingface.co/docs/hub/model-card-landscape-analysis)
* [IAPP EU AI Act Cheat Sheet](https://iapp.org/media/pdf/resource_center/eu_ai_act_cheat_sheet.pdf)
* [ICT Institute: A checklist for auditing AI systems](https://ictinstitute.nl/a-checklist-for-auditing-ai-systems/)
* IEEE: 
  * [IEEE P3119 Standard for the Procurement of Artificial Intelligence and Automated Decision Systems](https://standards.ieee.org/ieee/3119/10729/)
  * [IEEE Std 1012-1998 Standard for Software Verification and Validation](https://people.eecs.ku.edu/~hossein/Teaching/Stds/1012.pdf)
* [Independent Audit of AI Systems](https://forhumanity.center/independent-audit-of-ai-systems/)
* [Identifying and Overcoming Common Data Mining Mistakes](https://support.sas.com/resources/papers/proceedings/proceedings/forum2007/073-2007.pdf)
* [Infocomm Media Development Authority (Singapore) and AI Verify Foundation, Cataloguing LLM Evaluations, Draft for Discussion (October 2023)](https://aiverifyfoundation.sg/downloads/Cataloguing_LLM_Evaluations.pdf)
* [Infocomm Media Development Authority (Singapore), First of its kind Generative AI Evaluation Sandbox for Trusted AI by AI Verify Foundation and IMDA](https://www.imda.gov.sg/resources/press-releases-factsheets-and-speeches/press-releases/2023/generative-ai-evaluation-sandbox)
* [Institute of Internal Auditors: Artificial Intelligence Auditing Framework, Practical Applications, Part A, Special Edition](https://www.theiia.org/globalassets/documents/content/articles/gpi/2017/december/gpi-artificial-intelligence-part-ii.pdf)
* ISACA:
  * [ISACA: Auditing Artificial Intelligence](https://ec.europa.eu/futurium/en/system/files/ged/auditing-artificial-intelligence.pdf)
  * [ISACA: Auditing Guidelines for Artificial Intelligence](https://www.isaca.org/resources/news-and-trends/newsletters/atisaca/2020/volume-26/auditing-guidelines-for-artificial-intelligence)
  * [ISACA: Capability Maturity Model Integration Resources](https://cmmiinstitute.com/)
* [Integrity Institute Report, February 2024, On Risk Assessment and Mitigation for Algorithmic Systems](https://drive.google.com/file/d/1ZMt7igUcKUq00yakCnbxBCcaA7vajAix/view)
* [Know Your Data](https://knowyourdata.withgoogle.com/)
* [Large language models, explained with a minimum of math and jargon](https://www.understandingai.org/p/large-language-models-explained-with)
* [Larry G. Wlosinski, April 30, 2021, Information System Contingency Planning Guidance](https://www.isaca.org/resources/isaca-journal/issues/2021/volume-3/information-system-contingency-planning-guidance)
* [Library of Congress, LC Labs AI Planning Framework](https://github.com/LibraryOfCongress/labs-ai-framework)![](https://img.shields.io/github/stars/LibraryOfCongress/labs-ai-framework?style=social)
* [Llama 2 Responsible Use Guide](https://ai.meta.com/llama/responsible-use-guide/)
* [LLM Visualization](https://bbycroft.net/llm)
* [Machine Learning Quick Reference: Algorithms](https://support.sas.com/rnd/app/data-mining/enterprise-miner/pdfs/Machine_Learning_Quick_Ref_Algorithms_Mar2017.pdf)
* [Machine Learning Quick Reference: Best Practices](https://support.sas.com/rnd/app/data-mining/enterprise-miner/pdfs/Machine_Learning_Quick_Ref_Best_Practices.pdf)
* [Manifest MLBOM Wiki](https://github.com/manifest-cyber/mlbom)
  * [Towards Traceability in Data Ecosystems using a Bill of Materials Model](https://arxiv.org/pdf/1904.04253.pdf)
* Meta:
  * [System cards](https://ai.meta.com/tools/system-cards/)
* Microsoft:
  * [Azure AI Content Safety](https://azure.microsoft.com/en-us/products/ai-services/ai-content-safety)
     * [Harm categories in Azure AI Content Safety](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/concepts/harm-categories?tabs=warning)
     * [Microsoft Responsible AI Standard, v2](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE5cmFl)
* [MLA, How do I cite generative AI in MLA style?](https://style.mla.org/citing-generative-ai/)
* [model-cards-and-datasheets](https://github.com/ivylee/model-cards-and-datasheets)![](https://img.shields.io/github/stars/ivylee/model-cards-and-datasheets?style=social)
* [NewsGuard AI Tracking Center](https://www.newsguardtech.com/special-reports/ai-tracking-center/)
* [OpenAI, Building an early warning system for LLM-aided biological threat creation](https://openai.com/research/building-an-early-warning-system-for-llm-aided-biological-threat-creation)
* [OpenAI Cookbook, How to implement LLM guardrails](https://cookbook.openai.com/examples/how_to_use_guardrails)
* [OpenAI, Evals](https://github.com/openai/evals)![](https://img.shields.io/github/stars/openai/evals?style=social)
* [Open Sourcing Highly Capable Foundation Models](https://www.governance.ai/research-paper/open-sourcing-highly-capable-foundation-models)
* [Organization and Training of a Cyber Security Team](http://ieeexplore.ieee.org/document/1245662)
* [Our Data Our Selves, Data Use Policy](https://ourdataourselves.tacticaltech.org/data-use-policy/)
* [PAIR Explorables: Datasets Have Worldviews](https://pair.withgoogle.com/explorables/dataset-worldviews/)
* [Partnership on AI, ABOUT ML Reference Document](https://partnershiponai.org/paper/about-ml-reference-document/)
* [Partnership on AI, PAI’s Guidance for Safe Foundation Model Deployment: A Framework for Collective Action](https://partnershiponai.org/modeldeployment/)
* [Partnership on AI, Responsible Practices for Synthetic Media: A Framework for Collective Action](https://syntheticmedia.partnershiponai.org/)
* [PwC's Responsible AI](https://www.pwc.com/gx/en/issues/data-and-analytics/artificial-intelligence/what-is-responsible-ai.html)
* [Real-World Strategies for Model Debugging](https://towardsdatascience.com/strategies-for-model-debugging-aa822f1097ce)
* [RecoSense: Phases of an AI Data Audit – Assessing Opportunity in the Enterprise](https://recosenselabs.com/blog/phases-of-an-ai-data-audit-assessing-opportunity-in-the-enterprise)
* [Robust ML](https://www.robust-ml.org/)
* [Safe and Reliable Machine Learning](https://www.dropbox.com/s/sdu26h96bc0f4l7/FAT19-AI-Reliability-Final.pdf?dl=0)
* [Sample AI Incident Response Checklist](https://bnh-ai.github.io/resources/)
* [SHRM Generative Artificial Intelligence (AI) Chatbot Usage Policy](https://www.shrm.org/resourcesandtools/tools-and-samples/policies/pages/chatgpt-generative-ai-usage.aspx)
* [Special Competitive Studies Project and Johns Hopkins University Applied Physics Laboratory, Framework for Identifying Highly Consequential AI Use Cases](https://www.scsp.ai/wp-content/uploads/2023/11/SCSP_JHU-HCAI-Framework-Nov-6.pdf)
* [Stanford University, Responsible AI at Stanford: Enabling innovation through AI best practices](https://uit.stanford.edu/security/responsibleai)
* [Synack, The Complete Guide to Crowdsourced Security Testing, Government Edition](https://www.synack.com/wp-content/uploads/2022/09/Crowdsourced-Security-Landscape-Government.pdf)
* [The Rise of Generative AI and the Coming Era of Social Media Manipulation 3.0: Next-Generation Chinese Astroturfing and Coping with Ubiquitous AI](https://www.rand.org/pubs/perspectives/PEA2679-1.html)
* [Taskade: AI Audit PBC Request Checklist Template](https://www.taskade.com/templates/engineering/audit-pbc-request-checklist)
* [TechTarget: 9 questions to ask when auditing your AI systems](https://www.techrepublic.com/article/9-questions-to-ask-when-auditing-your-ai-systems/)
* [Troubleshooting Deep Neural Networks](http://josh-tobin.com/assets/pdf/troubleshooting-deep-neural-networks-01-19.pdf)
* [Twitter Algorithmic Bias Bounty](https://hackerone.com/twitter-algorithmic-bias?type=team)
* [Unite.AI: How to perform an AI Audit in 2023](https://www.unite.ai/how-to-perform-an-ai-audit-in-2023/)
* [University of California, Berkeley, Center for Long-Term Cybersecurity, A Taxonomy of Trustworthiness for Artificial Intelligence](https://cltc.berkeley.edu/wp-content/uploads/2023/12/Taxonomy_of_AI_Trustworthiness_tables.pdf)
* [University of California, Berkeley, Information Security Office, How to Write an Effective Website Privacy Statement](https://security.berkeley.edu/how-write-effective-website-privacy-statement)
* [University of Washington Tech Policy Lab, Data Statements](https://techpolicylab.uw.edu/data-statements/)
* [Warning Signs: The Future of Privacy and Security in an Age of Machine Learning](https://fpf.org/wp-content/uploads/2019/09/FPF_WarningSigns_Report.pdf)
* [When Not to Trust Your Explanations](https://docs.google.com/presentation/d/10a0PNKwoV3a1XChzvY-T1mWudtzUIZi3sCMzVwGSYfM/edit)
* [Why We Need to Know More: Exploring the State of AI Incident Documentation Practices](https://dl.acm.org/doi/fullHtml/10.1145/3600211.3604700)
* [You Created A Machine Learning Application Now Make Sure It's Secure](https://www.oreilly.com/ideas/you-created-a-machine-learning-application-now-make-sure-its-secure)

#### Infographics and Cheat Sheets

* [Future of Privacy Forum, The Spectrum of Artificial Intelligence](https://fpf.org/wp-content/uploads/2021/01/FPF_AIEcosystem_illo_03.pdf)
* [Machine Learning Attack_Cheat_Sheet](https://resources.oreilly.com/examples/0636920415947/-/blob/master/Attack_Cheat_Sheet.png)
* [Open Source Audit Tooling (OAT) Landscape](https://tools.auditing-ai.com/)
* [Trustible, Is It AI? How different laws & frameworks define AI](https://www.trustible.ai/post/is-it-ai-how-different-laws-frameworks-define-ai)

#### LLM Red Teaming Resources

* [@dotey on X/Twitter exploring GPT prompt security and prevention measures](https://x.com/dotey/status/1724623497438155031?s=20)
* [0xeb / GPT-analyst](https://github.com/0xeb/gpt-analyst/)![](https://img.shields.io/github/stars/0xeb/gpt-analyst?style=social)
* [0xk1h0 / ChatGPT "DAN" (and other "Jailbreaks")](https://github.com/0xk1h0/ChatGPT_DAN)![](https://github.com/0xk1h0/ChatGPT_DAN)![](https://img.shields.io/github/stars/0xk1h0/ChatGPT_DAN?style=social)
* [ACL 2024 Tutorial: Vulnerabilities of Large Language Models to Adversarial Attacks](https://llm-vulnerability.github.io/)
* [Azure's PyRIT](https://github.com/Azure/PyRIT)![](https://img.shields.io/github/stars/Azure/PyRIT?style=social)
* [CDAO frameworks, guidance, and best practices for AI test & evaluation](https://gitlab.jatic.net/home/frameworks)
* [ChatGPT_system_prompt](https://github.com/LouisShark/chatgpt_system_prompt)![](https://img.shields.io/github/stars/LouisShark/chatgpt_system_prompt?style=social)
* [coolaj86 / Chat GPT "DAN" (and other "Jailbreaks")](https://gist.github.com/coolaj86/6f4f7b30129b0251f61fa7baaa881516)![](https://img.shields.io/github/stars/coolaj86?style=social)
* [CSET, What Does AI-Red Teaming Actually Mean?](https://cset.georgetown.edu/article/what-does-ai-red-teaming-actually-mean/)
* [DAIR Prompt Engineering Guide](https://www.promptingguide.ai/)
  * [DAIR Prompt Engineering Guide GitHub](https://github.com/dair-ai/Prompt-Engineering-Guide)![](https://img.shields.io/github/stars/dair-ai/Prompt-Engineering-Guide?style=social)
* [Exploiting Novel GPT-4 APIs](https://arxiv.org/abs/2312.14302)
* [Extracting Training Data from ChatGPT](https://not-just-memorization.github.io/extracting-training-data-from-chatgpt.html)
* [Frontier Model Forum: What is Red Teaming?](https://www.frontiermodelforum.org/uploads/2023/10/FMF-AI-Red-Teaming.pdf)
* [HackerOne, An Emerging Playbook for AI Red Teaming with HackerOne](https://www.hackerone.com/thought-leadership/ai-safety-red-teaming)
* [Identifying and Eliminating CSAM in Generative ML Training Data and Models](https://purl.stanford.edu/kh752sm9123)
* [Jailbreaking Black Box Large Language Models in Twenty Queries](https://arxiv.org/abs/2310.08419)
* [Learn Prompting, Prompt Hacking](https://learnprompting.org/docs/category/-prompt-hacking)
  * [MiesnerJacob / learn-prompting, Prompt Hacking](https://github.com/MiesnerJacob/learn-prompting/blob/main/08.%F0%9F%94%93%20Prompt%20Hacking.ipynb)![](https://img.shields.io/github/stars/MiesnerJacob/learn-prompting?style=social)
* [Lakera AI's Gandalf](https://gandalf.lakera.ai/)
* [leondz / garak](https://github.com/leondz/garak)![](https://img.shields.io/github/stars/leondz/garak?style=social)
* [Microsoft AI Red Team building future of safer AI](https://www.microsoft.com/en-us/security/blog/2023/08/07/microsoft-ai-red-team-building-future-of-safer-ai/)
* [OpenAI Red Teaming Network](https://openai.com/blog/red-teaming-network)
* [r/ChatGPTJailbreak](https://www.reddit.com/r/ChatGPTJailbreak/)
* [Red Teaming Language Models to Reduce Harms: Methods, Scaling Behaviors, and Lessons Learned](https://arxiv.org/abs/2209.07858)
* [Red Teaming of Advanced Information Assurance Concepts](https://ieeexplore.ieee.org/document/821513)
* [Y Combinator, ChatGPT Grandma Exploit](https://news.ycombinator.com/item?id=35630801)

### Conferences and Workshops

This section is for conferences, workshops and other major events related to responsible ML.

* [AAAI Conference on Artificial Intelligence](https://aaai.org/conference/aaai/)
* [ACM FAccT (Fairness, Accountability, and Transparency)](https://facctconference.org/)
  * [FAT/ML (Fairness, Accountability, and Transparency in Machine Learning)](https://www.fatml.org/) 
* [ACM Conference on Equity and Access in Algorithms, Mechanisms, and Optimization (EAAMO)](https://eaamo.org/)
* [AIES (AAAI/ACM Conference on AI, Ethics, and Society)](https://www.aies-conference.com/) 
* [Black in AI](https://blackinai.github.io/#/)
* [Computer Vision and Pattern Recognition (CVPR)](https://thecvf.com/)
* [International Conference on Machine Learning (ICML)](https://icml.cc/)
  * **2020**:
    * [2nd ICML Workshop on Human in the Loop Learning (HILL)](https://icml.cc/virtual/2020/workshop/5747)
    * [5th ICML Workshop on Human Interpretability in Machine Learning (WHI)](https://icml.cc/virtual/2020/workshop/5746)
    * [Challenges in Deploying and Monitoring Machine Learning Systems](https://icml.cc/virtual/2020/workshop/5738)
    * [Economics of privacy and data labor](https://icml.cc/virtual/2020/workshop/5723)
    * [Federated Learning for User Privacy and Data Confidentiality](https://icml.cc/virtual/2020/workshop/5730)
    * [Healthcare Systems, Population Health, and the Role of Health-tech](https://icml.cc/virtual/2020/workshop/5726)
    * [Law & Machine Learning](https://icml.cc/virtual/2020/workshop/5718)
    * [ML Interpretability for Scientific Discovery](https://icml.cc/virtual/2020/workshop/5740)
    * [MLRetrospectives: A Venue for Self-Reflection in ML Research](https://icml.cc/virtual/2020/workshop/5739)
    * [Participatory Approaches to Machine Learning](https://icml.cc/virtual/2020/workshop/5720)
    * [XXAI: Extending Explainable AI Beyond Deep Models and Classifiers](https://icml.cc/virtual/2020/workshop/5734)
  * **2021**:
    * [Human-AI Collaboration in Sequential Decision-Making](https://icml.cc/virtual/2021/workshop/8367)
    * [Machine Learning for Data: Automated Creation, Privacy, Bias](https://icml.cc/virtual/2021/workshop/8356)
    * [ICML Workshop on Algorithmic Recourse](https://icml.cc/virtual/2021/workshop/8363)
    * [ICML Workshop on Human in the Loop Learning (HILL)](https://icml.cc/virtual/2021/workshop/8362)
    * [ICML Workshop on Theoretic Foundation, Criticism, and Application Trend of Explainable AI](https://icml.cc/virtual/2021/workshop/8355)
    * [Information-Theoretic Methods for Rigorous, Responsible, and Reliable Machine Learning (ITR3)](https://icml.cc/virtual/2021/workshop/8365)
    * [International Workshop on Federated Learning for User Privacy and Data Confidentiality in Conjunction with ICML 2021 (FL-ICML'21)](https://icml.cc/virtual/2021/workshop/8359)
    * [Interpretable Machine Learning in Healthcare](https://icml.cc/virtual/2021/workshop/8358)
    * [Self-Supervised Learning for Reasoning and Perception](https://icml.cc/virtual/2021/workshop/8353)
    * [The Neglected Assumptions In Causal Inference](https://icml.cc/virtual/2021/workshop/8349)
    * [Theory and Practice of Differential Privacy](https://icml.cc/virtual/2021/workshop/8376)
    * [Uncertainty and Robustness in Deep Learning](https://icml.cc/virtual/2021/workshop/8374)
    * [Workshop on Computational Approaches to Mental Health @ ICML 2021](https://icml.cc/virtual/2021/workshop/8352)
    * [Workshop on Distribution-Free Uncertainty Quantification](https://icml.cc/virtual/2021/workshop/8373)
    * [Workshop on Socially Responsible Machine Learning](https://icml.cc/virtual/2021/workshop/8347)
  * **2022**:
    * [1st ICML 2022 Workshop on Safe Learning for Autonomous Driving (SL4AD)](https://icml.cc/virtual/2022/workshop/13475)
    * [2nd Workshop on Interpretable Machine Learning in Healthcare (IMLH)](https://icml.cc/virtual/2022/workshop/13449)
    * [DataPerf: Benchmarking Data for Data-Centric AI](https://icml.cc/virtual/2022/workshop/13477)
    * [Disinformation Countermeasures and Machine Learning (DisCoML)](https://icml.cc/virtual/2022/workshop/13446)
    * [Responsible Decision Making in Dynamic Environments](https://icml.cc/virtual/2022/workshop/13453)
    * [Spurious correlations, Invariance, and Stability (SCIS)](https://icml.cc/virtual/2022/workshop/13461)
    * [The 1st Workshop on Healthcare AI and COVID-19](https://icml.cc/virtual/2022/workshop/13469)
    * [Theory and Practice of Differential Privacy](https://icml.cc/virtual/2022/workshop/13448)
    * [Workshop on Human-Machine Collaboration and Teaming](https://icml.cc/virtual/2022/workshop/13478)
  * **2023**:
    * [2nd ICML Workshop on New Frontiers in Adversarial Machine Learning](https://icml.cc/virtual/2023/workshop/21487)
    * [2nd Workshop on Formal Verification of Machine Learning](https://icml.cc/virtual/2023/workshop/21471)
    * [3rd Workshop on Interpretable Machine Learning in Healthcare (IMLH)](https://icml.cc/virtual/2023/workshop/21486)
    * [Challenges in Deployable Generative AI](https://icml.cc/virtual/2023/workshop/21481)
    * [“Could it have been different?” Counterfactuals in Minds and Machines](https://icml.cc/virtual/2023/workshop/21482)
    * [Federated Learning and Analytics in Practice: Algorithms, Systems, Applications, and Opportunities](https://icml.cc/virtual/2023/workshop/21473)
    * [Generative AI and Law (GenLaw)](https://icml.cc/virtual/2023/workshop/21490)
    * [Interactive Learning with Implicit Human Feedback](https://icml.cc/virtual/2023/workshop/21477)
    * [Neural Conversational AI Workshop - What’s left to TEACH (Trustworthy, Enhanced, Adaptable, Capable and Human-centric) chatbots?](https://icml.cc/virtual/2023/workshop/21485)
    * [The Second Workshop on Spurious Correlations, Invariance and Stability](https://icml.cc/virtual/2023/workshop/21493)
* [Knowledge, Discovery, and Data Mining (KDD)](https://kdd.org/)
  * **2023**:
    * [2nd ACM SIGKDD Workshop on Ethical Artificial Intelligence: Methods and Applications](https://charliezhaoyinpeng.github.io/EAI-KDD23/cfp/)
    * [KDD Data Science for Social Good 2023](https://kdd-dssg.github.io/)
* [Neural Information Processing Systems (NeurIPs)](https://neurips.cc/)
  * **2022**:
    * [5th Robot Learning Workshop: Trustworthy Robotics](https://neurips.cc/virtual/2022/workshop/49997)
    * [Algorithmic Fairness through the Lens of Causality and Privacy](https://neurips.cc/virtual/2022/workshop/49967)
    * [Causal Machine Learning for Real-World Impact](https://neurips.cc/virtual/2022/workshop/49993)
    * [Challenges in Deploying and Monitoring Machine Learning Systems](https://neurips.cc/virtual/2022/workshop/49982)
    * [Cultures of AI and AI for Culture](https://neurips.cc/virtual/2022/workshop/49983)
    * [Empowering Communities: A Participatory Approach to AI for Mental Health](https://neurips.cc/virtual/2022/workshop/49984)
    * [Federated Learning: Recent Advances and New Challenges](https://neurips.cc/virtual/2022/workshop/50002)
    * [Gaze meets ML](https://neurips.cc/virtual/2022/workshop/49990)
    * [HCAI@NeurIPS 2022, Human Centered AI](https://neurips.cc/virtual/2022/workshop/50008)
    * [Human Evaluation of Generative Models](https://neurips.cc/virtual/2022/workshop/49978)
    * [Human in the Loop Learning (HiLL) Workshop at NeurIPS 2022](https://neurips.cc/virtual/2022/workshop/49957)
    * [I Can’t Believe It’s Not Better: Understanding Deep Learning Through Empirical Falsification](https://neurips.cc/virtual/2022/workshop/49960)
    * [Learning Meaningful Representations of Life](https://neurips.cc/virtual/2022/workshop/49966)
    * [Machine Learning for Autonomous Driving](https://neurips.cc/virtual/2022/workshop/49981)
    * [Progress and Challenges in Building Trustworthy Embodied AI](https://neurips.cc/virtual/2022/workshop/49972)
    * [Tackling Climate Change with Machine Learning](https://neurips.cc/virtual/2022/workshop/49964)
    * [Trustworthy and Socially Responsible Machine Learning](https://neurips.cc/virtual/2022/workshop/49959)
    * [Workshop on Machine Learning Safety](https://neurips.cc/virtual/2022/workshop/49986)
  * **2023**: 
    * [AI meets Moral Philosophy and Moral Psychology: An Interdisciplinary Dialogue about Computational Ethics](https://neurips.cc/virtual/2023/workshop/66528)
    * [Algorithmic Fairness through the Lens of Time](https://neurips.cc/virtual/2023/workshop/66502)
    * [Attributing Model Behavior at Scale (ATTRIB)](https://neurips.cc/virtual/2023/workshop/66496)
    * [Backdoors in Deep Learning: The Good, the Bad, and the Ugly](https://neurips.cc/virtual/2023/workshop/66550)
    * [Computational Sustainability: Promises and Pitfalls from Theory to Deployment](https://neurips.cc/virtual/2023/workshop/66523)
    * [I Can’t Believe It’s Not Better (ICBINB): Failure Modes in the Age of Foundation Models](https://neurips.cc/virtual/2023/workshop/66506)
    * [Socially Responsible Language Modelling Research (SoLaR)](https://neurips.cc/virtual/2023/workshop/66526)
    * [Regulatable ML: Towards Bridging the Gaps between Machine Learning Research and Regulations](https://neurips.cc/virtual/2023/workshop/66512)
    * [Workshop on Distribution Shifts: New Frontiers with Foundation Models](https://neurips.cc/virtual/2023/workshop/66509)
    * [XAI in Action: Past, Present, and Future Applications](https://neurips.cc/virtual/2023/workshop/66529)
 * [Oxford Generative AI Summit Slides](https://drive.google.com/drive/folders/1WQPaL-ozhZbZaDichFm4gWZQpGwriT32)

### Official Policy, Frameworks, and Guidance

This section serves as a repository for policy documents, regulations, guidelines, and recommendations that govern the ethical and responsible use of artificial intelligence and machine learning technologies. From international legal frameworks to specific national laws, the resources cover a broad spectrum of topics such as fairness, privacy, ethics, and governance. 

* [12 CFR Part 1002 - Equal Credit Opportunity Act (Regulation B)](https://www.consumerfinance.gov/policy-compliance/rulemaking/regulations/1002/)
* [Aiming for truth, fairness, and equity in your company’s use of AI](https://www.ftc.gov/news-events/blogs/business-blog/2021/04/aiming-truth-fairness-equity-your-companys-use-ai)
* [Algorithmic Accountability Act of 2023](https://www.govinfo.gov/app/details/BILLS-118hr5628ih/)
* [Algorithm Charter for Aotearoa New Zealand](https://data.govt.nz/assets/data-ethics/algorithm/Algorithm-Charter-2020_Final-English-1.pdf)
* [A Regulatory Framework for AI: Recommendations for PIPEDA Reform](https://www.priv.gc.ca/en/about-the-opc/what-we-do/consultations/completed-consultations/consultation-ai/reg-fw_202011/)
* [Artificial Intelligence (AI) in the Securities Industry](https://www.finra.org/sites/default/files/2020-06/ai-report-061020.pdf)
* [Assessment List for Trustworthy Artificial Intelligence (ALTAI) for self-assessment - Shaping Europe’s digital future - European Commission](https://ec.europa.eu/digital-single-market/en/news/assessment-list-trustworthy-artificial-intelligence-altai-self-assessment)
* [Audit of Governance and Protection of Department of Defense Artificial Intelligence Data and Technology](https://media.defense.gov/2020/Jul/01/2002347967/-1/-1/1/DODIG-2020-098.PDF)
* [A Primer on Artificial Intelligence in Securities Markets](https://www.cftc.gov/media/2846/LabCFTC_PrimerArtificialIntelligence102119/download)
* [Biometric Information Privacy Act](https://www.ilga.gov/legislation/ilcs/ilcs3.asp?ActID=3004&ChapterID=57)
* [Booker Wyden Health Care Letters](https://www.scribd.com/document/437954989/Booker-Wyden-Health-Care-Letters#download)
* [California Consumer Privacy Act (CCPA)](https://oag.ca.gov/privacy/ccpa)
* [California Department of Justice, How to Read a Privacy Policy](https://www.oag.ca.gov/privacy/facts/online-privacy/privacy-policy)
* [California Privacy Rights Act (CPRA)](https://www.oag.ca.gov/system/files/initiatives/pdfs/19-0021A1%20%28Consumer%20Privacy%20-%20Version%203%29_1.pdf)
* [Can’t lose what you never had: Claims about digital ownership and creation in the age of generative AI](https://www.ftc.gov/business-guidance/blog/2023/08/cant-lose-what-you-never-had-claims-about-digital-ownership-creation-age-generative-ai)
* [Children's Online Privacy Protection Rule ("COPPA")](https://www.ftc.gov/legal-library/browse/rules/childrens-online-privacy-protection-rule-coppa)
* [Civil liability regime for artificial intelligence](https://www.europarl.europa.eu/doceo/document/TA-9-2020-0276_EN.pdf)
* [Congressional Research Service, Artificial Intelligence: Overview, Recent Advances, and Considerations for the 118th Congress](https://www.energy.gov/sites/default/files/2023-09/Artificial%20Intelligence%20Overview%2C%20Recent%20Advances%2C%20and%20Considerations%20for%20the%20118th%20Congress.pdf)
* [Consumer Data Protection Act (Code of Virginia)](https://law.lis.virginia.gov/vacodefull/title59.1/chapter53/)
* [Consumer Financial Protection Bureau (CFPB), Chatbots in consumer finance](https://www.consumerfinance.gov/data-research/research-reports/chatbots-in-consumer-finance/chatbots-in-consumer-finance/)
* [DARPA, Explainable Artificial Intelligence (XAI) (Archived)](https://www.darpa.mil/program/explainable-artificial-intelligence)
* [Data Availability and Transparency Act 2022 (Australia)](https://www.datacommissioner.gov.au/law/dat-act)
* [data.gov, Privacy Policy and Data Policy](https://data.gov/privacy-policy/)
* [Defense Technical Information Center, Computer Security Technology Planning Study, October 1, 1972](https://apps.dtic.mil/sti/citations/AD0758206)
* [De-identification Tools](https://www.nist.gov/itl/applied-cybersecurity/privacy-engineering/collaboration-space/focus-areas/de-id/tools)
* [Department for Science, Innovation and Technology, The Bletchley Declaration by Countries Attending the AI Safety Summit, 1-2 November 2023](https://www.gov.uk/government/publications/ai-safety-summit-2023-the-bletchley-declaration/the-bletchley-declaration-by-countries-attending-the-ai-safety-summit-1-2-november-2023)
* [Department for Science, Innovation and Technology, Frontier AI: capabilities and risks - discussion paper (United Kingdom)](https://www.gov.uk/government/publications/frontier-ai-capabilities-and-risks-discussion-paper)
* [Department for Science, Innovation and Technology, Guidance, Introduction to AI Assurance](https://www.gov.uk/government/publications/introduction-to-ai-assurance)
* [Department of Commerce, Intellectual property](https://www.commerce.gov/issues/intellectual-property)
* [Department of Defense, AI Principles: Recommendations on the Ethical Use of Artificial Intelligence](https://media.defense.gov/2019/Oct/31/2002204458/-1/-1/0/DIB_AI_PRINCIPLES_PRIMARY_DOCUMENT.PDF)
* [Department of Defense, Chief Data and Artificial Intelligence Officer (CDAO) Assessment and Assurance](https://gitlab.jatic.net/home)
    * [RAI Toolkit](https://rai.tradewindai.com/)
* [Developing Financial Sector Resilience in a Digital World: Selected Themes in Technology and Related Risks](https://www.osfi-bsif.gc.ca/Eng/Docs/tchrsk.pdf)
* [The Digital Services Act package (EU Digital Services Act and Digital Markets Act)](https://digital-strategy.ec.europa.eu/en/policies/digital-services-act-package)
* [Directive on Automated Decision Making (Canada)](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=32592)
* [(Draft Guideline) E-23 – Model Risk Management](https://www.osfi-bsif.gc.ca/en/guidance/guidance-library/draft-guideline-e-23-model-risk-management)
* [EEOC Letter (from U.S. senators re: hiring software)](https://www.bennet.senate.gov/public/_cache/files/0/a/0a439d4b-e373-4451-84ed-ba333ce6d1dd/672D2E4304D63A04CC3465C3C8BF1D21.letter-to-chair-dhillon.pdf)
* [European Commission, Hiroshima Process International Guiding Principles for Advanced AI system](https://digital-strategy.ec.europa.eu/en/library/hiroshima-process-international-guiding-principles-advanced-ai-system)
* [Executive Order 13960 (2020-12-03), Promoting the Use of Trustworthy Artificial Intelligence in the Federal Government](https://www.federalregister.gov/documents/2020/12/08/2020-27065/promoting-the-use-of-trustworthy-artificial-intelligence-in-the-federal-government)
* [Executive Order on the Safe, Secure, and Trustworthy Development and Use of Artificial Intelligence](https://www.whitehouse.gov/briefing-room/presidential-actions/2023/10/30/executive-order-on-the-safe-secure-and-trustworthy-development-and-use-of-artificial-intelligence/)
* [Facial Recognition and Biometric Technology Moratorium Act of 2020](https://drive.google.com/file/d/1gkTcjFtieMQdsQ01dmDa49B6HY9ZyKr8/view)
* [FDA Artificial Intelligence/Machine Learning (AI/ML)-Based: Software as a Medical Device (SaMD) Action Plan, updated January 2021](https://www.fda.gov/media/145022/download)
* [FDA Software as a Medical Device (SAMD) guidance (December 8, 2017)](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/software-medical-device-samd-clinical-evaluation)
* [FDIC Supervisory Guidance on Model Risk Management](https://www.fdic.gov/news/financial-institution-letters/2017/fil17022a.pdf)
* [Federal Consumer Online Privacy Rights Act (COPRA)](https://www.consumerprivacyact.com/federal/)
* [Federal Reserve Bank of Dallas, Regulation B, Equal Credit Opportunity, Credit Scoring Interpretations: Withdrawl of Proposed Business Credit Amendments, June 3, 1982](https://fraser.stlouisfed.org/files/docs/historical/frbdal/circulars/frbdallas_circ_19820603_no82-063.pdf)
* [FHA model risk management/model governance guidance](https://www.fhfa.gov/SupervisionRegulation/AdvisoryBulletins/Pages/Model-Risk-Management-Guidance.aspx)
* [FTC Business Blog](https://www.ftc.gov/business-guidance/blog):
  * [2020-04-08 Using Artificial Intelligence and Algorithms](https://www.ftc.gov/business-guidance/blog/2020/04/using-artificial-intelligence-and-algorithms)
  * [2021-01-11 Facing the facts about facial recognition](https://www.ftc.gov/business-guidance/blog/2021/01/facing-facts-about-facial-recognition)
  * [2021-04-19 Aiming for truth, fairness, and equity in your company’s use of AI](https://www.ftc.gov/business-guidance/blog/2021/04/aiming-truth-fairness-equity-your-companys-use-ai)
  * [2022-07-11 Location, health, and other sensitive information: FTC committed to fully enforcing the law against illegal use and sharing of highly sensitive data](https://www.ftc.gov/business-guidance/blog/2022/07/location-health-and-other-sensitive-information-ftc-committed-fully-enforcing-law-against-illegal)
  * [2023-07-25 Protecting the privacy of health information: A baker’s dozen takeaways from FTC cases](https://www.ftc.gov/business-guidance/blog/2023/07/protecting-privacy-health-information-bakers-dozen-takeaways-ftc-cases)
  * [2023-08-16 Can’t lose what you never had: Claims about digital ownership and creation in the age of generative AI](https://www.ftc.gov/business-guidance/blog/2023/08/cant-lose-what-you-never-had-claims-about-digital-ownership-creation-age-generative-ai)
  * [2023-08-22 For business opportunity sellers, FTC says “AI” stands for “allegedly inaccurate”](https://www.ftc.gov/business-guidance/blog/2023/08/business-opportunity-sellers-ftc-says-ai-stands-allegedly-inaccurate)
  * [2023-09-15 Updated FTC-HHS publication outlines privacy and security laws and rules that impact consumer health data](https://www.ftc.gov/business-guidance/blog/2023/09/updated-ftc-hhs-publication-outlines-privacy-security-laws-rules-impact-consumer-health-data)
  * [2023-09-18 Companies warned about consequences of loose use of consumers’ confidential data](https://www.ftc.gov/business-guidance/blog/2023/09/companies-warned-about-consequences-loose-use-consumers-confidential-data)
  * [2023-09-27 Could PrivacyCon 2024 be the place to present your research on AI, privacy, or surveillance?](https://www.ftc.gov/business-guidance/blog/2023/09/could-privacycon-2024-be-place-present-your-research-ai-privacy-or-surveillance)
  * [2022-05-20 Security Beyond Prevention: The Importance of Effective Breach Disclosures](https://www.ftc.gov/policy/advocacy-research/tech-at-ftc/2022/05/security-beyond-prevention-importance-effective-breach-disclosures)
  * [2023-02-01 Security Principles: Addressing underlying causes of risk in complex systems](https://www.ftc.gov/policy/advocacy-research/tech-at-ftc/2023/02/security-principles-addressing-underlying-causes-risk-complex-systems)
  * [2023-06-29 Generative AI Raises Competition Concerns](https://www.ftc.gov/policy/advocacy-research/tech-at-ftc/2023/06/generative-ai-raises-competition-concerns)
  * [2023-12-19 Coming face to face with Rite Aid’s allegedly unfair use of facial recognition technology](https://www.ftc.gov/business-guidance/blog/2023/12/coming-face-face-rite-aids-allegedly-unfair-use-facial-recognition-technology)
* [FTC Privacy Policy](https://www.ftc.gov/policy-notices/privacy-policy)
* [Government Accountability Office: Artificial Intelligence: An Accountability Framework for Federal Agencies and Other Entities](https://www.gao.gov/products/gao-21-519sp)
* [General Data Protection Regulation (GDPR)](https://gdpr-info.eu/)
  * [Article 22 EU GDPR "Automated individual decision-making, including profiling"](https://www.privacy-regulation.eu/en/article-22-automated-individual-decision-making-including-profiling-GDPR.htm)
* [General principles for the use of Artificial Intelligence in the financial sector](https://www.dnb.nl/media/jkbip2jc/general-principles-for-the-use-of-artificial-intelligence-in-the-financial-sector.pdf)
* [Gouvernance des algorithmes d’intelligence artificielle dans le secteur financier (France)](https://acpr.banque-france.fr/sites/default/files/medias/documents/20200612_gouvernance_evaluation_ia.pdf)
* [Guidelines for secure AI system development](https://media.defense.gov/2023/Nov/27/2003346994/-1/-1/0/GUIDELINES-FOR-SECURE-AI-SYSTEM-DEVELOPMENT.PDF)
* [IAPP Global AI Legislation Tracker](https://iapp.org/resources/article/global-ai-legislation-tracker/)
* [IAPP US State Privacy Legislation Tracker](https://iapp.org/resources/article/us-state-privacy-legislation-tracker/)
* [Innovation spotlight: Providing adverse action notices when using AI/ML models](https://www.consumerfinance.gov/about-us/blog/innovation-spotlight-providing-adverse-action-notices-when-using-ai-ml-models/)
* [Justice in Policing Act](https://democrats-judiciary.house.gov/issues/issue/?IssueID=14924)
* [National Conference of State Legislatures (NCSL) 2020 Consumer Data Privacy Legislation](https://www.ncsl.org/technology-and-communication/2020-consumer-data-privacy-legislation)
* [National Institute of Standards and Technology (NIST), AI 100-1 Artificial Intelligence Risk Management Framework (NIST AI RMF 1.0)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf)
* [National Institute of Standards and Technology (NIST), Four Principles of Explainable Artificial Intelligence, Draft NISTIR 8312, 2020-08-17](https://www.nist.gov/system/files/documents/2020/08/17/NIST%20Explainable%20AI%20Draft%20NISTIR8312%20%281%29.pdf)
* [National Institute of Standards and Technology (NIST), Four Principles of Explainable Artificial Intelligence, NISTIR 8312, 2021-09-29](https://www.nist.gov/publications/four-principles-explainable-artificial-intelligence)
* [National Institute of Standards and Technology (NIST), Measurement Uncertainty](https://www.nist.gov/itl/sed/topic-areas/measurement-uncertainty)
  * [International Bureau of Weights and Measures (BIPM), Evaluation of measurement data—Guide to the expression of uncertainty in measurement](https://www.bipm.org/documents/20126/2071204/JCGM_100_2008_E.pdf/cb0ef43f-baa5-11cf-3f85-4dcd86f77bd6)
* [National Institute of Standards and Technology (NIST), NIST Special Publication 800-30 Revision 1, Guide for Conducting Risk Assessments](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf)
* [National Security Commission on Artificial Intelligence, Final Report](https://assets.foleon.com/eu-central-1/de-uploads-7e3kk3/48187/nscai_full_report_digital.04d6b124173c.pdf)
* [National Science and Technology Council (NSTC), Select Committee on Artificial Intelligence, National Artificial Intelligence Research and Development Strategic Plan 2023 Update](https://www.whitehouse.gov/wp-content/uploads/2023/05/National-Artificial-Intelligence-Research-and-Development-Strategic-Plan-2023-Update.pdf)
* [New York City Automated Decision Systems Task Force Report (November 2019)](https://www.nyc.gov/assets/adstaskforce/downloads/pdf/ADS-Report-11192019.pdf)
* [OECD, Open, Useful and Re-usable data (OURdata) Index: 2019 - Policy Paper](https://www.oecd.org/gov/digital-government/policy-paper-ourdata-index-2019.htm)
* [Office of the Director of National Intelligence (ODNI), The AIM Initiative: A Strategy for Augmenting Intelligence Using Machines](https://www.dni.gov/files/ODNI/documents/AIM-Strategy.pdf)
* [Office of Management and Budget, Guidance for Regulation of Artificial Intelligence Applications, finalized November 2020](https://www.whitehouse.gov/wp-content/uploads/2020/11/M-21-06.pdf)
* [Office of Science and Technology Policy, Blueprint for an AI Bill of Rights: Making Automated Systems Work for the American People](https://www.whitehouse.gov/ostp/ai-bill-of-rights/)
* [Office of the Comptroller of the Currency (OCC), 2021 Model Risk Management Handbook](https://www.occ.gov/publications-and-resources/publications/comptrollers-handbook/files/model-risk-management/index-model-risk-management.html)
* [Online Harms White Paper: Full government response to the consultation (United Kingdom)](https://www.gov.uk/government/consultations/online-harms-white-paper)
* [Online Privacy Act of 2023](https://eshoo.house.gov/sites/evo-subsites/eshoo.house.gov/files/evo-media-document/4.12.23-opa.pdf)
* [Online Safety Bill (United Kingdom)](https://bills.parliament.uk/bills/3137)
* [Principles of Artificial Intelligence Ethics for the Intelligence Community](https://www.intel.gov/principles-of-artificial-intelligence-ethics-for-the-intelligence-community)
* [Privacy Act 1988 (Australia)](https://www.legislation.gov.au/Details/C2014C00076)
* [Proposal for a Regulation laying down harmonised rules on artificial intelligence (Artificial Intelligence Act)](https://digital-strategy.ec.europa.eu/en/library/proposal-regulation-laying-down-harmonised-rules-artificial-intelligence-artificial-intelligence)
  * [Amendments adopted by the European Parliament on 14 June 2023 on the proposal for a regulation of the European Parliament and of the Council on laying down harmonised rules on artificial intelligence (Artificial Intelligence Act) and amending certain Union legislative acts](https://www.europarl.europa.eu/doceo/document/TA-9-2023-0236_EN.html)
* [Psychological Foundations of Explainability and Interpretability in Artificial Intelligence](https://nvlpubs.nist.gov/nistpubs/ir/2021/NIST.IR.8367.pdf)
* [The Public Sector Bodies (Websites and Mobile Applications) Accessibility Regulations 2018 (United Kingdom)](https://www.legislation.gov.uk/uksi/2018/852/contents/made)
* [Questions and Answers to Clarify and Provide a Common Interpretation of the Uniform Guidelines on Employee Selection Procedures](https://www.eeoc.gov/laws/guidance/questions-and-answers-clarify-and-provide-common-interpretation-uniform-guidelines)
* [Questions from the Commission on Protecting Privacy and Preventing Discrimination](https://auditor.utah.gov/wp-content/uploads/sites/6/2021/02/Office-of-the-State-Auditor-Questions-to-help-Procuring-Agencies-_-Entities-with-Software-Procurement-Feb-1-2021-Final.pdf)
* [RE: Use of External Consumer Data and Information Sources in Underwriting for Life Insurance](https://www.dfs.ny.gov/industry_guidance/circular_letters/cl2019_01)
* [Singapore's Companion to the Model AI Governance Framework – Implementation and Self-Assessment Guide for Organizations](https://www.pdpc.gov.sg/-/media/files/pdpc/pdf-files/resource-for-organisation/ai/sgisago.pdf)
* [Singapore's Compendium of Use Cases: Practical Illustrations of the Model AI Governance Framework](https://www.pdpc.gov.sg/-/media/files/pdpc/pdf-files/resource-for-organisation/ai/sgaigovusecases.pdf)
* [Singapore's Model Artificial Intelligence Governance Framework (Second Edition)](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Resource-for-Organisation/AI/SGModelAIGovFramework2.pdf)
* [Supervisory Guidance on Model Risk Management](https://www.federalreserve.gov/supervisionreg/srletters/sr1107a1.pdf)
* [Testing the Reliability, Validity, and Equity of Terrorism Risk Assessment Instruments](https://www.homeaffairs.gov.au/foi/files/2023/fa-230400097-document-released-part-1.PDF)
* [UNESCO, Artificial Intelligence: examples of ethical dilemmas](https://www.unesco.org/en/artificial-intelligence/recommendation-ethics/cases)
* [Office of the United Nations High Commissioner for Human Rights](https://www.ohchr.org/sites/default/files/documents/issues/business/b-tech/taxonomy-GenAI-Human-Rights-Harms.pdf) 
* [United States Department of Energy Artificial Intelligence and Technology Office](https://www.energy.gov/ai/artificial-intelligence-technology-office):
  * [DOE AI Risk Management Playbook (AIRMP)](https://www.energy.gov/ai/doe-ai-risk-management-playbook-airmp)
  * [DOE AI Use Case Inventory (DOE Use Cases Releasable to Public in Accordance with E.O. 13960)](https://www.energy.gov/sites/default/files/2023-07/DOE_2023_AI_Use_Case_Inventory_0.pdf)
  * [DOE Digital Climate Solutions Inventory](https://www.energy.gov/sites/default/files/2022-09/Digital_Climate_Solutions_Inventory.pdf)
* [United States Department of Homeland Security, Use of Commercial Generative Artificial Intelligence (AI) Tools](https://www.dhs.gov/sites/default/files/2023-11/23_1114_cio_use_generative_ai_tools.pdf)
* [United States Department of Justice, Privacy Act of 1974](https://www.justice.gov/opcl/privacy-act-1974)
* [United States Department of Justice, Overview of The Privacy Act of 1974 (2020 Edition)](https://www.justice.gov/opcl/overview-privacy-act-1974-2020-edition) 
* [United States Patent and Trademark Office (USPTO), Public Views on Artificial Intelligence and Intellectual Property Policy](https://www.uspto.gov/sites/default/files/documents/USPTO_AI-Report_2020-10-07.pdf)
* [Using Artificial Intelligence and Algorithms](https://www.ftc.gov/news-events/blogs/business-blog/2020/04/using-artificial-intelligence-algorithms)
* [U.S. Army Concepts Analysis Agency, Proceedings of the Thirteenth Annual U.S. Army Operations Research Symposium, Volume 1, October 29 to November 1, 1974](https://apps.dtic.mil/sti/pdfs/ADA007126.pdf)
* [U.S. Web Design System (USWDS) Design principles](https://designsystem.digital.gov/design-principles/)


## Education Resources

### Comprehensive Software Examples and Tutorials

This section is a curated collection of guides and tutorials that simplify responsible ML implementation. It spans from basic model interpretability to advanced fairness techniques. Suitable for both novices and experts, the resources cover topics like COMPAS fairness analyses and explainable machine learning via counterfactuals. 

* [COMPAS Analysis Using Aequitas](https://github.com/dssg/aequitas/blob/master/docs/source/examples/compas_demo.ipynb)![](https://img.shields.io/github/stars/dssg/aequitas?style=social)
* [Explaining Quantitative Measures of Fairness (with SHAP)](https://github.com/slundberg/shap/blob/master/notebooks/overviews/Explaining%20quantitative%20measures%20of%20fairness.ipynb)![](https://img.shields.io/github/stars/slundberg/shap?style=social)
* [Getting a Window into your Black Box Model](http://projects.rajivshah.com/inter/ReasonCode_NFL.html)
* [H20.ai, From GLM to GBM Part 1](https://www.h2o.ai/blog/from-glm-to-gbm-part-1/)
* [H20.ai, From GLM to GBM Part 2](https://www.h2o.ai/blog/from-glm-to-gbm-part-2/)
* [IML](https://mybinder.org/v2/gh/christophM/iml/master?filepath=./notebooks/tutorial-intro.ipynb)
* [Interpretable Machine Learning with Python](https://github.com/jphall663/interpretable_machine_learning_with_python)![](https://img.shields.io/github/stars/jphall663/interpretable_machine_learning_with_python?style=social)
* [Interpreting Machine Learning Models with the iml Package](http://uc-r.github.io/iml-pkg)
* [Interpretable Machine Learning using Counterfactuals](https://docs.seldon.io/projects/alibi/en/v0.2.0/examples/cf_mnist.html)
* [Machine Learning Explainability by Kaggle Learn](https://www.kaggle.com/learn/machine-learning-explainability)
* [Model Interpretability with DALEX](http://uc-r.github.io/dalex)
  * **Model Interpretation series by Dipanjan (DJ) Sarkar**:
    * [The Importance of Human Interpretable Machine Learning](https://towardsdatascience.com/human-interpretable-machine-learning-part-1-the-need-and-importance-of-model-interpretation-2ed758f5f476)
    * [Model Interpretation Strategies](https://towardsdatascience.com/explainable-artificial-intelligence-part-2-model-interpretation-strategies-75d4afa6b739)
    * [Hands-on Machine Learning Model Interpretation](https://towardsdatascience.com/explainable-artificial-intelligence-part-3-hands-on-machine-learning-model-interpretation-e8ebe5afc608)
    * [Interpreting Deep Learning Models for Computer Vision](https://medium.com/google-developer-experts/interpreting-deep-learning-models-for-computer-vision-f95683e23c1d)
* [Partial Dependence Plots in R](https://journal.r-project.org/archive/2017/RJ-2017-016/)
* PiML:
  * [PiML Medium Tutorials](https://piml.medium.com)
  * [PiML-Toolbox Examples](https://github.com/SelfExplainML/PiML-Toolbox/tree/main/examples)![](https://img.shields.io/github/stars/SelfExplainML/PiML-Toolbox?style=social)
* [Reliable-and-Trustworthy-AI-Notebooks](https://github.com/ClementSicard/Reliable-and-Trustworthy-AI-Notebooks)![](https://img.shields.io/github/stars/ClementSicard/Reliable-and-Trustworthy-AI-Notebooks?style=social)
* [Saliency Maps for Deep Learning](https://medium.com/@thelastalias/saliency-maps-for-deep-learning-part-1-vanilla-gradient-1d0665de3284)
* [Visualizing ML Models with LIME](http://uc-r.github.io/lime)
* [Visualizing and debugging deep convolutional networks](https://rohitghosh.github.io/2018/01/05/visualising-debugging-deep-neural-networks/)
* [What does a CNN see?](https://colab.research.google.com/drive/1xM6UZ9OdpGDnHBljZ0RglHV_kBrZ4e-9)

### Free-ish Books

This section contains books that can be reasonably described as free, including some "historical" books dealing broadly with ethical and responsible tech.

* [César A. Hidalgo, Diana Orghian, Jordi Albo-Canals, Filipa de Almeida, and Natalia Martin, 2021, *How Humans Judge Machines*](https://archive.org/details/mit_press_book_9780262363266)
* [Charles Perrow, 1984, *Normal Accidents: Living with High-Risk Technologies*](https://archive.org/details/normalaccidentsl0000perr)
* [Charles Perrow, 1999, *Normal Accidents: Living with High-Risk Technologies with a New Afterword and a Postscript on the Y2K Problem*](https://archive.org/details/normalaccidentsl00perr)
* [Christoph Molnar, 2021, *Interpretable Machine Learning: A Guide for Making Black Box Models Explainable*](https://christophm.github.io/interpretable-ml-book/)
   * [christophM/interpretable-ml-book](https://github.com/christophM/interpretable-ml-book)![](https://img.shields.io/github/stars/christophM/interpretable-ml-book?style=social)
* [Deborah G. Johnson and Keith W. Miller, 2009, *Computer Ethics: Analyzing Information Technology*, Fourth Edition](https://archive.org/details/computerethicsan0004edjohn)
* [Ed Dreby and Keith Helmuth (contributors) and Judy Lumb (editor), 2009, *Fueling Our Future: A Dialogue about Technology, Ethics, Public Policy, and Remedial Action*](https://archive.org/details/fuelingourfuture0000unse/mode/2up)
* [George Reynolds, 2002, *Ethics in Information Technology*](https://archive.org/details/ethicsininformat00reyn)
* [George Reynolds, 2002, *Ethics in Information Technology*, Instructor's Edition](https://archive.org/details/ethicsininformat0000reyn)
* [Kenneth Vaux (editor), 1970, *Who Shall Live? Medicine, Technology, Ethics*](https://archive.org/details/whoshalllivemedi0000hous)
* [Kush R. Varshney, 2022, *Trustworthy Machine Learning: Concepts for Developing Accurate, Fair, Robust, Explainable, Transparent, Inclusive, Empowering, and Beneficial Machine Learning Systems*](http://www.trustworthymachinelearning.com/)
* [Marsha Cook Woodbury, 2003, *Computer and Information Ethics*](https://archive.org/details/computerinformat0000wood_q3r6)
* [M. David Ermann, Mary B. Williams, and Claudio Gutierrez, 1990, *Computers, Ethics, and Society*](https://archive.org/details/computersethicss0000unse)
* [Morton E. Winston and Ralph D. Edelbach, 2000, *Society, Ethics, and Technology*, First Edition](https://archive.org/details/societyethicstec00wins)
* [Morton E. Winston and Ralph D. Edelbach, 2003, *Society, Ethics, and Technology*, Second Edition](https://archive.org/details/societyethicstec0000unse)
* [Morton E. Winston and Ralph D. Edelbach, 2006, *Society, Ethics, and Technology*, Third Edition](https://archive.org/details/societyethicstec00edel)
* [Patrick Hall and Navdeep Gill, 2019, *An Introduction to Machine Learning Interpretability: An Applied Perspective on Fairness, Accountability, Transparency, and Explainable AI*, Second Edition](https://h2o.ai/content/dam/h2o/en/marketing/documents/2019/08/An-Introduction-to-Machine-Learning-Interpretability-Second-Edition.pdf)
* [Patrick Hall, Navdeep Gill, and Benjamin Cox, 2021, *Responsible Machine Learning: Actionable Strategies for Mitigating Risks & Driving Adoption*](https://info.h2o.ai/rs/644-PKX-778/images/OReilly_Responsible_ML_eBook.pdf)
* [Patrick Hall, James Curtis, Parul Pandey, and Agus Sudjianto, 2023, *Machine Learning for High-Risk Applications: Approaches to Responsible AI*](https://pages.dataiku.com/oreilly-responsible-ai)
* [Paula Boddington, 2017, *Towards a Code of Ethics for Artificial Intelligence*](https://archive.org/details/towardscodeofeth0000bodd)
* [Przemyslaw Biecek and Tomasz Burzykowski, 2020, *Explanatory Model Analysis: Explore, Explain, and Examine Predictive Models. With examples in R and Python*](https://ema.drwhy.ai/)
* [Przemyslaw Biecek, 2023, *Adversarial Model Analysis*](https://ama.drwhy.ai/)
* [Raymond E. Spier (editor), 2003, *Science and Technology Ethics*](https://archive.org/details/sciencetechnolog0000unse_k7m6)
* [Richard A. Spinello, 1995, *Ethical Aspects of Information Technology*](https://archive.org/details/ethicalaspectsof00spin)
* [Richard A. Spinello, 1997, *Case Studies in Information and Computer Ethics*](https://archive.org/details/unset0000unse_l0l0)
* [Richard A. Spinello, 2003, *Case Studies in Information Technology Ethics*, Second Edition](https://archive.org/details/casestudiesininf02edspin)
* [Solon Barocas, Moritz Hardt, and Arvind Narayanan, 2022, *Fairness and Machine Learning: Limitations and Opportunities*](https://fairmlbook.org/)
* [Soraj Hongladarom and Charles Ess, 2007, *Information Technology Ethics: Cultural Perspectives*](https://archive.org/details/informationtechn0000unse_k8c9)
* [Stephen H. Unger, 1982, *Controlling Technology: Ethics and the Responsible Engineer*, First Edition](https://archive.org/details/controllingtechn0000unge_y4t3)
* [Stephen H. Unger, 1994, *Controlling Technology: Ethics and the Responsible Engineer*, Second Edition](https://archive.org/details/controllingtechn0000unge)

### Glossaries and Dictionaries

This section features a collection of glossaries and dictionaries that are geared toward defining terms in ML, including some "historical" dictionaries.

* [A.I. For Anyone: The A-Z of AI](https://www.aiforanyone.org/glossary)
* [Alan Turing Institute: Data science and AI glossary](https://www.turing.ac.uk/news/data-science-and-ai-glossary)
* [Appen Artificial Intelligence Glossary](https://appen.com/ai-glossary/)
* [Artificial intelligence and illusions of understanding in scientific research - glossary on second page](https://www.nature.com/articles/s41586-024-07146-0.epdf?sharing_token=cbht6Q72InY18AtY6FiVM9RgN0jAjWel9jnR3ZoTv0Ni_LuMWrIZy_SmHlNQlu9tG1u0SCK_wTYxy6bvMe6U_BE3vc5yFmZEpTbIVJozkVYsOei9LdPpNr_wZzvTp4stmzGM54z-riqwhUCk0DD6_YkY_jcgZBnXR8P_8vyFvYpiCtjFrvczN9Lm6NhmrePm)
* [Brookings: The Brookings glossary of AI and emerging technologies](https://www.brookings.edu/articles/the-brookings-glossary-of-ai-and-emerging-technologies/)
* [Built In, Responsible AI Explained](https://builtin.com/artificial-intelligence/responsible-ai)
* [Center for Security and Emerging Technology: Glossary](https://cset.georgetown.edu/glossary/)
* [CompTIA: Artificial Intelligence (AI) Terminology: A Glossary for Beginners](https://connect.comptia.org/content/articles/artificial-intelligence-terminology)
* [Council of Europe Artificial Intelligence Glossary](https://www.coe.int/en/web/artificial-intelligence/glossary)
* [Coursera: Artificial Intelligence (AI) Terms: A to Z Glossary](https://www.coursera.org/articles/ai-terms)
* [Dataconomy: AI dictionary: Be a native speaker of Artificial Intelligence](https://dataconomy.com/2022/04/23/artificial-intelligence-terms-ai-glossary/)
* [Dennis Mercadal, 1990, *Dictionary of Artificial Intelligence*](https://archive.org/details/dictionaryofarti0000merc)
* [G2: 70+ A to Z Artificial Intelligence Terms in Technology](https://www.g2.com/articles/artificial-intelligence-terms)
* [General Services Administration: AI Guide for Government: Key AI terminology](https://coe.gsa.gov/coe/ai-guide-for-government/what-is-ai-key-terminology/)
* [Google Developers Machine Learning Glossary](https://developers.google.com/machine-learning/glossary)
* [H2O.ai Glossary](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/glossary.html)
* [IAPP Glossary of Privacy Terms](https://iapp.org/resources/glossary/)
* [IAPP International Definitions of Artificial Intelligence](https://iapp.org/media/pdf/resource_center/international_definitions_of_ai.pdf)
* [IAPP Key Terms for AI Governance](https://iapp.org/media/pdf/resource_center/key_terms_for_ai_governance.pdf)
* [IBM: AI glossary](https://www.ibm.com/cloud/architecture/architecture/practices/cognitive-glossary/)
* [ISO: Information technology — Artificial intelligence — Artificial intelligence concepts and terminology](https://standards.iso.org/ittf/PubliclyAvailableStandards/ISO_IEC_22989_2022_ed.1_id.74296_Publication_PDF_(en).zip)
* [Jerry M. Rosenberg, 1986, *Dictionary of Artificial Intelligence & Robotics*](https://archive.org/details/dictionaryofarti00rose)
* [MakeUseOf: A Glossary of AI Jargon: 29 AI Terms You Should Know](https://www.makeuseof.com/glossary-ai-jargon-terms/)
* [Moveworks: AI Terms Glossary](https://www.moveworks.com/us/en/resources/ai-terms-glossary)
* [NIST AIRC: The Language of Trustworthy AI: An In-Depth Glossary of Terms](https://airc.nist.gov/AI_RMF_Knowledge_Base/Glossary)
* [Oliver Houdé, 2004, *Dictionary of Cognitive Science: Neuroscience, Psychology, Artificial Intelligence, Linguistics, and Philosophy*](https://archive.org/details/dictionaryofcogn0000unse)
* [Otto Vollnhals, 1992, *A Multilingual Dictionary of Artificial Intelligence (English, German, French, Spanish, Italian)*](https://archive.org/details/multilingualdict0000voll)
* [Raoul Smith, 1989, *The Facts on File Dictionary of Artificial Intelligence*](https://archive.org/details/factsonfiledicti00smit)
* [Raoul Smith, 1990, *Collins Dictionary of Artificial Intelligence*](https://archive.org/details/collinsdictionar0000unse_w3w7)
* [Salesforce: AI From A to Z: The Generative AI Glossary for Business Leaders](https://www.salesforce.com/blog/generative-ai-glossary/)
* [Stanford University HAI Artificial Intelligence Definitions](https://hai.stanford.edu/sites/default/files/2023-03/AI-Key-Terms-Glossary-Definition.pdf)
* [TechTarget: Artificial intelligence glossary: 60+ terms to know](https://www.techtarget.com/whatis/feature/Artificial-intelligence-glossary-60-terms-to-know)
* [TELUS International: 50 AI terms every beginner should know](https://www.telusinternational.com/insights/ai-data/article/50-beginner-ai-terms-you-should-know)
* [University of New South Wales, Bill Wilson, The Machine Learning Dictionary](https://www.cse.unsw.edu.au/~billw/mldict.html)
* [VAIR (Vocabulary of AI Risks)](https://delaramglp.github.io/vair/)
* [Wikipedia: Glossary of artificial intelligence](https://en.wikipedia.org/wiki/Glossary_of_artificial_intelligence)
* [William J. Raynor, Jr, 1999, *The International Dictionary of Artificial Intelligence*, First Edition](https://archive.org/details/internationaldic0000rayn/mode/2up)
* [William J. Raynor, Jr, 2009, *International Dictionary of Artificial Intelligence*, Second Edition](https://archive.org/details/internationaldic0000rayn_t1n5/mode/2up)

### Open-ish Classes

This section features a selection of educational courses focused on ethical considerations and best practices in ML. The classes range from introductory courses on data ethics to specialized training in fairness and trustworthy deep learning.

* [An Introduction to Data Ethics](https://www.scu.edu/ethics/focus-areas/technology-ethics/resources/an-introduction-to-data-ethics/)
* [Carnegie Mellon University, Computational Ethics for NLP](http://demo.clab.cs.cmu.edu/ethical_nlp/)
* [Certified Ethical Emerging Technologist](https://certnexus.com/certification/ceet/)
* [Coursera, DeepLearning.AI, Generative AI for Everyone](https://www.coursera.org/learn/generative-ai-for-everyone)
* [Coursera, DeepLearning.AI, Generative AI with Large Language Models](https://www.coursera.org/learn/generative-ai-with-llms)
* [Coursera, Google Cloud, Introduction to Generative AI](https://www.coursera.org/learn/introduction-to-generative-ai)
* [Coursera, Vanderbilt University, Prompt Engineering for ChatGPT](https://www.coursera.org/learn/prompt-engineering)
* [CS103F: Ethical Foundations of Computer Science](https://www.cs.utexas.edu/~ans/classes/cs109/schedule.html)
* [ETH Zürich ReliableAI 2022 Course Project repository](https://github.com/angelognazzo/Reliable-Trustworthy-AI)![](https://img.shields.io/github/stars/angelognazzo/Reliable-Trustworthy-AI?style=social)
* [Fairness in Machine Learning](https://fairmlclass.github.io/)
* [Fast.ai Data Ethics course](http://ethics.fast.ai/syllabus)
* [Human-Centered Machine Learning](http://courses.mpi-sws.org/hcml-ws18/)
* [Introduction to AI Ethics](https://www.kaggle.com/code/var0101/introduction-to-ai-ethics)
* [INFO 4270: Ethics and Policy in Data Science](https://docs.google.com/document/d/1GV97qqvjQNvyM2I01vuRaAwHe9pQAZ9pbP7KkKveg1o/)
* [Introduction to Responsible Machine Learning](https://jphall663.github.io/GWU_rml/)
* [Machine Learning Fairness by Google](https://developers.google.com/machine-learning/crash-course/fairness/video-lecture)
* [Piotr Sapieżyński's CS 4910 - Special Topics in Computer Science: Algorithm Audits](https://sapiezynski.com/cs4910.html)
* [Tech & Ethics Curricula](https://docs.google.com/spreadsheets/d/1Z0DqQeZ-Aeq6LmD17J5m8zeeIR6ywWnH-WO-jWtXE9M/edit#gid=0)
* [Trustworthy Deep Learning](https://berkeley-deep-learning.github.io/cs294-131-s19/)

## Miscellaneous Resources

### AI Incident Information Sharing Resources

This section houses initiatives, networks, repositories, and publications that facilitate collective and interdisciplinary efforts to enhance AI safety. It includes platforms where experts and practitioners come together to share insights, identify potential vulnerabilities, and collaborate on developing robust safeguards for AI systems, including AI incident trackers.

* [AI Incident Database (Responsible AI Collaborative)](https://incidentdatabase.ai/)
* [AI Vulnerability Database (AVID)](https://avidml.org/)
* [AIAAIC](https://www.aiaaic.org/)
* [George Washington University Law School's AI Litigation Database](https://blogs.gwu.edu/law-eti/ai-litigation-database/)
* [Merging AI Incidents Research with Political Misinformation Research: Introducing the Political Deepfakes Incidents Database](https://osf.io/fvqg3/)
* [OECD AI Incidents Monitor](https://oecd.ai/en/incidents)
* [Verica Open Incident Database (VOID)](https://www.thevoid.community/)

### Challenges and Competitions

This section contains challenges and competitions related to responsible ML. 

* [FICO Explainable Machine Learning Challenge](https://community.fico.com/s/explainable-machine-learning-challenge)
* [OSD Bias Bounty](https://osdbiasbounty.com/)
* [National Fair Housing Alliance Hackathon](https://nationalfairhousing.org/hackathon2023/)
* [Twitter Algorithmic Bias](https://hackerone.com/twitter-algorithmic-bias?type=team)

### Curated Bibliographies

We are seeking curated bibliographies related to responsible ML across various topics, see [issue 115](https://github.com/jphall663/awesome-machine-learning-interpretability/issues/115). 

* **BibTeX**:
  * [Proposed Guidelines for Responsible Use of Explainable Machine Learning (presentation, bibliography)](https://github.com/jphall663/kdd_2019/blob/master/bibliography.bib)![](https://img.shields.io/github/stars/jphall663/kdd_2019?style=social)
  * [Proposed Guidelines for Responsible Use of Explainable Machine Learning (paper, bibliography)](https://github.com/jphall663/responsible_xai/blob/master/responsible_xai.bib)![](https://img.shields.io/github/stars/jphall663/responsible_xai?style=social)
  * [A Responsible Machine Learning Workflow (paper, bibliography)](https://github.com/h2oai/article-information-2019/blob/master/back_up/article-information-2019.bib.bak)![](https://img.shields.io/github/stars/h2oai/article-information-2019?style=social)
 
* **Web**:
  * [Fairness, Accountability, and Transparency in Machine Learning (FAT/ML) Scholarship](https://www.fatml.org/resources/relevant-scholarship)

### List of Lists

This section links to other lists of responsible ML or related resources.

* [A Living and Curated Collection of Explainable AI Methods](https://utwente-dmb.github.io/xai-papers/#/)
* [AI Ethics Guidelines Global Inventory](https://algorithmwatch.org/en/project/ai-ethics-guidelines-global-inventory/)
* [AI Ethics Resources](https://www.fast.ai/posts/2018-09-24-ai-ethics-resources.html)
* [AI Tools and Platforms](https://docs.google.com/spreadsheets/u/2/d/10pPQYmyNnYb6zshOKxBjJ704E0XUj2vJ9HCDfoZxAoA/htmlview#)
* [Awesome AI Guidelines](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines)![](https://img.shields.io/github/stars/EthicalML/awesome-artificial-intelligence-guidelines?style=social)
* [Awesome interpretable machine learning](https://github.com/lopusz/awesome-interpretable-machine-learning)![](https://img.shields.io/github/stars/lopusz/awesome-interpretable-machine-learning?style=social)
* [Awesome-explainable-AI](https://github.com/wangyongjie-ntu/Awesome-explainable-AI/)![](https://img.shields.io/github/stars/wangyongjie-ntu/Awesome-explainable-AI?style=social)
* [Awesome-ML-Model-Governance](https://github.com/visenger/Awesome-ML-Model-Governance)![](https://img.shields.io/github/stars/visenger/Awesome-ML-Model-Governance?style=social)
* [Awesome MLOps](https://github.com/visenger/awesome-mlops)![](https://img.shields.io/github/stars/visenger/awesome-mlops?style=social)
* [Awesome Production Machine Learning](https://github.com/EthicalML/awesome-machine-learning-operations)![](https://img.shields.io/github/stars/EthicalML/awesome-machine-learning-operations?style=social)
* [Awful AI](https://github.com/daviddao/awful-ai)![](https://img.shields.io/github/stars/daviddao/awful-ai?style=social)
* [criticalML](https://github.com/rockita/criticalML)![](https://img.shields.io/github/stars/rockita/criticalML?style=social)
* [Evaluation Repository for 'Sociotechnical Safety Evaluation of Generative AI Systems'](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vQObeTxvXtOs--zd98qG2xBHHuTTJOyNISBJPthZFr3at2LCrs3rcv73d4of1A78JV2eLuxECFXJY43/pubhtml)
* [IMDA-BTG, LLM-Evals-Catalogue](https://github.com/IMDA-BTG/LLM-Evals-Catalogue)![](https://img.shields.io/github/stars/IMDA-BTG/LLM-Evals-Catalogue?style=social)
* [Machine Learning Ethics References](https://github.com/radames/Machine-Learning-Ethics-References)![](https://img.shields.io/github/stars/radames/Machine-Learning-Ethics-References?style=social)
* [Machine Learning Interpretability Resources](https://github.com/h2oai/mli-resources)![](https://img.shields.io/github/stars/h2oai/mli-resources?style=social)
* [OECD-NIST Catalogue of AI Tools and Metrics](https://oecd.ai/en/catalogue/overview)
* [OpenAI Cookbook](https://github.com/openai/openai-cookbook/tree/main)![](https://img.shields.io/github/stars/openai/openai-cookbook?style=social)
* [private-ai-resources](https://github.com/OpenMined/private-ai-resources)![](https://img.shields.io/github/stars/OpenMined/private-ai-resources?style=social)
* [ResponsibleAI](https://romanlutz.github.io/ResponsibleAI/)
* [Tech & Ethics Curricula](https://docs.google.com/spreadsheets/d/1Z0DqQeZ-Aeq6LmD17J5m8zeeIR6ywWnH-WO-jWtXE9M/edit#gid=0)
* [Worldwide AI ethics: A review of 200 guidelines and recommendations for AI governance](https://doi.org/10.1016/j.patter.2023.100857)
* [XAI Resources](https://github.com/pbiecek/xai_resources)![](https://img.shields.io/github/stars/pbiecek/xai_resources?style=social)
* [xaience](https://github.com/andreysharapov/xaience)![](https://img.shields.io/github/stars/andreysharapov/xaience?style=social)

## Technical Resources

### Benchmarks

This section contains benchmarks or datasets used for benchmarks for ML systems, particularly those related to responsible ML desiderata.

| Resource | Description |
| --- | --- |
| [benchm-ml](https://github.com/szilard/benchm-ml) ![](https://img.shields.io/github/stars/szilard/benchm-ml?style=social) | "A minimal benchmark for scalability, speed and accuracy of commonly used open source implementations (R packages, Python scikit-learn, H2O, xgboost, Spark MLlib etc.) of the top machine learning algorithms for binary classification (random forests, gradient boosted trees, deep neural networks etc.)." |
| [Bias Benchmark for QA dataset (BBQ)](https://github.com/nyu-mll/bbq) ![](https://img.shields.io/github/stars/nyu-mll/bbq?style=social) | "Repository for the Bias Benchmark for QA dataset." |
| [DecodingTrust](https://github.com/AI-secure/DecodingTrust)![](https://img.shields.io/github/stars/huggingface/evaluate?style=social) | "A Comprehensive Assessment of Trustworthiness in GPT Models." |
| [GEM](https://gem-benchmark.com/) | "GEM is a benchmark environment for Natural Language Generation with a focus on its Evaluation, both through human annotations and automated Metrics." |
| [HELM](https://crfm.stanford.edu/helm/latest/) | "A holistic framework for evaluating foundation models." |
| [Hugging Face, evaluate](https://github.com/huggingface/evaluate)![](https://img.shields.io/github/stars/huggingface/evaluate?style=social) | "Evaluate: A library for easily evaluating machine learning models and datasets." |
| [i-gallegos, Fair-LLM-Benchmark](https://github.com/i-gallegos/Fair-LLM-Benchmark)![](https://img.shields.io/github/stars/i-gallegos/Fair-LLM-Benchmark?style=social) | Benchmark from "Bias and Fairness in Large Language Models: A Survey" |
| [Nvidia MLPerf](https://www.nvidia.com/en-us/data-center/resources/mlperf-benchmarks/) | "MLPerf™ benchmarks—developed by MLCommons, a consortium of AI leaders from academia, research labs, and industry—are designed to provide unbiased evaluations of training and inference performance for hardware, software, and services." | 
| [OpenML Benchmarking Suites](https://www.openml.org/search?type=benchmark&study_type=task) | OpenML's collection of over two dozen benchmarking suites. |
| [SafetyPrompts.com](https://safetyprompts.com/) | "A Living Catalogue of Open Datasets for LLM Safety." |
| [Sociotechnical Safety Evaluation Repository](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vQObeTxvXtOs--zd98qG2xBHHuTTJOyNISBJPthZFr3at2LCrs3rcv73d4of1A78JV2eLuxECFXJY43/pubhtml) | An extensive spreadsheet of sociotechnical safety evaluations in a spreadsheet. |
| [TrustLLM-Benchmark](https://trustllmbenchmark.github.io/TrustLLM-Website/index.html) | "A Comprehensive Study of Trustworthiness in Large Language Models." |
| [Trust-LLM-Benchmark Leaderboard](https://trustllmbenchmark.github.io/TrustLLM-Website/leaderboard.html) | A series of sortable leaderboards of LLMs based on different trustworthiness criteria. |
| [TruthfulQA](https://github.com/sylinrl/TruthfulQA) ![](https://img.shields.io/github/stars/sylinrl/TruthfulQA?style=social) | "TruthfulQA: Measuring How Models Imitate Human Falsehoods." |
| [WAVES: Benchmarking the Robustness of Image Watermarks](https://wavesbench.github.io/) | "This paper investigates the weaknesses of image watermarking techniques." |
| [Winogender Schemas](https://github.com/rudinger/winogender-schemas) ![](https://img.shields.io/github/stars/rudinger/winogender-schemas?style=social) | "Data for evaluating gender bias in coreference resolution systems." |
| [Real Toxicity Prompts (Allen Institute for AI)](https://allenai.org/data/real-toxicity-prompts) | "A dataset of 100k sentence snippets from the web for researchers to further address the risk of neural toxic degeneration in models." |

### Common or Useful Datasets

This section contains datasets that are commonly used in responsible ML evaulations or repositories of interesting/important data sources:

* [Adult income dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)
* [Balanced Faces in the Wild](https://github.com/visionjo/facerec-bias-bfw)![](https://img.shields.io/github/stars/visionjo/facerec-bias-bfw?style=social)
* [COMPAS Recidivism Risk Score Data and Analysis](https://www.propublica.org/datastore/dataset/compas-recidivism-risk-score-data-and-analysis)
  * **Data Repositories**:
    * [All Lending Club loan data](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
    * [Amazon Open Data](https://registry.opendata.aws/amazon-reviews/)
    * [Data.gov](https://data.gov/)
    * [Home Mortgage Disclosure Act (HMDA) Data](https://www.consumerfinance.gov/data-research/hmda/)
    * [MIMIC-III Clinical Database](https://physionet.org/content/mimiciii/1.4/)
    * [UCI ML Data Repository](https://archive.ics.uci.edu/)
* [FANNIE MAE Single Family Loan Performance](https://capitalmarkets.fanniemae.com/credit-risk-transfer/single-family-credit-risk-transfer/fannie-mae-single-family-loan-performance-data)
* [Presidential Deepfakes Dataset](https://www.media.mit.edu/publications/presidential-deepfakes-dataset/)
* [NYPD Stop, Question and Frisk Data](https://www.nyc.gov/site/nypd/stats/reports-analysis/stopfrisk.page)
* [socialfoundations / folktables](https://github.com/socialfoundations/folktables)![](https://img.shields.io/github/stars/socialfoundations/folktables?style=social)
* [Statlog (German Credit Data)](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)
* [Wikipedia Talk Labels: Personal Attacks](https://www.kaggle.com/datasets/jigsaw-team/wikipedia-talk-labels-personal-attacks)

### Domain-specific Software

This section curates specialized software tools aimed at responsible ML within specific domains, such as in healthcare, finance, or social sciences.

### Machine Learning Environment Management Tools

This section contains open source or open access ML environment management software.

| Resource | Description |
|----------|-------|
| [dvc](https://dvc.org/) | "Manage and version images, audio, video, and text files in storage and organize your ML modeling process into a reproducible workflow." |
| [gigantum](https://github.com/gigantum) ![gigantum stars](https://img.shields.io/github/stars/gigantum?style=social) | "Building a better way to create, collaborate, and share data-driven science." |
| [mlflow](https://mlflow.org/) | "An open source platform for the machine learning lifecycle." |
| [mlmd](https://github.com/google/ml-metadata) ![mlmd stars](https://img.shields.io/github/stars/google/ml-metadata?style=social) | "For recording and retrieving metadata associated with ML developer and data scientist workflows." |
| [modeldb](https://github.com/VertaAI/modeldb) ![modeldb stars](https://img.shields.io/github/stars/VertaAI/modeldb?style=social) | "Open Source ML Model Versioning, Metadata, and Experiment Management." |
| [neptune](https://neptune.ai/researchers) | "A single place to manage all your model metadata." |

### Open Source/Access Responsible AI Software Packages

This section contains open source or open access software used to implement responsible ML. As much as possible, descriptions are quoted verbatim from the respective repositories themselves. In rare instances, we provide our own descriptions (unmarked by quotes).

#### Browser

| Name | Description |
|------|-------------|
| [DiscriLens](https://github.com/wangqianwen0418/DiscriLens)![](https://img.shields.io/github/stars/wangqianwen0418/DiscriLens?style=social) | "Discrimination in Machine Learning." |
| [Hugging Face, BiasAware: Dataset Bias Detection](https://huggingface.co/spaces/avid-ml/biasaware) | "BiasAware is a specialized tool for detecting and quantifying biases within datasets used for Natural Language Processing (NLP) tasks." |
| [manifold](https://github.com/uber/manifold)![](https://img.shields.io/github/stars/uber/manifold?style=social) | "A model-agnostic visual debugging tool for machine learning." |
| [PAIR-code / datacardsplaybook](https://github.com/PAIR-code/datacardsplaybook)![](https://img.shields.io/github/stars/PAIR-code/datacardsplaybook?style=social) | "The Data Cards Playbook helps dataset producers and publishers adopt a people-centered approach to transparency in dataset documentation." |
| [PAIR-code / facets](https://github.com/PAIR-code/facets)![](https://img.shields.io/github/stars/PAIR-code/facets?style=social) | "Visualizations for machine learning datasets." |
| [PAIR-code / knowyourdata](https://github.com/pair-code/knowyourdata)![](https://img.shields.io/github/stars/PAIR-code/knowyourdata?style=social) | "A tool to help researchers and product teams understand datasets with the goal of improving data quality, and mitigating fairness and bias issues." |
| [TensorBoard Projector](http://projector.tensorflow.org) | "Using the TensorBoard Embedding Projector, you can graphically represent high dimensional embeddings. This can be helpful in visualizing, examining, and understanding your embedding layers." |
| [What-if Tool](https://pair-code.github.io/what-if-tool/index.html#about) | "Visually probe the behavior of trained machine learning models, with minimal coding." |

#### C/C++

| Name | Description |
|------|-------------|
| [Born-again Tree Ensembles](https://github.com/vidalt/BA-Trees)![](https://img.shields.io/github/stars/vidalt/BA-Trees?style=social) | "Born-Again Tree Ensembles: Transforms a random forest into a single, minimal-size, tree with exactly the same prediction function in the entire feature space (ICML 2020)." |
| [Certifiably Optimal RulE ListS](https://github.com/nlarusstone/corels)![](https://img.shields.io/github/stars/nlarusstone/corels?style=social) | "CORELS is a custom discrete optimization technique for building rule lists over a categorical feature space." |
| [Secure-ML](https://github.com/shreya-28/Secure-ML)![](https://img.shields.io/github/stars/shreya-28/Secure-ML?style=social) | "Secure Linear Regression in the Semi-Honest Two-Party Setting." |

#### JavaScript

| Name | Description |
|------|-------------|
| [LDNOOBW](https://github.com/LDNOOBW)![](https://img.shields.io/github/stars/LDNOOBW?style=social) | "List of Dirty, Naughty, Obscene, and Otherwise Bad Words" |

#### Python

| Name | Description |
|------|-------------|
| [acd](https://github.com/csinva/hierarchical_dnn_interpretations)![](https://img.shields.io/github/stars/csinva/hierarchical_dnn_interpretations?style=social) | "Produces hierarchical interpretations for a single prediction made by a pytorch neural network. Official code for *Hierarchical interpretations for neural network predictions*.” |
| [aequitas](https://github.com/dssg/aequitas)![](https://img.shields.io/github/stars/dssg/aequitas?style=social) | "Aequitas is an open-source bias audit toolkit for data scientists, machine learning researchers, and policymakers to audit machine learning models for discrimination and bias, and to make informed and equitable decisions around developing and deploying predictive tools.” |
| [AI Fairness 360](https://github.com/Trusted-AI/AIF360)![](https://img.shields.io/github/stars/Trusted-AI/AIF360?style=social) | "A comprehensive set of fairness metrics for datasets and machine learning models, explanations for these metrics, and algorithms to mitigate bias in datasets and models.” |
| [AI Explainability 360](https://github.com/IBM/AIX360)![](https://img.shields.io/github/stars/IBM/AIX360?style=social) | "Interpretability and explainability of data and machine learning models.” |
| [ALEPython](https://github.com/blent-ai/ALEPython)![](https://img.shields.io/github/stars/blent-ai/ALEPython?style=social) | "Python Accumulated Local Effects package.” |
| [Aletheia](https://github.com/SelfExplainML/Aletheia)![](https://img.shields.io/github/stars/SelfExplainML/Aletheia?style=social) | "A Python package for unwrapping ReLU DNNs.” |
| [allennlp](https://github.com/allenai/allennlp)![](https://img.shields.io/github/stars/allenai/allennlp?style=social) | "An open-source NLP research library, built on PyTorch.” |
| [algofairness](https://github.com/algofairness)![](https://img.shields.io/github/stars/algofairness?style=social) | See [Algorithmic Fairness][http://fairness.haverford.edu/). |
| [Alibi](https://github.com/SeldonIO/alibi)![](https://img.shields.io/github/stars/SeldonIO/alibi?style=social) | "Alibi is an open source Python library aimed at machine learning model inspection and interpretation. The focus of the library is to provide high-quality implementations of black-box, white-box, local and global explanation methods for classification and regression models.” |
| [anchor](https://github.com/marcotcr/anchor)![](https://img.shields.io/github/stars/marcotcr/anchor?style=social) | "Code for 'High-Precision Model-Agnostic Explanations' paper.” |
| [Bayesian Case Model](https://users.cs.duke.edu/~cynthia/code/BCM.zip) |
| [Bayesian Ors-Of-Ands](https://github.com/wangtongada/BOA)![](https://img.shields.io/github/stars/wangtongada/BOA?style=social) | "This code implements the Bayesian or-of-and algorithm as described in the BOA paper. We include the tictactoe dataset in the correct formatting to be used by this code.” |
| [Bayesian Rule List (BRL)](https://users.cs.duke.edu/~cynthia/code/BRL_supplement_code.zip) | Rudin group at Duke Bayesian case model implementation |
| [BlackBoxAuditing](https://github.com/algofairness/BlackBoxAuditing)![](https://img.shields.io/github/stars/algofairness/BlackBoxAuditing?style=social) | "Research code for auditing and exploring black box machine-learning models.” |
| [CalculatedContent, WeightWatcher](https://github.com/calculatedcontent/weightwatcher)![](https://img.shields.io/github/stars/calculatedcontent/weightwatcher?style=social) | "The WeightWatcher tool for predicting the accuracy of Deep Neural Networks." |
| [casme](https://github.com/kondiz/casme)![](https://img.shields.io/github/stars/kondiz/casme?style=social) | "contains the code originally forked from the ImageNet training in PyTorch that is modified to present the performance of classifier-agnostic saliency map extraction, a practical algorithm to train a classifier-agnostic saliency mapping by simultaneously training a classifier and a saliency mapping.” |
| [Causal Discovery Toolbox](https://github.com/FenTechSolutions/CausalDiscoveryToolbox)![](https://img.shields.io/github/stars/FenTechSolutions/CausalDiscoveryToolbox?style=social) | "Package for causal inference in graphs and in the pairwise settings. Tools for graph structure recovery and dependencies are included.” |
| [captum](https://github.com/pytorch/captum)![](https://img.shields.io/github/stars/pytorch/captum?style=social) | "Model interpretability and understanding for PyTorch.” |
| [causalml](https://github.com/uber/causalml)![](https://img.shields.io/github/stars/uber/causalml?style=social) | "Uplift modeling and causal inference with machine learning algorithms.” |
| [cdt15, Causal Discovery Lab., Shiga University](https://github.com/cdt15)![](https://img.shields.io/github/stars/cdt15?style=social) | "LiNGAM is a new method for estimating structural equation models or linear causal Bayesian networks. It is based on using the non-Gaussianity of the data." |
| [checklist](https://github.com/marcotcr/checklist)![](https://img.shields.io/github/stars/marcotcr/checklist?style=social) | "Beyond Accuracy: Behavioral Testing of NLP models with CheckList.” |
| [cleverhans](https://github.com/cleverhans-lab/cleverhans)![](https://img.shields.io/github/stars/cleverhans-lab/cleverhans?style=social) | "An adversarial example library for constructing attacks, building defenses, and benchmarking both.” |
| [contextual-AI](https://github.com/SAP/contextual-ai)![](https://img.shields.io/github/stars/SAP/contextual-ai?style=social) | "Contextual AI adds explainability to different stages of machine learning pipelines | data, training, and inference | thereby addressing the trust gap between such ML systems and their users. It does not refer to a specific algorithm or ML method — instead, it takes a human-centric view and approach to AI.” |
| [ContrastiveExplanation (Foil Trees)](https://github.com/MarcelRobeer/ContrastiveExplanation)![](https://img.shields.io/github/stars/MarcelRobeer/ContrastiveExplanation?style=social) | "provides an explanation for why an instance had the current outcome (fact) rather than a targeted outcome of interest (foil). These counterfactual explanations limit the explanation to the features relevant in distinguishing fact from foil, thereby disregarding irrelevant features.” |
| [counterfit](https://github.com/Azure/counterfit/)![](https://img.shields.io/github/stars/Azure/counterfit?style=social) | "a CLI that provides a generic automation layer for assessing the security of ML models.” |
| [dalex](https://github.com/ModelOriented/DALEX)![](https://img.shields.io/github/stars/ModelOriented/DALEX?style=social) | "moDel Agnostic Language for Exploration and eXplanation.” |
| [debiaswe](https://github.com/tolga-b/debiaswe)![](https://img.shields.io/github/stars/tolga-b/debiaswe?style=social) | "Remove problematic gender bias from word embeddings.” |
| [DeepExplain](https://github.com/marcoancona/DeepExplain)![](https://img.shields.io/github/stars/marcoancona/DeepExplain?style=social) | "provides a unified framework for state-of-the-art gradient and perturbation-based attribution methods. It can be used by researchers and practitioners for better undertanding the recommended existing models, as well for benchmarking other attribution methods.” |
| [DeepLIFT](https://github.com/kundajelab/deeplift)![](https://img.shields.io/github/stars/kundajelab/deeplift?style=social) | "This repository implements the methods in 'Learning Important Features Through Propagating Activation Differences' by Shrikumar, Greenside & Kundaje, as well as other commonly-used methods such as gradients, gradient-times-input (equivalent to a version of Layerwise Relevance Propagation for ReLU networks), guided backprop and integrated gradients.” |
| [deepvis](https://github.com/yosinski/deep-visualization-toolbox)![](https://img.shields.io/github/stars/yosinski/deep-visualization-toolbox?style=social) | "the code required to run the Deep Visualization Toolbox, as well as to generate the neuron-by-neuron visualizations using regularized optimization.” |
| [DIANNA](https://github.com/dianna-ai/dianna)![](https://img.shields.io/github/stars/dianna-ai/dianna?style=social) | "DIANNA is a Python package that brings explainable AI (XAI) to your research project. It wraps carefully selected XAI methods in a simple, uniform interface. It's built by, with and for (academic) researchers and research software engineers working on machine learning projects.” |
| [DiCE](https://github.com/interpretml/DiCE)![](https://img.shields.io/github/stars/interpretml/DiCE?style=social) | "Generate Diverse Counterfactual Explanations for any machine learning model.” |
| [DoWhy](https://github.com/microsoft/dowhy)![](https://img.shields.io/github/stars/microsoft/dowhy?style=social) | "DoWhy is a Python library for causal inference that supports explicit modeling and testing of causal assumptions. DoWhy is based on a unified language for causal inference, combining causal graphical models and potential outcomes frameworks.” |
| [dtreeviz](https://github.com/parrt/dtreeviz)![](https://img.shields.io/github/stars/parrt/dtreeviz?style=social) | "A python library for decision tree visualization and model interpretation.” |
| [ecco](https://github.com/jalammar/ecco)![](https://img.shields.io/github/stars/jalammar/ecco?style=social) | "Explain, analyze, and visualize NLP language models. Ecco creates interactive visualizations directly in Jupyter notebooks explaining the behavior of Transformer-based language models (like GPT2, BERT, RoBERTA, T5, and T0).” |
| [eli5](https://github.com/TeamHG-Memex/eli5)![](https://img.shields.io/github/stars/TeamHG-Memex/eli5?style=social) | "A library for debugging/inspecting machine learning classifiers and explaining their predictions.” |
| [explabox](https://github.com/MarcelRobeer/explabox)![](https://img.shields.io/github/stars/MarcelRobeer/explabox?style=social) | "aims to support data scientists and machine learning (ML) engineers in explaining, testing and documenting AI/ML models, developed in-house or acquired externally. The explabox turns your ingestibles (AI/ML model and/or dataset) into digestibles (statistics, explanations or sensitivity insights).” |
| [Explainable Boosting Machine (EBM)/GA2M](https://github.com/interpretml/interpret)![](https://img.shields.io/github/stars/interpretml/interpret?style=social) | "an open-source package that incorporates state-of-the-art machine learning interpretability techniques under one roof. With this package, you can train interpretable glassbox models and explain blackbox systems. InterpretML helps you understand your model's global behavior, or understand the reasons behind individual predictions.” |
| [ExplainaBoard](https://github.com/neulab/ExplainaBoard)![](https://img.shields.io/github/stars/neulab/ExplainaBoard?style=social) | "a tool that inspects your system outputs, identifies what is working and what is not working, and helps inspire you with ideas of where to go next.” |
| [explainerdashboard](https://github.com/oegedijk/explainerdashboard)![](https://img.shields.io/github/stars/oegedijk/explainerdashboard?style=social) | "Quickly build Explainable AI dashboards that show the inner workings of so-called "blackbox" machine learning models.” |
| [explainX](https://github.com/explainX/explainx)![](https://img.shields.io/github/stars/explainX/explainx?style=social) | "Explainable AI framework for data scientists. Explain & debug any blackbox machine learning model with a single line of code.” |
| [fair-classification](https://github.com/mbilalzafar/fair-classification)![](https://img.shields.io/github/stars/mbilalzafar/fair-classification?style=social) | "Python code for training fair logistic regression classifiers.” |
| [fairml](https://github.com/adebayoj/fairml)![](https://img.shields.io/github/stars/adebayoj/fairml?style=social) | "a python toolbox auditing the machine learning models for bias.” |
| [fairlearn](https://github.com/fairlearn/fairlearn)![](https://img.shields.io/github/stars/fairlearn/fairlearn?style=social) | "a Python package that empowers developers of artificial intelligence (AI) systems to assess their system's fairness and mitigate any observed unfairness issues. Fairlearn contains mitigation algorithms as well as metrics for model assessment. Besides the source code, this repository also contains Jupyter notebooks with examples of Fairlearn usage.” |
| [fairness-comparison](https://github.com/algofairness/fairness-comparison)![](https://img.shields.io/github/stars/algofairness/fairness-comparison?style=social) | "meant to facilitate the benchmarking of fairness aware machine learning algorithms.” |
| [fairness_measures_code](https://github.com/megantosh/fairness_measures_code)![](https://img.shields.io/github/stars/megantosh/fairness_measures_code?style=social) | "contains implementations of measures used to quantify discrimination.” |
| [Falling Rule List (FRL)](https://users.cs.duke.edu/~cynthia/code/falling_rule_list.zip) | Rudin group at Duke falling rule list implementation |
| [foolbox](https://github.com/bethgelab/foolbox)![](https://img.shields.io/github/stars/bethgelab/foolbox?style=social) | "A Python toolbox to create adversarial examples that fool neural networks in PyTorch, TensorFlow, and JAX.” |
| [Giskard](https://github.com/Giskard-AI/giskard)![](https://img.shields.io/github/stars/Giskard-AI/giskard?style=social) | "The testing framework dedicated to ML models, from tabular to LLMs. Scan AI models to detect risks of biases, performance issues and errors. In 4 lines of code.” |
| [Grad-CAM](https://github.com/topics/grad-cam) (GitHub topic) | Grad-CAM is a technique for making convolutional neural networks more transparent by visualizing the regions of input that are important for predictions in computer vision models. |
| [gplearn](https://github.com/trevorstephens/gplearn)![](https://img.shields.io/github/stars/trevorstephens/gplearn?style=social) | "implements Genetic Programming in Python, with a scikit-learn inspired and compatible API.” |
| [H2O-3](https://github.com/h2oai/h2o-3) [Penalized Generalized Linear Models](http://docs.h2o.ai/h2o/latest-stable/h2o-py/docs/modeling.html#h2ogeneralizedlinearestimator) | "Fits a generalized linear model, specified by a response variable, a set of predictors, and a description of the error distribution." |
| [H2O-3](https://github.com/h2oai/h2o-3) [Monotonic GBM](http://docs.h2o.ai/h2o/latest-stable/h2o-py/docs/modeling.html#h2ogradientboostingestimator) | "Builds gradient boosted classification trees and gradient boosted regression trees on a parsed data set." |
| [H2O-3](https://github.com/h2oai/h2o-3) [Sparse Principal Components (GLRM)](http://docs.h2o.ai/h2o/latest-stable/h2o-py/docs/modeling.html#h2ogeneralizedlowrankestimator) | "Builds a generalized low rank decomposition of an H2O data frame." |
| [h2o-LLM-eval](https://github.com/h2oai/h2o-LLM-eval)![](https://img.shields.io/github/stars/h2oai/h2o-LLM-eval?style=social) | "Large-language Model Evaluation framework with Elo Leaderboard and A-B testing." |
| [hate-functional-tests](https://github.com/paul-rottger/hate-functional-tests)![](https://img.shields.io/github/stars/paul-rottger/hate-functional-tests?style=social) | HateCheck: A dataset and test suite from an ACL 2021 paper, offering functional tests for hate speech detection models, including extensive case annotations and testing functionalities. |
| [imodels](https://github.com/csinva/imodels)![](https://img.shields.io/github/stars/csinva/imodels?style=social) | "Python package for concise, transparent, and accurate predictive modeling. All sklearn-compatible and easy to use.” |
| [iNNvestigate neural nets](https://github.com/albermax/innvestigate)![](https://img.shields.io/github/stars/albermax/innvestigate?style=social) | A comprehensive Python library to analyze and interpret neural network behaviors in Keras, featuring a variety of methods like Gradient, LRP, and Deep Taylor. |
| [Integrated-Gradients](https://github.com/ankurtaly/Integrated-Gradients)![](https://img.shields.io/github/stars/ankurtaly/Integrated-Gradients?style=social) | "a variation on computing the gradient of the prediction output w.r.t. features of the input. It requires no modification to the original network, is simple to implement, and is applicable to a variety of deep models (sparse and dense, text and vision).” |
| [interpret](https://github.com/interpretml/interpret)![](https://img.shields.io/github/stars/interpretml/interpret?style=social) | "an open-source package that incorporates state-of-the-art machine learning interpretability techniques under one roof.” |
| [interpret_with_rules](https://github.com/clips/interpret_with_rules)![](https://img.shields.io/github/stars/clips/interpret_with_rules?style=social) | "induces rules to explain the predictions of a trained neural network, and optionally also to explain the patterns that the model captures from the training data, and the patterns that are present in the original dataset.” |
| [InterpretME](https://github.com/SDM-TIB/InterpretME)![](https://img.shields.io/github/stars/SDM-TIB/InterpretME?style=social) | "integrates knowledge graphs (KG) with machine learning methods to generate interesting meaningful insights. It helps to generate human- and machine-readable decisions to provide assistance to users and enhance efficiency.” |
| [Keras-vis](https://github.com/raghakot/keras-vis)![](https://img.shields.io/github/stars/raghakot/keras-vis?style=social) | "a high-level toolkit for visualizing and debugging your trained keras neural net models.” |
| [keract](https://github.com/philipperemy/keract/)![](https://img.shields.io/github/stars/philipperemy/keract?style=social) | Keract is a tool for visualizing activations and gradients in Keras models; it's meant to support a wide range of Tensorflow versions and to offer an intuitive API with Python examples. |
| [L2X](https://github.com/Jianbo-Lab/L2X)![](https://img.shields.io/github/stars/Jianbo-Lab/L2X?style=social) | "Code for replicating the experiments in the paper [Learning to Explain: An Information-Theoretic Perspective on Model Interpretation](https://arxiv.org/pdf/1802.07814.pdf) at ICML 2018, by Jianbo Chen, Mitchell Stern, Martin J. Wainwright, Michael I. Jordan.” |
| [langtest](https://github.com/JohnSnowLabs/langtest)![](https://img.shields.io/github/stars/JohnSnowLabs/langtest?style=social) | "LangTest: Deliver Safe & Effective Language Models"
| [learning-fair-representations](https://github.com/zjelveh/learning-fair-representations)![](https://img.shields.io/github/stars/zjelveh/learning-fair-representations?style=social) | "Python numba implementation of Zemel et al. 2013 <http://www.cs.toronto.edu/~toni/Papers/icml-final.pdf>"
| [lilac](https://github.com/lilacai/lilac)![](https://img.shields.io/github/stars/lilacai/lilac?style=social) | "Curate better data for LLMs." |
| [lime](https://github.com/marcotcr/lime)![](https://img.shields.io/github/stars/marcotcr/lime?style=social) | "explaining what machine learning classifiers (or models) are doing. At the moment, we support explaining individual predictions for text classifiers or classifiers that act on tables (numpy arrays of numerical or categorical data) or images, with a package called lime (short for local interpretable model-agnostic explanations).” |
| [LiFT](https://github.com/linkedin/LiFT)![](https://img.shields.io/github/stars/linkedin/LiFT?style=social) | "The LinkedIn Fairness Toolkit (LiFT) is a Scala/Spark library that enables the measurement of fairness and the mitigation of bias in large-scale machine learning workflows. The measurement module includes measuring biases in training data, evaluating fairness metrics for ML models, and detecting statistically significant differences in their performance across different subgroups.” |
| [lit](https://github.com/pair-code/lit)![](https://img.shields.io/github/stars/pair-code/lit?style=social) | "The Learning Interpretability Tool (LIT, formerly known as the Language Interpretability Tool) is a visual, interactive ML model-understanding tool that supports text, image, and tabular data. It can be run as a standalone server, or inside of notebook environments such as Colab, Jupyter, and Google Cloud Vertex AI notebooks.” |
| [lofo-importance](https://github.com/aerdem4/lofo-importance)![](https://img.shields.io/github/stars/aerdem4/lofo-importance?style=social) | "LOFO (Leave One Feature Out) Importance calculates the importances of a set of features based on a metric of choice, for a model of choice, by iteratively removing each feature from the set, and evaluating the performance of the model, with a validation scheme of choice, based on the chosen metric.” |
| [lrp_toolbox](https://github.com/sebastian-lapuschkin/lrp_toolbox)![](https://img.shields.io/github/stars/sebastian-lapuschkin/lrp_toolbox?style=social) | "The Layer-wise Relevance Propagation (LRP) algorithm explains a classifer's prediction specific to a given data point by attributing relevance scores to important components of the input by using the topology of the learned model itself.” |
| [MindsDB](https://github.com/mindsdb/mindsdb)![](https://img.shields.io/github/stars/mindsdb/mindsdb?style=social) | "enables developers to build AI tools that need access to real-time data to perform their tasks.” |
| [MLextend](http://rasbt.github.io/mlxtend/) | "Mlxtend (machine learning extensions) is a Python library of useful tools for the day-to-day data science tasks.” |
| [ml-fairness-gym](https://github.com/google/ml-fairness-gym)![](https://img.shields.io/github/stars/google/ml-fairness-gym?style=social) | "a set of components for building simple simulations that explore the potential long-run impacts of deploying machine learning-based decision systems in social environments.” |
| [ml_privacy_meter](https://github.com/privacytrustlab/ml_privacy_meter)![](https://img.shields.io/github/stars/privacytrustlab/ml_privacy_meter?style=social) | "an open-source library to audit data privacy in statistical and machine learning algorithms. The tool can help in the data protection impact assessment process by providing a quantitative analysis of the fundamental privacy risks of a (machine learning) model.” |
| [mllp](https://github.com/12wang3/mllp)![](https://img.shields.io/github/stars/12wang3/mllp?style=social) | "This is a PyTorch implementation of Multilayer Logical Perceptrons (MLLP) and Random Binarization (RB) method to learn Concept Rule Sets (CRS) for transparent classification tasks, as described in our paper: [Transparent Classification with Multilayer Logical Perceptrons and Random Binarization](https://arxiv.org/abs/1912.04695).” |
| [Monotonic Constraints](http://xgboost.readthedocs.io/en/latest/tutorials/monotonic.html) | Guide on implementing and understanding monotonic constraints in XGBoost models to enhance predictive performance with practical Python examples. |
| [XGBoost](http://xgboost.readthedocs.io/en/latest/) | "an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable.” |
| [Multilayer Logical Perceptron (MLLP)](https://github.com/12wang3/mllp)![](https://img.shields.io/github/stars/12wang3/mllp?style=social) | "This is a PyTorch implementation of Multilayer Logical Perceptrons (MLLP) and Random Binarization (RB) method to learn Concept Rule Sets (CRS) for transparent classification tasks, as described in our paper: [Transparent Classification with Multilayer Logical Perceptrons and Random Binarization](https://arxiv.org/abs/1912.04695).” |
| [OptBinning](https://github.com/guillermo-navas-palencia/optbinning)![](https://img.shields.io/github/stars/guillermo-navas-palencia/optbinning?style=social) | "a library written in Python implementing a rigorous and flexible mathematical programming formulation to solve the optimal binning problem for a binary, continuous and multiclass target type, incorporating constraints not previously addressed.” |
| [Optimal Sparse Decision Trees](https://github.com/xiyanghu/OSDT)![](https://img.shields.io/github/stars/xiyanghu/OSDT?style=social) | "This accompanies the paper, ["Optimal Sparse Decision Trees"](https://arxiv.org/abs/1904.12847) by Xiyang Hu, Cynthia Rudin, and Margo Seltzer.” |
| [parity-fairness](https://pypi.org/project/parity-fairness/) | "This repository contains codes that demonstrate the use of fairness metrics, bias mitigations and explainability tool.” |
| [PDPbox](https://github.com/SauceCat/PDPbox)![](https://img.shields.io/github/stars/SauceCat/PDPbox?style=social) | "Python Partial Dependence Plot toolbox. Visualize the influence of certain features on model predictions for supervised machine learning algorithms, utilizing partial dependence plots.” |
| [PiML-Toolbox](https://github.com/SelfExplainML/PiML-Toolbox)![](https://img.shields.io/github/stars/SelfExplainML/PiML-Toolbox?style=social) | "a new Python toolbox for interpretable machine learning model development and validation. Through low-code interface and high-code APIs, PiML supports a growing list of inherently interpretable ML models.” |
| [Privacy-Preserving-ML](https://github.com/abhinav-bohra/Privacy-Preserving-ML)![](https://img.shields.io/github/stars/abhinav-bohra/Privacy-Preserving-ML?style=social) | "Implementation of privacy-preserving SVM assuming public model private data scenario (data in encrypted but model parameters are unencrypted) using adequate partial homomorphic encryption.” |
| [ProtoPNet](https://github.com/cfchen-duke/)![](https://img.shields.io/github/stars/cfchen-duke?style=social) | "This code package implements the prototypical part network (ProtoPNet) from the paper "This Looks Like That: Deep Learning for Interpretable Image Recognition" (to appear at NeurIPS 2019), by Chaofan Chen (Duke University), Oscar Li| (Duke University), Chaofan Tao (Duke University), Alina Jade Barnett (Duke University), Jonathan Su (MIT Lincoln Laboratory), and Cynthia Rudin (Duke University).” |
| [pyBreakDown](https://github.com/MI2DataLab/pyBreakDown)![](https://img.shields.io/github/stars/MI2DataLab/pyBreakDown?style=social) | See [dalex](https://dalex.drwhy.ai/). |
| [PyCEbox](https://github.com/AustinRochford/PyCEbox)![](https://img.shields.io/github/stars/AustinRochford/PyCEbox?style=social) | "Python Individual Conditional Expectation Plot Toolbox.” |
| [pyGAM](https://github.com/dswah/pyGAM)![](https://img.shields.io/github/stars/dswah/pyGAM?style=social) | "Generalized Additive Models in Python.” |
| [pymc3](https://github.com/pymc-devs/pymc3)![](https://img.shields.io/github/stars/pymc-devs/pymc3?style=social) | "PyMC (formerly PyMC3) is a Python package for Bayesian statistical modeling focusing on advanced Markov chain Monte Carlo (MCMC) and variational inference (VI) algorithms. Its flexibility and extensibility make it applicable to a large suite of problems.” |
| [pySS3](https://github.com/sergioburdisso/pyss3)![](https://img.shields.io/github/stars/sergioburdisso/pyss3?style=social) | "The SS3 text classifier is a novel and simple supervised machine learning model for text classification which is interpretable, that is, it has the ability to naturally (self)explain its rationale.” |
| [pytorch-grad-cam](https://github.com/jacobgil/pytorch-grad-cam)![](https://img.shields.io/github/stars/jacobgil/pytorch-grad-cam?style=social) | "a package with state of the art methods for Explainable AI for computer vision. This can be used for diagnosing model predictions, either in production or while developing models. The aim is also to serve as a benchmark of algorithms and metrics for research of new explainability methods.” |
| [pytorch-innvestigate](https://github.com/fgxaos/pytorch-innvestigate)![](https://img.shields.io/github/stars/fgxaos/pytorch-innvestigate?style=social) | "PyTorch implementation of Keras already existing project: [https://github.com/albermax/innvestigate/](https://github.com/albermax/innvestigate/).” |
| [Quantus](https://github.com/understandable-machine-intelligence-lab/Quantus)![](https://img.shields.io/github/stars/understandable-machine-intelligence-lab/Quantus?style=social) | "Quantus is an eXplainable AI toolkit for responsible evaluation of neural network explanations." |
| [rationale](https://github.com/taolei87/rcnn/tree/master/code/rationale)![](https://img.shields.io/github/stars/taolei87/rcnn?style=social) | "This directory contains the code and resources of the following paper: *"Rationalizing Neural Predictions". Tao Lei, Regina Barzilay and Tommi Jaakkola. EMNLP 2016. [[PDF]](https://people.csail.mit.edu/taolei/papers/emnlp16_rationale.pdf) [[Slides]](https://people.csail.mit.edu/taolei/papers/emnlp16_rationale_slides.pdf)*. The method learns to provide justifications, i.e. rationales, as supporting evidence of neural networks' prediction.” |
| [responsibly](https://github.com/ResponsiblyAI/responsibly)![](https://img.shields.io/github/stars/ResponsiblyAI/responsibly?style=social) | "Toolkit for Auditing and Mitigating Bias and Fairness of Machine Learning Systems.” |
| [REVISE: REvealing VIsual biaSEs](https://github.com/princetonvisualai/revise-tool)![](https://img.shields.io/github/stars/princetonvisualai/revise-tool?style=social) | "A tool that automatically detects possible forms of bias in a visual dataset along the axes of object-based, attribute-based, and geography-based patterns, and from which next steps for mitigation are suggested.” |
| [robustness](https://github.com/MadryLab/robustness)![](https://img.shields.io/github/stars/MadryLab/robustness?style=social) | "a package we (students in the [MadryLab](http://madry-lab.ml/)) created to make training, evaluating, and exploring neural networks flexible and easy.” |
| [RISE](https://github.com/eclique/RISE)![](https://img.shields.io/github/stars/eclique/RISE?style=social) | "contains source code necessary to reproduce some of the main results in the paper: [Vitali Petsiuk](http://cs-people.bu.edu/vpetsiuk/), [Abir Das](http://cs-people.bu.edu/dasabir/), [Kate Saenko](http://ai.bu.edu/ksaenko.html) (BMVC, 2018) [and] [RISE: Randomized Input Sampling for Explanation of Black-box Models](https://arxiv.org/abs/1806.07421).” |
| [Risk-SLIM](https://github.com/ustunb/risk-SLIM)![](https://img.shields.io/github/stars/ustunb/risk-SLIM?style=social) | "a machine learning method to fit simple customized risk scores in python.” |
| [SAGE](https://github.com/iancovert/sage/)![](https://img.shields.io/github/stars/iancovert/sage?style=social) | "SAGE (Shapley Additive Global importancE) is a game-theoretic approach for understanding black-box machine learning models. It quantifies each feature's importance based on how much predictive power it contributes, and it accounts for complex feature interactions using the Shapley value.” |
| [SALib](https://github.com/SALib/SALib)![](https://img.shields.io/github/stars/SALib/SALib?style=social) | "Python implementations of commonly used sensitivity analysis methods. Useful in systems modeling to calculate the effects of model inputs or exogenous factors on outputs of interest.” |
| [Scikit-Explain](https://scikit-explain.readthedocs.io/en/latest/index.html) | "User-friendly Python module for machine learning explainability," featuring PD and ALE plots, LIME, SHAP, permutation importance and Friedman's H, among other methods. |
| [Scikit-learn](https://scikit-learn.org/stable/) [Decision Trees](http://scikit-learn.org/stable/modules/tree.html) | "a non-parametric supervised learning method used for classification and regression.” |
| [Scikit-learn](https://scikit-learn.org/stable/) [Generalized Linear Models](http://scikit-learn.org/stable/modules/linear_model.html) | "a set of methods intended for regression in which the target value is expected to be a linear combination of the features.” |
| [Scikit-learn](https://scikit-learn.org/stable/) [Sparse Principal Components](http://scikit-learn.org/stable/modules/decomposition.html#sparse-principal-components-analysis-sparsepca-and-minibatchsparsepca) | "a variant of [principal component analysis, PCA], with the goal of extracting the set of sparse components that best reconstruct the data.” |
| [scikit-fairness](https://github.com/koaning/scikit-fairness)![](https://img.shields.io/github/stars/koaning/scikit-fairness?style=social) | Historical link. Merged with [fairlearn](https://fairlearn.org/). |
| [scikit-multiflow](https://scikit-multiflow.github.io/) | "a machine learning package for streaming data in Python.” |
| [shap](https://github.com/slundberg/shap)![](https://img.shields.io/github/stars/slundberg/shap?style=social) | "a game theoretic approach to explain the output of any machine learning model. It connects optimal credit allocation with local explanations using the classic Shapley values from game theory and their related extensions"
| [shapley](https://github.com/benedekrozemberczki/shapley)![](https://img.shields.io/github/stars/benedekrozemberczki/shapley?style=social) | "a Python library for evaluating binary classifiers in a machine learning ensemble.” |
| [sklearn-expertsys](https://github.com/tmadl/sklearn-expertsys)![](https://img.shields.io/github/stars/tmadl/sklearn-expertsys?style=social) | "a scikit-learn compatible wrapper for the Bayesian Rule List classifier developed by Letham et al., 2015, extended by a minimum description length-based discretizer (Fayyad & Irani, 1993) for continuous data, and by an approach to subsample large datasets for better performance.” |
| [skope-rules](https://github.com/scikit-learn-contrib/skope-rules)![](https://img.shields.io/github/stars/scikit-learn-contrib/skope-rules?style=social) | "a Python machine learning module built on top of scikit-learn and distributed under the 3-Clause BSD license.” |
| [solas-ai-disparity](https://github.com/SolasAI/solas-ai-disparity)![](https://img.shields.io/github/stars/SolasAI/solas-ai-disparity?style=social) | "a collection of tools that allows modelers, compliance, and business stakeholders to test outcomes for bias or discrimination using widely accepted fairness metrics.” |
| [Super-sparse Linear Integer models (SLIMs)](https://github.com/ustunb/slim-python)![](https://img.shields.io/github/stars/ustunb/slim-python?style=social) | "a package to learn customized scoring systems for decision-making problems.” |
| [tensorflow/lattice](https://github.com/tensorflow/lattice)![](https://img.shields.io/github/stars/tensorflow/lattice?style=social) | "a library that implements constrained and interpretable lattice based models. It is an implementation of Monotonic Calibrated Interpolated Look-Up Tables in TensorFlow.” |
| [tensorflow/lucid](https://github.com/tensorflow/lucid)![](https://img.shields.io/github/stars/tensorflow/lucid?style=social) | "a collection of infrastructure and tools for research in neural network interpretability.” |
| [tensorflow/fairness-indicators](https://github.com/tensorflow/fairness-indicators)![](https://img.shields.io/github/stars/tensorflow/fairness-indicators?style=social) | "designed to support teams in evaluating, improving, and comparing models for fairness concerns in partnership with the broader Tensorflow toolkit.” |
| [tensorflow/model-analysis](https://github.com/tensorflow/model-analysis)![](https://img.shields.io/github/stars/tensorflow/model-analysis?style=social) | "a library for evaluating TensorFlow models. It allows users to evaluate their models on large amounts of data in a distributed manner, using the same metrics defined in their trainer. These metrics can be computed over different slices of data and visualized in Jupyter notebooks.” |
| [tensorflow/model-card-toolkit](https://github.com/tensorflow/model-card-toolkit)![](https://img.shields.io/github/stars/tensorflow/model-card-toolkit?style=social) | "streamlines and automates generation of Model Cards, machine learning documents that provide context and transparency into a model's development and performance. Integrating the MCT into your ML pipeline enables you to share model metadata and metrics with researchers, developers, reporters, and more.” |
| [tensorflow/model-remediation](https://github.com/tensorflow/model-remediation)![](https://img.shields.io/github/stars/tensorflow/model-remediation?style=social) | "a library that provides solutions for machine learning practitioners working to create and train models in a way that reduces or eliminates user harm resulting from underlying performance biases.” |
| [tensorflow/privacy](https://github.com/tensorflow/privacy)![](https://img.shields.io/github/stars/tensorflow/privacy?style=social) | "the source code for TensorFlow Privacy, a Python library that includes implementations of TensorFlow optimizers for training machine learning models with differential privacy. The library comes with tutorials and analysis tools for computing the privacy guarantees provided.” |
| [tensorflow/tcav](https://github.com/tensorflow/tcav)![](https://img.shields.io/github/stars/tensorflow/tcav?style=social) | "Testing with Concept Activation Vectors (TCAV) is a new interpretability method to understand what signals your neural networks models uses for prediction.” |
| [tensorfuzz](https://github.com/brain-research/tensorfuzz)![](https://img.shields.io/github/stars/brain-research/tensorfuzz?style=social) | "a library for performing coverage guided fuzzing of neural networks.” |
| [TensorWatch](https://github.com/microsoft/tensorwatch)![](https://img.shields.io/github/stars/microsoft/tensorwatch?style=social) | "a debugging and visualization tool designed for data science, deep learning and reinforcement learning from Microsoft Research. It works in Jupyter Notebook to show real-time visualizations of your machine learning training and perform several other key analysis tasks for your models and data.” |
| [TextFooler](https://github.com/jind11/TextFooler)![](https://img.shields.io/github/stars/jind11/TextFooler?style=social) | "A Model for Natural Language Attack on Text Classification and Inference"
| [text_explainability](https://text-explainability.readthedocs.io/) | "text_explainability provides a generic architecture from which well-known state-of-the-art explainability approaches for text can be composed.” |
| [text_sensitivity](https://text-sensitivity.readthedocs.io/) | "Uses the generic architecture of text_explainability to also include tests of safety (how safe it the model in production, i.e. types of inputs it can handle), robustness (how generalizable the model is in production, e.g. stability when adding typos, or the effect of adding random unrelated data) and fairness (if equal individuals are treated equally by the model, e.g. subgroup fairness on sex and nationality).” |
| [tf-explain](https://github.com/sicara/tf-explain)![](https://img.shields.io/github/stars/sicara/tf-explain?style=social) | "Implements interpretability methods as Tensorflow 2.x callbacks to ease neural network's understanding.” |
| [Themis](https://github.com/LASER-UMASS/Themis)![](https://img.shields.io/github/stars/LASER-UMASS/Themis?style=social) | "A testing-based approach for measuring discrimination in a software system.” |
| [themis-ml](https://github.com/cosmicBboy/themis-ml)![](https://img.shields.io/github/stars/cosmicBboy/themis-ml?style=social) | "A Python library built on top of pandas and sklearnthat implements fairness-aware machine learning algorithms.” |
| [TorchUncertainty](https://github.com/ENSTA-U2IS/torch-uncertainty)![](https://img.shields.io/github/stars/ENSTA-U2IS/torch-uncertainty?style=social) | "A package designed to help you leverage uncertainty quantification techniques and make your deep neural networks more reliable.” |
| [treeinterpreter](https://github.com/andosa/treeinterpreter)![](https://img.shields.io/github/stars/andosa/treeinterpreter?style=social) | "Package for interpreting scikit-learn's decision tree and random forest predictions.” |
| [TRIAGE](https://github.com/seedatnabeel/TRIAGE)![](https://img.shields.io/github/stars/seedatnabeel/TRIAGE?style=social) | "This repository contains the implementation of TRIAGE, a "Data-Centric AI" framework for data characterization tailored for regression.” |
| [woe](https://github.com/boredbird/woe)![](https://img.shields.io/github/stars/boredbird/woe?style=social) | "Tools for WoE Transformation mostly used in ScoreCard Model for credit rating.” |
| [xai](https://github.com/EthicalML/xai)![](https://img.shields.io/github/stars/EthicalML/xai?style=social) | "A Machine Learning library that is designed with AI explainability in its core.” |
| [xdeep](https://github.com/datamllab/xdeep)![](https://img.shields.io/github/stars/datamllab/xdeep?style=social) | "An open source Python library for Interpretable Machine Learning.” |
| [xplique](https://github.com/deel-ai/xplique)![](https://img.shields.io/github/stars/deel-ai/xplique?style=social) | "A Python toolkit dedicated to explainability. The goal of this library is to gather the state of the art of Explainable AI to help you understand your complex neural network models.” |
| [ydata-profiling](https://github.com/ydataai/ydata-profiling)![](https://img.shields.io/github/stars/ydataai/ydata-profiling?style=social) | "Provide[s] a one-line Exploratory Data Analysis (EDA) experience in a consistent and fast solution.” |
| [yellowbrick](https://github.com/DistrictDataLabs/yellowbrick)![](https://img.shields.io/github/stars/DistrictDataLabs/yellowbrick?style=social) | "A suite of visual diagnostic tools called "Visualizers" that extend the scikit-learn API to allow human steering of the model selection process.” |
 
#### R

| Name | Description |
|------|-------------|
| [ALEPlot](https://cran.r-project.org/web/packages/ALEPlot/index.html) | "Visualizes the main effects of individual predictor variables and their second-order interaction effects in black-box supervised learning models."  |
| [arules](https://cran.r-project.org/web/packages/arules/index.html) | "Provides the infrastructure for representing, manipulating and analyzing transaction data and patterns (frequent itemsets and association rules). Also provides C implementations of the association mining algorithms Apriori and Eclat. Hahsler, Gruen and Hornik (2005)." |
| [Causal SVM](https://github.com/shangtai/githubcausalsvm)![](https://img.shields.io/github/stars/shangtai/githubcausalsvm?style=social) | "We present a new machine learning approach to estimate whether a treatment has an effect on an individual, in the setting of the classical potential outcomes framework with binary outcomes." |
| [DALEX](https://github.com/ModelOriented/DALEX)![](https://img.shields.io/github/stars/ModelOriented/DALEX?style=social) | "moDel Agnostic Language for Exploration and eXplanation." |
| [DALEXtra: Extension for 'DALEX' Package](https://cran.r-project.org/web/packages/DALEXtra/index.html) | "Provides wrapper of various machine learning models." |
| [DrWhyAI](https://github.com/ModelOriented/DrWhy)![](https://img.shields.io/github/stars/ModelOriented/DrWhy?style=social) | "DrWhy is [a] collection of tools for eXplainable AI (XAI). It's based on shared principles and simple grammar for exploration, explanation and visualisation of predictive models." |
| [elasticnet](https://cran.r-project.org/web/packages/elasticnet/index.html) | "Provides functions for fitting the entire solution path of the Elastic-Net and also provides functions for doing sparse PCA." |
| [ExplainPrediction](https://github.com/rmarko/ExplainPrediction)![](https://img.shields.io/github/stars/rmarko/ExplainPrediction?style=social) | "Generates explanations for classification and regression models and visualizes them." |
| [Explainable Boosting Machine (EBM)/GA2M](https://cran.r-project.org/web/packages/interpret/index.html) | "Package for training interpretable machine learning models." |
| [fairmodels](https://github.com/ModelOriented/fairmodels)![](https://img.shields.io/github/stars/ModelOriented/fairmodels?style=social) | "Flexible tool for bias detection, visualization, and mitigation. Use models explained with DALEX and calculate fairness classification metrics based on confusion matrices using fairness_check() or try newly developed module for regression models using fairness_check_regression()." |
| [fairness](https://cran.r-project.org/web/packages/fairness/index.html) | "Offers calculation, visualization and comparison of algorithmic fairness metrics." |
| [fastshap](https://github.com/bgreenwell/fastshap)![](https://img.shields.io/github/stars/bgreenwell/fastshap?style=social) | "The goal of fastshap is to provide an efficient and speedy approach (at least relative to other implementations) for computing approximate Shapley values, which help explain the predictions from any machine learning model." |
| [featureImportance](https://github.com/giuseppec/featureImportance)![](https://img.shields.io/github/stars/giuseppec/featureImportance?style=social) | "An extension for the mlr package and allows to compute the permutation feature importance in a model-agnostic manner." |
| [flashlight](https://github.com/mayer79/flashlight)![](https://img.shields.io/github/stars/mayer79/flashlight?style=social) | "The goal of this package is [to] shed light on black box machine learning models." |
| [forestmodel](https://cran.r-project.org/web/packages/forestmodel/index.html) | "Produces forest plots using 'ggplot2' from models produced by functions such as stats::lm(), stats::glm() and survival::coxph()." |
| [fscaret](https://cran.r-project.org/web/packages/fscaret/) | "Automated feature selection using variety of models provided by 'caret' package." |
| [gam](https://cran.r-project.org/web/packages/gam/index.html) | "Functions for fitting and working with generalized additive models, as described in chapter 7 of "Statistical Models in S" (Chambers and Hastie (eds), 1991), and "Generalized Additive Models" (Hastie and Tibshirani, 1990)." |
| [glm2](https://cran.r-project.org/web/packages/glm2/) | "Fits generalized linear models using the same model specification as glm in the stats package, but with a modified default fitting method that provides greater stability for models that may fail to converge using glm." |
| [glmnet](https://cran.r-project.org/web/packages/glmnet/index.html) | "Extremely efficient procedures for fitting the entire lasso or elastic-net regularization path for linear regression, logistic and multinomial regression models, Poisson regression, Cox model, multiple-response Gaussian, and the grouped multinomial regression." |
| [H2O-3](https://github.com/h2oai/h2o-3) [Penalized Generalized Linear Models](http://docs.h2o.ai/h2o/latest-stable/h2o-r/docs/reference/h2o.glm.html) | "Fits a generalized linear model, specified by a response variable, a set of predictors, and a description of the error distribution." |
| [H2O-3](https://github.com/h2oai/h2o-3) [Monotonic GBM](http://docs.h2o.ai/h2o/latest-stable/h2o-r/docs/reference/h2o.gbm.html) | "Builds gradient boosted classification trees and gradient boosted regression trees on a parsed data set." |
| [H2O-3](https://github.com/h2oai/h2o-3) [Sparse Principal Components (GLRM)](http://docs.h2o.ai/h2o/latest-stable/h2o-r/docs/reference/h2o.glrm.html) | "Builds a generalized low rank decomposition of an H2O data frame." |
| [iBreakDown](https://github.com/ModelOriented/iBreakDown)![](https://img.shields.io/github/stars/ModelOriented/iBreakDown?style=social) | "A model agnostic tool for explanation of predictions from black boxes ML models."|
| [ICEbox: Individual Conditional Expectation Plot Toolbox](https://cran.r-project.org/web/packages/ICEbox/index.html) | "Implements Individual Conditional Expectation (ICE) plots, a tool for visualizing the model estimated by any supervised learning algorithm."|
| [iml](https://github.com/christophM/iml)![](https://img.shields.io/github/stars/christophM/iml?style=social) | "An R package that interprets the behavior and explains predictions of machine learning models."|
| [ingredients](https://github.com/ModelOriented/ingredients)![](https://img.shields.io/github/stars/ModelOriented/ingredients?style=social) | "A collection of tools for assessment of feature importance and feature effects."|
| [interpret: Fit Interpretable Machine Learning Models](https://cran.r-project.org/web/packages/interpret/index.html) | "Package for training interpretable machine learning models."|
| [lightgbmExplainer](https://github.com/lantanacamara/lightgbmExplainer)![](https://img.shields.io/github/stars/lantanacamara/lightgbmExplainer?style=social) | "An R package that makes LightGBM models fully interpretable."|
| [lime](https://github.com/thomasp85/lime)![](https://img.shields.io/github/stars/thomasp85/lime?style=social) | "R port of the Python lime package."|
| [live](https://cran.r-project.org/web/packages/live/index.html) | "Helps to understand key factors that drive the decision made by complicated predictive model (black box model)."|
| [mcr](https://github.com/aaronjfisher/mcr)![](https://img.shields.io/github/stars/aaronjfisher/mcr?style=social) | "An R package for Model Reliance and Model Class Reliance."|
| [modelDown](https://cran.r-project.org/web/packages/modelDown/index.html) | "Website generator with HTML summaries for predictive models."|
| [modelOriented](https://github.com/ModelOriented)![](https://img.shields.io/github/stars/ModelOriented?style=social) | GitHub repositories of Warsaw-based MI².AI. |
| [modelStudio](https://github.com/ModelOriented/modelStudio)![](https://img.shields.io/github/stars/ModelOriented/modelStudio?style=social) | "Automates the explanatory analysis of machine learning predictive models."|
| [Monotonic](http://xgboost.readthedocs.io/en/latest/tutorials/monotonic.html) [XGBoost](http://xgboost.readthedocs.io/en/latest/) | Enforces consistent, directional relationships between features and predicted outcomes, enhancing model performance by aligning with prior data expectations. |
| [quantreg](https://cran.r-project.org/web/packages/quantreg/index.html) | "Estimation and inference methods for models for conditional quantile functions." |
| [rpart](https://cran.r-project.org/web/packages/rpart/index.html) | "Recursive partitioning for classification, regression and survival trees." |
| [RuleFit](http://statweb.stanford.edu/~jhf/R_RuleFit.html) | "Implements the learning method and interpretational tools described in *Predictive Learning via Rule Ensembles*." |
| [Scalable Bayesian Rule Lists (SBRL)](https://users.cs.duke.edu/~cynthia/code/sbrl_1.0.tar.gz) | A more scalable implementation of Bayesian rule list from the Rudin group at Duke. |
| [shapFlex](https://github.com/nredell/shapFlex)![](https://img.shields.io/github/stars/nredell/shapFlex?style=social) | Computes stochastic Shapley values for machine learning models to interpret them and evaluate fairness, including causal constraints in the feature space. |
| [shapleyR](https://github.com/redichh/ShapleyR)![](https://img.shields.io/github/stars/redichh/ShapleyR?style=social) | "An R package that provides some functionality to use mlr tasks and models to generate shapley values." |
| [shapper](https://cran.r-project.org/web/packages/shapper/index.html) | "Provides SHAP explanations of machine learning models." |
| [smbinning](https://cran.r-project.org/web/packages/smbinning/index.html) | "A set of functions to build a scoring model from beginning to end." |
| [vip](https://github.com/koalaverse/vip)![](https://img.shields.io/github/stars/koalaverse/vip?style=social) | "An R package for constructing variable importance plots (VIPs)." |
| [xgboostExplainer](https://github.com/AppliedDataSciencePartners/xgboostExplainer)![](https://img.shields.io/github/stars/AppliedDataSciencePartners/xgboostExplainer?style=social) | "An R package that makes xgboost models fully interpretable. |

### Citing Awesome Machine Learning Interpretability

#### ACM, APA, Chicago, and MLA

* **ACM (Association for Computing Machinery)**

The ACM citation format focuses on digital resources:

Author(s) Last Name, First Initial. Middle Initial. Year. Title of the Project. Publisher (if applicable). Version (if applicable). URL. DOI (if applicable).

Hall, Patrick. 2024. Awesome Machine Learning Interpretability. GitHub. https://github.com/jphall663/awesome-machine-learning-interpretability.

* **APA (American Psychological Association) 7th Edition**

APA style citation for a GitHub repository should include:

Author(s) Last Name, First Initial(s). (Year of Publication). Title of the project [Description]. GitHub. URL.

Hall, Patrick. (2024). Awesome Machine Learning Interpretability [GitHub repository]. GitHub. https://github.com/jphall663/awesome-machine-learning-interpretability.

* **Chicago Manual of Style 17th Edition**

Chicago style offers two options: notes and bibliography system or author-date system. For a GitHub repository, the author-date system is more suitable:

Author(s) Last Name, First Name. Year of Publication. "Title of the Project." GitHub. Last modified Year. URL.

Hall, Patrick. 2024. "Awesome Machine Learning Interpretability." GitHub. Last modified 2023. https://github.com/jphall663/awesome-machine-learning-interpretability.

* **MLA (Modern Language Association) 9th Edition**

To cite a GitHub repository in MLA style, include the following elements:

Author(s) Name(s). "Title of the Project." *GitHub*, Year of Last Update, URL. Accessed Day Month Year.

Hall, Patrick. "Awesome Machine Learning Interpretability." *GitHub*, 2024, https://github.com/jphall663/awesome-machine-learning-interpretability. Accessed 5 March 2024.
