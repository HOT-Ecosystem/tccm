
# Type: ValueSetReference


A reference to a named set of entity references.

URI: [tccm:ValueSetReference](https://hotecosystem.org/tccm/ValueSetReference)


![img](images/ValueSetReference.svg)

## Parents

 *  is_a: [NameAndMeaningReference](NameAndMeaningReference.md) - A NameAndMeaningReference consists of a local identifier that references a unique meaning within the context of

## Referenced by class

 *  **[CompleteValueSetReference](CompleteValueSetReference.md)** *[CompleteValueSetReference➞valueSet](CompleteValueSetReference_valueSet.md)*  <sub>REQ</sub>  **[ValueSetReference](ValueSetReference.md)**
 *  **[ValueSetDefinition](ValueSetDefinition.md)** *[ValueSetDefinition➞definitionOf](ValueSetDefinition_definitionOf.md)*  <sub>OPT</sub>  **[ValueSetReference](ValueSetReference.md)**
 *  **None** *[definitionOf](definitionOf.md)*  <sub>OPT</sub>  **[ValueSetReference](ValueSetReference.md)**
 *  **None** *[valueSet](valueSet.md)*  <sub>REQ</sub>  **[ValueSetReference](ValueSetReference.md)**

## Attributes


### Inherited from NameAndMeaningReference:

 * [NameAndMeaningReference➞href](NameAndMeaningReference_href.md)  <sub>OPT</sub>
    * range: [RenderingURI](types/RenderingURI.md)
 * [NameAndMeaningReference➞name](NameAndMeaningReference_name.md)  <sub>REQ</sub>
    * Description: An identifier that uniquely names the reference within the context of the particular reference type.
    * range: [LocalIdentifier](types/LocalIdentifier.md)
 * [NameAndMeaningReference➞synopsis](NameAndMeaningReference_synopsis.md)  <sub>OPT</sub>
    * Description: A summary of the role and purpose of the actual reference
    * range: [String](types/String.md)
 * [NameAndMeaningReference➞uri](NameAndMeaningReference_uri.md)  <sub>OPT</sub>
    * range: [ExternalURI](types/ExternalURI.md)