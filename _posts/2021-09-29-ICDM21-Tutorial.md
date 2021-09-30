---
layout: post
title: ICDM 2021 Tutorial -- Automated Taxonomy Discovery and Exploration
---

## Time and Location
<br>

Time: TBD (concrete date within Dec. 7-10, 2021 will be added later)
Location: Zoom link will be added later

## Slides
<br>

To be added in [here]()

## Abstracts
<br>

People nowadays are inundated with vast amounts of text data (e.g., news articles, corporate reports, scientific papers, etc.). Turning massive text data into actionable knowledge is an essential research issue in data science. Based on our vision, it is highly beneficial to first structure raw text using taxonomies and then analyze structured text data in a more fine-grained and user-guided way.

In this tutorial, we provide a comprehensive overview of recent research in this direction. We first show a series of methods to identify concept phrases from text corpora and then present methods to organize identified concepts into taxonomies. After that, we introduce techniques to automatically enrich an existing taxonomy and discuss how to explore taxonomies for different downstream applications. Finally, we demonstrate on real-world datasets from multiple domains how different taxonomies can be constructed based on different user tasks and how they can empower knowledge discovery from text data.


## Outline
<br>

1. Introduction
	* Motivations: Why constructing taxonomies and leveraging them to facilitate knowledge discovery from text data?
	* An overview of tasks related to taxonomy discovery such as concept phrase mining, automated taxonomy construction, and taxonomy enrichment.
	* An overview of applications that can benefit from knowledge in automatically discovered taxonomies.
2. Phrase Mining
	* Why phrase mining and how to define properties of high-quality phrases?
	* Supervised phrase mining methods based on noun phrase chunking and dependency.
	* Weakly/Distantly supervised phrase mining methods utilizing external knowledge bases.
	* Unsupervised phrase mining methods exploring signals from topic model and pre-trained language model.
	* System demos and software introduction
3. Taxonomy Construction
    * How to represent a taxonomy based on different application needs?
    * Concept taxonomy construction
    	* Two-step approaches: first extract hypernymy pairs and then organize extracted pairs into taxonomy structure.
    	* End-to-end approaches: (1) supervised method based on structure prediction, and (2) weakly supervised method based on user seed guidance.
    * Topic taxonomy construction
        * Hierarchical topic modeling
        * Hierarchical clustering
        * Combining text data with network structure
4. Taxonomy Enrichment
    * What are different types of taxonomy enrichment?
    * WordNet enrichment method
    * General taxonomy expansion methods:
    	* Leveraging knowledge transfer techniques
    	* Modeling implicit taxonomic relation semantics
    	* Utilizing position-enhanced graph neural network
		* Combining features from multiple sources
    * General taxonomy modification methods:
        * Modifying existing taxonomic relations
        * Generating new emerging concepts for direct taxonomy completion
5. Taxonomy Empowered Applications
    * Weakly-supervised text classification
    	* One-level multi-class classification
		* Hierarchical multi-class classification
		* Hierarchical multi-label classification
    * Query understanding and recommender system
6. Summary and Future Directions
    * Summarizing presented principles and techniques
    * Discussing future research directions
    * Interacting with the audience and discussing how to discover and explore taxonomies based on their own data and applications.
7. Question Answering and Discussions

## Presenters
<br>

| ![Jiaming Shen](/images/ICDM2021/JiamingShenAvatar.jpg?raw=True)| **Jiaming Shen**, Ph.D. candidate, Computer Science, Univ. of Illinois at Urbana-Champaign (UIUC). His research focuses on unleashing hidden knowledge buried in unstructured text using taxonomy structures. He has been awarded several fellowships and scholarships, including a Brian Totty Graduate Fellowship and a Yunni \& Maxine Pao Memorial Fellowship. |
| ![Xiaotao Gu](/images/ICDM2021/XiaotaoAvatar.jpg?raw=True)| **Xiaotao Gu**, Ph.D. candidate, Computer Science, UIUC. His research focuses on automated knowledge mining from unstructured text data in real scenarios, e.g., with limited human annotation and computation resource. His research work has been applied in several real-world systems, including Google News, Google Search, and the AMiner literature search and analytic platform. |
| ![Yu Meng](/images/ICDM2021/YuMengAvatar.jpg?raw=True)| **Yu Meng**, Ph.D. candidate, Computer Science, UIUC. His research focuses on mining structured knowledge from massive text corpora with minimum human supervision. He received the Google Ph.D. Fellowship (2021) in Structured Data and Database Management. |
| ![Jiawei Han](/images/ICDM2021/JiaweiHanAvatar.jpg) | **Jiawei Han**, Michael Aiken Chair Professor, Computer Science, UIUC. His research areas encompass data mining, text mining, data warehousing, and information network analysis, with over 800 research publications. He is a Fellow of ACM, Fellow of IEEE, and received numerous prominent awards, including ACM SIGKDD Innovation Award (2004) and IEEE Computer Society W. Wallace McDowell Award (2009). |

