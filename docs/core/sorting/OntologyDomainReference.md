
# Type: OntologyDomainReference


A reference to a subject domain for an ontology.

URI: [https://hotecosystem.org/tccm/sorting/OntologyDomainReference](https://hotecosystem.org/tccm/sorting/OntologyDomainReference)


![img](images/OntologyDomainReference.svg)

## Parents

 *  is_a: [NameAndMeaningReference](NameAndMeaningReference.md) - A NameAndMeaningReference consists of a local identifier that references a unique meaning within the context of

## Attributes


### Inherited from NameAndMeaningReference:

 * [➞href](nameAndMeaningReference__href.md)  <sub>OPT</sub>
    * range: [RenderingURI](types/RenderingURI.md)
 * [➞name](nameAndMeaningReference__name.md)  <sub>REQ</sub>
    * Description: An identifier that uniquely names the reference within the context of the particular reference type.
    * range: [LocalIdentifier](types/LocalIdentifier.md)
 * [➞synopsis](nameAndMeaningReference__synopsis.md)  <sub>OPT</sub>
    * Description: A summary of the role and purpose of the actual reference
    * range: [String](types/String.md)
 * [➞uri](nameAndMeaningReference__uri.md)  <sub>OPT</sub>
    * range: [ExternalURI](types/ExternalURI.md)
