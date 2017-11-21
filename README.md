# Replication Package for "Topic-based Software Defect Explanation"

Tse-Hsun Chen, Stephen W. Thomas, Meiyappan Nagappan, and Ahmed E. Hassan  
[Journal of Systems and Software, vol. 129, 2017](https://doi.org/10.1016/j.jss.2016.05.015)

Abstract: Researchers continue to propose metrics using measurable aspects of software systems to understand software quality. However, these metrics largely ignore the functionality, i.e., the conceptual concerns, of software systems. Such concerns are the technical concepts that reflect the system’s business logic. For instance, while lines of code may be a good general measure for defects, a large file responsible for simple I/O tasks is likely to have fewer defects than a small file responsible for complicated compiler implementation details. In this paper, we study the effect of concerns on software quality. We use a statistical topic modeling approach to approximate software concerns as topics (related words in source code). We propose various metrics using these topics to help explain the file defect-proneness. Case studies on multiple versions of Firefox, Eclipse, Mylyn, and NetBeans show that (i) some topics are more defect-prone than others; (ii) defect-prone topics tend to remain so over time; (iii) our topic-based metrics provide additional explanatory power for software quality over existing structural and historical metrics; and (iv) our topic-based cohesion metric outperforms state-of-the-art topic-based cohesion and coupling metrics in terms of defect explanatory power, while being simpler to implement and more intuitive to interpret.

## Bibtex

```bibtex
@article{Chen:2017:TSD:3104915.3104981,
 author = {Chen, Tse-Hsun and Shang, Weiyi and Nagappan, Meiyappan and Hassan, Ahmed E. and Thomas, Stephen W.},
 title = {Topic-based Software Defect Explanation},
 journal = {J. Syst. Softw.},
 issue_date = {July 2017},
 volume = {129},
 number = {C},
 month = jul,
 year = {2017},
 issn = {0164-1212},
 pages = {79--106},
 numpages = {28},
 url = {https://doi.org/10.1016/j.jss.2016.05.015},
 doi = {10.1016/j.jss.2016.05.015},
 acmid = {3104981},
 publisher = {Elsevier Science Inc.},
 address = {New York, NY, USA},
 keywords = {Code quality, Cohesion, Coupling, LDA, Metrics, Topic modeling},
} 
```

## Data and Scripts

- Topic Informaton Data (topic defect density and words etc.)
  - [Topic Information (all systems)](https://github.com/SAILResearch/replication-defect_explanation_topicmodel/releases/latest)
