# Crossref

*Last version: 2024-10-18*

Crossref is a membership organization with 19K members from commercial and institutional publishing. Crossref's main service is the linking of citing and cited publications. Participating publishers register Crossref DOIs and submit metadata of their own publications. 

## General Information

| Name | Crossref |
| :---- | :---- |
| **Website** | [https://www.crossref.org](https://www.crossref.org) |
| **Owner** | Publishers International Linking Association, Inc. (PILA) |
| **Owner type** | Non-profit orgnization |
| **Owner country** | USA |
| **Launch year** | 2000 |
| **Scope** | Any |
| **Number of items** | 150 M records of metadata |
| **Access for index users** | Free |
| **Access for index data providers** | Subscription fees |
| **Documentation** | [https://www.crossref.org/documentation/member-setup/](https://www.crossref.org/documentation/member-setup/) |
| **Application form for providers** | [https://www.crossref.org/\_apply/member/](https://www.crossref.org/_apply/member/) |

## Content and Service

| Content type | Books, journals, articles, datasets |
| :---- | :---- |
| **Content language** | Any |
| **Content geographical provenance** | Any |
| **Indexing level for publications** | Journals and articles |
| **Full text** | na |
| **Index sources** | Source of information for Crossref are the data providers, no aggregation is provided Journal list: [https://www.crossref.org/xref/xml/mddb.xml](https://www.crossref.org/xref/xml/mddb.xml)  |
| **Supported standards** | na |
| **Bibliodiversity support** | na |

**Additional services**

CrossRef REST API:  
https://www.crossref.org/documentation/retrieve-metadata/rest-api/

## Requirements for Academic Publications

### Joining Process

Membership is required to be registered by Crossref. Mermbership is open to either publishers or service providers.  
Members can then issue Crossref DOIs for their users. DOI generation can vary from one service to another: automated/on-demand generation, for any content/specific content, etc.

**Data Collection Process**

Crossref dedicated tools:  
Crossref XML plugin for OJS (Open Journal Systems)  
Web deposit form  
Grant registration form (to register grant metadata only)

Also possible to send XML files conform to Crossref XSD:  
Upload JATS XML using the web deposit form  
Upload XML files using our admin tool  
XML deposit using HTTPS POST

### Minimum Requirements

**Editorial minimum requirements**

None

**Technical minimum requirements**

*Metadata standard*  
Crossref standard XML schema for various objects: [https://www.crossref.org/documentation/schema-library/metadata-deposit-schema-5-3-1/](https://www.crossref.org/documentation/schema-library/metadata-deposit-schema-5-3-1/) 

*Data file format*  
na

*Metadata file format*  
XML

*Metadata mandatory fields*

* Journal: full title, ISSN or title-level DOI and URL  
* Issue: issue, publication date (year)  
* Article: titles, publication date (year), DOI

### Additional Criteria

**Editorial additional specifications**

* Journal: abbreviated title, DOI, coden, journal\_issue, archive locations (with one archive name), title-level DOI and URL  
* Issue: publication date (month, day), journal volume, contributors, issue, DOI  
* Article: contributors, ORCID, publication date (day, month), pages (first page, last page), citation list, funding, license, Crossmark metadata and JATS-formatted abstracts  
* Publisher item number  
* Special numbering for special issues  
* Additional components of the publication (e.g. tables, figures etc.)

**Technical additional specifications**

* Publisher item number  
* Special numbering for special issues  
* Additional components of the publication (e.g. tables, figures etc.)

List of metadata required for books, articles, datasets:  
[https://www.crossref.org/documentation/schema-library/required-recommended-elements/](https://www.crossref.org/documentation/schema-library/required-recommended-elements/) 
