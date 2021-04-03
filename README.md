<div align="center">
<h1>Machine Learning Ontology Research</h1>

[Julião Braga](http://www.braga.net.br), [Francisco Regateiro](https://fenix.tecnico.ulisboa.pt/homepage/ist13522) and [Joaquim Ramos Dias](https://fenix.tecnico.ulisboa.pt/homepage/ist13137) 
</div>

## 1. Preliminaries

The **ml-ontology-version.owl** file (Protégé 5 compatible, available in https://osf.io/chu5q/), is an ontology in the Machine Learning domain, including algorithms, problems, tools, and other associated features. This ontology is being developed in an interactive collaboration process involving human beings and software agents.

### In this version, here are some of the Ontology Metrics in Protégé's Active Ontology.
- Axiom: 1,877
- Logical axiom count: 1,157
- Class count: 433
- Object property count: 56

## 2. Introduction

Machine Learning Ontology (MLO) is built using Protégé and is based on seven higher level
classes visible in the figure below:

<div align="center">
  <img src="http://a2rd.net.br/img/mlontologyTopClasses600.jpg" width="600px" height="349px">.
  
  Figure 1. Top level classes of the 
</div>

The main characteristics of these seven highest level classes are:

- **Algorithms:** A set of rules that precisely defines a sequence of operations, which would include all computer programs, including programs that do not perform numeric calculations, and (for example) any prescribed bureaucratic procedure. 
- **Applications:** the action of putting something into operation.
- **Dependencies:** What are the prerequisites for solving an algorithm or problem and what are the requirements for a tool to be executed.
- **Dictionary:** Acronyms, nicknames and texts for which an interpretation is required.
- **Frameworks:** A set of tools and associated utilities for solving and implementing algorithms, problems or applications
- **Involved:** People or institutions that created and improved the available resources to facilitate the use and application of Machine Learning. 
- **MLTypes:** Usual classification of Machine Learning algorithms.  Although, more recently, the literature is adopting only three types of Machine Learning -- (a) SupervisedLearning, (b) Unsupervised Learning, (c) ReinforcementLearning -- we are initially adopting two additional types -- (d) AutoML, (e) Semi-Supervised Learning -- which eventually may show changes in types,  for less or for more depending on objects added or removed (Figure 2).

<div align="center">
  <img src="http://a2rd.net.br/img/P5-MLTypesHierarchy.jpg">.
  
 Figure 2 Mahine Line Types in MLO
</div>

## 3. Collaboration in the MLOnto construction

One of the main motivations for the creation of **MLOnto** is a model to support autonomous agents in applications over the Internet Infrastructure, called **Structure for Knowledge Acquisition, Use, Learning and Collaboration** (SKAU). A partial view of SKAU can be seen in Figure 3.

<div align="center">
  <img src="http://a2rd.net.br/img/partialSKAU.jpg">.
  
 Figure 3 SKAU. Partial View. Source: (BRAGA, 2019)
</div>

The agents of the SKAU model are part of another model called **Autonomous Architecture Over Restricted Domains** (A2RD) thatthat make use of and update data from a knowledge base, whose content is formed by ontology bases (BRAGA, 2019). A2RD is a model in four layers, in which different types of agents live with common objectives. An A2RD can host in the domain of an Autonomous System (AS) which, together with other ASes form the Internet Infrastructure. The other components of the partial SKAU environment (Fig. 3) can be ignored in this context.

An ontology like **MLOnto** is very large and complex. The chances of success in an undertaking like this depend on the collaboration of two key stakeholders: (a) the human being, collaborating in the construction, updating and/or complement the **MLOnto** through small others ontologies and (b) specialized autonomous agents dedicated to ensuring the construction of ontologies from unstructured databases, such as manuals, Web sites, among others, ensuring that all information collected and of interest to the **MLOnto** is properly updated. Agents are exclusive collaborators with very specific guidelines. Therefore, they can only serve the production of axioms in the **.owl** format.
Humans can collaborate over **.owl** files and benefit from the entire knowledge base in the SKAU environment.

The collaboration mechanism is an extremely sensitive process and must follow well-established rules. For this reason, a model was designed as shown in the Figure 4.

<div align="center">
  <img src="http://a2rd.net.br/img/ColaboratorModel.jpg">.
  
 Figure 4 Collaboration Model
</div>

Both of collaborators, human beings and specialized agents can create ontologies using any construction tool, as long as they use the **Web Ontology Language** (OWL) and the seven highest level classes included in the MLO organization as discussed above.

Each collaborator has a unique number that identifies and authorizes operations on **MLOnto** axioms (inclusion, updating, exclusion). This number is previously defined by the project coordinator. Thus, the collaborators’ files will be identified with the name mloCn.owl, where **n** is the number that identifies the collaborator. The collaborators’ productions are submitted to a set of procedures **P** that appropriately create, add or change axioms stored in the SKAU environment knowledge base, in the form of **.json** files and which are named *mlom.json*, where m is a number that identifies any of the files. The list of the **.json** files produced by the procedures on the files created by the collaborators can be seen in Figure 5.

<div align="center">
  <img src="http://a2rd.net.br/img/SKAUxmlo.jpg">.
  
 Figure 5 The relationship between **.json** files and the SKAU environment knowledge base
</div>

The representation of the knowledge base, in the SKAU model as a set of ontologies, some in the **.json** format, is appropriate to make the process of use by the A2RD agents and reasoning devices more effective and faster.

If you want more information, please email to **info at a2rd dot net dot br**.

## 4. References

BRAGA, J.Environment for Knowledge Acquisition by Agents in Internet Infrastructur-eRestricted Domains. Tese (Doutorado) — Instituto Superior Tecnico & UniversidadePresbiteriana Mackenzie, 2019. DOI: 10.31237/osf.io/83ztf. English version translatedby author. Available in https://thesiscommons.org/83ztf/.

**Content license:** [Creative Commons 4.0 BY](http://creativecommons.org/licenses/by/4.0/) 
