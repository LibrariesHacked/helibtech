---
title: Resource sharing and interlending
layout: default
nav_order: 6
parent: Core library systems
has_children: false
tags:
  - Library management systems
  - Library systems
  - Resource sharing
  - Interlending
---
# Resource sharing and interlending

## Overview

This page covers resource sharing and interlending between libraries. There is a long history of university libraries offering interlibrary loans to users in order to allow access to material outside of the home collection. This service may be offered on a differential basis to differing user groups but is often a core service for postgraduate and research students / academic staff.

Traditionally UK interlibrary loans were primarily facilitated by lending and document supply via the British Library. However, more recently market dominance of the British Library Document Supply Centre has been challenged by consortia lending (facilitated via resource sharing solutions integrated with library service platforms) and commercial document supply solutions.

Details of differing interlending solutions can be found on our product directory

## British Library & interlending

The traditional model of UK interlending in HE (and other sectors) has been based on significant, or in many cases exclusive use, of the British Library Document Supply Centre (BLDSC). Many UK focused library management systems have offered integrated interlibrary loans module to allow automated ordering via BLDSC and management of requests via the ILS.

BLDSC offers a charge per transaction service for both document supply and print loans with differential rates based on delivery times. The majority of end user document supply requests (of for example, journal articles) are supplied on the basis of library privilege (a term in UK Copyright Law) meaning that publication specific copyright fees are not paid. British Library also offers copyright fee paid services to allow redistribution of journal articles, book chapters etc. to groups of students either physically or digitally via a VLE.

During the 2000s BLDSC began to offer digital distribution of document supply and journal articles etc from their born digital collections. Content is emailed to users as encrypted files.

## Resource Sharing between libraries

A new Resource Sharing landscape is emerging with several providers offering new resource sharing solutions facilitating peer to peer document supply and lending between participating institutions.

### Resource Sharing solutions

### RapidILL

