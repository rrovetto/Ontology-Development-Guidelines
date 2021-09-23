# Ontology Development Guidelines (manual approach)
There are different methods, both automated and manual, to develop an ontology. This repository contains descriptions that succinctly explain one way to manually develop an ontology, and offers guidelines. NOTE: this is based on my limited experience and studies. The reader is encouraged to look at the diverse and relevant content from around the globe.   

### Related 
- [Ethical aspects of Ontology & Semantic modeling](https://github.com/rrovetto/Ethical-Ontology-Development)
- [Myths of Ontology Development & Use](https://github.com/rrovetto/Ethical-Ontology-Development/blob/master/Myths-Of-Ontology-Development.md).
### Support
If you find value in my work, please [support/donate here](https://gogetfunding.com/knowledge-organization-services-ontology-terminology-metadata-concept-analysis/). Financial support is needed to sustain development.

**For Hire**
- [Purchase services, products, or schedule a meeting at this link](https://tinyurl.com/yas7trzy)
- [List of Ontology Education (PPT file)](https://www.slideshare.net/RobertRovetto/ontology-courses-education)
- [List of Ontology Services (PPT file)](https://www.slideshare.net/RobertRovetto/ontology-services-238070099)

## Ontology Design Approaches
- **Botton-Up development from data (example 1)**: examine data and the identify the relevant subject matter. create ontology constructs (classes, etc.) from what the data is about (e.g., only classes for what the data contains).
- **Botton-Up development from subject matter (example 2)**: examine the subjectmatter (e.g., corpus documents, nomenclature, etc.) and create corresponding ontology constructs for the most common categories and concepts found in the subjectmatter.
- **Top-Down development (example)**: identify and create ontology constructs independent of examining data, but which can annotate the data. E.g., create abstract classes and modify accordingly once you examine the data and the intended meaning of the datasets and data elements. 
- **Hybrid development**: a combination of both bottom-up & top-down.

## A Generic Ontology Development Methodology (manual development)


### Stages of Ontology Development (dynamic and iterative)
A manual computational ontology development methodology includes the following activities: identifying and scoping your target subject-matter, set of concepts, data; subject/domain research; listing or creating a defined set of terms; listing statements and pieces of knowledge (e.g., general facts of the domain) to be captured; a taxonomy and classification system using the specified terminology; computational formalization of the terminological system; computational formalization of the knowledge statements; identifying applications. The development process is **iterative** and **non-linear**: some phases (or steps) of the development process may be performed concurrently with others and revisited. 

### 1. Purpose, Subject-matter & Data 
- Identify purpose(s), goal(s), or function(s), application(s) for the ontology. _What is the ontology(s) for? How is it intended to be used? What are the desired features and functionalities?_
- Identify the subject-matter or set of concepts (the universe/domain of discourse/interest) you wish to model in an ontology.
- Identify the data that the ontology will be applied to (e.g., to annotate), annotate, or be based on. _What datasets, databases? What types of data? What is the data about?_ 

**Meta-level Consideration**: the boundaries or limits of a given target area, and domain are often arbitrary. Some domains, perceived as disciplines, are in fact overlapping. Therefore there is a degree of arbitrariness when scoping and identifying or creating a target domain. One modeler may scope and model the same topic differently than anothe modeler.

### 2. Subject-matter Research
- Research the target subject and domain corpora: publications, data, projects, subject-matter experts, educational courses, etc.

### 3. Use-cases
- Identify use-cases for the ontology. _Where may the ontology be applied? How can the ontology be used? What stakeholders, societal sectors, computational systems, and applications may benefit from it? What are situations in which the ontology could be used?_

### 4. Scope
- Identify or specify the boundaries of the target subject-matter that the ontology(s) will represent. NOTE: consider [this](https://github.com/rrovetto/Ontology-Development-Guidelines/blob/master/DomainDemarcation.md).

### 5. Requirements & Specification Details
- Identify what will be required to (i) realize the purpose and (ii) apply the ontology to the use-cases. 
- State specification details: 
	- What natural language? 
	- What computable language (knowledge representation and reasoning language / implementation langauges)? 
	- Stylistic conventions, e.g., naming conventions for terms/labels, etc.  
	- Identify or create _competency questions_: queries that the ontology (and datasets) can be asked computationally.
- Select, Acquire or Develop resources and tools, e.g., ontology editor software, knowledge representation languages, 
- Corpora (research documents, domain knowledge), data sources, contributors, partners, subject-matter experts, etc.
- Identify and select supplemental tools: ontology engeineer tools, ontology development environments, automated reasoners, etc.  
NOTE: an example is the NEON Methodology.

### 6. Research & Conceptual Analysis of the Subject/domain
- Examine the target subject matter. Try to identify essential concepts, themes, challenges, etc. 
- Gain a big-picture understanding.
- Identify generic knowledge or beliefs to be represented in the ontology. These are often statements of a broad or universal nature. 

### 7. List...
- Identify & list specific things in the universe of discourse you want the ontology to represent.
- Identify & list concepts and terms needed to describe the things in universe of discourse. 
- Create concepts and terms where needed.
- For a candidate category, ask: is there a data element or dataset that can be annotated with this category? If not, then you may not need it (but it will be situational).
- List statements of knowledge or belief to be represented in the ontology: this can take the form of a set of sentences describing some general rule, fact, principle, or aspect about the target domain and its contents.
- WHEN CREATING AN ONTOLOGY FOR A SPECIFIC DATABASE: list the key terms and pieces of knowledge found therein. 
### 8. Definitions
- Identify the intended meaning for each of the list of things, concepts and terms.
	- You may begin with some intended meaning or concept, and the form a term that most clearly expresses it. 
- Research definitions (of key terms) from corpus material: dictionaries, academia, journal publications, subject-matter experts, etc.
- Identify undefined (primitive) terms. 
- Write definitions in natural-language that most closely expresses that intended meaning.
- For all primitive terms, state they are undefined, but also provide a clarifying note to provide the user with some sense of meaning. 

### 9. Structure
- In this process, identify how the things or terms denoting them are related (if at all). Distinguish between relationships between the word (term) and what it denotes. E.g., dogs have four legs. vs. the word 'dog' means [...].
- Create or select terms for how they are related (i.e., for the relationships between them).
- Define these relational terms.
- Use abstract distinctions and structuring relations, e.g., category vs. instance, class vs. member, class and subclass, broader & narrower, etc. 

### 10. Symbolically Formalize
- Develop semi-formal or formal logical definitions.
	- You may translate the intended meaning or natural language definitions into, e.g., first-order logic for precision. 
- Chose or create a formalism that is computable. 
- Translate the natural language meanings into the chosen formal language, or use your chosen ontology editor tool’s language.
- Formal definitions may use the labels to better foster automation.

### 11. Collect or create a test dataset. Apply the ontology to that data.
- Before deployment into actual use-cases or operational data owned by stakeholders or others, collect or create test data to test and validate the functionality, goals, and utility of the ontology. This will serve to identify any bugs (technical problems or limitations).
- Apply or use the ontology to that test data by using supplemental tools (See Stage 5): run any reasoner to test for functionalities such as classification, correct inference, etc.

### 12. 
 
## Author
[Robert J. Rovetto](https://orcid.org/0000-0003-3835-7817)
rrovetto(at)terpalum.umd.edu
* Education Technical Committee member, International Association for Ontology and its Applications (IAOA)
* Semantic Web & Applied Ontology Special Interest Group, IAOA
* NASA Datanauts open data group (class of 2017. 2017-20)
* Journal of Search and Rescue (webmaster, journal developer)

## Copyright
© 2013-2021, Robert John Rovetto. All right reserved.
Not authorized for commercial use unless explicitly negotiated with the author. Citation/attribution required.
No warranty. Presented "AS IS". Author and copyright holder is not liable. All content, work and products are subject to revision. No claims to completeness or complete accuracy.
