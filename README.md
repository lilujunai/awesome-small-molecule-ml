# Awesome Small Molecule ML [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome papers, data sets, frameworks, packages, blogs, and other resources for generating small molecules and making property and activity predictions on them.

## Contents

* [Related lists](#related-lists)
* [Papers](#papers)
    * [Survey papers](#papers-surveys)
    * [Representation and transfer learning](#papers-representation)
    * [Generative algorithms](#papers-generative-algorithms)
    * [Hit finding and potency prediciton](#papers-hit-finding)
    * [ADME and toxicity prediction](#papers-adme-tox)
    * [Synthetic accessability and retrosynthetic planning](#papers-synthetic-accessibility)
    * [Visualization and interpretability](#papers-viz)
* [Data sets](#datasets)
* [Frameworks](#frameworks)
* [Libraries](#libraries)
* [Blogs](#blogs)
* [Twitter](#twitter)

## Related lists
* [Awesome cheminformatics](https://github.com/hsiaoyi0504/awesome-cheminformatics)

## Papers

<a id="papers-surveys"></a>
### Survey papers

* Walters and Barzilay, 2021. [Critical assessment of AI in drug discovery](https://doi.org/10.1080/17460441.2021.1915982).
* Coley, 2020. [Defining and Exploring Chemical Spaces](https://dspace.mit.edu/handle/1721.1/131238).
* Chuang et al, 2020. [Learning Molecular Representations for Medicinal Chemistry](https://pubs.acs.org/doi/10.1021/acs.jmedchem.0c00385).
* Walters and Barzilay, 2020. [Applications of Deep Learning in Molecule Generation and Molecular Property Prediction](https://pubs.acs.org/doi/10.1021/acs.accounts.0c00699).
* Cai et al, 2020. [Transfer Learning for Drug Discovery](https://doi.org/10.1021/acs.jmedchem.9b02147).

<a id="papers-representation"></a>
### Representation and transfer learning

* Ahmad et al, 2021. [ChemBERTa-2: Towards Chemical Foundation Models](https://cloud.ml.jku.at/s/dZ7CwqBkHX97C6S). [[Code](https://github.com/seyonechithrananda/bert-loves-chemistry)]
* Chuang and Keiser, 2020. [Attention-Based Learning on Molecular Ensembles](https://arxiv.org/abs/2011.12820).
* Li and Fourches, 2020. [Inductive transfer learning for molecular activity prediction: Next-Gen QSAR Models with MolPMoFiT](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00430-x). [[Code](https://github.com/XinhaoLi74/MolPMoFiT)]
* Hu et al, 2019. [Strategies for Pre-training Graph Neural Networks](https://arxiv.org/abs/1905.12265). [[Code](https://github.com/snap-stanford/pretrain-gnns)]
* Yang et al, 2019. [Analyzing Learned Molecular Representations for Property Prediction (Chemprop)](https://pubs.acs.org/doi/10.1021/acs.jcim.9b00237) [[Code](https://github.com/chemprop/chemprop)]

<a id="papers-generative-algorithms"></a>
### Generative algorithms

* Berenger and Tsuda, 2021. [Molecular generation by Fast Assembly of (Deep)SMILES fragments](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00566-4). [[Code](https://github.com/UnixJunkie/FASMIFRA)]
* Takeuchi et al, 2021. [R-group replacement database for medicinal chemistry](https://www.future-science.com/doi/10.2144/fsoa-2021-0062).
* Imrie et al, 2020. [Deep Generative Models for 3D Linker Design](https://pubs.acs.org/doi/10.1021/acs.jcim.9b01120). [[Code](https://github.com/oxpig/DeLinker)]
* Jin et al, 2020. [Hierarchical Generation of Molecular Graphs using Structural Motifs](https://arxiv.org/abs/2002.03230). [[Code](https://github.com/wengong-jin/hgraph2graph)]
* Polishchuk, 2020. [CReM: chemically reasonable mutations framework for structure generation](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00431-w). [[Code](https://github.com/DrrDom/crem)]
* Brown, 2019. [GuacaMol: Benchmarking Models for de Novo Molecular Design](https://doi.org/10.1021/acs.jcim.8b00839). [[Code](https://github.com/BenevolentAI/guacamol)]
* Popova et al, 2019. [MolecularRNN: Generating realistic molecular graphs with optimized properties
](https://arxiv.org/abs/1905.13372).
* You et al, 2019. [Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation](https://arxiv.org/abs/1806.02473). [[Code](https://github.com/bowenliu16/rl_graph_generation)]
* Zhou et al, 2019. [Optimization of Molecules via Deep Reinforcement Learning](https://doi.org/10.1038/s41598-019-47148-x). [[Code (official version)](https://github.com/google-research/google-research/tree/master/mol_dqn)] [[PyTorch implementation](https://github.com/aksub99/MolDQN-pytorch)]
* Jin et al, 2018. [Junction Tree Variational Autoencoder for Molecular Graph Generation](https://arxiv.org/abs/1802.04364). [[Code](https://github.com/wengong-jin/icml18-jtnn)]
* Merk et al, 2018. [De Novo Design of Bioactive Small Molecules by Artificial Intelligence](https://pubmed.ncbi.nlm.nih.gov/29319225/).

<a id="papers-hit-finding"></a>
### Hit finding and potency prediciton

* Bender et al, 2021. [A practical guide to large-scale docking](https://www.nature.com/articles/s41596-021-00597-z).
* García-Ortegón et al, 2021. [DOCKSTRING: easy molecular docking yields better benchmarks for ligand design](https://arxiv.org/abs/2110.15486). [[Code](https://github.com/dockstring/dockstring)] [[Data](https://figshare.com/s/95f2fed733dec170b998)]
* Gentile et al, 2020. [Deep Docking: A Deep Learning Platform for Augmentation of Structure Based Drug Discovery](https://pubs.acs.org/doi/10.1021/acscentsci.0c00229). [[Code](https://github.com/jamesgleave/Deep-Docking-NonAutomated)]
* Cáceres et al, 2020. [Adding Stochastic Negative Examples into Machine Learning Improves Molecular Bioactivity Prediction](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00565).
* Lin et al, 2019. [Ultra-large library docking for discovering new chemotypes](https://www.nature.com/articles/s41586-019-0917-9).

<a id="papers-adme-tox"></a>
### ADME and toxicity prediction

* Siramshetty et al, 2021. [Validating ADME QSAR Models Using Marketed Drugs](https://journals.sagepub.com/doi/10.1177/24725552211017520).
* Göller et al, 2020. [Bayer’s in silico ADMET platform: a journey of machine learning over the past two decades](https://doi.org/10.1016/j.drudis.2020.07.001).
* Ryu et al, 2020. [DeepHIT: a deep learning framework for prediction of hERG-induced cardiotoxicity](https://doi.org/10.1093/bioinformatics/btaa075). [[Code](https://bitbucket.org/krictai/deephit/src/master/)]
* Lombardo et al, 2018. [In Silico Absorption, Distribution, Metabolism, Excretion, and Pharmacokinetics (ADME-PK): Utility and Best Practices](https://pubs.acs.org/doi/10.1021/acs.jmedchem.7b00487).

<a id="papers-synthetic-accessibility"></a>
### Synthetic accessability and retrosynthetic planning

* Coley et al, 2018. [SCScore: Synthetic Complexity Learned from a Reaction Corpus](https://pubs.acs.org/doi/10.1021/acs.jcim.7b00622). [[Code](https://github.com/connorcoley/scscore)] [[DeepChem implementation](https://github.com/deepchem/deepchem/blob/master/deepchem/models/scscore.py)]

<a id="papers-viz"></a>
### Visualization and interpretability

* Humer et al, 2021. [ChemInformatics Model Explorer (CIME): Exploratory analysis of chemical model explanations](https://chemrxiv.org/engage/chemrxiv/article-details/61a6579f568d33caaa4bff69). [[Code](https://github.com/jku-vds-lab/cime)]
* Matveieva and Polishchuk, 2021. [Benchmarks for interpretation of QSAR models](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00519-x). [[Code](https://github.com/ci-lab-cz/ibenchmark)]
* Atsushi et al, 2019. [Integrating the Structure–Activity Relationship Matrix Method with Molecular Grid Maps and Activity Landscape Models for Medicinal Chemistry Applications](https://pubs.acs.org/doi/10.1021/acsomega.9b00595).
* Naveja and Medina-Franco, 2019. [Finding Constellations in Chemical Space Through Core Analysis](https://www.frontiersin.org/articles/10.3389/fchem.2019.00510/full).


## Data sets and benchmarks
* Therapeutic Data Commons
* MoleculeNet
* DrugMatrix
* NCATS
* [Enamine Real database](https://enamine.net/compound-collections/real-compounds/real-database)
* Townshend et al, 2021. [ATOM3D: Tasks On Molecules in Three Dimensions](https://arxiv.org/abs/2012.04035)
* [The Open Reaction Database](https://docs.open-reaction-database.org/en/latest/)
* [Zinc](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00675)

## Frameworks

## Libraries
* [AutoDock Vina](https://autodock-vina.readthedocs.io/en/latest/index.html)
* [BioPandas](http://rasbt.github.io/biopandas/)
* [CReM - chemically reasonable mutations](https://github.com/DrrDom/crem)
* [pdb-tools](http://www.bonvinlab.org/pdb-tools/)
* [rd_filters](https://github.com/PatWalters/rd_filters)

## Blogs

## Twitter
* [Regina Barzilay](https://twitter.com/BarzilayRegina)
* [Bob the Grumpy Med Chemist](https://twitter.com/med_chemist)
* [John Chodera](https://twitter.com/jchodera)
* [Connor W. Coley](https://twitter.com/cwcoley)
* [Greg Landrum](https://twitter.com/dr_greg_landrum)
* [pen(Taka)](https://twitter.com/iwatobipen)
* [Bharath Ramsundar](https://twitter.com/rbhar90)
* [Marwin Segler](https://twitter.com/marwinsegler)
* [Patrick Walters](https://twitter.com/wpwalters)
