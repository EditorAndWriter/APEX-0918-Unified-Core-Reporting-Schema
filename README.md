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

