## Background - Preliminaries of Ontology Development: Some Conceptual and Ontological Distinctions 

If you find value in my work, [support/donate here](https://gogetfunding.com/knowledge-organization-services-ontology-terminology-metadata-concept-analysis/).

### Semantic / Terminological / Knowledge Organization Systems
The following are some types of semantic/terminological/knowledge systems (or resources), using modified descriptions from [slide 5 of this Slideshare presentation](https://www.slideshare.net/skhan/ontology-dev?qid=8e6605c2-e7c7-4e76-b5d3-1d817b9e299b&v=&b=&from_search=4). 
CAVEAT: there are different descriptions of these systems. E.g., some do not consider ontologies to be controlled vocabularies. And distinct disciplines and research areas may have unique meanings for them, disciplines such as AI, MBSE, library science, semntic web technology, formal ontology, (computational) linguistics, philosophy, data science, informatics, etc.   
NOTE: These systems are sometimes called 'knolwedge organization systems'. However--from an analytical perspective--that name is problematic because more than knowledge can be captured, and defining 'knowledge' is contentious. 
Each system has purposes and applications that may overlap with others. Some may be more structured, complex, or expressive than others.  

- **Controlled Vocabulary** = an organized set of term used to catalog and index content (or--more generally--used for a given project, topic, domain, application, or goal)
- **Classification** = a controlled vocabulary whose terms are grouped
- **Taxonomy** = a controlled vocabulary with some hierarchical structure (i.e., using structuring relationships such as 'broader-than', 'is-a-subclass-of', etc.)  
- **Thesaurus** = a controlled vocabulary with term relations
- **Ontology** = a controlled vocabulary with semantic relations, constraints, axioms, and rules.
- **Knowledge Base** = an ontology + instances of the classes in the ontology. (See distinction between A-Box and T-Box in AI)

### What are those Semantic Systems Used for?
- to index, tag, semantically annotate, and categorize content (e.g. documents, text, data, and other resources) in order to facilitate search, their discovery and their retrieval 
- to represent things and knowledge in a machine-readable manner using the constructs or terms in the respective system
- to partially structure unstructured data by adding an external semantic layer (e.g., set of semantic annotations)
- to offer a knowledge-based model of some target universe of discourse (serving as background knowledge) in order to facilitate automation or reasoning (e.g., in AI systems) 

### A Relationship between Artificial Intelligence (AI) & Ontology Engineering - Knowledge repreesntation, reasoning, modeling, & engineering
Part of AI is about how to represent human knowledge in a way computer systems can process and act on, called **knowledge representation and reasoning** (KRR). 
It often involves creating a database to store content or knowledge (a **knowledgebase**) and a way to process or reason over that content.
We read "knowledge represenation (KR) is the process of identifying the implicit knowledge, semantics or structure in raw data (from a given domain), encoding it symbolically or formally into a (formal) KR language, reasoning over this encoded knowledge, to automatically derive new knowledge by inference" ([quote source](https://camilothorne.altervista.org/sem_web17/Suppl_KRn.pdf))

There are different approaches for doing knowlege represetnation. One approach, or one tool, to KRR is to develop so-called **ontologies**.
Artificial languages (KRR languages), used to fomrally declare a vocabulary to compose computable expressions, are often used in KRR and ontology engineering.

### The different contexts for vocabularies On the purpose of the vocabulary being developed
Consider and ask: what is the purpose of the vocabulary
First there is natural language. Here, no one owns any word or phrase. It is fluid, dynamic, and mutuble over time.
T

**Some Basic Distinctions often made in modeling (conceptual, ontological, semantic, linguistic, etc.)** 
These distinctions are partially drawn from abstract and philosophical inquiry. The reader in encouraged to review literature on metaphysics.

### The Generic vs. The Specific - Genericity vs. Specificity and Particularity

The concept of the generic, the general, the universal, etc. is distinguished from that of the specific, the indvidiual, the particular, etc. 
Historically this is partially a reflection of human philosophical inquiry into attribute-agreement, or how things can be similar, how the seem to have the same attributes, characteristics, etc. 

This is basic distinction is exemplified by some more specific ones such as:

* category - instance
* type - instance
* kind - instance
* class - member
* set - element

Caution: the way categories, types, kinds, and classes are defined--which characteristics are chosen as exemplifying the given category--varies. So if you want to specify the type of an instance, you should consider how define the type and/or be aware of how a pre-defined type characterizes your given instance(s). 

### Characteristics vs. Possessors of characterstics

This is the distinction between a property, feature, attribute, quality (or characteristic) and something that is said to possess, have or bear it, i.e., a property-bearer.

## Copyright
© 2019-2021, Robert John Rovetto. All right reserved.
Not authorized for commercial use unless explicitly negotiated with the author. Citation/attribution required.


