## The Intended Meaning of your ontology constructs and terminology

This section describes the importance of understanding and asserting the intended meaning or purpose of the ontolog constructs (classes, relations, etc.), and any associated label (terms) assigned to each construct. 

NOTE: An example of an ontology construct is an OWL Class, or OWL Data Property. 
_Ontology Construct / Symbol-structure_ = the class, relation, individual, etc. being created in an ontology file, i.e., the computational structure being created.
_Label / Term_ = the (alpha)numeric string--often a natural language lexical term--assigned to an ontology construct.

Exmaple 1:
Class (ontology construct) = Stellar_Body
Label = 'stellar body'

Example 2:
Class (ontology construct) = SB-00157
Label = 'stellar body'

Intended meaning is often, if not always, essential to capture in an ontology.
_Intendd meaning can be captured by_: 
(a) including human-understandable definitions for each construct in the ontology.
and/or
(b) formal computable semantics for each construct. This can be accomplished via constraints, relations, rules, etc., which, in part, constraints the interpretations of the given constructs, the statements (or well-formed formulas) they may compose, etc.
(c) Documentation both within the ontology file, and external to it. External documentaiton may be a webpage, an ontology specification document, a spreadsheet document, etc.

An ontology presumably has a _scope_. The degree to which it formally captures/represents/models the scope is the degree of _coverage_.
The scope of an ontology includes various specific things.
Each identified and desired thing to be captured should be formally represented with an ontology construct (class, relation, individual, property, etc.).
Each construct should be given a defintion or desription that expresses the intended meaning of that construct, and that expresses an understanding of the thing.
Each construct should be given a natural-langauge label, i.e., a term (e.g., a name) that matches the definition and thus the intended meaning as closely as possible. 

The construct may be understood as a computable symbol for the thing in the target domain, whether the thing is a word, an imaginary creation, or some mind-external physical object, etc.
A definition or description expresses the meaning or purpose of that symbol.
The name (label, or term) is a string of symbols linked or assigned to the construct. This, too, appears to be an ontology construct.
In this way, we can consider the constructs (symbol-structures, or elements) of an ontology.

If you find value in my work, please [support/donate here](https://gogetfunding.com/knowledge-organization-services-ontology-terminology-metadata-concept-analysis/).

(c) 2019-2020, Robert John Rovetto.
