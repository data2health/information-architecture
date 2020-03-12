Identification, acquisition, modeling and dissemination of clinical and translational research knowledge is at the heart of the CD2H mission, and comprises one of the four outward-facing CD2H cores - Resource Discovery.

# CTSA Program Priorities

* CTSA Program Data to Health (CD2H) Coordinating Center (U24) (RFA-TR-17-006)
* Foster collaborative innovation in the area of informatics tools, methods, and processes
Clinical and Translational Science Award (U54 Clinical Trial Optional) (PAR-18-940)
  * Data interoperability
  * Data transparency/release
* NOT-TR-18-022 - Innovative informatics solutions that integrate clinical and basic research data which provide catalytic support for project with a significant and unmet needs

# Project Vision and Values

Information relevant to the CTSA community - and hub informatics teams in particular - is scattered across numerous scattered sources in widely-variant formats. Our initial work in the previous phase has resulted in an aggregated warehouse of uniformly formatted information. In Phase III, this project makes this resource available to the CTSA community in a variety of forms and engages the hubs in shared development of new ways of representing and consuming those resources.

# Hub Engagement

Engagement with the CTSA hubs and CLIC has to-date primarily been focused upon identification and acquisition of relevant information. Much of this work in Phase II was conducted in the context of the Science of Translational Science (SciTS) platform. The emphasis in Phase III within this project framework will focus on collaborative exploration of annotation of hub web content,  and specification and provisioning of micro services (widgets) into hub information environments.

# Implementation and Evaluation

Each component of this project has already-established community collaborators driving core use cases.  In addition, focus groups for each component will be convened as a means of driving iterative cycles of development over the six months of Phase III. Note that the majority of the planned activities are not software development per se, but rather information modeling and integration exercises.

# Other Resources

This project already draws from numerous Federal sources (e.g., MEDLINE, RePORTR, ClinicalTrials.gov, …) as well as CTSA hub web sites, CLIC and multiple cognate projects.

# Project Plan

Our planned work involves the following interlocking activities:

**Awareness Management**: We have deployed an initial version of AMP, a “living survey” tool, intended to support maintenance of status rather than repeated surveying of the CTSA community. Phase III activities in this area will include
production deployment (potentially in the NCATS cloud);
recruitment of groups involved in periodic polling of the consortium for migration to the new platform; and
dashboard and micro service configuration allowing integration of status data into local environments.

**Data Discovery Engine**: This project is intended to provide a complete infrastructure ecosystem to disseminate and consume structured metadata using schema.org as the sharing mechanism. A sufficient set of cloud-hosted utilities will be provided to extend the success from the consumer-space search engines (such as Google and Bing) to the biomedical use cases from the CTSA community. In phase II, we have developed a set of metadata authoring widgets and a schema playground. Both focus on constructing metadata following schema.org best practices to maximize their discoverability as data-providers. In phase III, we plan to streamline the process from distributed metadata to their data-portal consumers by building:
a metadata crawler to harvest the distributed metadata in real-time;
a centralized API to deliver harvested metadata to multiple downstream data portals (e.g. CTSASearch);
a “metadata-plus” web application to convert non-schema.org compatible websites (e.g. GEO) to compatible ones.
These new utilities will provide necessary incentives to promote schema.org mechanism, with the hope to form a positive feedback-loop between data-providers and their data consumers.

**Hub Website Annotation**: There is significant information embedded in natural language on hub websites. Much of this involves the services that hubs provide, the contact information regarding those services, and (albeit diffuse) characterization of the expertise of hub personnel. We currently harvest the full text of pages from hub websites for search indexing, but a curated approach to annotation of those services will yield significantly more useful information. Our approach to this curation will be a phased engagement with the hubs, developing a shared scheme for use in publishing service descriptions, optimally using the Data Discovery Engine as a means of authoring these annotations.

**Hub Services Modeling**: Our current collaboration with MUSC on the SPARCRequest platform substantially leverages CPT as a taxonomy for clinical services.  However, many of the services provided by hubs that will be generated by our annotation activities fall outside the scope of CPT. This activity will continue our preliminary work in the SciTS project on a taxonomy of services, that, when combined with the CPT-centric SPARCRequest content, will provide a service taxonomy to serve as a primary filtering facet in CTSAsearch.

**Semantic Integration Across Sources**: Individuals and organizations appear multiple times both within a single SciTS source and across multiple SciTS sources - frequently with no shared identifier. This component of the project will establish linkages across sources, enabling a more complete characterization of expertise, and a reduction in redundant occurrences of entities in search results. CTSAsearch currently links to a target page within a given source in a given search hit - comparable to a hit on a Google search.  To enable user presentation of aggregated information across sources, we will also create search landing pages that aggregate information across sources for a given entity. Machine-readable versions of landing pages will also be developed as micro services - enabling hubs to query for aggregated content.
