# APEX-0918-Unified-Core-Reporting-Schema
### Disclaimer:  
The introductory clause is strictly informative. 

## Introduction 
This advertising impression reporting schema specification is intended to facilitate the acceptance, recognition and accreditation of the unique media currency provided by airline publishers of streaming entertainment. It may also have applicability to other advertising workflows within the transportation sector.
The normative clauses of this document define a concise and slightly constrained subset of the VAST 4.0 and VMAP 1.0.1 elements and attributes. This subset is classified based on functionality that is core to the onboard experience. Every enumerated element and attribute shall be allowed in IFE servers, clients and back-end reporting systems. It is anticipated that commercial schema validiation practices will emerge from specific use cases that take advantage of the clasifications established within this concensus document.  

Please refer to the Appendix for further background information and for insights into the context of this unification effort.

## Terms and Definitions  
**Ad-ID:**
marketplace mandated voluntary web-based system for the registration of advertising assets <http://www.ad-id.org/about/mandate>

**DSP**
demand-side platform allowing buyers of digital advertising inventory to manage multiple accounts  

**EIDR:**
system for unique universal registration of movie and television assets <https://eidr.org/>  

**OMID:**
open measurement interface definition supported by a software development kit published by the IAB Technology Laboratory <https://iabtechlab.com/standards/open-measurement-sdk/>  

**VAST:**
video ad serving XML template standardized by the Interactive Advertising Bureau <https://iabtechlab.com/standards/vast/>  

**VMAP:**
XML template that can be used within VAST to provide playlist functionality for multiple ads <https://www.iab.com/guidelines/digital-video-multiple-ad-playlist-vmap-1-0-1/>


## Unified Core Reporting Schema
The following two tables define a concise and slightly constrained subset of the VAST 4.0 elements and attributes and the VMAP 1.0.1 elements and attributes respectively.  

**Optional:** 
items not highlighted—applicability depends on use case  
Elements and attributes that are not necessarily required and may be ignored

**Mandatory:** 
items highlighted in green  
Elements and attributes that are generally required in audience impression reports  

**Optional and Not Recommended:** 
items highlighted in red  
Elements and attributes that are generally considered unnecessary and wasteful of limited IFEC resources  


<figure>
	<img src="Tables/tableOneFigure.png" />
	<figcaption>Table 1: Core VAST Elements</figcaption>
</figure>
<figure>
	<img src="Tables/Table2VMAP-extension.png" />
	<figcaption>Table 2: VMAP Extensions</figcaption>
</figure>  

## Bibliography (Informative)  
**CMAF:**
common media application format—MPEG Standard 23000-19 <https://mpeg.chiariglione.org/standards/mpeg-a/common-media-application-format>  

**DASH-IF:**
streaming technology industry forum—developer and publisher of comprehensive interoperability points that encompass targeted ad-insertions through the use of MPEG-DASH periods <https://dashif.org/about/>

**DASH emsg:**
W3C triggers for timed media events <https://w3c.github.io/me-media-timed-events/>  

**ESAM**
cableLabs real-time event signaling and management API and schema <http://mibs.cablelabs.com/namespaces/opencable/xsd/esam/OC-SP-ESAM-API-C01-Signal.xsd>  

**Interoperable Master Format—Composition Playlist:**
SMPTE standard for content masters containing a MarkerResourceType schema encompassing MarkerType definitions for commercial blacks <https://ieeexplore.ieee.org/document/7560854>  

**Minimum Standards for Media Rating Research:**
disclosure and delivery conditions for industry mandated, self-regulatory ad impression accreditation—published by the Media Rating Council <http://www.mediaratingcouncil.org/MRC%20Standards.htm>

**MXF Ad-ID Digital Ad Slate:**
industry practice for associating the Advertising Digital Identifier (Ad-ID) and other machine-readable metadata items with content <https://amwa.tv/projects/AS-12.shtml>  

**OBID:**
SMPTE standards suite covering the open binding of specific content and distribution channel identifiers to audiovisual content <https://doi.org/10.5594/SMPTE.OV2112-0.2018>  

**OpenRTB:**
API specification supporting the automation of real-time ad impression bidding platforms <https://www.iab.com/guidelines/real-time-bidding-rtb-project/> 

**SAND:**
acronym for server and network assisted DASH—when used in conjunction with a companion streaming server specification called DANE, this ISO/IEC 23009-5 Standard enables quality of experience optimization, measurement, and reporting <http://tnomedialab.github.io/sand/>

**SCTE 35:**
core signaling standard for controlling advertisements within cable TV content <www.scte.org/SCTEDocs/Standards/SCTE%2035%202016.pdf>  

**SCTE 104:**
communications API covering SCTE 35 private sections, including the time_descriptor commands that convey wall clock time to a client <https://www.scte.org/SCTEDocs/Standards/SCTE%20104%202018r2.pdf>  

**SCTE 224:**
two-way event scheduling and notification interface enabling schemas that establish elements defining Audience Types <https://www.scte.org/SCTEDocs/Standards/ANSI_SCTE%20224%202018r1.pdf>  

