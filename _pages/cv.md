---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
[Download PDF]({{ site.baseurl }}/files/YasserZouzou_AcademicCV.pdf)

Education
======
* **MSc in Data Science, Sabanci University** *(2024)*
  * Thesis: Unsupervised detection of coordinated fake followers on social media
  * GPA: 3.95/4.0 
* **MSc in Civil Engineering, Erciyes University** *(2022)*
  * Thesis: Comparison of Regional and General Machine learning Models for Reference Evapotranspiration Prediction in Turkey
  * GPA: 4.0/4.0 
* **BSc in Civil Engineering, Damascus University** *(2018)*
  * GPA: 87/100 (3rd in class)

Work experience
======
* **AI Research Engineer, Huawei** *(Jan. 2024 - Present)*
  * Task-specific and general instruction SFT of LLMs
  * Synthetic data generation for SFT
  * Developing customized RAG and agentic workflows
  * Textual data curation, processing, and analysis
  * Experimenting with latest research on model structure and training improvement

Skills
======
* **Programming languages:** Python
* **Frameworks:** PyTorch
* **Libraries**: Pandas, Numpy, Matplotlib, NetworkX, transformers, accelerate
* **Other**:
  * Gephi (Network visualization)
  * Dify (Agent orchestration)
  * MySQL
* **Languages:** Arabic (Native), English (Fluent), Turkish (Fluent)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors and Awards
======
* **Sabanci University Teaching Awards** *(December 2023)*: Second place in the teaching assistant yearly awards.
* **[TUBITAK Scholarship](https://varollab.com/projects/chist-era.html)** *(Aug. 2023-Aug. 2024)*: Awarded a 100% tuition waiver and a monthly stipend as a researcher in the project [CON-NET](https://www.con-net-project.com/) funded by CHIST-ERA, EU, and TUBITAK 1071 programs.
* **Sabancı University Scholarship** *(Sep. 2022-Aug. 2023)*: Awarded a 100% tuition scholarship and a monthly stipend as an MSc student
* **[Turkiye Scholarships](https://www.turkiyeburslari.gov.tr)** *(Sep. 2019-Aug. 2022)*: Awarded a 100% tuition scholarship and a monthly stipend as an MSc Student

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
