---
permalink: /
title: "About Chase Brown"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Current Research Topics
--------------------------

My current research is in developing and utilizing the tools from an emerging field referred to as the "science of Science" in order to:

    Understand and find artificial neural network architectures for the neural processes by which researchers make decisions on research topics
    Develop automated processes for generating hypotheses and scoring them via a test of likelihood of a valid discovery
    Create a drug discovery system based off of conditional responses to drugs (tissue-specific, age-specific, or drug synergy responses)
    Use the discovery system to find new, potentially synergistic therapies for glioblastoma

## Literature-based Discovery
-----------------------------

Literature based discovery (LBD) is a well established field with a history closely linked to network analysis. LBD is typically performed by constructing a large database of textual information (such as abstracts from MEDLINE), extracting entities or concepts of interest from each unit of text, and creating a network or graph of the entities, with edges between entities that co-occur within the same document. In this manner, a large network of entities and their relations is created as a type of 'condensation' or 'compression' of the knowledge within the text. Although this method may seem crude and lacking in contextual detail for each entity and it's relation to other entities, this method has provided many successful predictions of the trajectory of science over the years.1,2

However, progress within the field is quite sparse, as the differences between recently published articles2 and similar research over a decade ago1 are minimal, if existent at all. Therefore, I am interested in pushing the boundaries of this field further, with the incorporation of multiple relationship type, transcriptomic, epigenetic, and drug perturbation information.


## Natural Language Processing
------------------------------

Natural Language Processing is a necessary tool for creating literature-based discovery systems. In order to improve upon previously implemented LBD systems, information must be extracted regarding the relationships between the entities within the text. One example of the types of available relationships would be inhibition between a drug and an enzyme (such as Rapamycin inhibits mTOR). There are numerous methodologies and tools used to extract these types of relationships developed over the years within the field of NLP. However, not all of them are highly performant.


## Neural Networks
------------------

Recently, neural networks have exploded in popularity due to the increase in available computational power via GPUs and TPUs. Additionally, these algorithms have, in recent years, allowed huge performance gains for language tasks due to thier excellent ability to model non-linear data.
Several different types of neural architectures have been implemented with the purpose of extracting entities and relationships from text. Early work in NLP showed that simple multi-layer perceptrons can achieve performances similar to that of support vector machines in named entity recognition.3 Additionally, some convolutional network architectures have seen success in similar textual tagging tasks, wherein only a relatively small and local amount of contextual information is required to achieve a decent performance. While these simpler neural systems have seen some success comparable to support vector machines or CRFs, recent works have seen a great increase in performance metrics via the use of recurrent neural networks (RNNs) and more specifically long short-term memory recurrent neural networks (LSTMs). However, the most recent and powerful neural method, neural attention has been made extremely influential to the field. Some of the earliest recognition of the utility of attention mechanisms came from combinations of LSTMs and attention.4 Nonetheless, the acknowledgement that the attention mechanism itself may be useful on it’s own came from a major paper in the field, with a fitting title Attention is all you need.5 The key finding from this article which evolved into major advancements for many fields is the Transformer architecture. Specifically within the field of NLP, the Transformer architecture saw its first huge success in bidirectional encoder representations from transformers (BERT).6 BERT is a masked language model, pre-trained to perform tasks such as predicting missing words and next sentence similarity. This type of pretraining step allowed the fine-tuned berT model to outperform state-of-the-art models in several NLP areas, such as NER, relationship extraction, question answering, and textual entailment. Several other models have followed which expand upon BERT’s original capabilities, such as transformer-XL7, ALBERT8, DistilBERT9, and RoBERTa.10


## Algebraic Topology
---------------------

Algebraic Topology is a field which has great potential for answering questions in neural processes, both artificial and biological in nature.11,12 Addiitionally, a tool within the field of Algebraic Topology, known as Persistent Homology, allows the study of topological holes within datasets, which are typically reffered to as 'knowledge gaps' within the context of LBD co-occurence networks.
(Expanding upon this section soon.)


