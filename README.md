# Protégé in a nutshell

[Protégé](https://protege.stanford.edu/) is a powerful open-source ontology development platform for semantic web.

## Protégé development environments

- [Protégé Desktop](https://protegewiki.stanford.edu/wiki/Install_Protege5)
  * Prerequisite: JAVA 8 or later
  * full features support
  * single workplace
- [WebProtégé](https://webprotege.stanford.edu/)
  * less features
  * cloud-based **collaborative** ontology development
- [Protégé 5 Server](https://protegewiki.stanford.edu/wiki/Protege_5_Development_Environment)
  * local web instance
  * allows 5 clients, such as ProtégéDesktop
  * SVN enabled
 
Before diving into it, here are the [tips for creating an ontology](https://protege.stanford.edu/publications/ontology_development/ontology101-noy-mcguinness.html)

## Protégé demo

- annotate ontology metadata, using [an ontology template](src/protege/ontology_template.ttl)
- create classes, object/data/annotation properties, individuals
- add restrictions*
- reasoning*
- [export ontology](src/protege/cronos.owl)

# Further readings

- [A Practical Guide to Building OWL Ontologies](https://drive.google.com/file/d/1A3Y8T6nIfXQ_UQOpCAr_HFSCwpTqELeP/view)
- [OWL 2 Web Ontology Language Manchester Syntax](https://www.w3.org/TR/owl2-manchester-syntax/)





