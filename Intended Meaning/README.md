## The Intended Meaning of your ontology constructs and terminology

This section describes the importance of understanding and asserting the intended meaning or purpose of the ontolog constructs (classes, relations, etc.), and any associated label (terms) assigned to each construct. An example of an ontology construct is an OWL Class, or OWL Data Property. 

_Ontology Construct / Symbol-structure_ = the class, relation, individual, etc. being created in an ontology file, i.e., the computational structure being created.
_Label / Term_ = the (alpha)numeric string--often a natural language lexical term--assigned to an ontology construct.

Exmaple 1:
Class (ontology construct) = Stellar_Body
Label = 'stellar body'

Example 2:
Class (ontology construct) = SB-00157
Label = 'stellar body'

### Metadata
- Metadata is data about data. But it is also often relative. 
- Distinguish between the construct (or symbol-structure) being created in the ontolgy (e.g., an OWL Class, OWL Object Property) and any lexical label (a display label) assigned to the construct.
  - Assert a metadata annotation construct to document the purpose or description of the construct itself.
  - Assert a metadata annotation construct to document the definition of the associated natural language label.