## Drug Discovery
-----------------

While LBD techniques have continued to receive attention even in today's academic environment, LBD via co-occurrence has been thoroughly investigated for decades. Therefore, it is likely that, in order to tackle questions regarding disease in today's academic environment, more is required than standard literature-based discovery techniques.

In order to address this disjoint between text-only sources and biological assay driven discoveries, we seek to develop both solutions, and join them together to search the solution space with more complete information.


## Tensor Fields for Signature Searches
---------------------------------------

The realization of drug-induced differential gene signatures as a useful tool for drug discovery is pervasive throughout our biological understanding.

However, few groups have noticed the alteration of drug-induced differential gene signatures within different conditions, such as tissue, age, or sex.

One manner to address this issue is to simply find data for each tissue or condition and evaluate the differential gene list between drug-treated and control. However, while this approach (if conditions are considered at all) is the standard, much more information can be gained from considering generalities between conditions and drugs.

In order to do this, we look at the entire transcriptome available for all conditions and drug treatments available via public information (most notably, the LINCS dataset). By using tensor fields, we can look at smoothed transitions of drug-induced differential gene vectors within a conditional vector space.

This analysis allows to gain an understanding of the attractors within the vector field of biologically allowable states.


## Glioblastoma
---------------

Glioblastoma is a common nervous system tumor with an abysmal survival rate, despite continual treatment efforts. Bioinformatics systems Rephetio13 and Iridescent1 provide drug repurposing predictions, and can suggest small-molecule therapies for glioblastoma. Similarly, suggestions for transmembrance protein targets have been suggested via Iridescent, which have yeilded viable immunotherapies for the disease.
Unfortunately, however, the survival rate for this disease still maintains one of the hardest to combat, as several technical challenges specific to brain caner hinder progress, such as the blood-brain barrier. Therefore, our automated discovery system which incorporates literature, transcriptomic, and epigenetic data will be challenged to find novel insights and therapies for this disease.


## Previous Research
--------------------

My previous research was heavily focused upon nanomaterials, optoelectronics, photophysics, and heterogeneous catalysis.

I previously worked for SouthWest Nanotechnologies, a company which was founded by a highly respected heterogeneous catalysis professor, Daniel E Resasco. The company was founded upon the improvements to SWCNT production allowed by the heterogeneous catalyst of Cobalt and Molybdenum (CoMo) on silica or Alumina based supports. My research at the company started with investigation into the characterization of SWCNT properties such as the electronic and optical properties, diameter, and length; however, it soon increased in scope to include separations and heterogeneous catalysis synthesis and optimization.

I additionally began working towards a Master's degree while also maintaining my position as a Lead Research and Development Engineer at SWeNT. The topic of my Master's thesis involved my expertise on SWCNT properties, but relied more heavily upon heterogeneous catalysis towards biofuel production (rather than SWCNT production) and defect or functionalization of SWCNTs (rather than optical properties of pristine SWCNTs).


