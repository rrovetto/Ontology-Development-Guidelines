# Guidelines for Developing Definitions in Computational Ontologies

1) Include at least one natural-language definition or description for each _ontology construct_, i.e., for each _class, individual, relation, property_, etc.

2) Include a computable definition that matches the natural-language definition as closely as possible.

3) Optionally include a tool-independent / implementation-independent formal logical definition (perhaps as a metadata annotation) 

NOTE: limit the loss of expressivity, as much as possible, during the translation from natural-language definition to computation definition. It can be limited by using a computable formal language that has high expressivity and minimal language bias. And more generally by spending time on conceptual analysis, hand-made first- and second-order logic translation of the n-l def., etc. 

4) Have human-readible metadata annotations or notes for each, e.g., labeled as 'Natural-language Definition'

NOTE: there are many types of definitions, e.g., ostensive, etc. For computation, you can follow the rules of your chosen formal langauge (e.g., RDF, OWL, CLIF, etc.). 
NOTE: one approach to making definitions is a genus-species-differentia form, specifying sub-categories and distinguishing features for each. They resemble a template such as:
CategoryX is-a-kind-of CategoryY that/which Z

### Research Documents 
- "UNE ISO 1087-1,  following  ISO  1087-1 and ISO 1087-2 in which an intensional definition states the superordinate concept and the delimiting characteristics. This means that definitions should not start with a verb" (https://www.sciencedirect.com/science/article/pii/S1877042815056608)
-

### Support
If you find value in my work, please [support/donate here](https://gogetfunding.com/knowledge-organization-services-ontology-terminology-metadata-concept-analysis/). Financial support is needed to sustain development.

(c) 2019-2020, Robert John Rovetto. All rights reserved.
