
# Awesome Machine Learning Interpretability [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A maintained and curated list of practical and awesome responsible machine learning resources.

If you want to contribute to this list (*and please do!*), read over the [contribution guidelines](contributing.md), send a [pull request](https://github.com/jphall663/awesome-machine-learning-interpretability/compare), or file an [issue](https://github.com/jphall663/awesome-machine-learning-interpretability/issues/new). 

If something you contributed or found here is missing after our September 2023 reboot, please check the [archive](https://github.com/jphall663/awesome-machine-learning-interpretability/blob/master/archive/README.md.bak).

## Contents

* **Community and Official Guidance Resources** 
  * [Community Frameworks and Guidance](#community-frameworks-and-guidance)
    * [Infographics and Cheat Sheets](#infographics-and-cheat-sheets)
    * [AI Red-Teaming Resources](#ai-red-teaming-resources)
    * [Generative AI Explainability](#generative-ai-explainability)
  * [Conferences and Workshops](#conferences-and-workshops)
  * [Official Policy, Frameworks, and Guidance](#official-policy-frameworks-and-guidance)
    * [Australia](#australia)
    * [Canada](#canada)
    * [France](#france)
    * [Germany](#germany)
    * [Netherlands](#netherlands)
    * [New Zealand](#new-zealand)
    * [Singapore](#singapore)
    * [United Kingdom](#united-kingdom)
    * [United States (Federal Government)](#united-states-federal-government)
    * [United States (State Governments)](#united-states-state-governments)
    * [International and Multilateral Frameworks](#international-and-multilateral-frameworks)
    * [European Union Policies and Regulations](#european-union-policies-and-regulations)
      * [European Commission and Parliament](#european-commission-and-parliament)
      * [European Data Protection Authorities](#european-data-protection-authorities)
    * [OECD](#oecd)
    * [NATO](#nato)
    * [United Nations](#united-nations)
  * [Law Texts and Drafts](#law-texts-and-drafts)

* **Education Resources**
  * [Comprehensive Software Examples and Tutorials](#comprehensive-software-examples-and-tutorials)
  * [Free-ish Books](#free-ish-books)
  * [Glossaries and Dictionaries](#glossaries-and-dictionaries)
  * [Open-ish Classes](#open-ish-classes)
  * [Podcasts and Channels](#podcasts-and-channels)

* **AI Incidents, Critiques, and Research Resources**
  * [AI Incident Information Sharing Resources](#ai-incident-information-sharing-resources)
    * [Bibliography of Papers on AI Incidents and Failures](#bibliography-of-papers-on-ai-incidents-and-failures)
  * [AI Law, Policy, and Guidance Trackers](#ai-law-policy-and-guidance-trackers)
  * [Challenges and Competitions](#challenges-and-competitions)
  * [Critiques of AI](#critiques-of-ai)
    * [Environmental Costs of AI](#environmental-costs-of-ai)
  * [Groups and Organizations](#groups-and-organizations)
  * [Curated Bibliographies](#curated-bibliographies)
  * [List of Lists](#list-of-lists)

* **Technical Resources**
  * [Benchmarks](#benchmarks)
  * [Common or Useful Datasets](#common-or-useful-datasets)
  * [Domain-specific Software](#domain-specific-software)
  * [Machine Learning Environment Management Tools](#machine-learning-environment-management-tools)
  * [Personal Data Protection Tools](#personal-data-protection-tools)
  * [Open Source/Access Responsible AI Software Packages](#open-sourceaccess-responsible-ai-software-packages)
    * [Browser](#browser)
    * [C/C++](#cc)
    * [JavaScript](#javascript)
    * [Python](#python)
    * [R](#r)
   
* **Citing Awesome Machine Learning Interpretability**
  * [Citation](#citing-awesome-machine-learning-interpretability)

## Community and Official Guidance Resources

### Community Frameworks and Guidance 

This section is for responsible ML guidance put forward by organizations or individuals, not for official government guidance.

* [8 Principles of Responsible ML](https://ethical.institute/principles.html)
* [A Brief Overview of AI Governance for Responsible Machine Learning Systems](https://arxiv.org/pdf/2211.13130.pdf)
* [Acceptable Use Policies for Foundation Models](https://github.com/kklyman/aupsforfms)![](https://img.shields.io/github/stars/kklyman/aupsforfms?style=social)
* [Access Now, Regulatory Mapping on Artificial Intelligence in Latin America: Regional AI Public Policy Report](https://www.accessnow.org/wp-content/uploads/2024/07/TRF-LAC-Reporte-Regional-IA-JUN-2024-V3.pdf)
* [Ada Lovelace Institute, Code and Conduct: How to Create Third-Party Auditing Regimes for AI Systems](https://www.adalovelaceinstitute.org/report/code-conduct-ai/)
* [Adversarial ML Threat Matrix](https://github.com/mitre/advmlthreatmatrix)![](https://img.shields.io/github/stars/mitre/advmlthreatmatrix?style=social)
* [AI Governance Needs Sociotechnical Expertise: Why the Humanities and Social Sciences Are Critical to Government Efforts](https://datasociety.net/wp-content/uploads/2024/05/DS_AI_Governance_Policy_Brief.pdf)
* [AI Verify](https://aiverifyfoundation.sg/what-is-ai-verify/):
  * [AI Verify Foundation](https://aiverifyfoundation.sg/what-is-ai-verify/)
  * [AI Verify Foundation, Cataloguing LLM Evaluations](https://aiverifyfoundation.sg/downloads/Cataloguing_LLM_Evaluations.pdf)
  * [AI Verify Foundation, Generative AI: Implications for Trust and Governance](https://aiverifyfoundation.sg/downloads/Discussion_Paper.pdf)
  * [AI Verfiy Foundation, Model Governance Framework for Generative AI](https://aiverifyfoundation.sg/wp-content/uploads/2024/05/Model-AI-Governance-Framework-for-Generative-AI-May-2024-1-1.pdf)
* [AI Snake Oil](https://www.aisnakeoil.com/)* 
* [The Alan Turing Institute, AI Ethics and Governance in Practice](https://www.turing.ac.uk/research/research-projects/ai-ethics-and-governance-practice)
* [The Alan Turing Institute, Responsible Data Stewardship in Practice](https://www.turing.ac.uk/sites/default/files/2024-06/aieg-ati-5-datastewardshipv1.2.pdf)
* [AllenNLP Interpret: A Framework for Explaining Predictions of NLP Models](http://sameersingh.org/files/papers/allennlp-interpret-demo-emnlp19.pdf)
* [Andreessen Horowitz (a16z) AI Canon](https://a16z.com/ai-canon/)
* [Anthropic's Responsible Scaling Policy](https://www-files.anthropic.com/production/files/responsible-scaling-policy-1.0.pdf)
* [AuditBoard: 5 AI Auditing Frameworks to Encourage Accountability](https://www.auditboard.com/blog/ai-auditing-frameworks/)
* [Auditing machine learning algorithms: A white paper for public auditors](https://www.auditingalgorithms.net/index.html)
* [AWS Data Privacy FAQ](https://aws.amazon.com/compliance/data-privacy-faq/)
* [AWS Privacy Notice](https://aws.amazon.com/privacy/)
* [AWS, What is Data Governance?](https://aws.amazon.com/what-is/data-governance/)
* [Berryville Institute of Machine Learning, Architectural Risk Analysis of Large Language Models (requires free account login)](https://berryvilleiml.com/results/BIML-LLM24.pdf)
* [BIML Interactive Machine Learning Risk Framework](https://berryvilleiml.com/interactive/)
* [Boston University AI Task Force Report on Generative AI in Education and Research](https://www.bu.edu/hic/files/2024/04/BU-AI-Task-Force-Report.pdf)
* [Brendan Bycroft's LLM Visualization](https://bbycroft.net/llm)
* [Brown University, How Can We Tackle AI-Fueled Misinformation and Disinformation in Public Health?](https://www.bu.edu/ceid/2024/04/25/how-can-we-tackle-ai-fueled-misinformation-and-disinformation-in-public-health/)
* [Casey Flores, AIGP Study Guide](https://www.linkedin.com/feed/update/urn:li:activity:7201048113090809856?utm_source=share&utm_medium=member_desktop)
* Center for Security and Emerging Technology (CSET):
  * [CSET's Harm Taxonomy for the AI Incident Database](https://github.com/georgetown-cset/CSET-AIID-harm-taxonomy)![](https://img.shields.io/github/stars/georgetown-cset/CSET-AIID-harm-taxonomy?style=social)
  * [CSET Publications](https://cset.georgetown.edu/publications/)
  * [Adding Structure to AI Harm: An Introduction to CSET's AI Harm Framework](https://cset.georgetown.edu/publication/adding-structure-to-ai-harm/)
  * [AI Incident Collection: An Observational Study of the Great AI Experiment](https://cset.georgetown.edu/publication/ai-incident-collection-an-observational-study-of-the-great-ai-experiment/)
  * [Repurposing the Wheel: Lessons for AI Standards](https://cset.georgetown.edu/publication/repurposing-the-wheel/)
  * [Translating AI Risk Management Into Practice](https://cset.georgetown.edu/article/translating-ai-risk-management-into-practice/)
  * [Understanding AI Harms: An Overview](https://cset.georgetown.edu/article/understanding-ai-harms-an-overview/)
* [Censius: AI Audit](https://censius.ai/wiki/ai-audit)
* [Center for AI and Digital Policy Reports](https://www.caidp.org/reports/)
* [Center for Democracy and Technology (CDT), Applying Sociotechnical Approaches to AI Governance in Practice](https://cdt.org/insights/applying-sociotechnical-approaches-to-ai-governance-in-practice/)
* [CivAI, GenAI Toolkit for the NIST AI Risk Management Framework: Thinking Through the Risks of a GenAI Chatbot](https://www.civai.org/genai-toolkit-pdf)
* [Coalition for Content Provenance and Authenticity (C2PA)](https://c2pa.org/)
* [Crowe LLP: Internal auditor's AI safety checklist](https://www.crowe.com/insights/asset/i/internal-auditors-ai-safety-checklist)
* [Data Provenance Explorer](https://www.dataprovenance.org/)
* [Data & Society, AI Red-Teaming Is Not a One-Stop Solution to AI Harms: Recommendations for Using Red-Teaming for AI Accountability](https://datasociety.net/wp-content/uploads/2023/10/Recommendations-for-Using-Red-Teaming-for-AI-Accountability-PolicyBrief.pdf)
* [Dealing with Bias and Fairness in AI/ML/Data Science Systems](https://docs.google.com/presentation/d/17o_NzplYua5fcJFuGcy1V1-5GFAHk7oHAF4dN44NkUE)
* [Debugging Machine Learning Models (ICLR workshop proceedings)](https://debug-ml-iclr2019.github.io/)
* [Decision Points in AI Governance](https://cltc.berkeley.edu/wp-content/uploads/2020/05/Decision_Points_AI_Governance.pdf)
* [Demos, AI – Trustworthy By Design: How to build trust in AI systems, the institutions that create them and the communities that use them](https://demos.co.uk/research/ai-trustworthy-by-design-how-to-build-trust-in-ai-systems-the-institutions-that-create-them-and-the-communities-that-use-them/)
* [Digital Policy Alert, The Anatomy of AI Rules: A systematic comparison of AI rules across the globe](https://digitalpolicyalert.org/ai-rules/the-anatomy-of-AI-rules)
* [Distill](https://distill.pub)
* [Dominique Shelton Leipzig, Countries With Draft AI Legislation or Frameworks](https://dominiquesheltonleipzig.com/country-legislation-frameworks/)
* [Ethical and social risks of harm from Language Models](https://www.deepmind.com/publications/ethical-and-social-risks-of-harm-from-language-models)
* [Ethics for people who work in tech](https://ethicsforpeoplewhoworkintech.com/)
* [EU Digital Partners, U.S. A.I. Laws: A State-by-State Study](https://eudigitalpartners.com/wp-content/uploads/2024/06/US-AI-LAWS.pdf)
* [Evaluating LLMs is a minefield](https://www.cs.princeton.edu/~arvindn/talks/evaluating_llms_minefield/)
* [Fairly's Global AI Regulations Map](https://github.com/fairlyAI/global-ai-regulations-map/blob/dev/README.md)![](https://img.shields.io/github/stars/fairlyAI/global-ai-regulations-map?style=social)
* [FATML Principles and Best Practices](https://www.fatml.org/resources/principles-and-best-practices)
* [Federation of American Scientists, A NIST Foundation To Support The Agency’s AI Mandate](https://fas.org/publication/nist-foundation/)
* [Financial Industry Regulatory Authority (FINRA), Artificial Intelligence (AI) in the Securities Industry](https://www.finra.org/sites/default/files/2020-06/ai-report-061020.pdf)
* [ForHumanity Body of Knowledge (BOK)](https://forhumanity.center/bok/)
* [The Foundation Model Transparency Index](https://crfm.stanford.edu/fmti/)
  * [Trustible, Model Transparency Ratings](https://aimodelratings.com/)
* [From Principles to Practice: An interdisciplinary framework to operationalise AI ethics](https://www.ai-ethics-impact.org/resource/blob/1961130/c6db9894ee73aefa489d6249f5ee2b9f/aieig---report---download-hb-data.pdf)
* [The Future Society](https://thefuturesociety.org/towards-effective-governance-of-foundation-models-and-generative-ai/)
* [Gage Repeatability and Reproducibility](https://asq.org/quality-resources/gage-repeatability)
* [Georgetown University Library's Artificial Intelligence (Generative) Resources](https://guides.library.georgetown.edu/ai)
* Google:
  * [Closing the AI accountability gap: defining an end-to-end framework for internal algorithmic auditing](https://dl.acm.org/doi/abs/10.1145/3351095.3372873)
  * [The Data Cards Playbook](https://sites.research.google/datacardsplaybook/)
  * [Data governance in the cloud - part 1 - People and processes](https://cloud.google.com/blog/products/data-analytics/data-governance-and-operating-model-for-analytics-pt1)
  * [Data Governance in the Cloud - part 2 - Tools](https://cloud.google.com/blog/products/data-analytics/data-governance-in-the-cloud-part-2-tools)
  * [Evaluating social and ethical risks from generative AI](https://deepmind.google/discover/blog/evaluating-social-and-ethical-risks-from-generative-ai/)
  * [Generative AI Prohibited Use Policy](https://policies.google.com/terms/generative-ai/use-policy)
  * [Perspectives on Issues in AI Governance](https://ai.google/static/documents/perspectives-on-issues-in-ai-governance.pdf)
  * [Principles and best practices for data governance in the cloud](https://services.google.com/fh/files/misc/principles_best_practices_for_data-governance.pdf)
  * [Responsible AI Framework](https://cloud.google.com/responsible-ai)
  * [Responsible AI practices](https://ai.google/responsibility/responsible-ai-practices/)
  * [Testing and Debugging in Machine Learning](https://developers.google.com/machine-learning/testing-debugging)
* [H2O.ai Algorithms](https://github.com/h2oai/h2o-tutorials/blob/master/training/h2o_algos/h2o_algos_cheat_sheet_04_25_17.pdf)![](https://img.shields.io/github/stars/h2oai/h2o-tutorials?style=social)
* [HackerOne Blog](https://www.hackerone.com/vulnerability-and-security-testing-blog)
* [Haptic Networks: How to Perform an AI Audit for UK Organisations](https://www.haptic-networks.com/cyber-security/how-to-perform-an-ai-audit/)
* [Hogan Lovells, The AI Act is coming: EU reaches political agreement on comprehensive regulation of artificial intelligence](https://www.engage.hoganlovells.com/knowledgeservices/news/the-ai-act-is-coming-eu-reaches-political-agreement-on-comprehensive-regulation-of-artificial-intelligence?nav=FRbANEucS95NMLRN47z%2BeeOgEFCt8EGQ71hKXzqW2Ec%3D&key=BcJlhLtdCv6%2FJTDZxvL23TQa3JHL2AIGr93BnQjo2SkGJpG9xDX7S2thDpAQsCconWHAwe6cJTmX%2FZxLGrXbZz2L%2BEiiz68X&uid=iZAX%2FROFT6Q%3D)
* [Hugging Face, The Landscape of ML Documentation Tools](https://huggingface.co/docs/hub/model-card-landscape-analysis)
* [IAPP, Global AI Governance Law and Policy: Canada, EU, Singapore, UK and US](https://iapp.org/media/pdf/resource_center/global_ai_governance_law_policy_series.pdf)
* [ICT Institute: A checklist for auditing AI systems](https://ictinstitute.nl/a-checklist-for-auditing-ai-systems/)
* IEEE: 
  * [IEEE P3119 Standard for the Procurement of Artificial Intelligence and Automated Decision Systems](https://standards.ieee.org/ieee/3119/10729/)
  * [IEEE Std 1012-1998 Standard for Software Verification and Validation](https://people.eecs.ku.edu/~hossein/Teaching/Stds/1012.pdf)
* [Independent Audit of AI Systems](https://forhumanity.center/independent-audit-of-ai-systems/)
* [Identifying and Overcoming Common Data Mining Mistakes](https://support.sas.com/resources/papers/proceedings/proceedings/forum2007/073-2007.pdf)
* [Infocomm Media Development Authority (Singapore) and AI Verify Foundation, Cataloguing LLM Evaluations, Draft for Discussion (October 2023)](https://aiverifyfoundation.sg/downloads/Cataloguing_LLM_Evaluations.pdf)
* [Infocomm Media Development Authority (Singapore), First of its kind Generative AI Evaluation Sandbox for Trusted AI by AI Verify Foundation and IMDA](https://www.imda.gov.sg/resources/press-releases-factsheets-and-speeches/press-releases/2023/generative-ai-evaluation-sandbox)
* [Institute for AI Policy and Strategy (IAPS), AI-Relevant Regulatory Precedents: A Systematic Search Across All Federal Agencies](https://www.iaps.ai/research/ai-relevant-regulatory-precedent)
* [Institute for Public Policy Research (IPPR), Transformed by AI: How Generative Artificial Intelligence Could Affect Work in the UK—And How to Manage It](https://ippr-org.files.svdcdn.com/production/Downloads/Transformed_by_AI_March24_2024-03-27-121003_kxis.pdf)
* [Institute of Internal Auditors: Artificial Intelligence Auditing Framework, Practical Applications, Part A, Special Edition](https://www.theiia.org/globalassets/documents/content/articles/gpi/2017/december/gpi-artificial-intelligence-part-ii.pdf)
* ISACA:
  * [ISACA: Auditing Artificial Intelligence](https://ec.europa.eu/futurium/en/system/files/ged/auditing-artificial-intelligence.pdf)
  * [ISACA: Auditing Guidelines for Artificial Intelligence](https://www.isaca.org/resources/news-and-trends/newsletters/atisaca/2020/volume-26/auditing-guidelines-for-artificial-intelligence)
  * [ISACA: Capability Maturity Model Integration Resources](https://cmmiinstitute.com/)
* [Integrity Institute Report, February 2024, On Risk Assessment and Mitigation for Algorithmic Systems](https://drive.google.com/file/d/1ZMt7igUcKUq00yakCnbxBCcaA7vajAix/view)
* [ISO/IEC 42001:2023, Information technology — Artificial intelligence — Management system](https://www.iso.org/standard/81230.html)
* [Know Your Data](https://knowyourdata.withgoogle.com/)
* [Language Model Risk Cards: Starter Set](https://github.com/leondz/lm_risk_cards)![](https://img.shields.io/github/stars/leondz/lm_risk_cards?style=social)
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
  * [Advancing AI responsibly](https://unlocked.microsoft.com/responsible-ai/)
  * [Azure AI Content Safety](https://azure.microsoft.com/en-us/products/ai-services/ai-content-safety)
     * [Harm categories in Azure AI Content Safety](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/concepts/harm-categories?tabs=warning)
     * [Microsoft Responsible AI Standard, v2](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE5cmFl)
  * [GDPR and Generative AI: A Guide for Public Sector Organizations](https://wwps.microsoft.com/blog/gdpr-genai)
* [MLA, How do I cite generative AI in MLA style?](https://style.mla.org/citing-generative-ai/)
* [model-cards-and-datasheets](https://github.com/ivylee/model-cards-and-datasheets)![](https://img.shields.io/github/stars/ivylee/model-cards-and-datasheets?style=social)
* [NewsGuard AI Tracking Center](https://www.newsguardtech.com/special-reports/ai-tracking-center/)
* [OpenAI, Building an early warning system for LLM-aided biological threat creation](https://openai.com/research/building-an-early-warning-system-for-llm-aided-biological-threat-creation)
* [OpenAI Cookbook, How to implement LLM guardrails](https://cookbook.openai.com/examples/how_to_use_guardrails)
* [OpenAI, Evals](https://github.com/openai/evals)![](https://img.shields.io/github/stars/openai/evals?style=social)
* [Open Data Institute, Understanding data governance in AI: Mapping governance](https://theodi.org/insights/reports/understanding-data-governance-in-ai-mapping-governance/)
* [Open Sourcing Highly Capable Foundation Models](https://www.governance.ai/research-paper/open-sourcing-highly-capable-foundation-models)
* [Organization and Training of a Cyber Security Team](http://ieeexplore.ieee.org/document/1245662)
* [Our Data Our Selves, Data Use Policy](https://ourdataourselves.tacticaltech.org/data-use-policy/)
* [Oxford Commission on AI & Good Governance, AI in the Public Service: From Principles to Practice](https://oxcaigg.oii.ox.ac.uk/wp-content/uploads/sites/11/2021/12/AI-in-the-Public-Service-Final.pdf)
* [PAIR Explorables: Datasets Have Worldviews](https://pair.withgoogle.com/explorables/dataset-worldviews/)
* [Partnership on AI, ABOUT ML Reference Document](https://partnershiponai.org/paper/about-ml-reference-document/)
* [Partnership on AI, PAI’s Guidance for Safe Foundation Model Deployment: A Framework for Collective Action](https://partnershiponai.org/modeldeployment/)
* [Partnership on AI, Responsible Practices for Synthetic Media: A Framework for Collective Action](https://syntheticmedia.partnershiponai.org/)
* [PwC's Responsible AI](https://www.pwc.com/gx/en/issues/data-and-analytics/artificial-intelligence/what-is-responsible-ai.html)
* [RAND Corporation, U.S. Tort Liability for Large-Scale Artificial Intelligence Damages
A Primer for Developers and Policymakers](https://www.rand.org/pubs/research_reports/RRA3084-1.html)
* [RAND Corporation, Analyzing Harms from AI-Generated Images and Safeguarding Online Authenticity](https://www.rand.org/pubs/perspectives/PEA3131-1.html)
* [Ravit Dotan's Projects](https://www.techbetter.ai/projects-1)
* [Real-World Strategies for Model Debugging](https://towardsdatascience.com/strategies-for-model-debugging-aa822f1097ce)
* [RecoSense: Phases of an AI Data Audit – Assessing Opportunity in the Enterprise](https://recosenselabs.com/blog/phases-of-an-ai-data-audit-assessing-opportunity-in-the-enterprise)
* [Robust ML](https://www.robust-ml.org/)
* [Safe and Reliable Machine Learning](https://www.dropbox.com/s/sdu26h96bc0f4l7/FAT19-AI-Reliability-Final.pdf?dl=0)
* [Sample AI Incident Response Checklist](https://bnh-ai.github.io/resources/)
* [Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html)
* [SHRM Generative Artificial Intelligence (AI) Chatbot Usage Policy](https://www.shrm.org/resourcesandtools/tools-and-samples/policies/pages/chatgpt-generative-ai-usage.aspx)
* [Special Competitive Studies Project and Johns Hopkins University Applied Physics Laboratory, Framework for Identifying Highly Consequential AI Use Cases](https://www.scsp.ai/wp-content/uploads/2023/11/SCSP_JHU-HCAI-Framework-Nov-6.pdf)
* [Stanford University, Responsible AI at Stanford: Enabling innovation through AI best practices](https://uit.stanford.edu/security/responsibleai)
* [Synack, The Complete Guide to Crowdsourced Security Testing, Government Edition](https://www.synack.com/wp-content/uploads/2022/09/Crowdsourced-Security-Landscape-Government.pdf)
* [The Rise of Generative AI and the Coming Era of Social Media Manipulation 3.0: Next-Generation Chinese Astroturfing and Coping with Ubiquitous AI](https://www.rand.org/pubs/perspectives/PEA2679-1.html)
* [Taskade: AI Audit PBC Request Checklist Template](https://www.taskade.com/templates/engineering/audit-pbc-request-checklist)
* [Taylor & Francis, AI Policy](https://taylorandfrancis.com/our-policies/ai-policy/)
* [Tech Policy Press - Artificial Intelligence](https://www.techpolicy.press/category/artificial-intelligence/)
* [TechTarget: 9 questions to ask when auditing your AI systems](https://www.techrepublic.com/article/9-questions-to-ask-when-auditing-your-ai-systems/)
* [Troubleshooting Deep Neural Networks](http://josh-tobin.com/assets/pdf/troubleshooting-deep-neural-networks-01-19.pdf)
* [Trustible, Enhancing the Effectiveness of AI Governance Committees](https://www.trustible.ai/post/enhancing-the-effectiveness-of-ai-governance-committees)
* [Twitter Algorithmic Bias Bounty](https://hackerone.com/twitter-algorithmic-bias?type=team)
* [Unite.AI: How to perform an AI Audit in 2023](https://www.unite.ai/how-to-perform-an-ai-audit-in-2023/)
* [University of California, Berkeley, Center for Long-Term Cybersecurity, A Taxonomy of Trustworthiness for Artificial Intelligence](https://cltc.berkeley.edu/wp-content/uploads/2023/12/Taxonomy_of_AI_Trustworthiness_tables.pdf)
* [University of California, Berkeley, Information Security Office, How to Write an Effective Website Privacy Statement](https://security.berkeley.edu/how-write-effective-website-privacy-statement)
* [University of Washington Tech Policy Lab, Data Statements](https://techpolicylab.uw.edu/data-statements/)
* [Warning Signs: The Future of Privacy and Security in an Age of Machine Learning](https://fpf.org/wp-content/uploads/2019/09/FPF_WarningSigns_Report.pdf)
* [When Not to Trust Your Explanations](https://docs.google.com/presentation/d/10a0PNKwoV3a1XChzvY-T1mWudtzUIZi3sCMzVwGSYfM/edit)
* [Why We Need to Know More: Exploring the State of AI Incident Documentation Practices](https://dl.acm.org/doi/fullHtml/10.1145/3600211.3604700)
* [WilmerHale, What Are High-Risk AI Systems Within the Meaning of the EU’s AI Act, and What Requirements Apply to Them?](https://www.wilmerhale.com/en/insights/blogs/wilmerhale-privacy-and-cybersecurity-law/20240717-what-are-highrisk-ai-systems-within-the-meaning-of-the-eus-ai-act-and-what-requirements-apply-to-them)
* [World Economic Forum, Responsible AI Playbook for Investors](https://www.weforum.org/publications/responsible-ai-playbook-for-investors/)
* [World Privacy Forum, AI Governance on the Ground: Canada’s Algorithmic Impact Assessment Process and Algorithm has evolved](https://www.worldprivacyforum.org/2024/08/ai-governance-on-the-ground-series-canada/)
* [World Privacy Forum, Risky Analysis: Assessing and Improving AI Governance Tools](https://www.worldprivacyforum.org/wp-content/uploads/2023/12/WPF_Risky_Analysis_December_2023_fs.pdf)
* [You Created A Machine Learning Application Now Make Sure It's Secure](https://www.oreilly.com/ideas/you-created-a-machine-learning-application-now-make-sure-its-secure)

#### Infographics and Cheat Sheets

* [A-LIGN, ISO 42001 Requirement, NIST SP 800-218A Task, Recommendations and Considerations](https://media.licdn.com/dms/image/D4E22AQGnjMez3xl43A/feedshare-shrink_2048_1536/0/1719511677553?e=1722470400&v=beta&t=N6PjK4U8Slw_aJhVBA3IJ2ZP_pRL_tHdsCzXnmflHuY)
* [AppliedAI Institute, Navigating the EU AI Act: A Process Map for making AI Systems available](https://www.appliedai-institute.de/assets/files/EU_AI_Act_Compliance_Journey.pdf)
* [BCG Robotaxonomy](https://media.licdn.com/dms/image/D4E22AQEthxl6jH6ZvA/feedshare-shrink_800/0/1712824765812?e=1718236800&v=beta&t=Kh3e_uANrmHfkgGT701PNSIRE3W5HfIRnU_W93ACCQk)
* [Center for Security and Emerging Technology (CSET), High Level Comparison of Legislative Perspectives on Artificial Intelligence US vs. EU](https://media.licdn.com/dms/image/D4E22AQHwjdd4LpjhEw/feedshare-shrink_1280/0/1716993189698?e=1720051200&v=beta&t=W6P-OTG25q-w94a-jrXhLTMKv0qrEel_WhbSHXj4wsg)
* [European Data Protection Board (EDPB), Checklist for AI Auditing](https://media.licdn.com/dms/image/D4D22AQFqyom2Oh-v0g/feedshare-shrink_1280/0/1720417814227?e=1724284800&v=beta&t=MPFkWOSAWs_KSfTNInDSJtBUscj_iB2T7f8wJDJAZTQ)
* [Future of Privacy Forum, EU AI Act: A Comprehensive Implementation & Compliance Timeline](https://fpf.org/resource/eu-ai-act-a-comprehensive-implementation-compliance-timeline/)
* [Future of Privacy Forum, The Spectrum of Artificial Intelligence](https://fpf.org/wp-content/uploads/2021/01/FPF_AIEcosystem_illo_03.pdf)
* [IAPP EU AI Act Cheat Sheet](https://iapp.org/media/pdf/resource_center/eu_ai_act_cheat_sheet.pdf)
* [IAPP, EU AI Act Compliance Matrix](https://iapp.org/resources/article/eu-ai-act-compliance-matrix/)
* [IAPP, EU AI Act Compliance Matrix - At a Glance](https://iapp.org/media/pdf/resource_center/eu_ai_act_compliance_matrix_at_a_glance.pdf)
* [Instruction finetuning an LLM from scratch](https://media.licdn.com/dms/image/D5622AQFYQb3j-dLRVw/feedshare-shrink_2048_1536/0/1720876450568?e=1723680000&v=beta&t=_LgUaL6sy0tO9OIu39u5YWPC8cELmINQ6V1_Ug68K9Y)
* [Machine Learning Attack_Cheat_Sheet](https://resources.oreilly.com/examples/0636920415947/-/blob/master/Attack_Cheat_Sheet.png)
* [Oliver Patel's Cheat Sheets](https://www.linkedin.com/in/oliver-patel/recent-activity/images/)
   * [10 Key Pillars for Enterprise AI Governance](https://media.licdn.com/dms/image/D4E22AQF4U8u-baT8hA/feedshare-shrink_1280/0/1709035425012?e=1714608000&v=beta&t=1DhhkNzNFtGg22y8j2KcrrV7SPiCQKZ0-l2uhkSs5zI)
   * [10 Key Questions for AI Risk Assessments](https://media.licdn.com/dms/image/D4E22AQFQ08VpJoOqgw/feedshare-shrink_1280/0/1722404801833?e=1725494400&v=beta&t=FGiXFoDN8m0MIC5jya4vA6G_fADGiCE8b2EY3fiB2jk)
   * [AI Governance in 2023](https://media.licdn.com/dms/image/D4D22AQEUkWMhXlQ8pA/feedshare-shrink_1280/0/1702536206607?e=1714608000&v=beta&t=ukGzNValTfCOyjR4XUt9dnemmdzv0eAi4oV5Zh8XgyI)
   * [Canada AI Law & Policy Cheat Sheet](https://media.licdn.com/dms/image/D4D22AQG-A4WvORqoGA/feedshare-shrink_1280/0/1713914692450?e=1717027200&v=beta&t=WAGqCMsjM6vtpxKGQmTcG_sftnAOOrEsXOuEua8QwMg)
   * [China AI Law Cheat Sheet](https://media.licdn.com/dms/image/D4E22AQF-6pEvkEG6PQ/feedshare-shrink_1280/0/1703158308976?e=1714608000&v=beta&t=DA3U5tCyGA3l9jLK6h_USn-76z9espPWwr2BNmNc-v8)
   * [Definitions, Scope & Applicability EU AI Act Cheat Sheet Series, Part 1](https://media.licdn.com/dms/image/D4D22AQFkbaPSUPwlcQ/feedshare-shrink_1280/0/1717064332181?e=1720051200&v=beta&t=OQ0BAM9Kqmej9Sm2PhmeT62XFj3k_G-aIi7SAWMWdrk)
   * [EU AI Act Cheat Sheet Series 1, Definitions, Scope & Applicability](https://media.licdn.com/dms/image/D4D22AQFkbaPSUPwlcQ/feedshare-shrink_1280/0/1717064332181?e=1721260800&v=beta&t=TBzLSLAMyWk5w0eV_78C-LcRomIxxiNsvYO2ur9--DM)
   * [EU AI Act Cheat Sheet Series 2, Prohibited AI Systems](https://media.licdn.com/dms/image/D4E22AQEuGzSfoRKYbA/feedshare-shrink_2048_1536/0/1717678634560?e=1720656000&v=beta&t=okE0jTZJhnrJRu_LWn9W3sjq2mE0mV5fcrZGQ47Pz8c)
   * [EU AI Act Cheat Sheet Series 3, High-Risk AI Systems](https://media.licdn.com/dms/image/D4E22AQHp9idr6g4r9w/feedshare-shrink_1280/0/1718350012563?e=1721260800&v=beta&t=HCUVfqf35znT3TdSULj0-I0qNSqkJgNDFSu1eC00usQ)
   * [EU AI Act Cheat Sheet Series 4, Requirements for Providers](https://media.licdn.com/dms/image/D4E22AQE41Al9Cd82Og/feedshare-shrink_1280/0/1718871651910?e=1721865600&v=beta&t=a8-nuNaoFotHyap1sE0EE6ui_cdYR25UhztlwICGXWU)
   * [EU AI Act Cheat Sheet Series 5, Requirements for Deployers](https://media.licdn.com/dms/image/D4E22AQHNWQbnsnDInw/feedshare-shrink_1280/0/1720096884880?e=1723075200&v=beta&t=9Dmb8bGOAPY2nEQm8cdYo7Ozn1PPPDBi3VquJcRdQQQ)
   * [EU AI Act Cheat Sheet Series 6, General-Purpose AI Models](https://media.licdn.com/dms/image/D4E22AQGhCpBi8toi3w/feedshare-shrink_1280/0/1720572248173?e=1723680000&v=beta&t=PPQSkqO2KYgsjIZv8uUfDrdW5DdBZVwO56U8OVecggo)
   * [EU AI Act Cheat Sheet Series 7, Compliance & Conformity Assessment](https://media.licdn.com/dms/image/D4E22AQFvIIneLanW5Q/feedshare-shrink_1280/0/1721115234718?e=1724284800&v=beta&t=kmRU5o5s_MnUC0urbyVglhPPRpZ9Y56S8nk4PQTtKWo)
   * [EU AI Act Cheat Sheet Series 8, Governance & Enforcement](https://media.licdn.com/dms/image/D4E22AQHg4PJRbbsWFQ/feedshare-shrink_1280/0/1721985339864?e=1725494400&v=beta&t=etLmpzFMO8ifzU2HloNqYQui5n8epQJufn0KDSIR0Yg)
   * [India AI Policy Cheat Sheet](https://media.licdn.com/dms/image/D4E22AQHi3zKIJHYxuA/feedshare-shrink_1280/0/1715251459456?e=1721260800&v=beta&t=eJGeYvud7M02i4IyyQhzQldOkC18HawL7kqVjBE2Qu8)
   * [Governance Audit, Model Audit, and Application Audit](https://media.licdn.com/dms/image/D4E22AQFc3N6PSYkyXQ/feedshare-shrink_2048_1536/0/1680540832478?e=1714608000&v=beta&t=NuQbcm7pQrwhy2ldD8HdzqHKt6xR8W7EI9OxwZ8OvbU)
   * [Gulf Countries AI Policy Cheat Sheet](https://media.licdn.com/dms/image/D4E22AQGFbfOnjgtiMg/feedshare-shrink_1280/0/1708519732711?e=1714608000&v=beta&t=BaJm411n2QWNm69uUEnIgbZxZqYf0YuWfBQHXXWaS-c)
   * [Singapore AI Policy Cheat Sheet](https://media.licdn.com/dms/image/D4D22AQFwuZiA4pVL0g/feedshare-shrink_1280/0/1711403787594?e=1714608000&v=beta&t=ka9xDLBo6jIHbsG6HJ0EcbWQjV9phGm84X-1LvBYklA)
   * [UK AI Policy Cheat Sheet](https://media.licdn.com/dms/image/D4E22AQHoHS_kht7g6w/feedshare-shrink_1280/0/1707393791731?e=1714608000&v=beta&t=CkyVLhOjN5mGVc0uuIDFbDzNcItYB1CdENp5NtnDITQ)
* [Open Source Audit Tooling (OAT) Landscape](https://tools.auditing-ai.com/)
* [Phil Lee, AI Act: Difference between AI systems and AI models](https://media.licdn.com/dms/image/D4E22AQEZcCGPcsLyDw/feedshare-shrink_1280/0/1713434378996?e=1716422400&v=beta&t=D5U544kF8BoUCnOYCxLdbsPAjBGcYz35I4zfqBomhcA)
* [Phil Lee, AI Act: Meet the regulators! (Arts 30, 55b, 56 and 59)](https://media.licdn.com/dms/image/D4E22AQF8Z1jGFR9YfQ/feedshare-shrink_1280/0/1709291091908?e=1716422400&v=beta&t=dJILHhKMXPRA107rteuwo1HbKbjw4I_WeM2vM7Ded7w)
* [Phil Lee, How the AI Act applies to integrated generative AI](https://media.licdn.com/dms/image/D4E22AQHakzcE_XHzDQ/feedshare-shrink_2048_1536/0/1710856943607?e=1716422400&v=beta&t=D8eeYdCVQ907xn0Idc_W26ZV2WFvcN-KizA9exBLuEI)
* [Phil Lee, Overview of AI Act requirements for deployers of high risk AI systems](https://media.licdn.com/dms/image/D4E22AQG_A7ufJs9zUA/feedshare-shrink_2048_1536/0/1710279179924?e=1716422400&v=beta&t=XdafTB5kQRNKmp5dVL4c5S04Nb2-YKGEuemFA0c_rzg)
* [Phil Lee, Overview of AI Act requirements for providers of high risk AI systems](https://media.licdn.com/dms/image/D4E22AQGvM1sNyEV1Hw/feedshare-shrink_2048_1536/0/1709811083311?e=1716422400&v=beta&t=YB0e3BO82JwaupHFkxlQIWiBnfFwRcK8qfIs5_UhmKw)
* [Pivot to AI](https://pivot-to-ai.com/)
* [Purpose and Means AI Explainer Series - issue #4 - Navigating the EU AI Act](https://media.licdn.com/dms/image/D4D22AQEXHwX7q4WUxw/feedshare-shrink_2048_1536/0/1715790151074?e=1718841600&v=beta&t=V9npUpSkYrCWoGLY9aNjtpLlS27SAb2lEwPXjGmw0XQ)
* [Trustible, Is It AI? How different laws & frameworks define AI](https://www.trustible.ai/post/is-it-ai-how-different-laws-frameworks-define-ai)
* [What Access Protections Do AI Companies Provide for Independent Safety Research?](https://media.licdn.com/dms/image/D5622AQELjohQn4Y8KQ/feedshare-shrink_2048_1536/0/1721718399115?e=1724889600&v=beta&t=y2P0LUXh4X2M61eosUlGKlXPl2BcJkMWMVs5-o3poSk)

#### AI Red-Teaming Resources

##### Papers
* [Exploiting Novel GPT-4 APIs](https://arxiv.org/abs/2312.14302)
* [Identifying and Eliminating CSAM in Generative ML Training Data and Models](https://purl.stanford.edu/kh752sm9123)
* [Jailbreaking Black Box Large Language Models in Twenty Queries](https://arxiv.org/abs/2310.08419)
* [LLM Agents can Autonomously Exploit One-day Vulnerabilities](https://arxiv.org/abs/2404.08144)
  * [No, LLM Agents can not Autonomously Exploit One-day Vulnerabilities](https://struct.github.io/auto_agents_1_day.html)
* [Red Teaming Language Models to Reduce Harms: Methods, Scaling Behaviors, and Lessons Learned](https://arxiv.org/abs/2209.07858)
* [Red Teaming of Advanced Information Assurance Concepts](https://ieeexplore.ieee.org/document/821513)

##### Tools and Guidance
* [@dotey on X/Twitter exploring GPT prompt security and prevention measures](https://x.com/dotey/status/1724623497438155031?s=20)
* [0xeb / GPT-analyst](https://github.com/0xeb/gpt-analyst/)![](https://img.shields.io/github/stars/0xeb/gpt-analyst?style=social)
* [0xk1h0 / ChatGPT "DAN" (and other "Jailbreaks")](https://github.com/0xk1h0/ChatGPT_DAN)![](https://github.com/0xk1h0/ChatGPT_DAN)![](https://img.shields.io/github/stars/0xk1h0/ChatGPT_DAN?style=social)
* [ACL 2024 Tutorial: Vulnerabilities of Large Language Models to Adversarial Attacks](https://llm-vulnerability.github.io/)
* [Azure's PyRIT](https://github.com/Azure/PyRIT)![](https://img.shields.io/github/stars/Azure/PyRIT?style=social)
* [Berkeley Center for Long-Term Cybersecurity (CLTC), https://cltc.berkeley.edu/publication/benchmark-early-and-red-team-often-a-framework-for-assessing-and-managing-dual-use-hazards-of-ai-foundation-models/](https://cltc.berkeley.edu/publication/benchmark-early-and-red-team-often-a-framework-for-assessing-and-managing-dual-use-hazards-of-ai-foundation-models/)
* [CDAO frameworks, guidance, and best practices for AI test & evaluation](https://gitlab.jatic.net/home/frameworks)
* [ChatGPT_system_prompt](https://github.com/LouisShark/chatgpt_system_prompt)![](https://img.shields.io/github/stars/LouisShark/chatgpt_system_prompt?style=social)
* [coolaj86 / Chat GPT "DAN" (and other "Jailbreaks")](https://gist.github.com/coolaj86/6f4f7b30129b0251f61fa7baaa881516)![](https://img.shields.io/github/stars/coolaj86?style=social)
* [CSET, What Does AI-Red Teaming Actually Mean?](https://cset.georgetown.edu/article/what-does-ai-red-teaming-actually-mean/)
* [DAIR Prompt Engineering Guide](https://www.promptingguide.ai/)
  * [DAIR Prompt Engineering Guide GitHub](https://github.com/dair-ai/Prompt-Engineering-Guide)![](https://img.shields.io/github/stars/dair-ai/Prompt-Engineering-Guide?style=social)
* [Extracting Training Data from ChatGPT](https://not-just-memorization.github.io/extracting-training-data-from-chatgpt.html)
* [Frontier Model Forum: What is Red Teaming?](https://www.frontiermodelforum.org/uploads/2023/10/FMF-AI-Red-Teaming.pdf)
* [Generative AI Red Teaming Challenge: Transparency Report 2024](https://drive.google.com/file/d/1JqpbIP6DNomkb32umLoiEPombK2-0Rc-/view)
* [HackerOne, An Emerging Playbook for AI Red Teaming with HackerOne](https://www.hackerone.com/thought-leadership/ai-safety-red-teaming)
* [Humane Intelligence, SeedAI, and DEFCON AI Village, Generative AI Red Teaming Challenge: Transparency Report 2024](https://drive.google.com/file/d/1JqpbIP6DNomkb32umLoiEPombK2-0Rc-/view)
* [In-The-Wild Jailbreak Prompts on LLMs](https://github.com/verazuo/jailbreak_llms)![](https://img.shields.io/github/stars/verazuo/jailbreak_llms?style=social)
* [leeky: Leakage/contamination testing for black box language models](https://github.com/mjbommar/leeky)![](https://img.shields.io/github/stars/mjbommar/leeky?style=social)
* [LLM Security & Privacy](https://github.com/chawins/llm-sp)![](https://img.shields.io/github/stars/chawins/llm-sp?style=social)
* [Membership Inference Attacks and Defenses on Machine Learning Models Literature](https://github.com/HongshengHu/membership-inference-machine-learning-literature)![](https://img.shields.io/github/stars/HongshengHu/membership-inference-machine-learning-literature?style=social)
* [Learn Prompting, Prompt Hacking](https://learnprompting.org/docs/category/-prompt-hacking)
  * [MiesnerJacob / learn-prompting, Prompt Hacking](https://github.com/MiesnerJacob/learn-prompting/blob/main/08.%F0%9F%94%93%20Prompt%20Hacking.ipynb)![](https://img.shields.io/github/stars/MiesnerJacob/learn-prompting?style=social)
* [Lakera AI's Gandalf](https://gandalf.lakera.ai/)
* [leondz / garak](https://github.com/leondz/garak)![](https://img.shields.io/github/stars/leondz/garak?style=social)
* [Microsoft AI Red Team building future of safer AI](https://www.microsoft.com/en-us/security/blog/2023/08/07/microsoft-ai-red-team-building-future-of-safer-ai/)
* [OpenAI Red Teaming Network](https://openai.com/blog/red-teaming-network)
* [r/ChatGPTJailbreak](https://www.reddit.com/r/ChatGPTJailbreak/)
  * [developer mode fixed](https://www.reddit.com/r/ChatGPTJailbreak/comments/144905t/developer_mode_fixed/)
* [Y Combinator, ChatGPT Grandma Exploit](https://news.ycombinator.com/item?id=35630801)

#### Generative AI Explainability

* [Backpack Language Models](https://arxiv.org/pdf/2305.16765)
* [Jay Alammar, Finding the Words to Say: Hidden State Visualizations for Language Models](https://jalammar.github.io/hidden-states/)
* [Jay Alammar, Interfaces for Explaining Transformer Language Models](https://jalammar.github.io/explaining-transformers/)
* [Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html)
* [The Remarkable Robustness of LLMs: Stages of Inference?](https://arxiv.org/pdf/2406.19384v1)

### Conferences and Workshops

This section is for conferences, workshops and other major events related to responsible ML.

* [AAAI Conference on Artificial Intelligence](https://aaai.org/conference/aaai/)
* [ACM FAccT (Fairness, Accountability, and Transparency)](https://facctconference.org/)
  * [FAT/ML (Fairness, Accountability, and Transparency in Machine Learning)](https://www.fatml.org/) 
* [ACM Conference on Equity and Access in Algorithms, Mechanisms, and Optimization (EAAMO)](https://eaamo.org/)
* [AIES (AAAI/ACM Conference on AI, Ethics, and Society)](https://www.aies-conference.com/) 
* [Black in AI](https://blackinai.github.io/#/)
* [Computer Vision and Pattern Recognition (CVPR)](https://thecvf.com/)
* [Evaluating Generative AI Systems: the Good, the Bad, and the Hype (April 15, 2024)](https://dc-workshop.genlaw.org/)
* [IAPP, AI Governance Global 2024, June 4-7, 2024](https://iapp.org/conference/iapp-ai-governance-global/)
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
* [Mission Control AI, Booz Allen Hamilton, and The Intellectual Forum at Jesus College, Cambridge, The 2024 Leaders in Responsible AI Summit, March 22, 2024](https://usemissioncontrol.com/summit/)
* [NAACL 24 Tutorial: Explanations in the Era of Large Language Models](https://explanation-llm.github.io/)
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
 * [OECD.AI, Building the foundations for collaboration: The OECD-African Union AI Dialogue](https://oecd.ai/en/wonk/oecd-au-ai-dialogue)
 * [Oxford Generative AI Summit Slides](https://drive.google.com/drive/folders/1WQPaL-ozhZbZaDichFm4gWZQpGwriT32)

### Official Policy, Frameworks, and Guidance

This section serves as a repository for policy documents, regulations, guidelines, and recommendations that govern the ethical and responsible use of artificial intelligence and machine learning technologies. From international legal frameworks to specific national laws, the resources cover a broad spectrum of topics such as fairness, privacy, ethics, and governance. 

#### Australia
* [National framework for the assurance of artificial intelligence in government](https://www.finance.gov.au/sites/default/files/2024-06/National-framework-for-the-assurance-of-AI-in-government.pdf)
* [Testing the Reliability, Validity, and Equity of Terrorism Risk Assessment Instruments](https://www.homeaffairs.gov.au/foi/files/2023/fa-230400097-document-released-part-1.PDF)

#### Canada
* [A Regulatory Framework for AI: Recommendations for PIPEDA Reform](https://www.priv.gc.ca/en/about-the-opc/what-we-do/consultations/completed-consultations/consultation-ai/reg-fw_202011/)
* [Developing Financial Sector Resilience in a Digital World: Selected Themes in Technology and Related Risks](https://www.osfi-bsif.gc.ca/Eng/Docs/tchrsk.pdf)
* [Directive on Automated Decision Making (Canada)](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=32592)
* [(Draft Guideline) E-23 – Model Risk Management](https://www.osfi-bsif.gc.ca/en/guidance/guidance-library/draft-guideline-e-23-model-risk-management)
* [Health Canada, Transparency for machine learning-enabled medical devices: Guiding principles](https://www.canada.ca/en/health-canada/services/drugs-health-products/medical-devices/transparency-machine-learning-guiding-principles.html)

#### France
* [Gouvernance des algorithmes d’intelligence artificielle dans le secteur financier (France)](https://acpr.banque-france.fr/sites/default/files/medias/documents/20200612_gouvernance_evaluation_ia.pdf)

#### Germany
* [Bundesamt für Sicherheit in der Informationstechnik, Generative AI Models - Opportunities and Risks for Industry and Authorities](https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/KI/Generative_AI_Models.html)

#### Netherlands
* [Autoriteit Persoonsgegevens, scraping bijna altijd illegal (Dutch Data Protection Authority, "Scraping is always illegal")](https://www.autoriteitpersoonsgegevens.nl/actueel/ap-scraping-bijna-altijd-illegaal)
* [General principles for the use of Artificial Intelligence in the financial sector](https://www.dnb.nl/media/jkbip2jc/general-principles-for-the-use-of-artificial-intelligence-in-the-financial-sector.pdf)

#### New Zealand
* [AI Safety Institute (AISI), Advanced AI evaluations at AISI: May update](https://www.aisi.gov.uk/work/advanced-ai-evaluations-may-update)
* [Algorithm Charter for Aotearoa New Zealand](https://data.govt.nz/assets/data-ethics/algorithm/Algorithm-Charter-2020_Final-English-1.pdf)
* [Callaghan Innovation, EU AI Fact Sheet 4, High-risk AI systems](https://www.callaghaninnovation.govt.nz/assets/documents/Resource-EU-AI-Act-Support/EU-AI-Policy-Fact-Sheet-4-High-Risk-AI-Systems.pdf)

#### Singapore
* [Personal Data Protection Commission (PDPC), Companion to the Model AI Governance Framework – Implementation and Self-Assessment Guide for Organizations](https://www.pdpc.gov.sg/-/media/files/pdpc/pdf-files/resource-for-organisation/ai/sgisago.pdf)
* [Personal Data Protection Commission (PDPC), Compendium of Use Cases: Practical Illustrations of the Model AI Governance Framework](https://www.pdpc.gov.sg/-/media/files/pdpc/pdf-files/resource-for-organisation/ai/sgaigovusecases.pdf)
* [Personal Data Protection Commission (PDPC), Model Artificial Intelligence Governance Framework (Second Edition)](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Resource-for-Organisation/AI/SGModelAIGovFramework2.pdf)
* [Personal Data Protection Commission (PDPC), Privacy Enhancing Technology (PET): Proposed Guide on Synthetic Data Generation](https://www.pdpc.gov.sg/-/media/files/pdpc/pdf-files/other-guides/proposed-guide-on-synthetic-data-generation.pdf)

#### United Kingdom
* [AI Safety Institute (AISI), Safety cases at AISI](https://www.aisi.gov.uk/work/safety-cases-at-aisi)
* [Department for Science, Innovation and Technology and AI Safety Institute, International Scientific Report on the Safety of Advanced AI](https://www.gov.uk/government/publications/international-scientific-report-on-the-safety-of-advanced-ai)
* [Department for Science, Innovation and Technology, The Bletchley Declaration by Countries Attending the AI Safety Summit, 1-2 November 2023](https://www.gov.uk/government/publications/ai-safety-summit-2023-the-bletchley-declaration/the-bletchley-declaration-by-countries-attending-the-ai-safety-summit-1-2-november-2023)
* [Department for Science, Innovation and Technology, Frontier AI: capabilities and risks - discussion paper (United Kingdom)](https://www.gov.uk/government/publications/frontier-ai-capabilities-and-risks-discussion-paper)
* [Department for Science, Innovation and Technology, Guidance, Introduction to AI Assurance](https://www.gov.uk/government/publications/introduction-to-ai-assurance)
* [National Physical Laboratory (NPL), Beginner's guide to measurement GPG118](https://www.npl.co.uk/gpgs/beginners-guide-to-measurement)
* [Online Harms White Paper: Full government response to the consultation (United Kingdom)](https://www.gov.uk/government/consultations/online-harms-white-paper)
* [The Public Sector Bodies (Websites and Mobile Applications) Accessibility Regulations 2018](https://www.legislation.gov.uk/uksi/2018/852/contents/made)

#### United States (Federal Government)

**Consumer Financial Protection Bureau (CFPB)**  
* [12 CFR Part 1002 - Equal Credit Opportunity Act (Regulation B)](https://www.consumerfinance.gov/policy-compliance/rulemaking/regulations/1002/)
* [Chatbots in consumer finance](https://www.consumerfinance.gov/data-research/research-reports/chatbots-in-consumer-finance/chatbots-in-consumer-finance/)
* [Innovation spotlight: Providing adverse action notices when using AI/ML models](https://www.consumerfinance.gov/about-us/blog/innovation-spotlight-providing-adverse-action-notices-when-using-ai-ml-models/)

**Commodity Futures Trading Commission (CFTC)**  
* [A Primer on Artificial Intelligence in Securities Markets](https://www.cftc.gov/media/2846/LabCFTC_PrimerArtificialIntelligence102119/download)
* [Responsible Artificial Intelligence in Financial Markets](https://www.cftc.gov/PressRoom/PressReleases/8905-24)

**Congressional Research Service** 
* [Artificial Intelligence: Overview, Recent Advances, and Considerations for the 118th Congress](https://www.energy.gov/sites/default/files/2023-09/Artificial%20Intelligence%20Overview%2C%20Recent%20Advances%2C%20and%20Considerations%20for%20the%20118th%20Congress.pdf)

**Copyright Office**
* [Copyright and Artificial Intelligence, Part 1: Digital Replicas, July 2024](https://www.copyright.gov/ai/Copyright-and-Artificial-Intelligence-Part-1-Digital-Replicas-Report.pdf)

**Data.gov**
* [Privacy Policy and Data Policy](https://data.gov/privacy-policy/)
 
**Defense Advanced Research Projects Agency (DARPA)**
* [Explainable Artificial Intelligence (XAI) (Archived)](https://www.darpa.mil/program/explainable-artificial-intelligence)  

**Defense Technical Information Center**  
* [Computer Security Technology Planning Study, October 1, 1972](https://apps.dtic.mil/sti/citations/AD0758206)

**Department of Commerce**
* [Artificial intelligence](https://www.commerce.gov/issues/artificial-intelligence)
* [Intellectual property](https://www.commerce.gov/issues/intellectual-property)
* [National Institute of Standards and Technology (NIST)](https://www.nist.gov/)
  * [AI 100-1 Artificial Intelligence Risk Management Framework (NIST AI RMF 1.0)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf)
  * [De-identification Tools](https://www.nist.gov/itl/applied-cybersecurity/privacy-engineering/collaboration-space/focus-areas/de-id/tools)
  * [NIST AI 100-2 E2023: Adversarial Machine Learning: A Taxonomy and Terminology of Attacks and Mitigations](https://csrc.nist.gov/pubs/ai/100/2/e2023/final)
  * [Assessing Risks and Impacts of AI (ARIA)](https://ai-challenges.nist.gov/aria/library)
  * [Four Principles of Explainable Artificial Intelligence, Draft NISTIR 8312, 2020-08-17](https://www.nist.gov/system/files/documents/2020/08/17/NIST%20Explainable%20AI%20Draft%20NISTIR8312%20%281%29.pdf)
  * [Four Principles of Explainable Artificial Intelligence, NISTIR 8312, 2021-09-29](https://www.nist.gov/publications/four-principles-explainable-artificial-intelligence)
  * [Engineering Statistics Handbook](https://doi.org/10.18434/M32189)
  * [Measurement Uncertainty](https://www.nist.gov/itl/sed/topic-areas/measurement-uncertainty)
    * [International Bureau of Weights and Measures (BIPM), Evaluation of measurement data—Guide to the expression of uncertainty in measurement](https://www.bipm.org/documents/20126/2071204/JCGM_100_2008_E.pdf/cb0ef43f-baa5-11cf-3f85-4dcd86f77bd6)
  * [NIST Special Publication 800-30 Revision 1, Guide for Conducting Risk Assessments](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf)
  * [Psychological Foundations of Explainability and Interpretability in Artificial Intelligence](https://nvlpubs.nist.gov/nistpubs/ir/2021/NIST.IR.8367.pdf)
* [National Telecommunications and Information Administration (NTIA)](https://www.ntia.gov/)
  * [AI Accountability Policy Report](https://www.ntia.gov/issues/artificial-intelligence/ai-accountability-policy-report)
  * [Internet Policy Task Force, Commercial Data Privacy and Innovation in the Internet Economy: A Dynamic Policy Framework](https://www.ntia.doc.gov/files/ntia/publications/iptf_privacy_greenpaper_12162010.pdf)

**Department of Defense**  
* [AI Principles: Recommendations on the Ethical Use of Artificial Intelligence](https://media.defense.gov/2019/Oct/31/2002204458/-1/-1/0/DIB_AI_PRINCIPLES_PRIMARY_DOCUMENT.PDF)
* [Audit of Governance and Protection of Department of Defense Artificial Intelligence Data and Technology](https://media.defense.gov/2020/Jul/01/2002347967/-1/-1/1/DODIG-2020-098.PDF)
* [Chief Data and Artificial Intelligence Officer (CDAO) Assessment and Assurance](https://gitlab.jatic.net/home)
    * [RAI Toolkit](https://rai.tradewindai.com/)
* Department of the Army
  * [Proceedings of the Thirteenth Annual U.S. Army Operations Research Symposium, Volume 1, October 29 to November 1, 1974](https://apps.dtic.mil/sti/pdfs/ADA007126.pdf)
* [Guidelines for secure AI system development](https://media.defense.gov/2023/Nov/27/2003346994/-1/-1/0/GUIDELINES-FOR-SECURE-AI-SYSTEM-DEVELOPMENT.PDF)

**Department of Education**
* [Office of Educational Technology](https://tech.ed.gov/)
  * [Designing for Education with Artificial Intelligence: An Essential Guide for Developers](https://tech.ed.gov/designing-for-education-with-artificial-intelligence/)

**Department of Energy** 
* [Artificial Intelligence and Technology Office](https://www.energy.gov/ai/artificial-intelligence-technology-office)
  * [AI Risk Management Playbook (AIRMP)](https://www.energy.gov/ai/doe-ai-risk-management-playbook-airmp)
  * [AI Use Case Inventory (DOE Use Cases Releasable to Public in Accordance with E.O. 13960)](https://www.energy.gov/sites/default/files/2023-07/DOE_2023_AI_Use_Case_Inventory_0.pdf)
  * [Digital Climate Solutions Inventory](https://www.energy.gov/sites/default/files/2022-09/Digital_Climate_Solutions_Inventory.pdf)
  * [Generative Artificial Intelligence Reference Guide](https://www.energy.gov/sites/default/files/2024-06/Generative%20AI%20Reference%20Guide%20v2%206-14-24.pdf)

**Department of Homeland Security**  
* [Safety and Security Guidelines for Critical Infrastructure Owners and Operators](https://www.dhs.gov/publication/safety-and-security-guidelines-critical-infrastructure-owners-and-operators)
* [Use of Commercial Generative Artificial Intelligence (AI) Tools](https://www.dhs.gov/sites/default/files/2023-11/23_1114_cio_use_generative_ai_tools.pdf)

**Department of Justice**  
* [Privacy Act of 1974](https://www.justice.gov/opcl/privacy-act-1974)
* [Overview of The Privacy Act of 1974 (2020 Edition)](https://www.justice.gov/opcl/overview-privacy-act-1974-2020-edition)

**Department of the Treasury**  
* [Managing Artificial Intelligence-Specific Cybersecurity Risks in the Financial Services Sector, March 2024](https://home.treasury.gov/system/files/136/Managing-Artificial-Intelligence-Specific-Cybersecurity-Risks-In-The-Financial-Services-Sector.pdf)

**Equal Employment Opportunity Commission (EEOC)**
* [EEOC Letter (from U.S. senators re: hiring software)](https://www.bennet.senate.gov/public/_cache/files/0/a/0a439d4b-e373-4451-84ed-ba333ce6d1dd/672D2E4304D63A04CC3465C3C8BF1D21.letter-to-chair-dhillon.pdf)
* [Questions and Answers to Clarify and Provide a Common Interpretation of the Uniform Guidelines on Employee Selection Procedures](https://www.eeoc.gov/laws/guidance/questions-and-answers-clarify-and-provide-common-interpretation-uniform-guidelines)

**Executive Office of the President of the United States**
* [Obama White House Archives, Consumer Data Privacy in a Networked World: A Framework for Protecting Privacy and Promoting Innovation in the Global Digital Economy, February 2012](https://obamawhitehouse.archives.gov/sites/default/files/privacy-final.pdf)
* [Office of Management and Budget (OMB)](https://www.whitehouse.gov/omb/)
  * [Guidance for Regulation of Artificial Intelligence Applications, November 2020](https://www.whitehouse.gov/wp-content/uploads/2020/11/M-21-06.pdf)
* [Office of Science and Technology Policy (OSTP)](https://www.whitehouse.gov/ostp/)
  * [Blueprint for an AI Bill of Rights: Making Automated Systems Work for the American People](https://www.whitehouse.gov/ostp/ai-bill-of-rights/)
  * [National Science and Technology Council (NSTC)](https://www.whitehouse.gov/ostp/ostps-teams/nstc/)
    * [Select Committee on Artificial Intelligence, National Artificial Intelligence Research and Development Strategic Plan 2023 Update](https://www.whitehouse.gov/wp-content/uploads/2023/05/National-Artificial-Intelligence-Research-and-Development-Strategic-Plan-2023-Update.pdf)    

**Federal Deposit Insurance Corporation (FDIC)**  
* [Supervisory Guidance on Model Risk Management](https://www.fdic.gov/news/financial-institution-letters/2017/fil17022a.pdf)

**Federal Housing Finance Agency (FHFA)**
* [Advisory Bulletin AB 2013-07 Model Risk Management Guidance](https://www.fhfa.gov/sites/default/files/2023-03/ab_2013-07_model_risk_management_guidance.pdf)

**Federal Reserve**
* [Supervisory Guidance on Model Risk Management](https://www.federalreserve.gov/supervisionreg/srletters/sr1107a1.pdf)

**Federal Trade Commission (FTC)**
* [Artificial Intelligence/Machine Learning (AI/ML)-Based: Software as a Medical Device (SaMD) Action Plan, updated January 2021](https://www.fda.gov/media/145022/download)
* [Business Blog](https://www.ftc.gov/business-guidance/blog):
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
* [Children's Online Privacy Protection Rule ("COPPA")](https://www.ftc.gov/legal-library/browse/rules/childrens-online-privacy-protection-rule-coppa)
* [Privacy Policy](https://www.ftc.gov/policy-notices/privacy-policy)
* [Software as a Medical Device (SAMD) guidance (December 8, 2017)](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/software-medical-device-samd-clinical-evaluation)

**Government Accountability Office (GAO)** 
* [Artificial Intelligence: An Accountability Framework for Federal Agencies and Other Entities, GAO-21-519SP](https://www.gao.gov/products/gao-21-519sp) 

**National Security Agency (NSA)**
* [Central Security Service, Artificial Intelligence Security Center](https://www.nsa.gov/AISC/)
  
**National Security Commission on Artificial Intelligence**  
* [Final Report](https://assets.foleon.com/eu-central-1/de-uploads-7e3kk3/48187/nscai_full_report_digital.04d6b124173c.pdf)

**Office of the Comptroller of the Currency (OCC)**  
* [2021 Model Risk Management Handbook](https://www.occ.gov/publications-and-resources/publications/comptrollers-handbook/files/model-risk-management/index-model-risk-management.html)

**Office of the Director of National Intelligence (ODNI)** 
* [The AIM Initiative: A Strategy for Augmenting Intelligence Using Machines](https://www.dni.gov/files/ODNI/documents/AIM-Strategy.pdf)
* [Principles of Artificial Intelligence Ethics for the Intelligence Community](https://www.intel.gov/principles-of-artificial-intelligence-ethics-for-the-intelligence-community)
 
**Securities and Exchange Commission (SEC)**  
* [SEC Charges Two Investment Advisers with Making False and Misleading Statements About Their Use of Artificial Intelligence](https://www.sec.gov/news/press-release/2024-36)
 
**United States Patent and Trademark Office (USPTO)**
* [Public Views on Artificial Intelligence and Intellectual Property Policy](https://www.uspto.gov/sites/default/files/documents/USPTO_AI-Report_2020-10-07.pdf)  

**United States Web Design System (USWDS)**
* [Design principles](https://designsystem.digital.gov/design-principles/)

#### United States (State Governments) 

**California**
* [California Consumer Privacy Act (CCPA)](https://oag.ca.gov/privacy/ccpa)
* [California Department of Justice, How to Read a Privacy Policy](https://www.oag.ca.gov/privacy/facts/online-privacy/privacy-policy)
* [California Department of Technology, GenAI Executive Order](https://cdt.ca.gov/technology-innovation/artificial-intelligence-community/genai-executive-order/)
* [California Privacy Rights Act (CPRA)](https://www.oag.ca.gov/system/files/initiatives/pdfs/19-0021A1%20%28Consumer%20Privacy%20-%20Version%203%29_1.pdf)
* [Department of Technology, Office of Information Security, Generative Artificial Intelligence Risk Assessment, SIMM 5305-F, March 2024](https://cdt.ca.gov/wp-content/uploads/2024/03/SIMM-5305-F-Generative-Artificial-Intelligence-Risk-Assessment-FINAL.pdf)

**Mississippi**
* [Mississippi Department of Education, Artificial Intelligence Guidance for K-12 Classrooms](https://www.mdek12.org/sites/default/files/Offices/MDE/OTSS/DL/ai_guidance_final.pdf)

**New York**
* [New York City Automated Decision Systems Task Force Report (November 2019)](https://www.nyc.gov/assets/adstaskforce/downloads/pdf/ADS-Report-11192019.pdf)
* [RE: Use of External Consumer Data and Information Sources in Underwriting for Life Insurance](https://www.dfs.ny.gov/industry_guidance/circular_letters/cl2019_01)

**Texas**
* [Federal Reserve Bank of Dallas, Regulation B, Equal Credit Opportunity, Credit Scoring Interpretations: Withdrawl of Proposed Business Credit Amendments, June 3, 1982](https://fraser.stlouisfed.org/files/docs/historical/frbdal/circulars/frbdallas_circ_19820603_no82-063.pdf)

**Utah**
* [Questions from the Commission on Protecting Privacy and Preventing Discrimination](https://auditor.utah.gov/wp-content/uploads/sites/6/2021/02/Office-of-the-State-Auditor-Questions-to-help-Procuring-Agencies-_-Entities-with-Software-Procurement-Feb-1-2021-Final.pdf)

#### International and Multilateral Frameworks

#### European Union Policies and Regulations

#### European Commission and Parliament
* [Assessment List for Trustworthy Artificial Intelligence (ALTAI) for self-assessment - Shaping Europe’s digital future - European Commission](https://ec.europa.eu/digital-single-market/en/news/assessment-list-trustworthy-artificial-intelligence-altai-self-assessment)
* [Proposal for a Regulation laying down harmonised rules on artificial intelligence (Artificial Intelligence Act)](https://digital-strategy.ec.europa.eu/en/library/proposal-regulation-laying-down-harmonised-rules-artificial-intelligence-artificial-intelligence)
  * [Amendments adopted by the European Parliament on 14 June 2023 on the proposal for a regulation of the European Parliament and of the Council on laying down harmonised rules on artificial intelligence (Artificial Intelligence Act) and amending certain Union legislative acts](https://www.europarl.europa.eu/doceo/document/TA-9-2023-0236_EN.html)
* [The Digital Services Act package (EU Digital Services Act and Digital Markets Act)](https://digital-strategy.ec.europa.eu/en/policies/digital-services-act-package)
* [Civil liability regime for artificial intelligence](https://www.europarl.europa.eu/doceo/document/TA-9-2020-0276_EN.pdf)
* [European Parliament, Addressing AI risks in the workplace: Workers and algorithms](https://www.europarl.europa.eu/thinktank/en/document/EPRS_BRI(2024)762323)
* [European Parliament, The impact of the General Data Protection Regulation (GDPR) on artificial intelligence](https://www.europarl.europa.eu/RegData/etudes/STUD/2020/641530/EPRS_STU(2020)641530_EN.pdf)
* [European Commission, Hiroshima Process International Guiding Principles for Advanced AI system](https://digital-strategy.ec.europa.eu/en/library/hiroshima-process-international-guiding-principles-advanced-ai-system)

#### European Data Protection Authorities
* [European Data Protection Board (EDPB), AI Auditing documents](https://www.edpb.europa.eu/our-work-tools/our-documents/support-pool-expert-projects/ai-auditing_en)
* [European Data Protection Supervisor, First EDPS Orientations for EUIs using Generative AI](https://www.edps.europa.eu/data-protection/our-work/publications/guidelines/2024-06-03-first-edps-orientations-euis-using-generative-ai_en)
* [European Labour Authority (ELA), Artificial Intelligence and Algorithms in Risk Assessment: Addressing Bias, Discrimination and other Legal and Ethical Issues](https://www.ela.europa.eu/sites/default/files/2023-08/ELA-Handbook-AI-training.pdf)

#### OECD
* [OECD.AI, The Bias Assessment Metrics and Measures Repository](https://oecd.ai/en/catalogue/tools/the-bias-assessment-metrics-and-measures-repository)
* [OECD, AI, data governance and privacy: Synergies and areas of international co-operation](https://www.oecd.org/en/publications/ai-data-governance-and-privacy_2476b1a4-en.html)
* [OECD, Open, Useful and Re-usable data (OURdata) Index: 2019 - Policy Paper](https://www.oecd.org/gov/digital-government/policy-paper-ourdata-index-2019.htm)

#### NATO
* [AI in Precision Persuasion. Unveiling Tactics and Risks on Social Media](https://stratcomcoe.org/publications/ai-in-precision-persuasion-unveiling-tactics-and-risks-on-social-media/309)
* [Narrative Detection and Topic Modelling in the Baltics](https://stratcomcoe.org/publications/narrative-detection-and-topic-modelling-in-the-baltics/303)

#### United Nations
* [UNESCO, Artificial Intelligence: examples of ethical dilemmas](https://www.unesco.org/en/artificial-intelligence/recommendation-ethics/cases)
* [UNESCO, Consultation paper on AI regulation: emerging approaches across the world](https://unesdoc.unesco.org/ark:/48223/pf0000390979)
* [Office of the United Nations High Commissioner for Human Rights](https://www.ohchr.org/sites/default/files/documents/issues/business/b-tech/taxonomy-GenAI-Human-Rights-Harms.pdf)

### Law Texts and Drafts

This section is a collection of law texts and drafts pertaining to responsible AI.

* [Algorithmic Accountability Act of 2023](https://www.govinfo.gov/app/details/BILLS-118hr5628ih/)
* [Arizona, House Bill 2685](https://www.azleg.gov/legtext/55leg/2r/bills/hb2685h.htm)
* [Australia, Data Availability and Transparency Act 2022](https://www.datacommissioner.gov.au/law/dat-act)
* [Australia, Privacy Act 1988](https://www.legislation.gov.au/Details/C2014C00076)
* [California, Consumer Privacy Act of 2018, Civil Code - DIVISION 3. OBLIGATIONS [1427 - 3273.69]](https://leginfo.legislature.ca.gov/faces/codes_displayText.xhtml?division=3.&part=4.&lawCode=CIV&title=1.81.5)
* [Colorado, SB24-205 Consumer Protections for Artificial Intelligence, Concerning consumer protections in interactions with artificial intelligence systems](https://leg.colorado.gov/bills/SB24-205)
* [European Union, General Data Protection Regulation (GDPR)](https://gdpr-info.eu/)
  * [Article 22 EU GDPR "Automated individual decision-making, including profiling"](https://www.privacy-regulation.eu/en/article-22-automated-individual-decision-making-including-profiling-GDPR.htm)
* [Executive Order 13960 (2020-12-03), Promoting the Use of Trustworthy Artificial Intelligence in the Federal Government](https://www.federalregister.gov/documents/2020/12/08/2020-27065/promoting-the-use-of-trustworthy-artificial-intelligence-in-the-federal-government)
* [Executive Order on the Safe, Secure, and Trustworthy Development and Use of Artificial Intelligence](https://www.whitehouse.gov/briefing-room/presidential-actions/2023/10/30/executive-order-on-the-safe-secure-and-trustworthy-development-and-use-of-artificial-intelligence/)
* [Facial Recognition and Biometric Technology Moratorium Act of 2020](https://drive.google.com/file/d/1gkTcjFtieMQdsQ01dmDa49B6HY9ZyKr8/view)
* [Federal Consumer Online Privacy Rights Act (COPRA)](https://www.consumerprivacyact.com/federal/)
* [Germany, Bundesrat Drucksache 222/24 - Entwurf eines Gesetzes zum strafrechtlichen Schutz von Persönlichkeitsrechten vor Deepfakes (Draft Law on the Criminal Protection of Personality Rights from Deepfakes)](https://www.bundesrat.de/SharedDocs/drucksachen/2024/0201-0300/222-24(B).pdf?__blob=publicationFile&v=1)
* [Illinois, Biometric Information Privacy Act](https://www.ilga.gov/legislation/ilcs/ilcs3.asp?ActID=3004&ChapterID=57)
* [Justice in Policing Act](https://democrats-judiciary.house.gov/issues/issue/?IssueID=14924)
* [National Conference of State Legislatures (NCSL) 2020 Consumer Data Privacy Legislation](https://www.ncsl.org/technology-and-communication/2020-consumer-data-privacy-legislation)
* [Nebraska, LB1203 - Regulate artificial intelligence in media and political advertisements under the Nebraska Political Accountability and Disclosure Act](https://nebraskalegislature.gov/bills/view_bill.php?DocumentID=55088)
* [Rhode Island, Executive Order 24-06: Artificial Intelligence and Data Centers of Excellence](https://governor.ri.gov/executive-orders/executive-order-24-06)
* [Virginia, Consumer Data Protection Act](https://law.lis.virginia.gov/vacodefull/title59.1/chapter53/)
* [Washington State, SB 6513 - 2019-20](https://apps.leg.wa.gov/billsummary/?BillNumber=6513&Year=2020&Initiative=false)
* [United States Congress, 118th Congress (2023-2024), H.R.5586 - DEEPFAKES Accountability Act](https://www.congress.gov/bill/118th-congress/house-bill/5586/text)
* [United States Congress, 118th Congress (2023-2024), S.4769 - VET Artificial Intelligence Act](https://www.congress.gov/bill/118th-congress/senate-bill/4769/text)

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
* [Ethics for people who work in tech](https://ethicsforpeoplewhoworkintech.com/)
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
* [The Alan Turing Institute: Data science and AI glossary](https://www.turing.ac.uk/news/data-science-and-ai-glossary)
* [Appen Artificial Intelligence Glossary](https://appen.com/ai-glossary/)
* [Artificial intelligence and illusions of understanding in scientific research (glossary on second page)](https://www.nature.com/articles/s41586-024-07146-0.epdf?sharing_token=cbht6Q72InY18AtY6FiVM9RgN0jAjWel9jnR3ZoTv0Ni_LuMWrIZy_SmHlNQlu9tG1u0SCK_wTYxy6bvMe6U_BE3vc5yFmZEpTbIVJozkVYsOei9LdPpNr_wZzvTp4stmzGM54z-riqwhUCk0DD6_YkY_jcgZBnXR8P_8vyFvYpiCtjFrvczN9Lm6NhmrePm)
* [Brookings: The Brookings glossary of AI and emerging technologies](https://www.brookings.edu/articles/the-brookings-glossary-of-ai-and-emerging-technologies/)
* [Built In, Responsible AI Explained](https://builtin.com/artificial-intelligence/responsible-ai)
* [Center for Security and Emerging Technology: Glossary](https://cset.georgetown.edu/glossary/)
* [CompTIA: Artificial Intelligence (AI) Terminology: A Glossary for Beginners](https://connect.comptia.org/content/articles/artificial-intelligence-terminology)
* [Council of Europe Artificial Intelligence Glossary](https://www.coe.int/en/web/artificial-intelligence/glossary)
* [Coursera: Artificial Intelligence (AI) Terms: A to Z Glossary](https://www.coursera.org/articles/ai-terms)
* [Dataconomy: AI dictionary: Be a native speaker of Artificial Intelligence](https://dataconomy.com/2022/04/23/artificial-intelligence-terms-ai-glossary/)
* [Dennis Mercadal, 1990, *Dictionary of Artificial Intelligence*](https://archive.org/details/dictionaryofarti0000merc)
* [European Commission, EU-U.S. Terminology and Taxonomy for Artificial Intelligence - Second Edition](https://digital-strategy.ec.europa.eu/en/library/eu-us-terminology-and-taxonomy-artificial-intelligence-second-edition)
* [European Commission, Glossary of human-centric artificial intelligence](https://publications.jrc.ec.europa.eu/repository/handle/JRC129614)
* [G2: 70+ A to Z Artificial Intelligence Terms in Technology](https://www.g2.com/articles/artificial-intelligence-terms)
* [General Services Administration: AI Guide for Government: Key AI terminology](https://coe.gsa.gov/coe/ai-guide-for-government/what-is-ai-key-terminology/)
* [Google Developers Machine Learning Glossary](https://developers.google.com/machine-learning/glossary)
* [H2O.ai Glossary](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/glossary.html)
* [IAPP Glossary of Privacy Terms](https://iapp.org/resources/glossary/)
* [IAPP International Definitions of Artificial Intelligence](https://iapp.org/media/pdf/resource_center/international_definitions_of_ai.pdf)
* [IAPP Key Terms for AI Governance](https://iapp.org/resources/article/key-terms-for-ai-governance/)
* [IBM AI glossary](https://www.ibm.com/cloud/architecture/architecture/practices/cognitive-glossary/)
* [IEEE, A Glossary for Discussion of Ethics of Autonomous and Intelligent Systems, Version 1](https://standards.ieee.org/wp-content/uploads/import/documents/other/eadv2_glossary.pdf)
* [ISO/IEC DIS 22989(en) Information technology — Artificial intelligence — Artificial intelligence concepts and terminology](https://www.iso.org/obp/ui/fr/#iso:std:iso-iec:22989:dis:ed-1:v1:en)
* [Jerry M. Rosenberg, 1986, *Dictionary of Artificial Intelligence & Robotics*](https://archive.org/details/dictionaryofarti00rose)
* [MakeUseOf: A Glossary of AI Jargon: 29 AI Terms You Should Know](https://www.makeuseof.com/glossary-ai-jargon-terms/)
* [Moveworks: AI Terms Glossary](https://www.moveworks.com/us/en/resources/ai-terms-glossary)
* [National Institute of Standards and Technology (NIST), NIST AI 100-2 E2023: Adversarial Machine Learning: A Taxonomy and Terminology of Attacks and Mitigations](https://csrc.nist.gov/pubs/ai/100/2/e2023/final)
* [National Institute of Standards and Technology (NIST), The Language of Trustworthy AI: An In-Depth Glossary of Terms](https://airc.nist.gov/AI_RMF_Knowledge_Base/Glossary)
* [Oliver Houdé, 2004, *Dictionary of Cognitive Science: Neuroscience, Psychology, Artificial Intelligence, Linguistics, and Philosophy*](https://archive.org/details/dictionaryofcogn0000unse)
* [Open Access Vocabulary](https://repository.ifla.org/bitstream/123456789/3272/1/Open%20Access%20Vocabulary%20Feb2024%20v2.pdf)
* [Otto Vollnhals, 1992, *A Multilingual Dictionary of Artificial Intelligence (English, German, French, Spanish, Italian)*](https://archive.org/details/multilingualdict0000voll)
* [Raoul Smith, 1989, *The Facts on File Dictionary of Artificial Intelligence*](https://archive.org/details/factsonfiledicti00smit)
* [Raoul Smith, 1990, *Collins Dictionary of Artificial Intelligence*](https://archive.org/details/collinsdictionar0000unse_w3w7)
* [Salesforce: AI From A to Z: The Generative AI Glossary for Business Leaders](https://www.salesforce.com/blog/generative-ai-glossary/)
* [Siemens, Artificial Intelligence Glossary](https://www.siemens.com/global/en/company/stories/artificial-intelligence/ai-glossary.html)
* [Stanford University HAI Artificial Intelligence Definitions](https://hai.stanford.edu/sites/default/files/2023-03/AI-Key-Terms-Glossary-Definition.pdf)
* [TechTarget: Artificial intelligence glossary: 60+ terms to know](https://www.techtarget.com/whatis/feature/Artificial-intelligence-glossary-60-terms-to-know)
* [TELUS International: 50 AI terms every beginner should know](https://www.telusinternational.com/insights/ai-data/article/50-beginner-ai-terms-you-should-know)
* [Towards AI, Generative AI Terminology — An Evolving Taxonomy To Get You Started](https://towardsai.net/p/machine-learning/generative-ai-terminology-an-evolving-taxonomy-to-get-you-started)
* [UK Parliament, Artificial intelligence (AI) glossary](https://post.parliament.uk/artificial-intelligence-ai-glossary/)
* [University of New South Wales, Bill Wilson, The Machine Learning Dictionary](https://www.cse.unsw.edu.au/~billw/mldict.html)
* [VAIR (Vocabulary of AI Risks)](https://delaramglp.github.io/vair/)
* [Wikipedia: Glossary of artificial intelligence](https://en.wikipedia.org/wiki/Glossary_of_artificial_intelligence)
* [William J. Raynor, Jr, 1999, *The International Dictionary of Artificial Intelligence*, First Edition](https://archive.org/details/internationaldic0000rayn/mode/2up)
* [William J. Raynor, Jr, 2009, *International Dictionary of Artificial Intelligence*, Second Edition](https://archive.org/details/internationaldic0000rayn_t1n5/mode/2up)

### Open-ish Classes

This section features a selection of educational courses focused on ethical considerations and best practices in ML. The classes range from introductory courses on data ethics to specialized training in fairness and trustworthy deep learning.

* [An Introduction to Data Ethics](https://www.scu.edu/ethics/focus-areas/technology-ethics/resources/an-introduction-to-data-ethics/)
* [Awesome LLM Courses](https://github.com/wikit-ai/awesome-llm-courses)![](https://img.shields.io/github/stars/wikit-ai/awesome-llm-courses?style=social)
* [AWS Skill Builder](https://skillbuilder.aws/)
* [Build a Large Language Model (From Scratch)](https://github.com/rasbt/LLMs-from-scratch/tree/main)![](https://img.shields.io/github/stars/rasbt/LLMs-from-scratch?style=social)
* [Carnegie Mellon University, Computational Ethics for NLP](http://demo.clab.cs.cmu.edu/ethical_nlp/)
* [Certified Ethical Emerging Technologist](https://certnexus.com/certification/ceet/)
* [Coursera, DeepLearning.AI, Generative AI for Everyone](https://www.coursera.org/learn/generative-ai-for-everyone)
* [Coursera, DeepLearning.AI, Generative AI with Large Language Models](https://www.coursera.org/learn/generative-ai-with-llms)
* [Coursera, Google Cloud, Introduction to Generative AI](https://www.coursera.org/learn/introduction-to-generative-ai)
* [Coursera, Vanderbilt University, Prompt Engineering for ChatGPT](https://www.coursera.org/learn/prompt-engineering)
* [CS103F: Ethical Foundations of Computer Science](https://www.cs.utexas.edu/~ans/classes/cs109/schedule.html)
* [DeepLearning.AI](https://www.deeplearning.ai/courses/)
* [ETH Zürich ReliableAI 2022 Course Project repository](https://github.com/angelognazzo/Reliable-Trustworthy-AI)![](https://img.shields.io/github/stars/angelognazzo/Reliable-Trustworthy-AI?style=social)
* [Fairness in Machine Learning](https://fairmlclass.github.io/)
* [Fast.ai Data Ethics course](http://ethics.fast.ai/syllabus)
* [Google Cloud Skills Boost](https://www.cloudskillsboost.google/)
  * [Attention Mechanism](https://www.cloudskillsboost.google/course_templates/537)
  * [Create Image Captioning Models](https://www.cloudskillsboost.google/course_templates/542)
  * [Encoder-Decoder Architecture](https://www.cloudskillsboost.google/course_templates/543)
  * [Introduction to Generative AI](https://www.cloudskillsboost.google/course_templates/536)
  * [Introduction to Image Generation](https://www.cloudskillsboost.google/course_templates/541)
  * [Introduction to Large Language Models](https://www.cloudskillsboost.google/course_templates/539)
  * [Introduction to Responsible AI](https://www.cloudskillsboost.google/course_templates/554)
  * [Introduction to Vertex AI Studio](https://www.cloudskillsboost.google/course_templates/552)
  * [Transformer Models and BERT Model](https://www.cloudskillsboost.google/course_templates/538)
* [Grow with Google, Generative AI for Educators](https://grow.google/ai-for-educators/)
* [Human-Centered Machine Learning](http://courses.mpi-sws.org/hcml-ws18/)
* [IBM SkillsBuild](https://sb-auth.skillsbuild.org/)
* [Introduction to AI Ethics](https://www.kaggle.com/code/var0101/introduction-to-ai-ethics)
* [INFO 4270: Ethics and Policy in Data Science](https://docs.google.com/document/d/1GV97qqvjQNvyM2I01vuRaAwHe9pQAZ9pbP7KkKveg1o/)
* [Introduction to Responsible Machine Learning](https://jphall663.github.io/GWU_rml/)
* [Jay Alammar, Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention)](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/)
* [Machine Learning Fairness by Google](https://developers.google.com/machine-learning/crash-course/fairness/video-lecture)
* [OECD.AI, Disability-Centered AI And Ethics MOOC](https://oecd.ai/en/catalogue/tools/disability-centered-ai-and-ethics-mooc)
* [Piotr Sapieżyński's CS 4910 - Special Topics in Computer Science: Algorithm Audits](https://sapiezynski.com/cs4910.html)
* [Tech & Ethics Curricula](https://docs.google.com/spreadsheets/d/1Z0DqQeZ-Aeq6LmD17J5m8zeeIR6ywWnH-WO-jWtXE9M/edit#gid=0)
* [Trustworthy Deep Learning](https://berkeley-deep-learning.github.io/cs294-131-s19/)

### Podcasts and Channels

This section features podcasts and channels (such as on YouTube) that offer insightful commentary and explanations on responsible AI and machine learning interpretability.

* [Internet of Bugs](https://www.youtube.com/@InternetOfBugs/videos)
* [Tech Won't Save Us](https://techwontsave.us/)


## AI Incidents, Critiques, and Research Resources

### AI Incident Information Sharing Resources

This section houses initiatives, networks, repositories, and publications that facilitate collective and interdisciplinary efforts to enhance AI safety. It includes platforms where experts and practitioners come together to share insights, identify potential vulnerabilities, and collaborate on developing robust safeguards for AI systems, including AI incident trackers.

* [AI Incident Database (Responsible AI Collaborative)](https://incidentdatabase.ai/)
* [AI Vulnerability Database (AVID)](https://avidml.org/)
* [AIAAIC](https://www.aiaaic.org/)
* [AI Badness: An open catalog of generative AI badness](https://badness.ai/)
* [AI Risk Database](https://airisk.io/)
* [EthicalTech@GW, Deepfakes & Democracy Initiative](https://blogs.gwu.edu/law-eti/deepfakes-disinformation-democracy/)
* [George Washington University Law School's AI Litigation Database](https://blogs.gwu.edu/law-eti/ai-litigation-database/)
* [Merging AI Incidents Research with Political Misinformation Research: Introducing the Political Deepfakes Incidents Database](https://osf.io/fvqg3/)
* [OECD AI Incidents Monitor](https://oecd.ai/en/incidents)
* [Verica Open Incident Database (VOID)](https://www.thevoid.community/)

#### Bibliography of Papers on AI Incidents and Failures

* Bogucka, Edyta, Marios Constantinides, Julia De Miguel Velazquez, Sanja Šćepanović, Daniele Quercia, and Andrés Gvirtz. "The Atlas of AI Incidents in Mobile Computing: Visualizing the Risks and Benefits of AI Gone Mobile." *arXiv* (July 22, 2024). [https://doi.org/10.48550/arXiv.2407.15685](https://doi.org/10.48550/arXiv.2407.15685).
* Chanda, Sasanka Sekhar, and Debarag Narayan Banerjee. "Omission and Commission Errors Underlying AI Failures." *AI & Society* 39 (2024): 937–960. Published November 17, 2022. [https://doi.org/10.1007/s00146-022-01477-w](https://doi.org/10.1007/s00146-022-01477-w).
* Grosse, Kathrin, Lukas Bieringer, Tarek R. Besold, Battista Biggio, and Alexandre Alahi. "When Your AI Becomes a Target: AI Security Incidents and Best Practices." *Proceedings of the AAAI Conference on Artificial Intelligence* 38, no. 21 (March 24, 2024): 23041-23046. [https://doi.org/10.1609/aaai.v38i21.30347](https://doi.org/10.1609/aaai.v38i21.30347).
* Hong, Matthew K., Adam Fourney, Derek DeBellis, and Saleema Amershi. "Planning for Natural Language Failures with the AI Playbook." In *CHI '21: Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems*, Article 386, 1-11. Published May 7, 2021. [https://doi.org/10.1145/3411764.3445735](https://doi.org/10.1145/3411764.3445735).
* May, Richard, Jacob Krüger, and Thomas Leich. "SoK: How Artificial-Intelligence Incidents Can Jeopardize Safety and Security." In *Proceedings of the 19th International Conference on Availability, Reliability and Security (ARES '24)*, Article 44, 1-12. July 30, 2024. [https://doi.org/10.1145/3664476.3664510](https://doi.org/10.1145/3664476.3664510).
* McGregor, Sean. "Preventing Repeated Real World AI Failures by Cataloging Incidents: The AI Incident Database." *Proceedings of the AAAI Conference on Artificial Intelligence* 35, no. 17 (2021): 15458-15463. [https://doi.org/10.1609/aaai.v35i17.17817](https://doi.org/10.1609/aaai.v35i17.17817).
* McGregor, Sean, Kevin Paeth, and Khoa Lam. "Indexing AI Risks with Incidents, Issues, and Variants." *arXiv* (November 18, 2022). [https://doi.org/10.48550/arXiv.2211.10384](https://doi.org/10.48550/arXiv.2211.10384).
* Nasim, Syeda Faiza, Muhammad Rizwan Ali, and Umme Kulsoom. "Artificial Intelligence Incidents & Ethics: A Narrative Review." *International Journal of Technology, Innovation and Management* 2, no. 2 (October 2022): 52-64. [https://doi.org/10.54489/ijtim.v2i2.80](https://doi.org/10.54489/ijtim.v2i2.80).
* O'Brien, Joe, Shaun Ee, and Zoe Williams. "Deployment Corrections: An Incident Response Framework for Frontier AI Models." *arXiv* (September 30, 2023). [https://doi.org/10.48550/arXiv.2310.00328](https://doi.org/10.48550/arXiv.2310.00328).
* Schmill, Matthew D., Darsana Josyula, Michael L. Anderson, Shomir Wilson, Tim Oates, Don Perlis, Dean Wright, and Scott Fults. "Ontologies for Reasoning about Failures in AI Systems." In *Proceedings from the Workshop on Metareasoning in Agent Based Systems at the Sixth International Joint Conference on Autonomous Agents and Multiagent Systems*, 2007. [https://mclumd.github.io/ALMECOM%20Papers/2007/Schmill%20et%20al.%20-%202007%20-%20Ontologies%20for%20reasoning%20about%20failures%20in%20AI%20syst.pdf](https://mclumd.github.io/ALMECOM%20Papers/2007/Schmill%20et%20al.%20-%202007%20-%20Ontologies%20for%20reasoning%20about%20failures%20in%20AI%20syst.pdf).
* Slota, Stephen C., Kenneth R. Fleischmann, Sherri Greenberg, Nitin Verma, Brenna Cummings, Lan Li, and Chris Shenefiel. "Good Systems, Bad Data?: Interpretations of AI Hype and Failures." *Proceedings of the Association for Information Science and Technology* 57, no. 1 (2020): e275. [https://doi.org/10.1002/pra2.275](https://doi.org/10.1002/pra2.275).
* Stanley, Jeff C., and Stephen L. Dorton. "Exploring Trust With the AI Incident Database." *Proceedings of the Human Factors and Ergonomics Society Annual Meeting* 67, no. 1 (October 25, 2023). [https://doi.org/10.1177/21695067231198084](https://doi.org/10.1177/21695067231198084).
* Wei, Mengyi, and Zhixuan Zhou. "AI Ethics Issues in Real World: Evidence from AI Incident Database." *arXiv* (August 18, 2022). [https://doi.org/10.48550/arXiv.2206.07635](https://doi.org/10.48550/arXiv.2206.07635).
* Williams, Robert, and Roman Yampolskiy. "Understanding and Avoiding AI Failures: A Practical Guide." *Philosophies* 6, no. 3 (2021): 53. [https://doi.org/10.3390/philosophies6030053](https://doi.org/10.3390/philosophies6030053).
* Yampolskiy, Roman V., and M. S. Spellchecker. "Artificial Intelligence Safety and Cybersecurity: A Timeline of AI Failures." *arXiv* (2016). [https://doi.org/10.48550/arXiv.1610.07997](https://doi.org/10.48550/arXiv.1610.07997).


### AI Law, Policy, and Guidance Trackers

This section contains trackers, databases, and repositories of laws, policies, and guidance pertaining to AI.

* [Access Now, Regulatory Mapping on Artificial Intelligence in Latin America: Regional AI Public Policy Report](https://www.accessnow.org/wp-content/uploads/2024/07/TRF-LAC-Reporte-Regional-IA-JUN-2024-V3.pdf)
* [The Ethical AI Database](https://www.eaidb.org/)
* [George Washington University Law School's AI Litigation Database](https://blogs.gwu.edu/law-eti/ai-litigation-database/)
* [IAPP Global AI Legislation Tracker](https://iapp.org/resources/article/global-ai-legislation-tracker/)
* [IAPP US State Privacy Legislation Tracker](https://iapp.org/resources/article/us-state-privacy-legislation-tracker/)
* [Institute for the Future of Work, Tracking international legislation relevant to AI at work](https://www.ifow.org/publications/legislation-tracker)
* [Legal Nodes, Global AI Regulations Tracker: Europe, Americas & Asia-Pacific Overview](https://legalnodes.com/article/global-ai-regulations-tracker)
* [National Conference of State Legislatures, Deceptive Audio or Visual Media (‘Deepfakes’) 2024 Legislation](https://www.ncsl.org/technology-and-communication/deceptive-audio-or-visual-media-deepfakes-2024-legislation)
* [OECD.AI, National AI policies & strategies](https://oecd.ai/en/dashboards/overview)
* [Raymond Sun, Global AI Regulation Tracker](https://www.techieray.com/GlobalAIRegulationTracker)
* [Runway Strategies, Global AI Regulation Tracker](https://www.runwaystrategies.co/global-ai-regulation-tracker)
* [University of North Texas, Artificial Intelligence (AI) Policy Collection](https://digital.library.unt.edu/explore/collections/AIPC/)
* [VidhiSharma.AI, Global AI Governance Tracker](https://vidhisharmaai.com/global-ai-governance-tracker/)
* [White & Case, AI Watch: Global regulatory tracker - United States](https://www.whitecase.com/insight-our-thinking/ai-watch-global-regulatory-tracker-united-states)

### Challenges and Competitions

This section contains challenges and competitions related to responsible ML. 

* [FICO Explainable Machine Learning Challenge](https://community.fico.com/s/explainable-machine-learning-challenge)
* [OSD Bias Bounty](https://osdbiasbounty.com/)
* [National Fair Housing Alliance Hackathon](https://nationalfairhousing.org/hackathon2023/)
* [Twitter Algorithmic Bias](https://hackerone.com/twitter-algorithmic-bias?type=team)

### Critiques of AI

This section contains an assortment of papers, articles, essays, and general resources that take critical stances toward generative AI.

* [Against predictive optimization](https://predictive-optimization.cs.princeton.edu/)
* [AI chatbots use racist stereotypes even after anti-racism training](https://www.newscientist.com/article/2421067-ai-chatbots-use-racist-stereotypes-even-after-anti-racism-training/)
* [AI hype as a cyber security risk: the moral responsibility of implementing generative AI in business](https://link.springer.com/article/10.1007/s43681-024-00443-4)
* [AI hype, promotional culture, and affective capitalism](https://link.springer.com/article/10.1007/s43681-024-00483-w)
* [AI Is a Lot of Work](https://nymag.com/intelligencer/article/ai-artificial-intelligence-humans-technology-business-factory.html)
* [AI is effectively ‘useless’—and it’s created a ‘fake it till you make it’ bubble that could end in disaster, veteran market watcher warns](https://finance.yahoo.com/news/ai-effectively-useless-created-fake-194008129.html)
* [AI Safety Is a Narrative Problem](https://hdsr.mitpress.mit.edu/pub/wz35dvpo/release/1?readingCollection=3974b7e6)
* [AI Snake Oil](https://www.aisnakeoil.com/)
* [AI Tools Still Permitting Political Disinfo Creation, NGO Warns](https://www.barrons.com/news/ai-tools-still-permitting-political-disinfo-creation-ngo-warns-ac791521)
* [Anthropomorphism in AI: hype and fallacy](https://link.springer.com/article/10.1007/s43681-024-00419-4)
* [Are Emergent Abilities of Large Language Models a Mirage?](https://arxiv.org/pdf/2304.15004.pdf)
* [Are Language Models Actually Useful for Time Series Forecasting?](https://arxiv.org/abs/2406.16964v1)
* [Artificial Hallucinations in ChatGPT: Implications in Scientific Writing](https://assets.cureus.com/uploads/editorial/pdf/138667/20230219-28928-6kcyip.pdf)
* [Artificial intelligence and illusions of understanding in scientific research](https://rdcu.be/dAw4I)
* [Artificial Intelligence: Hope for Future or Hype by Intellectuals?](https://ieeexplore.ieee.org/abstract/document/9596410)
* [ArtPrompt: ASCII Art-based Jailbreak Attacks against Aligned LLMs](https://arxiv.org/pdf/2402.11753.pdf)
* [Aylin Caliskan's publications](https://faculty.washington.edu/aylin/publications.html)
* [Beyond Preferences in AI Alignment](https://arxiv.org/pdf/2408.16984)
* [Chatbots in consumer finance](https://www.consumerfinance.gov/data-research/research-reports/chatbots-in-consumer-finance/chatbots-in-consumer-finance/)
* [ChatGPT is bullshit](https://link.springer.com/article/10.1007/s10676-024-09775-5)
* [Companies like Google and OpenAI are pillaging the internet and pretending it’s progress](https://bgr.com/business/companies-like-google-and-openai-are-pillaging-the-internet-and-pretending-its-progress/)
* [Consciousness in Artificial Intelligence: Insights from the Science of Consciousness](https://arxiv.org/abs/2308.08708)
* [The Cult of AI](https://www.rollingstone.com/culture/culture-features/ai-companies-advocates-cult-1234954528/)
* [Data and its (dis)contents: A survey of dataset development and use in machine learning research](https://www.cell.com/patterns/pdf/S2666-3899(21)00184-7.pdf)
* [The Data Scientific Method vs. The Scientific Method](https://odsc.com/blog/the-data-scientific-method-vs-the-scientific-method/)
* [Ed Zitron's Where's Your Ed At](https://www.wheresyoured.at/)
* [Emergent and Predictable Memorization in Large Language Models](https://arxiv.org/abs/2304.11158)
* [Evaluating Language-Model Agents on Realistic Autonomous Tasks](https://arxiv.org/pdf/2312.11671.pdf)
* [FABLES: Evaluating faithfulness and content selection in book-length summarization](https://arxiv.org/abs/2404.01261)
* [The Fallacy of AI Functionality](https://dl.acm.org/doi/pdf/10.1145/3531146.3533158)
* [Futurism, Disillusioned Businesses Discovering That AI Kind of Sucks](https://futurism.com/the-byte/businesses-discovering-ai-sucks)
* [Gen AI: Too Much Spend, Too Little Benefit?](https://www.goldmansachs.com/intelligence/pages/gs-research/gen-ai-too-much-spend-too-little-benefit/report.pdf)
* [Generative AI: UNESCO study reveals alarming evidence of regressive gender stereotypes](https://www.unesco.org/en/articles/generative-ai-unesco-study-reveals-alarming-evidence-regressive-gender-stereotypes)
* [Get Ready for the Great AI Disappointment](https://www.wired.com/story/get-ready-for-the-great-ai-disappointment/)
* [Ghost in the Cloud: Transhumanism’s simulation theology](https://www.nplusonemag.com/issue-28/essays/ghost-in-the-cloud/)
* [Handling the hype: Implications of AI hype for public interest tech projects](https://www.tatup.de/index.php/tatup/article/view/7080)
* [The harms of terminology: why we should reject so-called “frontier AI”](https://link.springer.com/article/10.1007/s43681-024-00438-1)
* [HealthManagement.org, The Journal, Volume 19, Issue 2, 2019, Artificial Hype](https://egve.hu/downloads/health_management/health_management_2019_2_szam.pdf)
* [How AI hype impacts the LGBTQ + community](https://link.springer.com/article/10.1007/s43681-024-00423-8)
* [How AI lies, cheats, and grovels to succeed - and what we need to do about it](https://www.zdnet.com/article/how-ai-lies-cheats-and-grovels-to-succeed-and-what-we-need-to-do-about-it/)
* [Identifying and Eliminating CSAM in Generative ML Training Data and Models](https://stacks.stanford.edu/file/druid:kh752sm9123/ml_training_data_csam_report-2023-12-23.pdf)
* [Insanely Complicated, Hopelessly Inadequate](https://www.lrb.co.uk/the-paper/v43/n02/paul-taylor/insanely-complicated-hopelessly-inadequate)
* [Internet of Bugs, Debunking Devin: "First AI Software Engineer" Upwork lie exposed! (video)](https://www.youtube.com/watch?v=tNmgmwEtoWE)
* [I Will Fucking Piledrive You If You Mention AI Again](https://ludic.mataroa.blog/blog/i-will-fucking-piledrive-you-if-you-mention-ai-again/)
* [Julia Angwin, Press Pause on the Silicon Valley Hype Machine](https://www.nytimes.com/2024/05/15/opinion/artificial-intelligence-ai-openai-chatgpt-overrated-hype.html)
* [Lazy use of AI leads to Amazon products called “I cannot fulfill that request”](https://arstechnica.com/ai/2024/01/lazy-use-of-ai-leads-to-amazon-products-called-i-cannot-fulfill-that-request/)
* [Leak, Cheat, Repeat: Data Contamination and Evaluation Malpractices in Closed-Source LLMs](https://arxiv.org/pdf/2402.03927.pdf)
* [LLMs Can’t Plan, But Can Help Planning in LLM-Modulo Frameworks](https://arxiv.org/pdf/2402.01817.pdf)
* [Long-context LLMs Struggle with Long In-context Learning](https://huggingface.co/papers/2404.02060)
* [Low-Resource Languages Jailbreak GPT-4](https://arxiv.org/abs/2310.02446v1)
* [Machine Learning: The High Interest Credit Card of Technical Debt](https://research.google/pubs/machine-learning-the-high-interest-credit-card-of-technical-debt/)
* [Measuring the predictability of life outcomes with a scientific mass collaboration](https://www.pnas.org/doi/10.1073/pnas.1915006117)
* [Meta AI Chief: Large Language Models Won't Achieve AGI](https://www.msn.com/en-us/news/technology/meta-ai-chief-large-language-models-won-t-achieve-agi/ar-BB1mRPa5)
* [Meta’s AI chief: LLMs will never reach human-level intelligence](https://thenextweb.com/news/meta-yann-lecun-ai-behind-human-intelligence)
* [Most CEOs aren’t buying the hype on generative AI benefits](https://www.itpro.com/business/leadership/most-ceos-arent-buying-the-hype-on-generative-ai-benefits)
* [Nepotistically Trained Generative-AI Models Collapse](https://arxiv.org/abs/2311.12202)
* [Non-discrimination Criteria for Generative Language Models](https://arxiv.org/abs/2403.08564)
* [Open Problems in Technical AI Governance](https://arxiv.org/pdf/2407.14981)
* [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?](https://dl.acm.org/doi/pdf/10.1145/3442188.3445922)
* [The perpetual motion machine of AI-generated data and the distraction of ChatGPT as a ‘scientist’](https://www.nature.com/articles/s41587-023-02103-0)
* [Pretraining Data Mixtures Enable Narrow Model Selection Capabilities in Transformer Models](https://arxiv.org/pdf/2311.00871.pdf)
* [Promising the future, encoding the past: AI hype and public media imagery](https://link.springer.com/article/10.1007/s43681-024-00474-x)
* [Quantifying Memorization Across Neural Language Models](https://arxiv.org/abs/2202.07646)
* [Re-evaluating GPT-4’s bar exam performance](https://link.springer.com/article/10.1007/s10506-024-09396-9)
* [Researchers surprised by gender stereotypes in ChatGPT](https://www.dtu.dk/english/news/all-news/researchers-surprised-by-gender-stereotypes-in-chatgpt?id=7e5936d1-dfce-485b-8a90-78f7c757177d)
* [Ryan Allen, Explainable AI: The What’s and Why’s, Part 1: The What](https://ryanallen42.medium.com/explainable-ai-the-whats-and-why-s-175ea344bf3a)
* [Scalable Extraction of Training Data from (Production) Language Models](https://arxiv.org/pdf/2311.17035.pdf)
* [Speed of AI development stretches risk assessments to breaking point](https://www.ft.com/content/499c8935-f46e-4ec8-a8e2-19e07e3b0438)
* [Talking existential risk into being: a Habermasian critical discourse perspective to AI hype](https://link.springer.com/article/10.1007/s43681-024-00464-z)
* [Task Contamination: Language Models May Not Be Few-Shot Anymore](https://arxiv.org/pdf/2312.16337.pdf)
* [Theory Is All You Need: AI, Human Cognition, and Decision Making](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4737265)
* [There Is No A.I.](https://www.newyorker.com/science/annals-of-artificial-intelligence/there-is-no-ai)
* [Three different types of AI hype in healthcare](https://link.springer.com/article/10.1007/s43681-024-00465-y)
* [Toward Sociotechnical AI: Mapping Vulnerabilities for Machine Learning in Context](https://link.springer.com/article/10.1007/s11023-024-09668-y)
* [We still don't know what generative AI is good for](https://www.msn.com/en-us/news/technology/we-still-dont-know-what-generative-ai-is-good-for/ar-AA1nz1QH)
* [What’s in a Name? Experimental Evidence of Gender Bias in Recommendation Letters Generated by ChatGPT](https://www.jmir.org/2024/1/e51837/)
* [Which Humans?](https://osf.io/preprints/psyarxiv/5b26t)
* [Why We Must Resist AI’s Soft Mind Control]( https://www.theatlantic.com/ideas/archive/2024/03/artificial-intelligence-google-gemini-mind-control/677683/)
* [Winner's Curse? On Pace, Progress, and Empirical Rigor](https://openreview.net/pdf?id=rJWF0Fywf)

#### Environmental Costs of AI

* [AI already uses as much energy as a small country. It’s only the beginning.](https://www.vox.com/climate/2024/3/28/24111721/ai-uses-a-lot-of-energy-experts-expect-it-to-double-in-just-a-few-years)
* [The AI Carbon Footprint and Responsibilities of AI Scientists](https://www.mdpi.com/2409-9287/7/1/4)
* [Beyond CO2 Emissions: The Overlooked Impact of Water Consumption of Information Retrieval Models](https://dl.acm.org/doi/abs/10.1145/3578337.3605121)
* [The carbon impact of artificial intelligence](https://www.nature.com/articles/s42256-020-0219-9)
* [Data centre water consumption](https://www.nature.com/articles/s41545-021-00101-w)
* [Environment and sustainability development: A ChatGPT perspective](https://www.taylorfrancis.com/chapters/oa-edit/10.1201/9781003471059-8/environment-sustainability-development-chatgpt-perspective-priyanka-bhaskar-neha-seth)
* [The Environmental Impact of AI: A Case Study of Water Consumption by Chat GPT](https://puiij.com/index.php/research/article/view/39)
* [The Environmental Price of Intelligence: Evaluating the Social Cost of Carbon in Machine Learning](https://ieeexplore.ieee.org/abstract/document/10553496)
* [Generative AI’s environmental costs are soaring — and mostly secret](https://www.nature.com/articles/d41586-024-00478-x)
* [The Hidden Environmental Impact of AI](https://jacobin.com/2024/06/ai-data-center-energy-usage-environment/)
* [Making AI Less "Thirsty": Uncovering and Addressing the Secret Water Footprint of AI Models](https://arxiv.org/abs/2304.03271)
* [The mechanisms of AI hype and its planetary and social costs](https://link.springer.com/article/10.1007/s43681-024-00461-2)
* [Power Hungry Processing: Watts Driving the Cost of AI Deployment?](https://dl.acm.org/doi/pdf/10.1145/3630106.3658542)
* [Promoting Sustainability: Mitigating the Water Footprint in AI-Embedded Data Centres](https://www.igi-global.com/chapter/promoting-sustainability/341617)
* [Sustainable AI: Environmental Implications, Challenges and Opportunities](https://proceedings.mlsys.org/paper_files/paper/2022/file/462211f67c7d858f663355eff93b745e-Paper.pdf)

### Groups and Organizations

* [Center for AI and Digital Policy](https://www.caidp.org)
* [Institute for Advanced Study (IAS), AI Policy and Governance Working Group](https://www.ias.edu/stsv-lab/aipolicy) 
    
### Curated Bibliographies

We are seeking curated bibliographies related to responsible ML across various topics, see [issue 115](https://github.com/jphall663/awesome-machine-learning-interpretability/issues/115). 

* [Blair Attard-Frost, INF1005H1S: Artificial Intelligence Policy Supplementary Reading List](https://www.blairaf.com/library/resources/teaching/2024-INF1005H1S/INF1005-Supplementary-Reading-List.pdf)
* [Internet Rules Lab, Responsible Computing](https://www.internetruleslab.com/responsible-computing)
* [LLM Security & Privacy](https://github.com/chawins/llm-sp)![](https://img.shields.io/github/stars/chawins/llm-sp?style=social)
* [Membership Inference Attacks and Defenses on Machine Learning Models Literature](https://github.com/HongshengHu/membership-inference-machine-learning-literature)![](https://img.shields.io/github/stars/HongshengHu/membership-inference-machine-learning-literature?style=social)
* [White & Case, AI Watch: Global regulatory tracker - United States](https://www.whitecase.com/insight-our-thinking/ai-watch-global-regulatory-tracker-united-states)

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
* [Casey Fiesler's AI Ethics & Policy News spreadsheet](https://docs.google.com/spreadsheets/d/11Ps8ILDHH-vojJGyIx7CcaoB5l1mBRHy3OQAgWkm0W4/edit#gid=0)
* [criticalML](https://github.com/rockita/criticalML)![](https://img.shields.io/github/stars/rockita/criticalML?style=social)
* [Ethics for people who work in tech](https://ethicsforpeoplewhoworkintech.com/)
* [Evaluation Repository for 'Sociotechnical Safety Evaluation of Generative AI Systems'](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vQObeTxvXtOs--zd98qG2xBHHuTTJOyNISBJPthZFr3at2LCrs3rcv73d4of1A78JV2eLuxECFXJY43/pubhtml)
* [IMDA-BTG, LLM-Evals-Catalogue](https://github.com/IMDA-BTG/LLM-Evals-Catalogue)![](https://img.shields.io/github/stars/IMDA-BTG/LLM-Evals-Catalogue?style=social)
* [Machine Learning Ethics References](https://github.com/radames/Machine-Learning-Ethics-References)![](https://img.shields.io/github/stars/radames/Machine-Learning-Ethics-References?style=social)
* [Machine Learning Interpretability Resources](https://github.com/h2oai/mli-resources)![](https://img.shields.io/github/stars/h2oai/mli-resources?style=social)
* [OECD-NIST Catalogue of AI Tools and Metrics](https://oecd.ai/en/catalogue/overview)
* [OpenAI Cookbook](https://github.com/openai/openai-cookbook/tree/main)![](https://img.shields.io/github/stars/openai/openai-cookbook?style=social)
* [private-ai-resources](https://github.com/OpenMined/private-ai-resources)![](https://img.shields.io/github/stars/OpenMined/private-ai-resources?style=social)
* [Ravit Dotan's Resources](https://www.techbetter.ai/resources)
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
| [benchm-ml](https://github.com/szilard/benchm-ml)![](https://img.shields.io/github/stars/szilard/benchm-ml?style=social) | "A minimal benchmark for scalability, speed and accuracy of commonly used open source implementations (R packages, Python scikit-learn, H2O, xgboost, Spark MLlib etc.) of the top machine learning algorithms for binary classification (random forests, gradient boosted trees, deep neural networks etc.)." |
| [Bias Benchmark for QA dataset (BBQ)](https://github.com/nyu-mll/bbq)![](https://img.shields.io/github/stars/nyu-mll/bbq?style=social) | "Repository for the Bias Benchmark for QA dataset." |
| [Cataloguing LLM Evaluations](https://github.com/IMDA-BTG/LLM-Evals-Catalogue)![](https://img.shields.io/github/stars/IMDA-BTG/LLM-Evals-Catalogue?style=social) | "This repository stems from our paper, 'Cataloguing LLM Evaluations,' and serves as a living, collaborative catalogue of LLM evaluation frameworks, benchmarks and papers." |
| [DecodingTrust](https://github.com/AI-secure/DecodingTrust)![](https://img.shields.io/github/stars/huggingface/evaluate?style=social) | "A Comprehensive Assessment of Trustworthiness in GPT Models." |
| [EleutherAI, Language Model Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness)![](https://img.shields.io/github/stars/EleutherAI/lm-evaluation-harness?style=social) | "A framework for few-shot evaluation of language models." |
| [GEM](https://gem-benchmark.com/) | "GEM is a benchmark environment for Natural Language Generation with a focus on its Evaluation, both through human annotations and automated Metrics." |
| [HELM](https://crfm.stanford.edu/helm/latest/) | "A holistic framework for evaluating foundation models." |
| [Hugging Face, evaluate](https://github.com/huggingface/evaluate)![](https://img.shields.io/github/stars/huggingface/evaluate?style=social) | "Evaluate: A library for easily evaluating machine learning models and datasets." |
| [i-gallegos, Fair-LLM-Benchmark](https://github.com/i-gallegos/Fair-LLM-Benchmark)![](https://img.shields.io/github/stars/i-gallegos/Fair-LLM-Benchmark?style=social) | Benchmark from "Bias and Fairness in Large Language Models: A Survey" |
| [MLCommons, MLCommons AI Safety v0.5 Proof of Concept](https://mlcommons.org/2024/04/mlc-aisafety-v0-5-poc/) | "The MLCommons AI Safety Benchmark aims to assess the safety of AI systems in order to guide development, inform purchasers and consumers, and support standards bodies and policymakers." |
| [MLCommons, Introducing v0.5 of the AI Safety Benchmark from MLCommons](https://arxiv.org/pdf/2404.12241.pdf) | A paper about the MLCommons AI Safety Benchmark v0.5. |
| [Nvidia MLPerf](https://www.nvidia.com/en-us/data-center/resources/mlperf-benchmarks/) | "MLPerf™ benchmarks—developed by MLCommons, a consortium of AI leaders from academia, research labs, and industry—are designed to provide unbiased evaluations of training and inference performance for hardware, software, and services." | 
| [OpenML Benchmarking Suites](https://www.openml.org/search?type=benchmark&study_type=task) | OpenML's collection of over two dozen benchmarking suites. |
| [Real Toxicity Prompts (Allen Institute for AI)](https://allenai.org/data/real-toxicity-prompts) | "A dataset of 100k sentence snippets from the web for researchers to further address the risk of neural toxic degeneration in models." |
| [SafetyPrompts.com](https://safetyprompts.com/) | "A Living Catalogue of Open Datasets for LLM Safety." |
| [Sociotechnical Safety Evaluation Repository](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vQObeTxvXtOs--zd98qG2xBHHuTTJOyNISBJPthZFr3at2LCrs3rcv73d4of1A78JV2eLuxECFXJY43/pubhtml) | An extensive spreadsheet of sociotechnical safety evaluations in a spreadsheet. |
| [TrustLLM-Benchmark](https://trustllmbenchmark.github.io/TrustLLM-Website/index.html) | "A Comprehensive Study of Trustworthiness in Large Language Models." |
| [Trust-LLM-Benchmark Leaderboard](https://trustllmbenchmark.github.io/TrustLLM-Website/leaderboard.html) | A series of sortable leaderboards of LLMs based on different trustworthiness criteria. |
| [TruthfulQA](https://github.com/sylinrl/TruthfulQA)![](https://img.shields.io/github/stars/sylinrl/TruthfulQA?style=social) | "TruthfulQA: Measuring How Models Imitate Human Falsehoods." |
| [WAVES: Benchmarking the Robustness of Image Watermarks](https://wavesbench.github.io/) | "This paper investigates the weaknesses of image watermarking techniques." |
| [Wild-Time: A Benchmark of in-the-Wild Distribution Shifts over Time](https://github.com/huaxiuyao/Wild-Time)![](https://img.shields.io/github/stars/huaxiuyao/Wild-Time?style=social) | "Benchmark for Natural Temporal Distribution Shift (NeurIPS 2022)." |
| [Winogender Schemas](https://github.com/rudinger/winogender-schemas)![](https://img.shields.io/github/stars/rudinger/winogender-schemas?style=social) | "Data for evaluating gender bias in coreference resolution systems." |
| [yandex-research / tabred](https://github.com/yandex-research/tabred)![](https://img.shields.io/github/stars/yandex-research/tabred?style=social) | "A Benchmark of Tabular Machine Learning in-the-Wild with real-world industry-grade tabular datasets." |


### Common or Useful Datasets

This section contains datasets that are commonly used in responsible ML evaulations or repositories of interesting/important data sources:

* [Adult income dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)
* [Balanced Faces in the Wild](https://github.com/visionjo/facerec-bias-bfw)![](https://img.shields.io/github/stars/visionjo/facerec-bias-bfw?style=social)
* [Bruegel, A dataset on EU legislation for the digital world](https://www.bruegel.org/dataset/dataset-eu-legislation-digital-world)
* [COMPAS Recidivism Risk Score Data and Analysis](https://www.propublica.org/datastore/dataset/compas-recidivism-risk-score-data-and-analysis)
  * **Data Repositories**:
    * [All Lending Club loan data](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
    * [Amazon Open Data](https://registry.opendata.aws/amazon-reviews/)
    * [Data.gov](https://data.gov/)
    * [Home Mortgage Disclosure Act (HMDA) Data](https://www.consumerfinance.gov/data-research/hmda/)
    * [MIMIC-III Clinical Database](https://physionet.org/content/mimiciii/1.4/)
    * [UCI ML Data Repository](https://archive.ics.uci.edu/)
* [FANNIE MAE Single Family Loan Performance](https://capitalmarkets.fanniemae.com/credit-risk-transfer/single-family-credit-risk-transfer/fannie-mae-single-family-loan-performance-data)
* [Have I Been Trained?](https://haveibeentrained.com/)
* [nikhgarg / EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)![](https://img.shields.io/github/stars/nikhgarg/EmbeddingDynamicStereotypes?style=social)
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
| [CometLLM](https://github.com/comet-ml/comet-llm) |  "A tool to log and visualize your LLM prompts and chains." |
| [dvc](https://dvc.org/) | "Manage and version images, audio, video, and text files in storage and organize your ML modeling process into a reproducible workflow." |
| [gigantum](https://github.com/gigantum) ![gigantum stars](https://img.shields.io/github/stars/gigantum?style=social) | "Building a better way to create, collaborate, and share data-driven science." |
| [mlflow](https://mlflow.org/) | "An open source platform for the machine learning lifecycle." |
| [mlmd](https://github.com/google/ml-metadata) ![mlmd stars](https://img.shields.io/github/stars/google/ml-metadata?style=social) | "For recording and retrieving metadata associated with ML developer and data scientist workflows." |
| [modeldb](https://github.com/VertaAI/modeldb) ![modeldb stars](https://img.shields.io/github/stars/VertaAI/modeldb?style=social) | "Open Source ML Model Versioning, Metadata, and Experiment Management." |
| [neptune](https://neptune.ai/researchers) | "A single place to manage all your model metadata." |

### Personal Data Protection Tools

This section contains tools for personal data protection.

| Name | Description |
|------|-------------|
| [LLM Dataset Inference: Did you train on my dataset?](https://github.com/pratyushmaini/llm_dataset_inference/)![](https://img.shields.io/github/stars/pratyushmaini/llm_dataset_inference?style=social) | "Official Repository for Dataset Inference for LLMs" |

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
| [leeky: Leakage/contamination testing for black box language models](https://github.com/mjbommar/leeky)![](https://img.shields.io/github/stars/mjbommar/leeky?style=social) | "leeky - training data contamination techniques for blackbox models" |
| [leondz / garak, LLM vulnerability scanner](https://github.com/leondz/garak)![](https://img.shields.io/github/stars/leondz/garak?style=social) | "LLM vulnerability scanner" |
| [lilac](https://github.com/lilacai/lilac)![](https://img.shields.io/github/stars/lilacai/lilac?style=social) | "Curate better data for LLMs." |
| [lime](https://github.com/marcotcr/lime)![](https://img.shields.io/github/stars/marcotcr/lime?style=social) | "explaining what machine learning classifiers (or models) are doing. At the moment, we support explaining individual predictions for text classifiers or classifiers that act on tables (numpy arrays of numerical or categorical data) or images, with a package called lime (short for local interpretable model-agnostic explanations).” |
| [LiFT](https://github.com/linkedin/LiFT)![](https://img.shields.io/github/stars/linkedin/LiFT?style=social) | "The LinkedIn Fairness Toolkit (LiFT) is a Scala/Spark library that enables the measurement of fairness and the mitigation of bias in large-scale machine learning workflows. The measurement module includes measuring biases in training data, evaluating fairness metrics for ML models, and detecting statistically significant differences in their performance across different subgroups.” |
| [lit](https://github.com/pair-code/lit)![](https://img.shields.io/github/stars/pair-code/lit?style=social) | "The Learning Interpretability Tool (LIT, formerly known as the Language Interpretability Tool) is a visual, interactive ML model-understanding tool that supports text, image, and tabular data. It can be run as a standalone server, or inside of notebook environments such as Colab, Jupyter, and Google Cloud Vertex AI notebooks.” |
| [LLM Dataset Inference: Did you train on my dataset?](https://github.com/pratyushmaini/llm_dataset_inference/)![](https://img.shields.io/github/stars/pratyushmaini/llm_dataset_inference?style=social) | "Official Repository for Dataset Inference for LLMs" |
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
| [pjsaelin / Cubist](https://github.com/pjaselin/Cubist?tab=readme-ov-file)![](https://img.shields.io/github/stars/pjaselin/Cubist?style=social) | "A Python package for fitting Quinlan's Cubist regression model" |
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

Contributors with over 100 edits can be named coauthors in the citation of visible names. Otherwise, all contributors with fewer than 100 edits are included under "et al."

#### Bibtex

```
@misc{amli_repo,
  author={Patrick Hall and Daniel Atherton},
  title={Awesome Machine Learning Interpretability},
  year={2024},
  note={\url{https://github.com/jphall663/awesome-machine-learning-interpretability}}
}
```

#### ACM, APA, Chicago, and MLA

* **ACM (Association for Computing Machinery)**

Hall, Patrick, Daniel Atherton, et al. 2024. Awesome Machine Learning Interpretability. GitHub. https://github.com/jphall663/awesome-machine-learning-interpretability.

* **APA (American Psychological Association) 7th Edition**

Hall, Patrick, Daniel Atherton, et al. (2024). Awesome Machine Learning Interpretability [GitHub repository]. GitHub. https://github.com/jphall663/awesome-machine-learning-interpretability.

* **Chicago Manual of Style 17th Edition**

Hall, Patrick, Daniel Atherton, et al. "Awesome Machine Learning Interpretability." GitHub. Last modified 2023. https://github.com/jphall663/awesome-machine-learning-interpretability.

* **MLA (Modern Language Association) 9th Edition**

Hall, Patrick, Daniel Atherton, et al. "Awesome Machine Learning Interpretability." *GitHub*, 2024, https://github.com/jphall663/awesome-machine-learning-interpretability. Accessed 5 March 2024.