[RapidILL](https://exlibrisgroup.com/products/rapidill-interlibrary-loan/) was developed by inter-library loan staff at Colorado State University and subsequently acquired by Ex Libris. It facilitates quick, reciprocal resource requesting for ‘pods’ of libraries and interfaces with software solutions from a variety of vendors. It is optimised for ‘non-returnables’ (i.e. electronic copies such as journal articles, rather than print resources such as books) and offers the following features:

RapidILL ‘pods’ are groups of libraries (a pod could be all NHS libraries in England) that have agreed to freely share journal article and e-chapters and commit to supplying these within 24 hours. Their holdings are loaded into RapidILL via automatic, monthly OAI-PMH harvesting.

RapidILL provides load balancing to ensure that each library receives as many copies as they supply. When sourcing items, it selects the holding library with the lowest net number of requests. RapidILL can also manage requests made to fee-based services such as Research Solutions (Reprints Desk, inc), as an optional add-on, billed separately.

Once requests are fulfilled, details are transferred to and held within the local LMS/ILDS systems with which RapidILL interfaces. This means that user data is held only temporarily in RapidILL, and requests managed and user data held on local systems. With the Alma LMS and CLIO ILDS system, there is full integration and the transfer of requests is automatic. This level of integration does not yet (July 2021) exist for other systems and manual data transfer is required.

##### RapidILL working groups

The [IGeLU RapidILL Working Group](https://igelu.org/rapidill-working-group/) serves as a vital link between the international user community and Ex Libris, ensuring that user needs and perspectives are effectively communicated and addressed in the product’s ongoing development and improvement. Similarly, the [ELUNA RapidILL Working Group](https://el-una.org/leadership/working-groups/rapidill-wg/) serves the extensive user community in the Americas.

### Tipasa

[Tipasa](https://www.oclc.org/en/tipasa.html) is supplied by OCLC and described as ‘an ILL management system for individual libraries to share and obtain materials through different resources and systems as well as to provide an exceptional experience for the library user’. It is designed to manage both ‘returnables’ and ‘non-returnables’.

Tipasa claims to be system agnostic but ( (at July 2021) only integrates with OCLC WMS, Ex Libris Alma and CLIO. It uses a ‘proven sender’ concept, with libraries designated as proven senders where they have demonstrated that they provide good quality documents quickly. Optionally, Tipasa offers Article Exchange, a secure area for article delivery where staff can place requests for users to download .

Tipasa uses the NCIP protocol to integrate with local LMS circulation systems to create temporary records in circulation systems. Tipasa can also manage requests made to fee-based services such as Reprints Desk. Conversely, libraries which charge for document supply can be excluded.

Tipasa can be implemented as part of the of OCLC WMS LMS or deployed separately. Library holdings are uploaded to WorldCat. OCLC manages the holding upload process as part of the implementation and will do regular, automated uploads for the life of the subscription.

Rotas and load balancing are managed by ‘smart lender strings’. The library selects the locations that go into strings. Tipasa calculates turnaround time so it works out which library can supply fastest and undertakes load balancing so that no library gets more requests than it can handle. Libraries that demonstrate they can achieve a quick turnaround can be included in an ‘express program’ group.

User data is ingested into Tipasa from the LMSs that are integrated with Tipasa by an initial upload as part of the implementation process then managed by batch loads or an online API. Articles (PDFs) can be emailed to users or OCLC’s ‘Article Exchange’ may be used as the delivery mechanism.

### ReShare

[Project ReShare](https://projectreshare.org/) is an open-source community driven project ‘creating a new and open approach to library resource sharing systems that sets the standard for how we connect library patrons to the resources and information they require…..designing an open source, highly-scalable platform that supports discovery, fulfilment, and delivery workflows, with a focus on user-centered design’.

Although not formally part of the Folio open source LMS initiative, Project ReShare uses the same core developers IndexData and the Folio technical infrastructure and has much of the same community ethos. Although community-owned and driven, it encourages libraries and commercial organisations to participate meaningfully in advancing its goals. Currently the community of libraries actively engaged with project ReShare is exclusively US-based. ReShare supports consortial, peer-to-peer borrowing between defined resource sharing groups, which can restrict resource sharing amongst themselves. It has a strong focus on interoperability, using standards such as NCIP, Z39.50, ISO10160 and ISO18626. Its current focus is returnables. Non-returnables are on the road map (July 2021) but with no clear date.

### The Open Resource Sharing Coalition (OpenRS)

[Introducing The Open Resource Sharing Coalition (OpenRS)](https://openlibraryfoundation.org/newsroom/news/introducing-the-open-resource-sharing-coalition-openrs/)

Partnership Between Libraries, Open Source Developers, and Vendors to Enhance Consortial Resource Sharing. Open Library Foundation, Press Release. August 22, 2023 Open Library Foundation, Press Release.

The Open Library Foundation (OLF) is introducing the Open Resource Sharing Coalition (OpenRS), a resource sharing initiative created in partnership with library consortia, open source developers, and vendors. OpenRS is a heterogeneous resource sharing system that is ILS and Discovery agnostic and accommodates the full spectrum of mediated and unmediated resource sharing.

OpenRS acts upon a “consortia first” mentality, striving to provide libraries with the tools needed for robust and extended functionality for resource sharing. The project will focus on developing and implementing software systems, protocols, and best practices that foster collaboration and support various library services, including seamless unmediated intra-consortial borrowing functionality and expanded sharing across multiple consortia. The software will provide a containerized code base configured for ease of deployment, maintenance, and upgrades. Libraries and consortia can choose to host the service locally or with a third party.

Project governance will be centralized in a governing board elected by contributing partners and will also rely on feedback from a wide community of project adopters and investors. The coalition recognizes that the project will only succeed if all stakeholders’ needs – whether libraries, consortia, developers, or vendors – are heard, validated, and addressed. Coalition governance will be based on open source principles and rely on trust, transparency, agility, and a welcoming community.

OpenRS will be an Open Library Foundation (OLF) project which operates with an open, transparent approach, emphasizing the best practices for open source governance and DevSecOps. The OpenRS software is built and maintained by Knowledge Integration, with support from EBSCO Information Services (EBSCO). Additional OpenRS Community members include representatives from the MOBIUS consortium, GALILEO/University System of Georgia (USG), Marmot Library Network, Boston Library Consortium, Colorado Alliance of Research Libraries, and others.

### INN-Reach

[INN-Reach](https://www.iii.com/products/resource-sharing/) is a resource sharing solution developed by Innovative, part of Clarivate. It unifies multiple libraries into a shared online catalog, offers patron-initiated requests, and provides cost-effective fulfillment of requests.

### Resource sharing schemes

### WHELF+

[WHELF+ Interlending Scheme:](https://whelf.ac.uk/the-whelf-interlending-scheme/) “In January 2018, WHELF members came together to launch a scheme of free, reciprocal, inter-library borrowing. This was made possible by our shared use of the Ex-Libris Alma Library Management System, which allows us to use core system functionality to lend print and digital resources to each other, free of charge. The scheme has been an amazing success, in 2022 the member libraries saved over £44K in total. As well as the undoubted financial benefit, it has also led to much greater co-operation and knowledge sharing between participating institutions.The scheme proved so successful, that in 2021, with the backing of Ex-Libris and the British Library, we began rolling out membership to non-WHELF institutions (hence the ‘+’ in ‘WHELF+’!). There are now nearly twenty institutions, covering a good geographical spread and a wide range of teaching and research specialities, reaping the benefits of WHELF+ membership; and, with more institutions expressing an interest in joining, and the potential of using new Alma functionality to automate processes further, the scheme has a bright future.”

Current WHELF+ members:

* Aberystwyth University
* Bangor University
* Cardiff Metropolitan University
* Cardiff University
* Harper Adams University
* Kingston University
* London School of Economics
* Natural History Museum
* Northumbria University
* Swansea University
* University of Cumbria
* University of Leeds
* University of Liverpool
* University of Salford
* University of South Wales
* University of Wales Trinity Saint David
* University of Westminster
* University of Winchester
* Wrexham University



### ISO ILL compliant LMS

For many years, ILDS functionality was either not included in library management systems (LMSs) or, in the UK, focussed on placing requests with the British Library's document supply service (BLDSS) rather than managing peer-to-peer ILDS. This has changed in the last few years with LMS suppliers, such as SirsiDynix, OCLC and PTFS-Europe (Koha) adopting the ISO ILL 10160/10161 standard. However, the adoption of the ISO protocol for practical peer-to-peer resource sharing in the UK is limited.

The only example application In December 2021) is in Wales, where a consortium of eight higher education libraries with the Ex Libris Alma LMS use the ISO standard to enable both digital and physical sharing and ensure an equitable spread of requests across participating institutions. There are future plans to extend this to the NHS libraries in Wales (which also use Alma). It should be noted that the resource sharing participants all use the same (Alma) LMS and, for practical implementation reasons, the WHELF invitation to extend the network is currently only open to other Alma customers.

## Commercial document delivery suppliers

The resource sharing landscape has recently seen the growth of a number of third party content aggregators providing document delivery services to libraries. These aggregators work across publishers to provide direct end-user ordering of articles / chapters delivered digitally direct to customers. Prevalent in commercial research libraries, these providers offer advantages in terms of customer ease of access by providing a request interface analogous with the discovery experience to access internal collections. Typically users search for the article they wish to access via a simple search interface, submit an online order and receive un-encrypted documents direct to their email inbox.

Examples of such services include:

* [Article Galaxy](https://www.researchsolutions.com/products/academic) (Research Solutions)
* [DeepDyve](https://www.deepdyve.com/)

However, such services come at a significant cost overhead as the business model for such services is usually a combination of a subscription cost (dependent on user numbers) and / or payment of publication specific copyright fees. For many publishers, working with such aggregators provides another means of driving access to their content in addition to direct article sales via their own platforms.

Due to high subscription costs and the payment of copyright fees on requests, such services may be cost prohibitive to higher education institutions.
