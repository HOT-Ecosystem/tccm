
# Type: AbstractResourceDescription


The description of the characteristics of a resource that are independent of the resource content.

URI: [tccm:AbstractResourceDescription](https://hotecosystem.org/tccm/AbstractResourceDescription)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[Extension],[Annotation],[SourceAndNotation],[ResourceDescription],[SourceAndNotation]<releaseFormat%200..*-++[AbstractResourceDescription&#124;releaseDocumentation:string%20%3F;about(i):ExternalURI;resourceID(i):LocalIdentifier;formalName(i):string%20%3F;keyword(i):string%20*;resourceSynopsis(i):string%20%3F;additionalDocumentation(i):PersistentURI%20*;rights(i):string%20%3F;alternateID(i):string%20%3F],[ResourceDescription]^-[AbstractResourceDescription])

## Parents

 *  is_a: [ResourceDescription](ResourceDescription.md) - ResourceDescription represents the shared characteristics common to both abstract and resource version descriptions. ResourceDescription is an abstract type and, as such, cannot be directly created. Resource descriptions are Changeable, meaning that they have identity and can be created, updated, and deleted.

## Referenced by class


## Attributes


### Own

 * [AbstractResourceDescription➞releaseDocumentation](AbstractResourceDescription_releaseDocumentation.md)  <sub>OPT</sub>
    * Description: Documentation about the frequency and nature of releases (version) of this resource.
    * range: [String](types/String.md)
 * [AbstractResourceDescription➞releaseFormat](AbstractResourceDescription_releaseFormat.md)  <sub>0..*</sub>
    * Description: A format and notation that the releases (versions) of this resource are published in.
    * range: [SourceAndNotation](SourceAndNotation.md)

### Inherited from ResourceDescription:

 * [ResourceDescription➞about](ResourceDescription_about.md)  <sub>REQ</sub>
    * Description: The (or a) definitive URI that represents the resource being described. Note that this is NOT the URI of the resource description in the TCCM or other format, but of the resource itself. As an example, the about URI for the Wine ontology would be “http://www.w3.org/TR/2003/PR-owl-guide-2003 1209/wine#.” The NCI Thesaurus has, among others, the about URI of http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl#. HL7 uses ISO Object Identifiers (OIDs) to label resources so, from the HL7 perspective, the about URI of the NCI Thesaurus would be “urn:oid:2.16.840. 1.113883.3.26.1.1”
    * range: [ExternalURI](types/ExternalURI.md)
 * [ResourceDescription➞additionalDocumentation](ResourceDescription_additionalDocumentation.md)  <sub>0..*</sub>
    * Description: A reference to a document that provide additional information about the resource.
    * range: [PersistentURI](types/PersistentURI.md)
 * [ResourceDescription➞alternateID](ResourceDescription_alternateID.md)  <sub>OPT</sub>
    * Description: An alternative identifier that uniquely names this resource in other environments as contexts. As an example, if a resource had both an ISO Object Identifier and a DNS name, the DNS name might be assigned as the entryID of the resource by one service while the ISO OID would be recorded as an alternateURI using the “urn:oid” prefix. Note that alternateIds can be added or removed during resource updates.
    * range: [String](types/String.md)
 * [ResourceDescription➞formalName](ResourceDescription_formalName.md)  <sub>OPT</sub>
    * Description: The formal or officially assigned name of this resource, if any.
    * range: [String](types/String.md)
 * [ResourceDescription➞keyword](ResourceDescription_keyword.md)  <sub>0..*</sub>
    * Description: Additional identifiers that are used to index and locate the resource.
    * range: [String](types/String.md)
 * [ResourceDescription➞resourceID](ResourceDescription_resourceID.md)  <sub>REQ</sub>
    * Description: A local identifier that uniquely names the resource within the context of the describedResourceType and implementing service. As an example, this might be “SCT” for the SNOMED-CT code system, “SCT-2010AA” for a SNOMED-CT code system version.
    * range: [LocalIdentifier](types/LocalIdentifier.md)
 * [ResourceDescription➞resourceSynopsis](ResourceDescription_resourceSynopsis.md)  <sub>OPT</sub>
    * Description: A textual summary of the resource - what it is, what it is for, etc.
    * range: [String](types/String.md)
 * [ResourceDescription➞rights](ResourceDescription_rights.md)  <sub>OPT</sub>
    * Description: Copyright and IP information. Note that rights applies to the source resource, not the CTS2 rendering.
    * range: [String](types/String.md)