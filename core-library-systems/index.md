---
title: Core library systems
layout: enhanced
tags:
  - LMS
  - Library management systems
  - Library services platform
  - Library systems
  - LSP
nav_order: 9
has_children: true
---

# Core library systems

This section covers the key different aspects of library resource **management** systems. It does not cover discovery solutions which are covered in more detail under the dedicated section on [discovery.](/discovery/)

### What are library management systems?

Resource management solutions are known in the UK as library management systems (LMS) a term which equates to integrated library system (ILS) which is the term more commonly used in the US. Library management systems can be simply described as software that are enterprise systems used to manage library collections and their associated workflows/processes such as cataloguing, orders made and users who have borrowed items.

Typically library management systems consist of a number of core modules including:

- acquisitions - ordering, receiving and invoicing materials; funds management for budget profiling. Most systems will enable automated integration with suppliers for ordering via EDI (Electronic Data Interchange)
- cataloguing - for classifying and cataloguing materials (usually based on MARC standards)
- borrowers / patrons - details of library users grouped into types of borrowers
- circulation - lending materials based on loan rules linked to borrower types
- serials - for receipt and management of journals and magazines

Additionally systems may also include modules for or integration with:

- interlibrary loans/resource sharing - for managing document delivery / loans from external libraries. In the UK these may be enabled for automated ordering via suppliers such as the British Library Document Supply Centre (BLDSC)
- electronic resource management - for managing subscriptions to online content packages.
- reading/Resource list management

Library management systems will typically also include some form of OPAC (online public access catalogue); a web based interface allowing end users to search the library catalogue (of predominantly print resources) and access their individual borrower account. These are being displaced by 'discovery services' which enable the integrated discovery of print and online resources such as journal articles and ebooks.

Library management systems were traditionally hosted on premise on an organization's internal server. Hosting provided (sometimes referred to a cloud hosting) by the vendor is now a popular option.

### Library service platforms

From around 2010 a new generation of web and cloud based systems emerged. These are termed Library Services Platforms (LSPs). The most widely deployed LSPs are Clarivate/Ex Libris Alma, and OCLC WMS. They were largely developed from the ground up rather than being evolved from past 'legacy' solutions. In functional terms the key differentiation from a LMS/ILS was a fully web based staff interface and **integrated** management of print and electronic resources. This meant libraries did not need a separate electronic resource management (ERM) system or spreadsheets to manage their (predominantly) journal subscriptions and associated licenses.

In technology terms LSPs are fully web based and hosted in the cloud. “A born cloud based system” is essentially a single system with the multiplicity of client libraries being ‘tenants.’ These ‘clouds’ may be regional (e.g. European) in order to meet legislative requirements but, within each multi-tenant environment, there is only one copy of the application software, one operating system and one database supporting multiple libraries. The vendor only has to deploy, develop, maintain and upgrade one copy of the software. There is no option for the software to be supported 'on premise' - on local servers.

In contrast a hosted LMS/ILS solution is much less efficient. While the hardware infrastructure may be shared the vendor still has to support a multiplicity of client systems that need to be maintained separately. The efficiency benefits to the vendor of what is in effect one single global (or at least multi-national) library system are clear.

The open source FOLIO library system is characterized as a LSP, being built from the ground up using modern 'microservices' architecture. However unlike Alma or WMS there may be multiple versions - inherent in a open source approach where code is open to be modified. FOLIO can be deployed as a hosted or on promise solution.

Another feature of a LSP it that it comes paired with a ‘discovery service’ - Primo with Alma WorldCat discovery with WMS). Folio does not have a discovery service but is often paired with the Ebsco Discovery Services (EDS).

### The evolution of 'legacy' library systems

Rather than take the path of creating wholly new LSPs some vendors such as Innovative Interfaces (now part of Clariate), SirsiDynix and ESS (formerly Capita) maintained their legacy systems but moved to a hosted model and layered web interfaces (eg SirsiDynix BlueCloud) and additional functionality over that.
