
# Type: CodeSystemVersionReference


A reference to a specific version of code system and, if known, the code system which it is a version of.

URI: [tccm:CodeSystemVersionReference](https://hotecosystem.org/tccm/CodeSystemVersionReference)


![img](images/CodeSystemVersionReference.svg)

## Parents

 *  is_a: [NameAndMeaningReference](NameAndMeaningReference.md) - A NameAndMeaningReference consists of a local identifier that references a unique meaning within the context of

## Referenced by class

 *  **None** *[➞fromCodeSystemVersion](mapVersion__fromCodeSystemVersion.md)*  <sub>OPT</sub>  **[CodeSystemVersionReference](CodeSystemVersionReference.md)**
 *  **None** *[➞toCodeSystemVersion](mapVersion__toCodeSystemVersion.md)*  <sub>OPT</sub>  **[CodeSystemVersionReference](CodeSystemVersionReference.md)**
 *  **None** *[➞useCodeSystemVersion](mapVersion__useCodeSystemVersion.md)*  <sub>0..*</sub>  **[CodeSystemVersionReference](CodeSystemVersionReference.md)**

## Attributes


### Own

 * [➞codeSystem](codeSystemVersionReference__codeSystem.md)  <sub>REQ</sub>
    * range: [CodeSystemReference](CodeSystemReference.md)

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
