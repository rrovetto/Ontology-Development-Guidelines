## Guidelines for developing Identifiers
Depending on the degree of abstraction one considers, the following is an approximation.

For all constructs in an ontology, we can declare the following.

- **Identifiers** are those symbol-structures (e.g., a set of alphanumeric characters) that identify a given ontology construct (class, relation, individual, etc.).
Depending on the situation, you may assign either so-called **opaque** or **transparent/readible/semantically-meaningful** identifiers.
- **Opaque or Semantically-neutral identifiers**. These identifiers do not express meaning. They are composed of (alpha)numeric characters/symbols that are not intended to convey any meaning (e.g., they are not a natural language word). E.g., "34568ijngoi465j". They may be composed of random-generated numbers, or may be sequentially-numbered (e.g., 00012). 
  - UUIDs (universally unique identifiers)
  - GUIDs (globally unique identifiers) are types of opaque identifiers.
or
- **Human-readible identifiers**. These includes human-readible character strings, e.g., "Motor vehcile" or "motor-vehicle"

- Select a type and format for identifiers, e.g., random-generated alphanumeric, sequential numeric, etc.

- **Display Label**
  - Display labels for a given construct (class, relationship, instance, etc.) are how the construct will be read/seen by a person. It is therefore typically a human-readible natural-language identifier.
  - Additional labels can be added as desired or needed. For example:
  - Alternative labels (e.g., using the rdfs:altLabel construct)
  - Synonyms. Including synonyms indirectly show the degree of usage and meaning in a natural language for the given domain/topic. 

### Research about Identifiers, Labels, etc.
- https://www.sciencedirect.com/science/article/pii/S1877042815056608
-   "the main objective of labels is to be as descriptive and meaningful of the ontology entity as possible, in order to guarantee an appropriate use and, hence, the adoption of the ontology by final users."
-   "In this way we are able to “read” the triple as a sentence, or with a syntactic structure quite close to the  natural  language  interpretation."
-   "we should respect the common or natural  syntagmatic  structures  of  each  language."


### Support
If you find value in my work, please [support/donate here](https://gogetfunding.com/knowledge-organization-services-ontology-terminology-metadata-concept-analysis/). Financial support is needed to sustain development.

## Copyright
© 2019-2021, Robert John Rovetto. All right reserved.
Not authorized for commercial use unless explicitly negotiated with the author. Citation/attribution required.
