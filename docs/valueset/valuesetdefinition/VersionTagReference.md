
# Type: VersionTagReference


A reference to a tag that can be assigned to versionable resources within the context of a service implementation.

URI: [tccm:VersionTagReference](https://hotecosystem.org/tccm/VersionTagReference)


![img](images/VersionTagReference.svg)

## Parents

 *  is_a: [NameAndMeaningReference](NameAndMeaningReference.md) - A NameAndMeaningReference consists of a local identifier that references a unique meaning within the context of

## Referenced by class

 *  **[ValueSetDefinition](ValueSetDefinition.md)** *[ValueSetDefinition➞versionTag](ValueSetDefinition_versionTag.md)*  <sub>0..*</sub>  **[VersionTagReference](VersionTagReference.md)**
 *  **None** *[versionTag](versionTag.md)*  <sub>0..*</sub>  **[VersionTagReference](VersionTagReference.md)**

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