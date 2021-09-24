## Background for Ontology Development: Some Conceptual and Ontological Preliminaries 

**SUPPORT:** If you find value in my work, [support/donate here](https://gogetfunding.com/knowledge-organization-services-ontology-terminology-metadata-concept-analysis/).

### Semantic / Terminological / Knowledge Organization Systems
The following are some types of semantic/terminological/knowledge systems (or resources), using modified descriptions from [slide 5 of this Slideshare presentation](https://www.slideshare.net/skhan/ontology-dev?qid=8e6605c2-e7c7-4e76-b5d3-1d817b9e299b&v=&b=&from_search=4).

CAVEAT NOTE: there are different descriptions of these systems. E.g., some do not consider ontologies to be controlled vocabularies. And distinct disciplines and research areas may have unique meanings for them, disciplines such as AI, MBSE, library science, semntic web technology, formal ontology, (computational) linguistics, philosophy, data science, informatics, etc.   

BASIC TAKE-AWAY: a common aspect for all these strcutures is _the specification of some set of symbol-structures (e.g., set of terms, a vocabulary, etc.) which may or may have an ascribed computable set of meanings_.

NOTE: These systems are sometimes called 'knolwedge organization systems' or 'KOS' for short. However, that name is problematic if we do not assume any particular sense for 'knowledge', because more than knowledge (in an intuitive sense) can be captured. Defining 'knowledge' is a challenging task in any case. The AI community, however, may have a specific sense for it, which may or may not implicitly be assumed in the intended meaning and use of 'KOS', e.g., knowledge in sense of anything computably represented that an artificial system can act on, whether from sensors observing the external environment, from a knowledge base or knowledge model (e.g. ontology) in the system, etc.

NOTE: Each system has purposes and applications that may overlap with others. Some may be more structured, complex, or expressive than others.  

- **Controlled Vocabulary** = an organized set of term used to catalog and index content (or--more generally--used for a given project, topic, domain, application, or goal)
- **Classification** = a controlled vocabulary whose terms are grouped
- **Taxonomy** = a controlled vocabulary with some hierarchical structure (i.e., using structuring relationships such as 'broader-than', 'is-a-subclass-of', etc.)  
- **Thesaurus** = a controlled vocabulary with term relations
- **Ontology** = a controlled vocabulary with semantic relations, constraints, axioms, and rules.
- **Knowledge Base** = an ontology + instances of the classes in the ontology. (See distinction between A-Box and T-Box in AI)

From ["Knowledge Representation and Reasoning for Intelligent Software Systems"](https://ulir.ul.ie/bitstream/handle/10344/1780/2011_Vassev%20(d).pdf;sequence=2) we read (bold emphasis added to mark the additional system):

"Knowledge  is  often  best  under-stood as a set of related concepts. A **semantic network** is a directed graph consisting of nodes—which represent concepts—connected  by  edges—which represent semantic relations between those concepts. [...] the following relations are common: 
- instance: X is an instance of Y if X is a specific example of the general concept Y 
- isa: X isa Y if X is a subset of the more general concept Y 
- haspart: X haspart Y if the con-cept Y is a part of the concept X"

### What are those Semantic Systems Used for?
- to index, tag, semantically annotate, and categorize content (e.g. documents, text, data, and other resources) in order to facilitate search, their discovery and their retrieval 
- to represent things and knowledge in a machine-readable manner using the constructs or terms in the respective system
- to partially structure unstructured data by adding an external semantic layer (e.g., set of semantic annotations)
- to offer a knowledge-based model of some target universe of discourse (serving as background knowledge) in order to facilitate automation or reasoning (e.g., in AI systems) 

### A Relationship between Artificial Intelligence (AI) & Ontology Engineering - Knowledge repreesntation, reasoning, modeling, & engineering
Part of AI is about how to represent human knowledge in a way computer systems can process and act on, called **knowledge representation and reasoning** (KRR). 
It often involves creating a database to store content or knowledge (a **knowledgebase**) and a way to process or reason over that content.
We read "knowledge represenation (KR) is the process of identifying the implicit knowledge, semantics or structure in raw data (from a given domain), encoding it symbolically or formally into a (formal) KR language, reasoning over this encoded knowledge, to automatically derive new knowledge by inference" ([quote source](https://camilothorne.altervista.org/sem_web17/Suppl_KRn.pdf))

There are different approaches for doing knowlege represetnation, i.e., for encoding knowledge as it were. One approach, or one system/tool listed above, to KRR is to develop so-called **ontologies**.
Artificial languages (KRR languages), used to fomrally declare a vocabulary to compose computable expressions, are often used in KRR and ontology engineering.
"To achieve the precise semantics necessary for computational purposes, intelligent system designers often use logic to formalize KR" (source)[https://ulir.ul.ie/bitstream/handle/10344/1780/2011_Vassev%20(d).pdf;sequence=2]. However, there are other approaches besides formal logic.

### Perspectives on Ontology
From [this MIT lecture (PPT)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-871-knowledge-based-applications-systems-spring-2005/lecture-notes/lect22_ontolog.pdf) we read how ontology may be used for each distinct disciplinary purpose:
- In philosophy, ontology aims to categorize the world
- In library science, it helps "organize bibliographic world, model universal and domain knowledge" which may help access bibliographic entries
- In NLP, it aims to "model lexical and domain knowledge", to help with machine translation
- In AI, it aims to "model common sense and domain knowledge", and is sometimes used in KRR 
- In semantic web technologies, it "provide[s] semantics for web resources", helping to describe those resources

### Different contexts of vocabularies and sets of terms
- Natural language context. Here--our everyday speech--it is fluid, dynamic, and mutable over time. No one, no org., no project owns any word or phrase. 
- Organizational context: Here--as in a private company, government agency, etc.--there may be organization-specific vocabulary: each organization may have (in)formally used some terms which may or may not be different from natural language terms. An organizationare may also have terms of art unique to itself. An organization may have jargon.
- Research/Academic/other Project context. Here--a specific project--vocabulary may be formally specified to have specific meaning. It may or may not be similar to natural langauge terms. It may or may not involve jargon. 
-   Example: explicitly defining the vocabulary of an ontology, using some symbolic logic or some computable formalism (artificial language)
- Discipline-specific context. Here--as in physics or sociology--a discipline may have jardon, terms not used in everyday discourse, and terms with more precise meaning than the same terms used in natural language. 

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