## References:
--------------

    Wren, Jonathan D., Raffi Bekeredjian, Jelena A. Stewart, Ralph V. Shohet, and Harold R. Garner. "Knowledge discovery by automated identification and ranking of implicit relationships." Bioinformatics 20, no. 3 (2004): 389-398.
    Pyysalo, Sampo, Simon Baker, Imran Ali, Stefan Haselwimmer, Tejas Shah, Andrew Young, Yufan Guo et al. "LION LBD: a literature-based discovery system for cancer biology." Bioinformatics 35, no. 9 (2019): 1553-1561.
    Szarvas, György, Richárd Farkas, László Felföldi, András Kocsor, and János Csirik. "A highly accurate Named Entity corpus for Hungarian." In LREC, pp. 1957-1960. 2006.
    Luo, Ling, Zhihao Yang, Pei Yang, Yin Zhang, Lei Wang, Hongfei Lin, and Jian Wang. "An attention-based BiLSTM-CRF approach to document-level chemical named entity recognition." Bioinformatics 34, no. 8 (2018): 1381-1388.
    Vaswani, Ashish, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, and Illia Polosukhin. "Attention is all you need." In Advances in neural information processing systems, pp. 5998-6008. 2017.
    Devlin, Jacob, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova. "Bert: Pre-training of deep bidirectional transformers for language understanding." arXiv preprint arXiv:1810.04805 (2018).
    Dai, Zihang, Zhilin Yang, Yiming Yang, Jaime Carbonell, Quoc V. Le, and Ruslan Salakhutdinov. "Transformer-xl: Attentive language models beyond a fixed-length context." arXiv preprint arXiv:1901.02860 (2019).
    Lan, Zhenzhong, Mingda Chen, Sebastian Goodman, Kevin Gimpel, Piyush Sharma, and Radu Soricut. "Albert: A lite bert for self-supervised learning of language representations." arXiv preprint arXiv:1909.11942 (2019).
    Sanh, Victor, Lysandre Debut, Julien Chaumond, and Thomas Wolf. "DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter." arXiv preprint arXiv:1910.01108 (2019).
    Liu, Yinhan, Myle Ott, Naman Goyal, Jingfei Du, Mandar Joshi, Danqi Chen, Omer Levy, Mike Lewis, Luke Zettlemoyer, and Veselin Stoyanov. "Roberta: A robustly optimized bert pretraining approach." arXiv preprint arXiv:1907.11692 (2019).
    Rieck, Bastian, Matteo Togninalli, Christian Bock, Michael Moor, Max Horn, Thomas Gumbsch, and Karsten Borgwardt. "Neural persistence: A complexity measure for deep neural networks using algebraic topology." arXiv preprint arXiv:1812.09764 (2018).
    Sizemore, Ann, Chad Giusti, Richard F. Betzel, and Danielle S. Bassett. "Closures and cavities in the human connectome." arXiv preprint arXiv:1608.03520 (2016).
    Himmelstein, Daniel Scott, Antoine Lizee, Christine Hessler, Leo Brueggeman, Sabrina L. Chen, Dexter Hadley, Ari Green, Pouya Khankhanian, and Sergio E. Baranzini. "Systematic integration of biomedical knowledge prioritizes drugs for repurposing." Elife 6 (2017): e26726.



## Current Research
-------------------

  I am currently a student in the Neuroscience Ph.D program at the University of Oklahoma Health Sciences Center. As a member of the bioinformatics group led by Dr. Jonathan Wren, I construct novel artificial intelligence architectures for drug repositioning and discovery using scientific text and biological networks.
  My research interests include machine learning, topological data analysis, DNA methylation, aging, glioblastoma, nanotechnology, photophysics, and particle physics.


## Background
-------------

  Throughout my Master's in Chemical and Biological Materials Engineering on the separation and characterization of nanomaterials applied towards biofuel catalysis, my excitement towards modeling physical and biological phenomenon grew, leading my career path towards software development for modeling biological phenomenon in brain cancer.
  I received a Master's in Chemical and Biological Materiels Engineering from the University of Oklahoma in May of 2016. During this time I worked with Dr. Steven Crossley (PI) and Dr. Daniel Resasco to synthesize heterogenous catalytic supports, consisting of magnetic nanoparticles and single-walled carbon nanotubes, for use in multiphase biofuel reactors.
  In the spring of 2014, I graduated with a B.S. in Chemical and Biological Materials Engineering and worked as the lead Research and Development Engineer at a Nanotechnology company developing, characterizing, and separating new materials for electronic applications.

## Information
--------------

PhD Candidate, Neuroscience
Masters of Science, Chemical and Biological Materials Engineering

-  chase-brown@ouhsc.edu
-  University of Oklahoma Health Sciences Center
-  Bioinformatics and Machine Learning Laboratory
-  Arthritis and Clinical Immunology Program, Oklahoma Medical Research Foundation


