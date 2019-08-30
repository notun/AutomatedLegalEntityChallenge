# MIT Media Lab - Computational Law

## Law ReImagined-
## Inventing Automated and Autonomous Legal Entities Part 4
## (Preparation Stage)

### "AALE" Collaborative Hack with Dazza, Beth, Brenden, Bryan, Silke et al. 
#### [New File For Pull Request Toward MIT Media Lab AALE Challenge Repository](https://github.com/mitmedialab/AutomatedLegalEntityChallenge/new/master)

#

### Topic for this note:
#
### SALI LMSS Computational Law Relevance and Usability for our AALE Challenge.
#
#### Building up from SALI Alliance - LMSS Legal Matter Specification Standard Draft Project (updated June 2019) 
#
### First Iteration - DRAFT WITH “REQUEST FOR COMMENT” - Thank You.

#

#### The idea of a closer look at SALI LMSS in an AALE context came from a Computational Law discussion, serendipitously triggered by our CL colleague Diana, together with Dazza and pics he took at the SALI LMSS presentation - ILTACON conference https://www.iltacon.org in Orlando, Florida on August 18th-22nd 2019. After Brenden nailed the SQL aspect, the conversation expanded to APIs vs Protocols, legal data & process representation & interoperabilty.

#### In addition to Dazza's pics comprehensively reflecting the SALI LMSS presentation, the reference document we use is the SALI Alliance's Draft Legal Matter Specification Standard (LMSS) 1.0, Rev 2 (June 2019), together with associated SALI Alliance reference working materials- which altogether cover the content of the ILTACON presentation pics:

#### https://salilegal.org/sali3/docs/SALI%20LMSS%201.0%20rev2c.pdf?1566567194
#### Version Revision 2c - Last Update: 2019-06-08 - SALI Matter Specification Committee - Adam L. Stock
#
#### SALI Alliance materials are subject to © Copyright 2019 Standards Advancement for the Legal Industry Alliance - This SALI LMSS work is licensed under a Creative Commons Attribution-NoDerivatives 4.0 International License.
#### See also: SALI Alliance Intellectual Property Rights Policy - Draft 07 June 2018: https://salilegal.org/sali3/docs/SALI%20IPR%20Policy%2007JUN18.pdf .
#

#### For our (non-Lawyer Chris) Part A observations on computational law relevance & usability of SALI LMSS to AALE Challenge, and possible Computational Law & AALE work topics, that aggregate & synthesize our group discussion:
 
**Creative Commons Attribution License: https://creativecommons.org/licenses/by/4.0/**

**Attribution: Christophe Bosquillon, MSc in cryptocurrency, digital assets & blockchain at the University of Nicosia, Cyprus (on-going). Also an alumni of Mines Paritech & HEC (Entrepreneurs) Paris.**

#

#
### SALI LMSS Computational Law Relevance and Usability for our AALE Challenge.
#
#### Building up from SALI Alliance - LMSS Legal Matter Specification Standard Draft Project (updated June 2019) 
#
### First Iteration - DRAFT WITH “REQUEST FOR COMMENT” - Thank You.

#

### Summary & Objectives

#

_**What to read, why and where**_:

Part A covers observations on the computational law relevance and usability of SALI LMSS to our AALE Challenge, and possible Computational Law & AALE work topics, that aggregate & synthesize our group discussion.

Parts B to E are a consolidation of SALI LMSS draft features, other working and demonstration materials as of June 2019, including tables, chats and sample coding- _plus our own tinkering screen-shots as a log-in (non paying) member._ 

For sake of ease of use by anyone unfamiliar with SALI LMSS, we wanted to edit, with some _**emphasis**_ on most salient parts, the content of SALI Alliance LMSS reference materials, keeping them handy in this GitHub file to start with.

For hurried readers already experienced with SALI LMSS, you don't need to read Parts B-C-D-E, and here's a spoiler for our main findings in Part A: [Most salient Computational Law aspects of SALI LMSS](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#most-salient-computational-law-aspects-of-sali-lmss). 

For readers unfamiliar with SALI LMSS, you may first review Parts B-C-D-E to form your own opinion, then check out Part A. 

If you don't have time, you can still check above part A spoiler, which has links to relevant SALI LMSS body features.

This might be worth the time you don't have, actually:)

#

_**Summary**_

With their efficient, productivity & performance-streamlining oriented, cost-conscious approach, these SALI LMSS draft features should prove quite attractive for professionals and senior decision makers. 

Also for SALI LMSS well explained, intuitive ease of use and clear-cut legal profession BPM approach, in the context of practicing Law and/or providing alternative Legal services, it has our vote. 

No mind-stretching decentralized thinking nor much bleeding-edge tech yet ... here, mostly an SQL-based system that mostly does queries. We're talking about straightforward legal profession BPM that is simple, effective, usable, now, within a legal profession still dominant paper paradigm, that nonetheless has started to pivot toward integrating more Legal Tech.

According to the project leaders:

>_"The LMSS structure can be expressed as a database schema for storage or an XML or JSON structure for transmission of the matter information"._ 

Incorporating features such as tree-based structure, hierarchical, objects and parameters based, this may not sound too earth-shattering, but _it does the job_. It does.

Of course, one could argue about the SQL paradigm, or reality-reduction by hierarchy, parameters, and language, but these old-fashioned SQL database features hold a clear advantage of functioning in an intelligible, digestible and palastable way, _so that we can start working on training wheels and build up complexity from there_ (a formula borrowed from Dazza's book). 

We won't speculate whether SALI LMSS features will ultimately nail the standard, or even if there should and will be "a" standard (there is probably such a need, though), but to us it sounds like a move in "a" (if not "the") right direction. 

_**Objectives**_

Furthermore, regardless of the SQL paradigm choice, and this is the point here, _we are intrigued by some of SALI LMSS features possible computational law relevance and usability for our AALE challenge: we like what this SALI LMSS tool does_, and because it could do even more with some flexible and modular extensions, _having been conceived with that mindset_.

In [Part A](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-a---computational-law-relevance-and-usability-of-sali-lmss-for-our-aale-challenge), we look at the [computational law relevance and usability of SALI LMSS features for our AALE Challenge](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-a-1-computational-law-relevance-and-usability-of-sali-lmss-for-our-aale-challenge-1).

In [Part B - SALI Legal Matter Standard Update Presentation (June 2018)](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-b---sali-legal-matter-standard-update-presentation-june-2018),  we review the June 2018 high level outlook of the SALI LMSS project, that was initially conceived in 2017. 

For the 2017 Zeitgeist around the conception of the SALI LMSS project at the time, see also: 

- SKU for legal services (SKU = Stock Keeping Unit) http://www.legalexecutiveinstitute.com/skus-matter-standards/ (2017) by David Curle. David Curle is Director of the Technology and Innovation Platform for Thomson Reuters Legal Executive Institute, providing research and thought leadership around the competitive environment and the changing legal services industry - follow David on Twitter: @davidcurle, 

and (of course!),

- CodeX Future Law 2017 conference materials at https://conferences.law.stanford.edu/futurelaw2017/materials/.


In [Part C - Draft Legal Matter Specification Standard (LMSS) 1.0, Rev 2 (June 2019)](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-c---draft-legal-matter-specification-standard-lmss-10-rev-2-june-2019), we look at the SALI LMSS detailed features, starting with a [Table of Contents](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#table-of-contents---draft-legal-matter-specification-standard-lmss-10-rev-2-june-2019) that links to the full [Body](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#body-of-draft-legal-matter-specification-standard-lmss-10-rev-2-june-2019) of the SALI LMSS detailed features.

In [Part D](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-d---fully-expanded-sali-lmss-tree-structure-and-detailed-parameters-of-sali-lmss-structure-and-code-browsers), we include the fully expanded SALI LMSS tree structure (also shown in [Part B](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-b---sali-legal-matter-standard-update-presentation-june-2018)), and we post screen-shots of SALI LMSS structure, and code browsers parameters, having tinkered with this tool as log-in (non paying) member.

In [Part E](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-e---additional-samples-of-sali-lmss-coding), we list other detailed examples of coding (reference: https://salilegal.org/sali3/docs/LMSS%20Examples.pdf?1566567194), in addition to the sample coding already provided in the [Body](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#body-of-draft-legal-matter-specification-standard-lmss-10-rev-2-june-2019) of [Part C](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-c---draft-legal-matter-specification-standard-lmss-10-rev-2-june-2019).

#
#
#

## Part A - Computational Law Relevance and Usability of SALI-LMSS for our AALE Challenge

### Content:

### [PART A-1 Computational Law Relevance and Usability of SALI LMSS for our AALE Challenge](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-a-1-computational-law-relevance-and-usability-of-sali-lmss-for-our-aale-challenge-1)
#
#### [A-1-1. Education & persuasion](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-1-1-education--persuasion-2)
#### [A-1-2. It's a (legal) BPM issue- Keep It Simple and (not too) Stupid](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-1-2-its-a-legal-bpm-issue--keep-it-simple-and-not-too-stupid-2)
#### [A-1-3. SALI LMSS legal structure and coding might be helpful to think of AALE legal objects & legal functions](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-1-3-sali-lmss-legal-structure-and-coding-might-be-helpful-to-think-of-aale-legal-objects--legal-functions-2)
#### [A-1-4. Give SALI LMSS some benefits of the doubt: consider interoperability should it become mainstream](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-1-4-give-sali-lmss-some-benefits-of-the-doubt-consider-interoperability-should-it-become-mainstream-2)
#
#
### [PART A-2 What SALI LMSS won't do and other issues left out](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-a-2-what-sali-lmss-wont-do-and-other-issues-left-out-1)
#
#### [A-2-1: Expected paradigm of exponentially increasing dynamic data](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-2-1-expected-paradigm-of-exponentially-increasing-dynamic-data-2)
#### [A-2-2: Expected paradigm of increasing share of ultra high-speed M2M transactions under AALE management](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-2-2-expected-paradigm-of-increasing-share-of-ultra-high-speed-m2m-transactions-under-aale-management-2)
#### [A-2-3. The non-verified non-immutable, trust-dependent, falsifiable data paradigm of an SQL database](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-2-3-the-non-verified-non-immutable-trust-dependent-falsifiable-data-paradigm-of-an-sql-database-2)
#### [A-2-4. Generations and types of database and reality representation systems beyond that](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-2-4-generations-and-types-of-database-and-reality-representation-systems-beyond-that-2)
#### [A-2-5: Protocols vs APIs](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-2-5-protocols-vs-apis-2)
#
#
### [PART A-3 Available Legal Tech and possible working topics for SALI LMSS and/or Computational Law and/or AALE design](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-a-3-available-legal-tech-and-possible-working-topics-for-sali-lmss-andor-computational-law-andor-aale-design-1)
#
#### [A-3-1. Different types of legal records database for legal research](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-3-1-different-types-of-legal-records-database-for-legal-research-2)
#### [A-3-2. Array of "Legal Case Management Software"](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-3-2-array-of-legal-case-management-software-2)
#### [A-3-3 APIs vs Protocols and more on current major database solution vendors to the legal profession ecosystem](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-3-3-apis-vs-protocols-and-more-on-current-major-database-solution-vendors-to-the-legal-profession-ecosystem-2)
#### [A-3-4 Computational Law required features and takeaway for AALE design](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-3-4-computational-law-required-features-and-takeaway-for-aale-design-2)
#### [A-3-5 SQL structure-related collapsible interactive tree, chart-Database representation, etc](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-3-5-sql-structure-related-collapsible-interactive-tree-chart-database-representation-etc-2)
#### [A-3-6. Tech paradigms & information frameworks at play in legal process management](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-3-6-tech-paradigms--information-frameworks-at-play-in-legal-process-management-2)
#
#
#

### PART A-1 Computational Law Relevance and Usability of SALI LMSS for our AALE Challenge

### Content:

#### [A-1-1. Education & persuasion]()
#### [A-1-2. It's a (legal) BPM issue- Keep It Simple and (not too) Stupid]()
#### [A-1-3. SALI LMSS legal structure and coding might be helpful to think of AALE legal objects & legal functions]()
#### [A-1-4. Give SALI LMSS some benefits of the doubt: consider interoperability should it become mainstream]()

#
#

#### A-1-1. Education & persuasion

No horse is to dead to be flogged. We could take example from the SALI LMSS narrative being simple and effective for:

- educational purpose: Law firms established senior partners not too eager for Legal Tech adoption might find SALI LMSS intelligible, digestible, and palatable enough to adopt it, letting more tech-eager juniors do the search & rescue of data. And partners who are already comfortable with various kinds of Legal software might seek a similar level of use of ease.

- political & senior decision makers persuasion purpose: SALI LLMS sticks to the KISS principle (Keep It Simple and (not too) Stupid) and may work well with the most automatisation-reluctant policy & law makers and senior regulators. 
#

#### A-1-2. It's a (legal) BPM issue- Keep It Simple and (not too) Stupid

>_**Note: careful with the word "process"!!!**_. 
>
>In SALI LMSS, the term "process" is to be understood as a specific legal practice process within a set of defined structures and parameters. 
>
>Therefore the SALI LMSS "process" is _not to be understood as_ one of the following:
>
>- "process" in SALI LMSS is _not to be understood as_ the different clerical operations in a _case management_ (desk officer's work), that are covered by an array of "Legal Case Management Software" as described e.g. there: https://www.g2.com/categories/legal-case-management#learn-more .
>
>- "process" in SALI LMSS is _not to be understood as_ the combination of legal object and legal functions that we have considered in previous AALE sessions.
>
>- "process" in SALI LMSS is _not to be understood as_ the set of functions and "sub-processes" that we have covered in a recent Contract Law vs AALE analysis. 
>
>When we say that Contract Law revolves roughly around two categories of functionalities, one related to the consequences of human behavior, and one related to the consequences of established business practices, we mention that each categories cover a number of "(sub-)processes". We might want to stop using the generic term (sub-)process, sticking to (sub-)functions only, to avoid confusion when simultaneously talking about the SALI LMSS "process" context.

SALI LMSS is first and foremost _an SQL-based Legal BPM "progressive" improvement proposition_ for Law practices. 

It suggests some _next evolutionary stage_, beyond current "Legal Case Management Software" (LCMS), often used together with eDiscovery, and with more accounting oriented internal BPM systems to co-manage billing. 

For Law firms partners of various backgrounds, used to no-brainer LCMS, it looks rather mindful and wise for SALI LMSS to come across as equally user-friendly under the form of an SQL database approach, i.e. Keep It Simple and (not too) Stupid. 

#

#### A-1-3. SALI LMSS legal structure and coding might be helpful to think of AALE legal objects & legal functions

SALI LMSS does look at roles, functions and legal context / scenarios. 

It does look at formalizing values, bodies of law, legal processes structure, the coding parameters, successive “states” when advancing through new bodies of Law.

Or adding context-specific extensions, as broad categories of processes whose pathways can also be charted, in ways that are backward compatible- which is nice in an evolutive legal process not clearly charted at the onset. 

And inside these broad processes, it looks at a variety of sub-processes that can describe both the application of bodies of laws and to a certain extent parallel the way they execute in analog life legal processes. 

Yes, we do have to be careful in terms of defining and structuring what levels of protocols & functionalities are (more on this in section A-2 and A-3 below).

And how data, its veridical validation, should be organized, to generate & relate to valid Computational Law processes. 

But, in our recent AALE experience & Contract Law analysis, we find we need to sort out relevance & functionality of a number of legal functions & sub-fuctions, in relation with bodies of Law, in a human-AAS interaction context, under AALE process. 

While not exhaustive, a methodology like the one used in SALI, looks like some sort of pattern, from which we might be willing to (selectively) extract inspiration, in the way we approach problems and chart pathways to AALE solution design. 

In Dazza's words:

>That’s how it matters. You can barely count, calculate, describe, reason about or predict from natural language or format/ display oriented structures. But SALI LMSS at least starts to reveal the relevant context and salient bodies of law or legal actions. These are very important dimensions to have for making law and legal processes computational.

Here's a non-exhaustive list of some SALI LMSS aspects that retained our attention and _ring a bell in relation with AALE design_, which motivated us to complete the current memo, and do this without getting to hung up with the Keep It Simple and (not too) Stupid SQL aspect- an important, yes, but still separate, issue. 

We introduce relevant links to the Body of SALI LMSS of Parts B & C, so readers not familiar with it can get up to speed easily.

### Most salient Computational Law aspects of SALI LMSS:

The SALI LMSS delivers [structure, codes, and APIs](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#what-the-lms-standard-is-delivering).

The SALI LMSS structure defines [where information is stored](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#the-lms-structure-defines-where-information-is-stored).

The SALI LMSS code sets define what are [allowable values](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#the-lms-code-sets-define-what-are-allowable-values).

The SALI LMSS APIs are tools to help [implement the standard](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#the-lms-apis-are-tools-to-help-implement-the-standard).

The [Computational Law components of the LMSS](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#13-what-are-the-components-of-the-lmss-1) help think about an AALE context as well, as they cover structure, allowed values, and dependencies and supports both matter instances and matter templates. 

##### Interoperability aspect- 
The legal matter application programming interfaces (APIs) include: the transport API for exchanging data and the UX API for supporting the user interface of applications that use the standard.  

Structure & components first details can be found [there](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#3-legal-matter-specification-lmss-components-1).

##### Interoperability aspect-
Because the standard is designed to provide clear guidance and [party-independent enumerated values](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#21-playerviewer-independence-1) to ensure that matters are encoded the same way independent of the party involved in matter, this is relevant to an AALE/DAO and a legal counsel establishing a lawyer-client relationship and setting up a process and procedures (either with AALE/DAO as a whole or with a specific individual loaded with "attribution").


Because the LMSS is intended to be used for legal matters, to describe legal matters that are being executed, the standard implements [hierarchical and additive coding.](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#22-successive-refinement-and-additive-coding-1). For example, when a matter begins, the area of law for a matter may not yet be fully determined: with the Publishing DAO legal analysis, it only became clearly apparent after a while that Agency Law wasn't sufficient to cover all scenarios and that Contract Law was required to replace and/or supplement Agency Law in most scenarios. As such:

##### Interoperability aspect-
_**The SALI LMSS design ensure that other systems that depend upon the initial restructuring code continue to work.**_  

Since the LMSS cannot anticipate all needs, there is a well-defined way to [extend the standard while staying within the design and API functionality](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#24-extensible-1). _This would be useful to add and plug-in many new ontologies born from AAS/AALE needs._

##### Interoperability aspect-
As part of [LMSS Components](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#3-legal-matter-specification-lmss-components-1), the [Extensions](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#35-extensions-to-the-lmss-codes-1) to the LMSS code are intended to be adaptable to the needs of customers. _The processus is straightforward and could be used to test-experiment new structures and codes in the context of new ontologies born from AAS/AALE needs._ All there is to do is to define these.

##### Interoperability aspect-
The [structure](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#4-structure-of-lmss-document-1) of SALI LMSS documents provide a template for what would be required as parameters and output to warrant AALE _interoperability_ with SALI LMSS, including but not limited to managing new AAS ontologies in a human-AAS interaction and attribution context.

In order to do that, specific care should be placed on formatting AAS/AALE ontologies with respect to [Matter](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#46-matter-1), [Narrative](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#47-narrative-1), [Description](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#48-description-1). The issue of language may or not be optional.

##### Interoperability aspect-
Because the [Process](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#49-process-1) container describes the process, service or product being delivered, it would be the bulk of efforts to further define the lawyer-client relationship process in a AALE/human-AAS context, and register all parameters of actions taken in that context. 

New types of [Players](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#410-player-1) would need to be defined, since we might as well have electronic agents whose (consequences of) actions are attributed to a (human) legal person, but also possibly AAS as full fledge legal agent.

And the AALE itself is a [Legal Entity](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#4104-legal-entity-1) player.

The [Counsel](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#411-counsel-1) matters as well, since it could be human, or it could be partially or fully an AAS/AALE itself, in a context where a Counsel-AAS/AALE has a "constructive" interaction with a human-AAS/AALE context in order to mitigate rather than exacerbate the risks of litigation, faciliate ADR in various ways, etc.

##### Interoperability aspect-
The [Process Object](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#412-process-object-1) itself would need to internalize a number of extensions and changes in a human-AAS/AALE context. Because a process can have multiple process objects (a process object itself can simply be a summary of key attributes of the overall process), that functionality would allow to test-experiment additional layers of process objects linked to the human-AAS/AALE in a modular way, until that works well with the human-only inherited paradigm.

The component of [Monetary Value](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#413-monetary-value-1) might want to be expanded to integrate various cryptrocurrencies, not merely "a currency code as defined by ISO 4217". 

_Non-monetary value type of assets of digital / crypto nature_ would also require definition and integration under bodies of Law.

##### Interoperability aspect-
Settlements and Restitutions involving on-chain digital / cryptoassets processes might want to be considered.

##### Interoperability aspect-
While [LMSS APIs](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#5-the-legal-matter-application-programming-interfaces-apis-1) are not supported in Draft LMSS 1.0 Rev 2, suffice to say that they primarily support queries, SQL primary raison d'être, not data verification and validation in relation with blockchains and oracles, etc. This point links back to the conversation on APIs and Protocols where we might want to dig more education and clarifications.

[Code Sets](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#6-code-sets-1) types might need to be enriched, also as part of the actions required as parameters and output, to warrant AALE _interoperability_ with SALI LMSS, including but not limited to managing new AAS ontologies in a human-AAS interaction and attribution context.

In [Part D](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-d---fully-expanded-sali-lmss-tree-structure-and-detailed-parameters-of-sali-lmss-structure-and-code-browsers) we provided a fully expanded SALI LMSS tree structure and detailed parameters of SALI LMSS structure and code browsers. 

_Scanning through the tree structure and further detailed fine print, shows where parameters, generated by new AAS ontologies in a human-AAS interaction and attribution context, could be defined and introduced, starting obvioulsy with_:

- new types of legal entity (AALE/DAO), 
- new roles of human player in relation with AALE/DAO, 
- new roles of human in a context of attribution of (consequences of) actions of an electronic agent, 
- new possible fully fledged AAS legal agents, 
- new types of Law or amendments related to characterization and treatment of specific digital / crypto assets, 
- existing & new aspects of cyber/internet Law & other Laws applicable (Property, Contract, Tort & Restitution, Int'l etc), 

like we again discussed recently, whereas Common Law sounds more advanced than Civil law in this progress, as we speak.

_**The question of R4 - Roles and Relationships, Rights and Responsibilities**_

The R4 framework is very important and useful for us to consider for legal analysis in an AALE/human-AAS context. 

In SALI LMSS structure and codes, R4 doesn't appear exactly as such, and this would require some tweaking: 

- Players can have several Roles via distinct Relationships with other Players, that would need structure in Extensions. 
- Rights and Responsibilities are somewhat reflected by "Privileges and Obligations" so that too might do the job. 

_**AALE/human-AAS context Legal Objects and Legal Functions vs SALI LMSS structure, codes and processes**_

We also refer to discussions on AALE/human-AAS context Legal Objects and Legal Functions in recent Live sessions, in particular 3rd Live session in Berlin, with Beth, Cem & Jim, Dazza, Bryan, Brenden, and Silke:

##### Interoperability aspect-
Intuitively we should still _move ahead in a totally independent fashion with regard to specific AALE B/L/T/ design_, but might want to bear in mind aspects of _interoperability_ and/or parallelism with the SALI LMSS features. More on this below. 

Also, it could be that some of the most relevant (though "merely" SQL-based- sorry) features of SALI LMSS may be sort of extracted, and integrated within the AALE B/L/T/ design either as a plug-in or as one of the AALE components. 

_In which case the extracted SALI LMSS relevant features become wrapped up within the AALE B/L/T/ construct._

Intuitively it should matter whether we "like" or not integrating some of SALI LMSS upcoming APIs with the various AALE B/L/T/ construct-based Protocols. So we need to dig more these APIs vs Protocols aspects, definitely.

#

#### A-1-4. Give SALI LMSS some benefits of the doubt: consider interoperability should it become mainstream

And even if it doesn't, something else quite similar might as well break through- you never know.

Suppose for example that a few years from now, there is a critical mass of legal profession players that work with SALI LMSS or something close enough. And that among other things, these legal profession players deal with a rapidly increasing proportion of cases involving AAS and AALE issues. 

Say a fleet of fetch-pay-deliver drones have been hacked and gone rogue somewhere in the middle of 'Murica but they AAS drones are legally under management of a highly sophisticated Vermont BBLLC that supports a DAO with a system of attribution to (human) legal entities for the consequences of their acts, starting with liability.

Yet, the case on the plaintiffs side is handled by a relatively middle-of-the-road local Law firm from where the harmed parties originate, and while that local law firm has integrated the SALI LMSS features in its legal practice process, it is rather clueless with regard to AAS/AALE B/L/T/ process management issues.

Suppose that, meanwhile, some good enough solutions to deal with human-AAS issues under AALE management emerged from Cambridge: obviously you want the two systems SALI LMSS and AALE B/L/T/ process to be able to work together. 

##### We noticed some 10 (ten) _**interoperability aspects**_ ...

... in above previous paragraph [A-1-3. SALI LMSS legal structure and coding might be helpful to think of AALE legal objects & legal functions](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-1-3-sali-lmss-legal-structure-and-coding-might-be-helpful-to-think-of-aale-legal-objects--legal-functions-2) ... [there](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#interoperability-aspect-), [there](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#interoperability-aspect--1), [there](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#interoperability-aspect--2), [there](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#interoperability-aspect--3), [there](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#interoperability-aspect--4), [there](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#interoperability-aspect--5), [there](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#interoperability-aspect--6), [there](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#interoperability-aspect--7), [there](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#interoperability-aspect--8), and [there](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#interoperability-aspect--9).

#
#

### PART A-2 What SALI LMSS won't do and other issues left out

### Content:

#### [A-2-1: Expected paradigm of exponentially increasing dynamic data](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-2-1-expected-paradigm-of-exponentially-increasing-dynamic-data-2)
#### [A-2-2: Expected paradigm of increasing share of ultra high-speed M2M transactions under AALE management](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-2-2-expected-paradigm-of-increasing-share-of-ultra-high-speed-m2m-transactions-under-aale-management-2)
#### [A-2-3. The non-verified non-immutable, trust-dependent, falsifiable data paradigm of an SQL database](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-2-3-the-non-verified-non-immutable-trust-dependent-falsifiable-data-paradigm-of-an-sql-database-2)
#### [A-2-4. Generations and types of database and reality representation systems beyond that](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-2-4-generations-and-types-of-database-and-reality-representation-systems-beyond-that-2)
#### [A-2-5: Protocols vs APIs](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-2-5-protocols-vs-apis-2)

#

#### A-2-1: Expected paradigm of exponentially increasing dynamic data

SALI LMSS has a pathway for a train of applicable bodies of Law when you don't know where to start and/or in which order.

SALI LMSS has a pathway to create and adapt narratives based on the audience.

How do you automatize that processing of exponentially increasing dynamic data, when it involves AAS under AALE management? It seems like AALE has to pre-digest the work (thanks to its internal self-monitoring, reporting and correcting B/L/T/ features) and produce outputs that are fathomable by the still semi-human external SALI LMSS process. 

But then is SALI LMSS really needed then ??? ... or could an AALE just in fact absorb the useful features of SALI LMSS and transform the interoperability issue into some SQL plug-in compatible with AALE own B/L/T/ design. 

Both options may be confronted to adverse conditions of previous feasibility of legal standardization anyhow.

This could end up looking like a "patchwork" especially across jurisdictions and unstructured dynamic data.

#

#### A-2-2: Expected paradigm of increasing share of ultra high-speed M2M transactions under AALE management

Similar remarks as above A-2-1. 

In addition, SALI LMSS could also be seen (externally or as an internal SQL plug-in to an AALE B/L/T/ system) as a kind of _"pathway toward re-introducing a human in the loop"_ at a much _**slower**_ human speed. 

This e.g. for manually-handled case such as tort & restitution, off-chain assets liquidation, or corporate restructuration offline, when there isn't any automated alternative to that process. 

Or even just for managing some of the attribution process to a responsible (human) legal entity of the consequences of the acts of an "electronic agent" under UETA framework (Dazza).

Like a seasoned 4x4 all-terrain vehicle with its "bush mechanics", it doesn't look very glamorous & the mechanics works only with rather rudimentary tools and worn-out spare parts ...

... but _it does the job_ under adverse, non fully automated conditons, in a B/L/T/ equivalent of the middle of nowhere. 

A battle-hardened A10 Warthog is another analogy: don't send an F-35 do a combat air support job an A10 can do just fine.

It may take some time before both old A10 Warthog and old SQL DB are fully decommissioned, meanwhile they get upgrades.

Sometimes in (the) business (of life) you can accomplish much even if merely "surviving" with less than ideal means. 

As often, it depends.

#

#### A-2-3. The non-verified non-immutable, trust-dependent, falsifiable data paradigm of an SQL database

We can't disagree with Brenden there, at least on the sentiment- this sounds a little bit backward especially if you've spent the past decade or even just half or a third of it in the blockchain paradigm ... it almost feels like an odd regression.

Question being: what tool do we need to do which job in relation with which representation of reality to what effect?

So it could be that some parameters of SALI LMSS matter definition are extracted via oracles from a verified trustless environment and that others are susceptible to falsification- how do we deal with that? 

But then again it depends on the structure of representation of reality and data verification in the context of building up a case. 

We might expect several level of data integrity and level of "truth" to cohabit, unless it's a fully automatized process at the onset (and still it could go rogue, etc). The concept of "representation of reality" takes precedence over "truth".

So it's a layer cake and we have to see the merits of having SALI LMSS in the loop or not, maybe it depends on the case context, and its evolution stage.

Then again, to have SALI LMSS as a sort of "back-bencher & note taker" for humans-in-the-loop doesn't sound that bad.

#

#### A-2-4. Generations and types of database and reality representation systems beyond that

Another aspect perhaps not to be omitted is the backward compatibility with other types of databases (SQL or non-SQL or else) in the ecosystem of dominant vendors and independent in-house developers, in addition to the small issue of making sure that SALI LMSS features can work in _interoperability_ with above mentioned LCMS Legal Case Management Software.

_We also agree with remarks by Diana (slightly edited below) that reality representation and use case do matter._

>While an API is first and foremost an interface, SQL language itself is a data structures that is a choice of representation of reality, that belongs to pre-defined domains and frameworks, on which policies and/or algorithms are being executed to implement or perform a given task. So the issue of trustless verification of "truth" matters but it is a separated one.
>
>Because Law relies primarily on language, not only does context matter, but part if not most of the problem goes back to information theory: every time we store information in a given format, we are losing dimensions. 
>
>Even with text, the activity of writing “A performed B” is already some subjective filter about a given fact. 
>
>Even if using the same word, signal, may have different meanings.
>
>This goes back to knowledge representation and ontologies, universe and domain. And most languages are abstract and general purpose. How we represent ideas (that can go beyond text) most is embodied in a given domain. But there isn’t a “general truth”. 
>
>The difference is to build something closer and for the legal domain rather than applying a general purpose language to a specific domain. 
>
>As every time we generalize we loose dimensions, when using this general rules they may not fit a specific domain.
>
>There is also the issue that such a frozen hierarchical structure may not allow various roles or attributes by nodes. 
>
>An alternative solution can be found with graph-Databases, whereas each node has several attributes. And they don't need to be so hierarchical, in additon to the fact that chart-Databases may be seen as a visually & conceptually preferable representation.
>
>As a matter of fact, data structures is where most time and resources get consumed, for tasks such as cleaning, transforming, etc. 
>
>While graph-Databases show a nice aspect of blending two solutions in a not-so-hierarchical way, it all depends on what data is available and what the output should be, as there is no general “right/best” solution. 
>
>And in the case of unstructured data, this isn't manageable by SQL, so yet another case of "monster" data.

#

#### A-2-5: Protocols vs APIs

We have an opportunity to clear the air for everyone here, that it is indeed duly understood, that _APIs are interfaces_, and that's that, like SQL is a language interface that primarily support queries- forgive the over-simplification. 

Whereas _Protocols are completely different animals_, that may need to be considered (or not) for certain functions. 

Each one is a tool that may be used in a given context to perform a given task. 

_Question is (again): what tool do we need to do which job in relation with which representation of reality to what effect?_

This said we agree with Brenden that _Protocols do matter, in particular those "wire protocols" like what blockchains do_. 

Part of SALI LMSS design question in relation with AALE might be (roughly and intuitively):

- when we have to operate AALE-linked wire protocols (blockchain etc.) can we just do that and bypass the whole SALI LMSS approach to manage both input, outut and the whole legal practice process and lawyer-client relationship process?
- should we see (part of) the AALE B/L/T/ process as an additonal layer on top of SALI LMSS or a side-process working in full interoperability (ideally) with SALI LMSS?
- should we see (part of) the AALE B/L/T/ system as in fact extracting relevant features from SALI LMSS and integrating them as an SQL-plugin within the AALE B/L/T/ construct,...

... _in which case SALI LMSS becomes almost totally "wrapped" within the AALE B/L/T/ construct._

_But we do agree intuitively and in principle (before going into details) with Brenden rising the issue of Protocols: because it is so important, and, even if that's a "it depends where, when, and for what" issue, protocol still matter fundamentally for a general design of both SALI LMSS and how they should have interoperability with fully functional AALE B/L/T/systems._

>While an API only indicates how to fetch data, a protocol informs about the data & how a system is expected to function. 

Among various protocols, "wire protocols" such as blockchain have a central role in the trustless verification of the veridical representation of data in relation with a "reality" formalized under certain domain(s) and framework(s).

For now, Brenden listed some examples of protocols- _and maybe we might want to dig a bit deeper these questions._


>Overview 
https://blog.chronobank.io/ethereum-token-standards-19fbcc54fe27
>
>“Some Ideas to Unlock Programmability in Security Tokens” by Jesus Rodriguez
https://link.medium.com/nWrUtvS1qX
>
>ERC884 tokens
>“Tokenising Shares: Introducing ERC-884” by Dave Sag
>https://link.medium.com/aGJ9R3FpBU
>A reference ERC-884 implementation has been published under the MIT open-source license.
>
>ERC 1440
>
>DS Protocol
>https://securitize.sfo2.digitaloceanspaces.com/whitepapers/DS-Protocolv1.0.pdf
>
>https://thetokenist.io/securitize-open-sources-core-protocol-launches-v3-0-of-its-digital-securities-platform/
>
>https://www.prnewswire.com/news-releases/securitize-announces-the-ds-protocol-to-help-unlock-the-potential-liquidity-of-security-tokens-300659963.html
>
>https://www.securitize.io
>
>ST-20
>
>https://blog.polymath.network/overview-of-the-st-20-interface-and-polymath-core-86bf64c8929?gi=7661496f8e11

 #

### PART A-3 Available Legal Tech and possible working topics for SALI LMSS and/or Computational Law and/or AALE design

### Content:

#### [A-3-1. Different types of legal records database for legal research](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-3-1-different-types-of-legal-records-database-for-legal-research-2)
#### [A-3-2. Array of "Legal Case Management Software"](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-3-2-array-of-legal-case-management-software-2)
#### [A-3-3 APIs vs Protocols and more on current major database solution vendors to the legal profession ecosystem](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-3-3-apis-vs-protocols-and-more-on-current-major-database-solution-vendors-to-the-legal-profession-ecosystem-2)
#### [A-3-4 Computational Law required features and takeaway for AALE design](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-3-4-computational-law-required-features-and-takeaway-for-aale-design-2)
#### [A-3-5 SQL structure-related collapsible interactive tree, chart-Database representation, etc](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-3-5-sql-structure-related-collapsible-interactive-tree-chart-database-representation-etc-2)
#### [A-3-6. Tech paradigms & information frameworks at play in legal process management](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-3-6-tech-paradigms--information-frameworks-at-play-in-legal-process-management-2)

#

#### A-3-1. Different types of legal records database for legal research

Today, most legal research done in law schools, courts, and the legal profession at large is conducted via computerized databases. Legal professionals depend primarily on services purchased from the two giants in the field, Westlaw and LexisNexis. This may need to evolve at some point as we go deeper into the era of AAS/AALE.
See Legal Databases: Comparative Analysis | CRL
https://www.crl.edu/collections/topics/legal-databases-comparative-analysis

#

#### A-3-2. Array of "Legal Case Management Software" 

An array of "Legal Case Management Software" is described e.g. there: https://www.g2.com/categories/legal-case-management

>_**Legal case management or matter management software**_ provides standard tools for lawyers to oversee their practice. Law firms utilize these tools as a database for past, ongoing, and future cases and clients. This can include document assembly for relevant case details, notes on the opposition when applicable, time tracking, and any other case-related information. Legal case management software often integrates with ediscovery tools to gather relevant case information, and integrates or comes packaged with legal billing software to track man-hours and process fees from clients.
>
>**To qualify for inclusion in the Legal Case Management category, a product must:**
>
>-_**Assist law firms with entering, storing, and finding case and client information**_
>
>-_**Provide time tracking or workflow tools to aid lawyers through the case lifecycle**_
 
It is often used in association with eDiscovery processes and more advanced billing & accouting systems.

_Whatever crops up from new Legal Tech to SALI LMSS to AALE systems might (or not) have to deal with **interoperability**._

#

#### A-3-3 APIs vs Protocols and more on current major database solution vendors to the legal profession ecosystem

To rebound on Dazza's suggestion:

>Maybe a little more education and many examples (with links to authoritative sources and clear documentation) _**for APIs and for Protocols**_ would be appropriate now.  

Also, a quick state of the art of current major database solution vendors to the legal profession ecosystem (Legal Tech - Law tech - Legal Engineering) might come handy just to roughly evaluate the share of SQL vs non-SQL and alternatives.

#

#### A-3-4 Computational Law required features and takeaway for AALE design

Let's keep patching what we can learn from what SALI LMSS does or doesn't do, as discussed above in [A-1-3. SALI LMSS legal structure and coding might be helpful to think of AALE legal objects & legal functions](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#a-1-3-sali-lmss-legal-structure-and-coding-might-be-helpful-to-think-of-aale-legal-objects--legal-functions-2) , for Computational Law required features and as takeaway for AALE design, including but not limited to noticed [interoperability](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#we-noticed-some-10-ten-interoperability-aspects-) aspects.

#

#### A-3-5 SQL structure-related collapsible interactive tree, chart-Database representation, etc

For tools to help represent collapsible interactive trees as e.g. used in an SQL context here, we found the following:

https://observablehq.com/@d3/collapsible-tree

https://gist.github.com/d3noob/8323795

https://www.rdocumentation.org/packages/collapsibleTree/versions/0.1.7

Diana mentioned Python-based chart-Database approaches that are worth investigating.

#

#### A-3-6. Tech paradigms & information frameworks at play in legal process management.

At this stage it becomes difficult to resist the temptation to refer to both paradigms of Schumpeterian creative destruction and Adam Smith's Invisible Hand role in consolidating individual self-interest for the sake of the common good. 

And in this space we try to stick to the simple, effective & usable, but still you can't help noticing a couple of things.

There are different tech paradigms and information frameworks at play in legal process management, both competing & cooperating among humans who "decide" vs humans "who do the grunt work" and seat lower in the corporate food chain.

To speculate or advocate, whether such hierarchical patterns of social and corporate food chain are slated to remain frozen, or to start to evolve, isn't the object of our conversations here. But it looks as if there is a mutually re-enforcing relationship, between tech paradigms and information frameworks at play in legal process management, and the social & hierarchical organization of the conservative (with all due respect, not a derogatory label in our meaning, quite the contrary) core of the legal professions, its agents of change, and the Future of Work & Business for the Lawyer-Client relationship.

There is no such thing as a one-size-fits-all, all-weather-solution. However, any evolutionary tech paradigm & framework decision has immediate operational implications, which means first and foremost _staffing_, delivering on budget and on schedule, reducing costs and increasing margins, while slashing already cannibalized and less lucrative areas of services.

Forming & leading great teams is a fine challenge: juniors _if you can attract & retain them_ well educated yet inexperienced in tortuous and humanly complicated legal processes ; or "re-skilled" old-dogs-new-tricks seniors (good luck with that).

Easier said than done in the corporate & government world in particular in the context of legal process management. 

But we live in a world where the mere fact of access to (Liberty and) Justice (for All) and being able to afford that, not only financially, but cognitively, socially, and institutionally, is far from being granted, even to us champions of Freedom.

We need not to lose sight of the fact that making systemic improvements serves, among other things, that particular cause.

For effective, performant, low-cost external providers, to offer services that _do more with less_ may compell legal profession players to adapt & evolve, or else, by "moving their cheese" away if they don't get on with the program asap now.

While a more encompassing, technologically advanced solution might sound desirable, or inevitable on the horizon, a solution that is a couple of tech-generations behind, _but does the job, in fact, more jobs with less_, may further & compound a long overdue restructuration process within the legal profession. Then the dam collapses: they won't stop a tide with a broom.  

Or, like some kind of Luchino Visconti paradigm (https://www.criterion.com/films/790-the-leopard or free "elsewhere"):

_"In the end,_ something _had to change, so that everything stays the same."_

#

_A cautionary business process management tech tale:_

>Not an analoguous case, but some usable lessons for this evolving legal tech services provision context.
>
>Once upon a time there was a very young BPM firm, just spun-off from the financial department of a large established corporation. That very young BPM firm had a really nice & progressive bleeding edge process of analytical accounting & corporate reporting with an internal monitoring system in natural language, that "told the story behind the numbers". 
>
>That very young BPM firm did record star achievements, like supporting a major automotive manufacturer reorganization in the early 2000's, and several other prestigious and well paying clients. But it was struggling for wider market adoption & capitalistic funding. 
>
>Eventually that very young BPM firm got acquired by a larger, innovative & advanced, yet somewhat more mainstream BPM firm. 
>
>Next, the resulting merged entity got in turn acquired, by a several orders of magnitude bigger firm, that did systems applications and products in data processing, marketing suites of very successful enterprise resource planning software. 
>
>That very big firm wasn't made of innovative geniuses & cool geeks, more like bland company men with suits and neckties, but it sat significantly higher on the corporate & capitalistic food chain.
>
>That very big firm wasn't particularly bleeding edge, in fact it was borderline "boring", but it was totally mainstream, and had the necessary war chest to impose itself in corporate & government users markets, and in capital markets. 
>
>Stakeholders did cash out handsomely at all successive stages of divestiture. Those who believed in surviving and thriving independently on the sole coattail of bleeding edge innovation, got a rude awakening ... 
>
>... but such is the nature of that business. 
>
>So, it's not just about the tech- at least for some players. 

#
#
#

## Part B - SALI Legal Matter Standard Update Presentation (June 2018)
#### https://salilegal.org/sali3/docs/SALI%20Matter%20Standard%20Updates%202018-06-21.pdf

#

_**The SALI Alliance is an independent organization of law firms, companies, solution providers, industry organizations
and academics focused on developing open, practical standards for the legal industry.**_

### SALI stakeholders represent all parts of the legal industry: 
- Legal services buyers (companies)
- Legal services providers (law firms and alternatives)
- Association and academics
- Technology and solution providers

### Goals for the matter profiling legal standard:
- **Open:** free and available to all stakeholders
- **Industry-driven:** managed by an independent non-profit industry organization
- **Hierarchical:** will have multiple layers of specificity and structure
- **Extensible:** defined way to extend codes to meet the proprietary needs of stakeholders
- **Practical:** will come with associated sample implementations of user interfaces,
and Application Programming Interfaces (APIs)

### The Legal Matter Specification (LMS) standard seeks to provide a common vocabulary across legal operations to improve our processes and efficiency

### LMS Mission: building “SKUs” for legal services ("SKU" = Stock Keeping Units)

#

_**WHY IS THIS SO HARD?**_

### TIME INVARIANCE
#### For a LMS to be practical, it needs to identify a matter in a constant manner as it evolves with minimal disruption to existing systems that are depending up on the data
#### The legal matter specification must be able to describe the matter through its lifecycle: as the legal matter progresses, we need to describe it in a way that does not invalidate the previous descriptions
#### Different uses of the data must identify matters consistently over time:
- ---> Marketing: What experience does your law firm/department have in providing these services?
- ------> Matter Staffing: Which time-keepers have the expertise we need?
- ---------> Pricing: What are the budgets and potential pricing options / costs for the requested services?
- ------------> Project Management: Is the matter appropriately staffed? Is the matter on budget?

#

_**WHY IS THIS SO HARD?**_

### VIEWER INVARIANCE
#### No matter which party is describing the matter, it should be coded consistently using **viewer-independent descriptors:**
- ---> DON'T: Client / Adverse Party 
- ------> DO: Plaintiff / Defendant 
- ---------> DO: Lessor / Lessee
- ------------> DO: Licensor / Licensee
#### Maintain constancy through viewer independent descriptors (GPS analogy: say turn West, don't say turn Left, etc.)

#

### What the LMS Standard is delivering?
1. A standard structure to describe a matter <-- **Structure** 
>_**Structure Browser: https://salilegal.org/sali3/structure2.php**_

2. A standard vocabulary to describe a matter <-- **Codes** 
>_**Code Browser: https://salilegal.org/sali3/browser.php**_

3. A standard set of tools to assist the above <-- **APIs**

### The LMS structure defines where information is stored

![SALI-LMSS interactive tree](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/Image-of-SALI-LMSS-Structure-Collapsible-Interactive-Tree.png)

### The LMS code sets define what are allowable values
- The SALI LMS Standard builds upon several international standards 
- The LMS Code browser shows allowable codes defining our common vocabulary 

### The LMS APIs are tools to help implement the standard

#### API /// Purpose

**Instance**

- Helps create conforming matters
- Validates matter structures
- Supports user-defined extensions
- Supports default values/templates

**Query** 

- Provide a protocol for requesting information and returning results

**UI/Synch**

- Supports applications in getting the latest version of the standard, new codes, etc.

#
#

## Part C - Draft Legal Matter Specification Standard (LMSS) 1.0, Rev 2 (June 2019)
### https://salilegal.org/sali3/docs/SALI%20LMSS%201.0%20rev2c.pdf?1566567194
### Version Revision 2c - Last Update: 2019-06-08 - SALI Matter Specification Committee - Adam L. Stock

#

#### © Copyright 2019 Standards Advancement for the Legal Industry Alliance - This work is licensed under a Creative Commons Attribution-NoDerivatives 4.0 International License

#
#

## [Table of Contents - Draft Legal Matter Specification Standard (LMSS) 1.0, Rev 2 (June 2019)](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#body-of-draft-legal-matter-specification-standard-lmss-10-rev-2-june-2019)
#
## [1 Overview](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#1-overview-1)  
### [1.1 What do we mean by a “legal matter”?](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#11-what-do-we-mean-by-a-legal-matter-1) 
### [1.2 What do we mean by the “legal matter lifecycle”?](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#12-what-do-we-mean-by-the-legal-matter-lifecycle-1)  
### [1.3 What are the components of the LMSS?](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#13-what-are-the-components-of-the-lmss-1)  
#
## [2 Design Principles](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#2-design-principles-1)  
### [2.1 Player/Viewer independence](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#21-playerviewer-independence-1)  
### [2.2 Successive refinement and additive coding](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#22-successive-refinement-and-additive-coding-1)   
### [2.3 Standards based](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#23-standards-based-1)  
### [2.4 Extensible](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#24-extensible-1)  
### [2.5 Agile approach](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#25-agile-approach-1)  
#
## [3 Legal Matter Specification (LMSS) Components](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#3-legal-matter-specification-lmss-components-1)  
### [3.1 LMSS Structure](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#31-lmss-structure-1)  
### [3.2 LMSS Allowed Values](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#32-lmss-allowed-values-1)  
#### [3.2.1 Enumerated Values](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#321-enumerated-values-1)  
#### [3.2.2 Text Values](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#322-text-values-1)  
#### [3.2.3 Numeric Values](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#323-numeric-values-1)  
### [3.3 Dependencies](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#33-dependencies-1)  
### [3.4 LMSS Encodings](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#34-lmss-encodings-1)  
### [3.5 Extensions to the LMSS Codes](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#35-extensions-to-the-lmss-codes-1)  
#### [3.5.1 Extension Example](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#351-extension-example-1)  
#
## [4 Structure of LMSS Document](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#4-structure-of-lmss-document-1)   
### [4.1 Overview](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#41-overview-1)  
### [4.2 Document](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#42-document-1)  
### [4.3 Document Header](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#43-document-header-1)  
#### [4.3.1 Title](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#431-title-1)  
#### [4.3.2 Version](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#432-version-1)  
#### [4.3.3 Type](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#433-type-1)  
#### [4.3.4 Language](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#434-language-1)  
#### [4.3.5 Charset](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#435-charset-1)  
#### [4.3.6 Extension Link](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#436-extension-link-1)  
### [4.4 Extension](https://github.com/Crhttps://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#443-parent-1yptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#44-extension-1)  
#### [4.4.1 Code Set](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#441-code-set-1)  
#### [4.4.2 Code](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#442-code-1)  
#### [4.4.3 Parent](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#443-parent-1)  
#### [4.4.4 Name](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#444-name-1)  
### [4.5 Declaration](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#45-declaration-1)  
#### [4.5.1 NameID](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#451-nameid-1)  
#### [4.5.2 Name](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#452-name-1)  
### [4.6 Matter](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#46-matter-1)   
#### [4.6.1 Title](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#461-title-1)  
#### [4.6.2 Locale](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#462-locale-1)  
### [4.7 Narrative](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#47-narrative-1)  
#### [4.7.1 Type](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#471-type-1)  
#### [4.7.2 Usage](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#472-usage-1)  
#### [4.7.3 Source](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#473-source-1)  
### [4.8 Description](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#48-description-1)  
#### [4.8.1 Text](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#481-text-1)  
#### [4.8.2 Format](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#482-format-1)  
#### [4.8.3 Language](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#483-language-1)  
### [4.9 Process](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#49-process-1)  
#### [4.9.1 Title](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#491-title-1)  
#### [4.9.2 Description](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#492-description-1)  
#### [4.9.3 Process Type](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#493-process-type-1)  
#### [4.9.4 Area of Law](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#494-area-of-law-1)  
### [4.10 Player](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#410-player-1) 
#### [4.10.1 Name](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#4101-name-1)  
#### [4.10.2 Player Role](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#4102-player-role-1)  
#### [4.10.3 Industry](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#4103-industry)
#### [4.10.4 Legal Entity](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#4104-legal-entity-1)  
#### [4.10.5 Governmental Authority](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#4105-governmental-authority-1)  
### [4.11 Counsel](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#411-counsel-1)  
#### [4.11.1 Name](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#4111-name-1)  
#### [4.11.2 Firm Name](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#4112-firm-name-1)  
#### [4.11.3 Representation Role](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#4113-representation-role-1)  
### [4.12 Process Object](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#412-process-object-1)  
### [4.13 Monetary Value](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#413-monetary-value-1) 
#
## [5 The Legal Matter Application Programming Interfaces (APIs)](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#5-the-legal-matter-application-programming-interfaces-apis-1)  
### [5.1 LMSS Instance](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#51-lmss-instance-1)  
### [5.2 LMSS Queries](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#52-lmss-queries-1)  
#### [5.2.1 LMSS Query WHERE Clauses](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#521-lmss-query-where-clauses-1)  
#### [5.2.2 LMSS Query SELECT Statements](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#522-lmss-query-select-statements-1)  
### [5.3 LMSS UI/Synch API](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#53-lmss-uisynch-api-1)  
#
## [6 Code Sets](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#6-code-sets-1)  
### [6.1 Code Set Types](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#61-code-set-types-1)  

#

# Body of Draft Legal Matter Specification Standard (LMSS) 1.0, Rev 2 (June 2019)

#

## 1 Overview

_**The SALI Legal Matter Specification Standard (LMSS) was developed by the Standards for the Advancement of the Legal Industry (SALI) Alliance to provide a standard way for parties to specify, describe and exchange information describing legal services at the matter level throughout a legal matter’s lifecycle.**_

_**The SALI LMSS is designed to function as a worldwide legal matter standard.**_

#

### 1.1 What do we mean by a “legal matter”?

For the purpose of the LMSS, _**a Legal Matter is considered to be any group of activities for the purposes of delivering a legal service to one or more parties.**_ The activities are either a major project with start and end point (e.g. litigation, acquisition of a business, a regulatory filing, etc.) or a grouping of micro projects (e.g. advice).

#

### 1.2 What do we mean by the “legal matter lifecycle”?

The _**legal matter lifecycle means the description of the matter from its conception as a request for services through its inception and execution through closing.**_ Because the LMSS must support a matter that will evolve through its lifecycle, it is designed to accommodate the evolution of the matter _**without jeopardizing the integrity of systems that are depending on data provided at an earlier stage of the matter.**_

#

### 1.3 What are the components of the LMSS?

The SALI LMSS has the following components:

- The legal matter specification includes: _**structure, allowed values, and dependencies**_ and supports both _**matter instances**_ (the description of specific matters), and _**matter templates**_ (the description of classes of matters).

- The legal matter application programming interfaces (APIs) include: the _**transport API for exchanging data**_ and the _**UX API for supporting the user interface of applications that use the standard.**_

#
#

## 2 Design Principles

_**The SALI LMSS was designed using the following principles:**_

#

### 2.1 Player/Viewer independence

The standard is designed to provide clear guidance and _**party-independent enumerated values**_ to ensure that matters are encoded the same way independent of the party involved in matter. As an example, the standard supports terms such as _**“plaintiff” and “defendant”**_ which have the same meaning no matter who is looking at the matter over terms like “client” and “opposing party” which change depending upon a player’s role in the matter.

#

### 2.2 Successive refinement and additive coding

Because the LMSS is intended to be used for legal matters, _**to describe legal matters that are being executed, the standard implements hierarchical and additive coding.**_

As an example, when a matter begins, _**the area of law for a matter may not yet be fully determined.**_

For example, we may know that it is a environmental matter, but not what specialty in environmental law. Such a matter would initially be encoded as environmental – ENVT. At a later point it may be determined that the matter is an air quality matter -- AIRQ. This would be encoded as "ENVT-AIRQ" The successive code is added to the previous code and is a further refinement of the previous code. 

_**This design ensure that other systems that depend upon the initial restructuring code continue to work.**_

Furthermore, each code in a code set _**is guaranteed to be unique, and each code is guaranteed to have a single parent code.**_ This means that if you simply use the code "AIRQ", the full coding path "ENVT-AIRQ" can be derived. 

In cases where the SALI standard has adopted codes from _**other standards that don’t adhere to this requirement, the "+" notation is used.**_

For example both US, California and El Salvador, Cardenas use the same ISO code "CA". To distinguish these, the code is prepended with the parent code followed by a "+". USA ("US"), California ("CA") is coded as "US+CA"; El Salvador ("SV"), Cardenas ("CA") is coded as "CV+CA".

#

### 2.3 Standards based

The LMSS is _**built on and incorporates existing international standards in addition to specifying new codes applicable to the legal services domain.**_ 

#

### 2.4 Extensible

Since the LMSS cannot anticipate all needs, there is a _**well-defined way to extend the standard while staying within the design and API functionality.**_ There is a methodology for providing including _**private structural components and private allowable values**_ that at some point may be submitted and considered for incorporation into future versions of the LMSS.

#

### 2.5 Agile approach

The LMSS is designed using an agile approach wherein the proposed standard drafts are _**revised and tested by a broad group of stakeholders representing law firms, clients and solution providers**_ to ensure that the standard is practical and appropriate to the specific needs and use cases being addressed.

The process is as follows is described in the table below:

|Name | Description | Comment |
|-----|-------------|---------|
|Draft LMSS 1.0 Rev. 1 | First draft revision 1 of the LMSS 1.0 specification | The first version always had the word "Draft" and "Rev. <#>" in its title.|
|Draft LMSS 1.0 Rev <n> | Nth draft revision 1 of the LMSS 1.0 specification | For each successive draft, the revision number is incremented.|
|LMMS 1.0 | Final version of the LMSS 1.0 standard | "Draft" and "Rev. <#>" are removed from the title once the standard is adopted by SALI Alliance members.|
|Draft LMSS 2.0 Rev 1 | First draft revision 1 of the LMSS 2.0 specification | Successive versions of the standard will increment LMSS number.|

#
#

## 3 Legal Matter Specification (LMSS) Components

The _**legal matter specification**_ includes the following components:

- **structure**,
- **allowed values**,
- **dependencies**, and,
- **extensions**.

In addition, the LMSS supports both:

- **matter instances** (the description of specific matters), and
- **matter templates** (the description of classes of matters).

#

### 3.1 LMSS Structure

The _**LMSS Structure**_ specifies where descriptive elements of matter are stored and how those elements relate to each other. 

The structure is comprised of components called _**“containers.”**_ Containers can be thought of as _tables in a relational database._ 

The structure defines _structure of each container – its **elements** –_ how containers _relate to each other_, which elements are _required and which are optional_, and whether the _**relationship**_ between containers are _one-to-one or one-to-many_.

The LMSS structure can be expressed as a _**database schema for storage or an XML or JSON structure for transmission of the matter information**_.

#

### 3.2 LMSS Allowed Values

The _**LMSS Allowed Values**_ specify the _**type of information**_ that may be stored in different elements of the containers. Allowed values fall into the following categories:

#

#### 3.2.1 Enumerated Values

_**Enumerated values are specifically defined values that are allowed at permitted as values of specific container elements.**_

The LMSS relies extensively on enumerated values to ensure that _**common definitions across systems and languages are incorporated.**_

Some standards are officially incorporated in the standard such as ISO-4217, which provides standard codes standard names codes for currencies. Enumerated values components are summarized in the table below

_**Enumerated value components**_

| Type | Characters | Explanation |
|------|------------|-------------|
| **Code Set** | Text(40) | The name of the code set |
| **Code** | Up to 16 | A code for the value. |
| **Parent Code** | Text(250) | The code of the parent in a hierarchical coding system. This is null for top level codes.|
| **Short Name** | Up to 40 | The name of the value intended for use in user interfaces and other applications with limited space.|
| **Name** | Up to 100 | The full name of the value.|
| **Description** | Up to 4000 | A description of the value.|
| **Tags** | Up to 10 | Synonyms or common usage. Tags are used to enhance search.|
| **URL** | Text(250) | Optional URL used as a reference.|

>- Codes are alphanumeric characters excluding the ‘-‘ character. They are _**case insensitive**_. Codes are typically stored in Text(250) fields because codes may be additive. Separate code may be appended to each other using the “-“ character as a separator. The 16 character limit does not include extension prefixes.
>
>- Codes are of the form: (@[A-Z0-9]+:)?([A-Z0-9.]+ | [A-Z0-9.]+[+][A-Z0-9.]+)
>
>- '+' has a special meaning _**to support non-conforming code sets**_.

_**Enumerated value codes**_ are combined by adding a "-" (dash character) and _**the next most specific code as a suffix.**_

Examples:

| Code | Concatenated Code | Short Name |
|------|-------------------|------------|
| NAM | NAM | North America |
| US | NA-US | United States |
| US+CA | NA-US-US+CA | California |

#### 3.2.2 Text Values

_**Text values are unstructured natural language descriptions**_ intended to be _**human readable and informative**_. 

Text values are also used to _**store information not yet specified by the standard**_. Text values are intended to be _**searchable, and subject to standard text operations**_.

#### 3.2.3 Numeric Values

_**Numeric values store scalar numeric information**_. 

Numeric values are subject to _**common mathematical operations**_. 

Numeric values can be _**floating point, whole number and boolean**_.

#

### 3.3 Dependencies

_**Dependencies restrict which structural components and which allowed values may appear in a valid matter instance based on other values in the matter**_. 

As an example, if a process is of type “transaction,” the players in that transaction may not be of the type “plaintiff” or “defendant.” These values are restricted to process of type “dispute.”

> Remark: _**Dependencies are not part of Draft LMSS 1.0 Rev 2.**_

#

### 3.4 LMSS Encodings

_**The LMSS can be encoded machine readable formats. JSON is the baseline supported format.**_

Machine Readable JSON

```

{
    "document" : {
        "header" : {
            "lmss version" : "1.02" //Draft LMSS 1.0 Rev 2
            ,"lmss type" : "INST" //Instance
            ,"language" : "en-us"
            ,"charset" : "UTF-8"
        }
        ,"matter" : {
            "title" : "Wage and hour class action against XYZ Corp."
            ,"locale" : "NAM-US-US+NY" //New York
            ,"process" : {
                "title" : "Wage and hour class action against XYZ Corp."
                ,"process type" : "D-CCI" //Court Proceeding, Civil
                ,"area of law" : "LEMP-WGHR" //Wage and Hour Law
                ,"player" : [{
                    "name" : "Jane Smith and co-workers"
                    ,"player role" : "PLTF" //Plaintiff
                    ,"legal entity" : "GROUP-CLASS" //Class of Plaintiffs
                }
                ,{
                    "name" : "XYZ Corporation, Inc."
                    ,"player role" : "DEFT" //Defendant
                    ,"legal entity" : "ENTITY-CORP" //Corporation
                    ,"industry" : "TEC" //Technology
                }]
            }
        }
    }
}

```

#

### 3.5 Extensions to the LMSS Codes

The LMSS is intended to be _**adaptable to the needs of customers.**_ 

It is our intent that _later versions of the standard will incorporate extensions that have been developed._

_**The LMSS has a well-defined way to extend enumerated codes.**_

Codes are extended by:

- Defining an _**extension prefix**_ of the format "@<alphanumeric(6)>". This prefix followed by a colon (":") will be used as a prefix to any extended codes.

- Creating an _**extension code table**_ that conforms to the specification in section 3.2.1.

- Embedding the _**extension table or a reference to it in the header**_.

#

#### 3.5.1 Extension Example

Law firm AM would like to extend the SALI industry codes to include subcategories of real estate. In this example the "Real Estate" industry type with code "RES" will be extended by adding subtypes of real estate below it.

The prefix code chosen is "@am". This prefix is chosen arbitrarily, but in planned versions of the API, extension keys and prefix may be registered and stored to facilitate data exchange.

The extension table would have the following data.

|Code | Set Code | Parent Code | Full Code Name |
|-----|----------|-------------|----------------|
| SALI Industries | MULFAM | RES | RES-@am:MULFAM | Multi-Family Residential |
| SALI Industries | OFFICE | RES | RES-@am:OFFICE | Office |
| SALI Industries | INDUST | RES | RES-@am:INDUST | Industrial |
| SALI Industries | RESIDL | RES | RES-@am:RESIDL | Residential |
| SALI Industries | MIXUSE | RES | RES-@am:MIXUSE | Mixed-Use |
| SALI Industries | RETAIL | RES | RES-@am:RETAIL | Retail | 
| SALI Industries | DATCTR | RES | RES-@am:DATCTR | Data Center |

_**The following show and example of how the code would appear in an LMSS Structure:**_

```

"player": [{
        "name": "ZZZ Corporation, Inc",
        "legal-entity": "ENTITY-CORP",
        "industry": "RES-@AM:OFFICE" //Real Estate - Office
        }]
 
 ```

#
#

## 4 Structure of LMSS Document

#

### 4.1 Overview

The LMSS document is comprised of _**a Header and one or more Matters**_. 

The _**Header and the Matter(s) are containers**_.

Each container has elements that may be of type _**Text, Numeric, Enumeration or Container.**_

_**Enumerations**_ are stored in Text(250) fields to accommodate multiple levels of specificity that are represented as _**concatenated codes**_.

_**Containers are pointers**_ to other structures.

_**A well-formed Document is a structure that includes all required fields.**_

(Note that the concept of a _**well-formed document applies to instance but not templates or queries**_.) 

In the tables below, 

- “REQ” indicates whether the _**element is required**_ (in an LMSS instance but not a query), 
- “MULT” indicates whether _**multiple values are permitted**_. 

A well-formed document _**is required in the interchange of instances of matters between systems**_. 

A well-formed document _**is not required when the LMSS is used in a query**_. 

In those instances, a missing field matches all instances. See LMSS Queries below.

#

### 4.2 Document

The _**Document container is the top-level container in the LMSS instance**_. 

The Document must have _**a Header and one or more Matters**_.

Document container elements:

| ELEMENT | REQ | MULT. | TYPE | COMMENTS |
|---------|-----|-------|------|----------|
| Header | Y | N | Container | The header information for the document. |
| Matter | Y | Y | Container | The matters included in the document. |

#

### 4.3 Document Header

The LMSS document _**Header describes the version, type, default language and character set needed to correctly read the LMSS document**_.

|ELEMENT | REQ | MULT. | TYPE | COMMENTS |
|--------|-----|-------|------|----------|
|Title | N | N | Text(250) | An optional title for the document. |
| Version | Y | N | Float | The version of the LMSS standard being encoded. |
| Type | Y | N | Enumeration: SALI LMSS Type | The type of the document. Supported types include "Instance", "Template", and "Query". The default value is "Instance". |
| Language | N | N | Enumeration: IETF BCP 47 | Languages follow the Internet Engineering Task Force recommendation in BCP 47. |
| Charset | N | N | Text | Default value is UTF-8. |
| Extension Link | N | Y | Text: URI | A link to an extension file. |
| Extension | N | Y | Container | One or more extension definitions. |
| Declaration | N | Y | Container | Declarations are indexes of names that need to be cross referenced in a specification. NameIDs can be used in place of names wherever names may appear. |

#

#### 4.3.1 Title

An _**optional title**_ for the document.

#### 4.3.2 Version

The LMSS version is defined and maintained by SALI. Published version of the standard may be found at _**Sali.org**_.

#### 4.3.3 Type

Type refers to the _**type of the Document. Permissible values include**_:

- **Instance** – An instance encodes a specific matter. Instances have required containers and elements to be well formed.
- **Template** – A template encodes default settings of an instance. Parts of templates that are not specified are assumed to accept all values. Templates must adhere to the LMSS container structure, however required elements are relaxed.
- **Query** – A query encodes a database query _**following a SQL-like structure**_. Queries have select, where, order by and limit structures.

#### 4.3.4 Language

Language declares the default language of the LMSS structure. 

Languages follow the _**Internet Engineering Task Force recommendation in BCP 47**_.

#### 4.3.5 Charset

The charset describes the encoding of the characters in the LMSS document. _**The default encoding is UTF-8**_.

#### 4.3.6 Extension Link

A _**link to an extension file**_ that conforms to the _**LMSS Extension file format**_.

#

### 4.4 Extension

An _**extension container**_ is an _**in-document definition of an extension**_. 

A document may _**include an array of these in the header**_.

The scope applies to the document.

| ELEMENT | REQ. | MULT. | TYPE | COMMENTS |
|---------|------|-------|------|----------|
| Code Set | Y | N | Text(40) | The code of the code set being extended. |
| Code | Y | N | Text(40) | The extension code. | Must be unique in the namespace. |
| Parent | Y | N | Text(40) | The parent code. | This code must be defined before this definition. |
| Name | Y | N | Text(250) | The short name of the extended code. |

A sample in-document extension is shown below:

```

{
    "document" : {
        "header" : {
            "lmss version" : "1.02" //Draft LMSS 1.0 Rev 2
            ,"lmss type" : "INST" //Instance
            ,"language" : "en-us"
            ,"charset" : "UTF-8"
            ,"extension" : [{
                "code set" : "SALI-IND"
                ,"code" : "@MULFAM"
                ,"parent" : "RES"
                ,"name" : "Multi-Family Residential"
            }
            ,{
                "code set" : "SALI-IND"
                ,"code" : "@OFFICE"
                ,"parent" : "RES"
                ,"name" : "Office"
            }
            ,{
                "code set" : "SALI-IND"
                ,"code" : "@INDUST"
                ,"parent" : "RES"
                ,"name" : "Industrial"
            }
            ,{
                "code set" : "SALI-IND"
                ,"code" : "@RESIDL"
                ,"parent" : "RES"
                ,"name" : "Residential"
            }]
        }
    }
}

```
#

#### 4.4.1 Code Set

The _**LMSS Code of the code set**_. (See 6.1)

#### 4.4.2 Code

The _**code assigned to the extension**_. The code will have _**a "@" prepended to it**_ when used.

#### 4.4.3 Parent

The _**parent code**_. The parent code must be an _**existing standard code**_ in the code set, or a _**previously defined extension**_. Examples include "RES" or "@OFFICE".

#### 4.4.4 Name

The _**short name of extension code**_.

#

### 4.5 Declaration

A _**declaration**_ may be used to _**assign and index to an item to ensure accurate cross referencing**_. 

Declarations are typically used for _**legal entities**_ but can be used _**in place of a Name**_ (See 4.10.1, 4.11.1 and 4.11.2).

A _**legal person or entity is any human or non-human entity**_, in other words, any _**human being, firm, or government agency**_ that is recognized as having _**privileges and obligations**_, such as having _**the ability to enter into contracts, to sue, and to be sued**_.

_**Entities**_ are used to maintain _**referential integrity across LMSS structure**_. 

For example, if the matter includes _**two processes that refer to the same legal entity**_ as in the example, "Review and negotiate project labor agreement for Jane Smith." 

The matter may be encoded to have two processes – one for review and another of negotiation. But the review and negotiation concern the same legal entity. An entity declaration should be used in this instance and the entity NameID should be used in each process to ensure that it is understood that the objects of both process are the same.

| ELEMENT | REQ. | MULT. | TYPE | COMMENTS |
|---------|------|-------|------|----------|
| NameID | Y | N | Text(40) | The NameID of the entity. | Must be of the regular expression form \^[A-Za-z0-9_-]{1,39} |
| Name | Y | N | Text(250) | Name to be inserted wherever the NameID appears. |

#

#### 4.5.1 NameID

The _**ID to be used in place of a name**_. NameIDs must begin with a caret symbol. (e.g. ^102 or ^EntityXYZ).

#### 4.5.2 Name

The _**name to be used in place of the NameID**_.

#

### 4.6 Matter

The _**Matter container encapsulates the information for a matter**_. 

There may be _**more than one matter per document**_. 

The matter must have a _**title, a human readable description, a locale and one or more processes**_. 

The _**locale may restrict the types of the processes**_. F

or example, certain bankruptcy processes are limited to the US because those processes a defined by US Bankruptcy law.

Matter container elements:

|ELEMENT | REQ | MULT. | TYPE | COMMENTS |
|--------|-----|-------|------|----------|
| Title | Y | N | Text(250) | The title of the matter. |
| Locale | Y | N | Enumeration: ISO 3166-2 | The location of the matter. |
| Process | Y | Y | Container | The process or processes for this matter. |
| Narrative | Y | N | Container | The description of the matter. |

#

#### 4.6.1 Title

A _**required title for the process**_.

#### 4.6.2 Locale

A _**required locale for the matter**_. The _**locale is an enumeration**_.

#

### 4.7 Narrative

A _**narrative**_ holds a _**group of related matter descriptions**_. 

It includes a _**required type**_ which is an _**enumerated list**_, an _**optional usage tag**_, and _**an optional source**_. 

Each _**narrative can have a specified usage**_ so _**a Matter can have multiple narratives based on the audience**_. 

Each _**narrative is intended to capture a logically unique interpretation of the matter**_. 

_**Formatting**_ and _**language variants**_ are accommodated in the _**description container**_.

Narrative container elements:

| ELEMENT | REQ. | MULT. | TYPE | COMMENTS |
|---------|------|-------|------|----------|
|Type | Y | N | Enumeration: SALI Narrative Type | The type of the narrative. |
| Usage | N | N | Text(250) | Descriptions of the intended audience or other usage of the narrative. |
| Description | Y | Y | Container | One or more descriptions of a narrative. |
| Source | N | Y | Text(250) | The source of the narrative. |

#

#### 4.7.1 Type

The _**narrative type**_ is an _**enumerated list**_ intended to _**capture the sensitivity of the narrative**_. 

Values include: _**public, confidential, private, generic, etc**_.

#### 4.7.2 Usage

_**Usage**_ is an _**optional human readable field**_ that should capture the _**audience or usage of the narrative**_. 

Examples for the same matter might be: 

- "Narrative written for pitches to lenders",
- "Narrative written for pitches to borrowers"
- "Narrative written for generic finance pitches"

#### 4.7.3 Source

The _**source_** is an _**optional element**_ that describe the _**source of the narrative**_. 

You may provide _**multiple sources**_. 

Examples include: "2015 litigation department compensation memo," and "2017 environmental practice Chambers submission."

#

### 4.8 Description

The _**description in a container**_ encapsulates the _**specific text of a specific narrative**_. 

The description has _**text, a format and a language**_. 

If the _**language is not specified, it is inherited from the matter**_. 

For example, if a firm keeps French and English versions of the same narrative, or plain text and HTML formatted versions of the same narrative, these would be accommodated in the description container.

| ELEMENT | REQ. | MULT. | TYPE | COMMENTS |
|---------|------|-------|------|----------|
| Text | Y | N | Text(4000) | The description of the matter. |
| Format | Y | N | Enumeration of Narrative Formats | Text or HTML |
| Language | N | N | Enumeration: IETF BCP 47 | The language of the description. If omitted, it is assumed to be the same as that of the matter. |

#

#### 4.8.1 Text

The _**text holds the characters of the description**_. 

The _**format of the text is interpreted based on the description type**_.

#### 4.8.2 Format

_**Two formats are supported: Text and HTML.**_

#### 4.8.3 Language

_**Language is optionally specified by using BCP 47.**_

#

### 4.9 Process

The _**Process container**_ describes the _**process, service or product being delivered**_.

Every _**process**_ must have _**a single process type**_. 

Top-level _**process types**_ are _**transactions, disputes, regulatory proceedings, bankruptcy/restructurings, and advisory**_.

If we think of the process as a sentence, _**the process type reprints the “verb.”**_ 

They describe _**the action that is being taken.**_

The _**players are the legal entities involved in the process.**_ 

These should be thought of the subject (Joe Smith) and object (Company X) in the sentence “Joe Smith sued Company X for $500,000 for breach of contract.”

The _**process predicate**_ contains the _**predecessors or outcomes of the process.**_ 

In the sentence above, “for $500,000” and “for breach of contract.”

The _**Area of Law provides context to the process.**_ 

The _**Area of Law**_ should be thought of the _**primary subject of law for the process.**_ 

Think the class that’s the attorney was in when she learned about the applicable law. 

The area of law is provided primarily for _**context**_ as in the examples, “He prosecuted the defendant” and “She prosecuted the patent.” The first is criminal law, the second is intellectual property law.

Process container elements:

|ELEMENT | REQ. | MULT. | TYPE | COMMENTS |
|--------|------|-------|------|----------|
| Title | N | N | Text(100) | The title of the process. |
| Description | N | N | Text(4000) | An optional description of the process. |
| Process Type | Y | N | Enumeration: SALI Process Type | The type of the process. The process should be thought of a verb. |
| Area of Law | Y | Y | Enumeration: SALI Area of Law | The primary area of law for the process. Area of Law provides context for interpreting other elements of the process. |
| Player | Y | Y | Container | The players involved in a process.
| Process Object | N | Y | Container | The process object hold information specific to each kind of process. See the discussion below. |

#

#### 4.9.1 Title

The _**optional title of the process**_. 

Examples include: "LLC formation in California", and "License of technology to French company.".

#### 4.9.2 Description

An _**optional field**_ to _**store additional information about the process.**_

#### 4.9.3 Process Type

A _**SALI enumerated value.**_ 

Top-level process types are _**transactions, disputes, regulatory proceedings, bankruptcy/restructurings, and advisory. 

If we think of the process as a sentence, the process type reprints the “verb.” They describe the action that is being taken.

#### 4.9.4 Area of Law

The _**Area of Law is a SALI enumerated value that provides context to the process.**_ 

The Area of Law should be thought of the _**primary subject of law for the process.**_ 

Think the class that’s the attorney was in when she learned about the applicable law. 

The area of law is provided primarily for _**context**_ as in the examples, “He prosecuted the defendant” and “She prosecuted the patent.” The first is criminal law, the second is intellectual property law. 

There can be _**multiple areas of law.**_

#

### 4.10 Player

The _**players are the subject of the sentence and sometimes the object.**_ 

_**Primary players are the primary parties involved in a legal process.**_ 

The Player container has the following fields:

Player container elements:

| ELEMENT | REQ. | MULT. | TYPE | COMMENTS |
|---------|------|-------|------|----------|
| Name | Y* | N | Text(250) | The name of the player. This is usually a company name or individual name. May use a Name or a declared ID. |
| Player Role | N | Y | Enumeration: SALI Player Role | The contextual role that the player has in the process. (e.g. Plaintiff, Licensee, etc.) |
| Industry | N | N | Enumeration: SALI Industry | The industry that the player is in. This often provides context for how the process is executed. |
| Legal Entity | Y | N | Enumeration: SALI Legal Entity | The type of legal entity that the player is. A corporation, a partnership, a person, etc. |
| Governmental Authority | N | N | Enumeration: SALI Governmental Authority | Used when the player is a governmental authority. |
| Counsel | N | Y | Container | The legal representatives of the player. |

*Either a Name or a NameID is required.

#

#### 4.10.1 Name

The _**name is the name of player in human readable form._** If a NameID is used, a Name is not required.

#### 4.10.2 Player Role

The _**Player Role is an optional element that provides context.**_ 

Examples of roles are _**Plaintiff, Defendant, Acquiror, etc.**_

_**The Roles span both legal roles and functional roles.**_ 

_**Player Role is an enumerated value.**_

#### 4.10.3 Industry

The industry is _**an optional field that describes the industry of the player.**_ 

_**Industry is an enumerated value.**_

#### 4.10.4 Legal Entity

_**Legal entity describes the type of the player.**_ 

In Law, _**a "legal person" or "legal entity" is any human or non-human entity,**_ in other words, _**any human being, firm, or government agency that is recognized as having privileges and obligations,**_ such as having _**the ability to enter into contracts, to sue, and to be sued.**_ 

_**Legal Entity is an enumerated value.**_

#### 4.10.5 Governmental Authority

_**The enumerated identification of the governmental authority if the player is a governmental authority.**_

#

### 4.11 Counsel

_**The counsel container includes all of the legal representatives of the player.**_ 

The fields of the counsel container are described below:

Counsel container elements:

| ELEMENT | REQ. | MULT. | TYPE | COMMENTS |
|---------|------|-------|------|----------|
| Name | Y* | N | Text(250) | The name of the legal representative. May use a Name or a declared ID. |
| Firm Name | N* | N | Text(250) | The firms of the legal representative. May use a Name or a declared ID. |
| Representation Role | Y | N | Enumeration The role of the legal representative. |

*Either a Name or a NameID is required.

#

#### 4.11.1 Name

The _**name is the name of counsel in human readable form.**_ 

If a NameID is used, a Name is not required. (NameIDs are indicated by prefixing them with a caret "^" symbol. e.g. "^103".)

#### 4.11.2 Firm Name

The _**firm name is the name of firm that the counsel is part of in human readable form.**_

If a NameID is used, a Firm Name is not required.

#### 4.11.3 Representation Role

The _**role of the legal representative.**_ 

_**Role is an enumerated value.**_

#

### 4.12 Process Object

The _**process object encapsulates important elements of the process.**_

A _**process can have multiple process object.**_ 

The process object can simply be a _**summary of key attributes of the overall process.**_ 

Additional process objects can be attached to describe _**the preconditions and post conditions of a process.**_

For example, for a merger, there optionally can be individual process objects describing the predecessor entities and resulting entity.

| ELEMENT | REQ. | MULT. | TYPE | COMMENTS |
|---------|------|-------|------|----------|
| Description | N | N | Text(4000) | The description of the Process Object. |
| Status | N | N | Enumeration | An enumerated status: Open, closed, Canceled. |
| Cross-Border | N | N | Boolean | Is the process cross border? |
| Filing Date | N | N | Date | The filing date, if appropriate. |
| Term Sheet Date | N | N | Date | The term sheet date, if appropriate. |
| Effective Date | N | N | Date | The effective date of the process. |
| Closing Date | N | N | Date | Closing date, if appropriate. |
| Announce Date | N | N | Date | The date process was announced, if appropriate. |
| Asset Location | N | N | Text(4000) | Location of the transaction - esp. for real property. |
| Asset Description | N | N | Text(4000) | Description of the asset such as asset type, asset size, etc. |
| Monetary Value | N | N | Container | The monetary value of the transaction, dispute or object. |
| Non-Monetary Value | N | N | Text(400) | The non-monetary value of the transaction, dispute or object. |
| Transaction: Consideration | N | Y | Text(4000) | Description of the consideration for the deal - Stock, Cash, Real Estate, etc. |
| Transaction: Deal Type | N | Y | Text(4000) | Type of deal. |
| Transaction: Location | N | Y | Text(4000) |mLocation of the transaction. |
| Transaction: Legal Entity | N | Y | Enumerated Value: Legal Entity | If a formation or dissolution, the kind of legal entity formed or destroyed. |
| Regulatory: Authority | N | Y | Enumerated Value: Governmental Authority Regulator. | A public authority or government agency responsible for exercising autonomous authority over some area of human activity in a regulatory or supervisory capacity. |
| Regulatory: Authority Other | N | Y | Text(250) | Regulatory authority not included in the enumeration values |
| Dispute: Venue | N | Y | Enumerated Value: Court | The venue of the dispute. |
| Dispute: Venue Other | N | Y | Text(250) | Dispute venue not fully covered by the enumerated values. |
| Dispute: Trial Type | N | N | Enumerated Value: Trial Type | The type of the trial. |
| Dispute: Case Name | N | N | Text(250) | Name of the case. |
| Dispute: Resolution | N | N | Text(250) | Enumeration TBD. |
| Dispute: Resolution Date | N | N | Date | Date of the dispute resolution. |
| Dispute: Duration (Months) | N | N | Integer | Duration of the dispute in months. |
| Dispute: MultiJurisdictional | N | N | Boolean | Set if the dispute is multijurisdictional. |
| Dispute: Number of Depositions | N | N | Integer | Number of depositions. |
| Dispute: Number of Experts | N | N | Integer | Number of experts. |

See the table above for descriptions.

#

### 4.13 Monetary Value

_**Monetary Value encapsulates a financial value attribute._**

It consists of a _**floating point number and a currency code.**_

Monetary value container elements:

| ELEMENT | REQ. | MULT. | TYPE | COMMENTS |
|---------|------|-------|------|----------|
| Currency | Y | N | Enumeration: Currency | A currency code a defined by ISO 4217. |
| Value | Y | N | Float | A floating point number that represents the value. |

#
#

## 5 The Legal Matter Application Programming Interfaces (APIs)

_**LMSS APIs are not supported in Draft LMSS 1.0 Rev 2.**_

The LMSS supports several types of APIs:

- **LMSS Instance**
- **LMSS Queries**
- **LMSS UI/Synch API**

#

### 5.1 LMSS Instance

The _**Instance API is used to create, import and export matters._ 

It also supports _**default values and user-defined extensions.**_

- Helps create conforming matters
- Validates matter structures
- Supports user-defined extensions
- Supports default values/templates

#

### 5.2 LMSS Queries

An important part of the LMSS is to support _**the querying of data stores against different criteria.**_ 

The standard leverages the LMSS definition — _structure, enumerated values, text and numeric values_ — to _**specify search criteria.**_ 

In these instances sparse version of the LMSS are applied to develop search criteria.

#

#### 5.2.1 LMSS Query WHERE Clauses

In the _**standard SQL queries clauses SELECT, WHERE, and ORDER BY,**_ the LMSS template can be used to define the WHERE clauses.

For enumerated values that are filled in, the search uses the _**“starts with” criteria**_ for specifying a search. For _**text and numeric fields,**_ you can apply _**standard SQL wildcard matching.**_

Below are several examples of how this applied, using LMSS Templates in Queries:

QUERY STRUCTURE 

- Select all matters WHERE lease transactions are in New York State:

```

{
    "document" : {
        "header" : {
            "lmss version" : "1.02" //Draft LMSS 1.0 Rev 2
            ,"lmss type" : "QRY" //Query
            ,"language" : "en-us"
            ,"charset" : "UTF-8"
        }
        ,"matter" : {
            "locale" : "NAM-US-US+NY" //New York
            ,"process" : {
                "process type" : "T-LEA" //Lease
            }
        }
    }
}

```

- Select all matters WHERE McEvoy & Edwards represented the buyer in real estate transactions

```

{
    "document" : {
        "header" : {
            "lmss version" : "1.02" //Draft LMSS 1.0 Rev 2
            ,"lmss type" : "QRY" //Query
            ,"language" : "en-us"
            ,"charset" : "UTF-8"
        }
        ,"matter" : {
            "process" : {
                "process type" : "T" //Transaction
                ,"area of law" : "REAL" //Real Property Law
                ,"player" : {
                    "player role" : "BUYR" //Buyer
                    ,"counsel" : {
                        "firm name" : "McEvoy & Edwards%"
                        ,"representation role" : "COUN" //Counsel/Attorney
                    }
                }
            }
        }
    }
}

```

- Select all civil court matters where Wells Fargo was the defendant in an employment class action.

```

{
    "document" : {
        "header" : {
            "lmss version" : "1.02" //Draft LMSS 1.0 Rev 2
            ,"lmss type" : "QRY" //Query
            ,"language" : "en-us"
            ,"charset" : "UTF-8"
        }
        ,"matter" : {
            "process" : {
                "area of law" : "LEMP" //Labor and Employment Law
                ,"player" : [{
                    "name" : "Wells Fargo%"
                    ,"player role" : "DEFT" //Defendant
                }
                ,{
                    "player role" : "PLTF" //Plaintiff
                    ,"legal entity" : "GROUP-CLASS" //Class of Plaintiffs
                }]
            }
        }
    }
}

```

- Select all matters where there is an enforcement action involving the U.S. National Labor Relations Board

```

{
    "document" : {
        "header" : {
            "lmss version" : "1.02" //Draft LMSS 1.0 Rev 2
            ,"lmss type" : "QRY" //Query
            ,"language" : "en-us"
            ,"charset" : "UTF-8"
        }
        ,"matter" : {
            "process" : {
                "process type" : "R-ENF" //Enforcement
                ,"process object" : {
                    "regulatory: authority" : "US-FD-NLRB" //National Labor Relations Board
                }
            }
        }
    }
}

```

#### 5.2.2 LMSS Query SELECT Statements

We anticipate the following select specifications as part of the API.

>Remark: _**Not implemented in Draft LMSS 1.0 Rev 2**_

| SELECT TYPE | RETURN TYPES | COMMENTS |
|-------------|--------------|----------| 
| Aggregate values | Returns single values for aggregate functions such as: COUNT, COUNT DISTINCT AVERAGE, SUM |   |
| Scalar values | Return lists of named values |   |
| Partial Structures | Return lists of structures with descriptions and narratives stripped out |   |
| Full Structures | Full lists of full structures |   |
| Comparison Operators | >, >=, <, <=, <>, LIKE, NOT, IN | Need to support wildcard characters. |

#

### 5.3 LMSS UI/Synch API

>Remark: _**Not implemented in Draft LMSS 1.0 Rev 2**_


The LMSS has an API designed to help application providers drive keep the applications updated with the most current versions of the standard. The API supports returning structures code information.

| REQUEST | RETURN TYPES | COMMENTS |
|---------|--------------|----------|
| List Supported Enumerations | Returns list of enumerations. |   |
| Get Enumeration List | Returns key value pairs of a given enumeration to drive dropdown and autocomplete user interface elements. Supports simple filtering by level, by "contains" and by "starts with". |   |

#

## 6 Code Sets

#

### 6.1 Code Set Types

The following code sets are used by Draft LMSS 1.0 Rev 2.:

| Code Set | Code | Description | View |
|----------|------|-------------|------|
| SALI Areas of Law | SALI-AOL:2 | SALI Area of Law/Practice. | View |
| SALI Court | SALI-COURT | Codes for courts. Currently limited to U.S. courts. | View |
| SALI Currency (ISO 4217) | ISO-4217 | List of world currencies. | View |
| SALI Format | SALI-FMT | The format of a description. | View |
| SALI Governmental Body | SALI-GOVT | Government codes. Currently U.S. federal only. | View |
| SALI Industry | SALI-IND | A default set of codes provided to define industries. Industry codes are not officially part of the SALI Legal Matter standard. | View |
| SALI Legal Entity | SALI-LEGENT:2 | Specifies the kind of legal entity of a party to a legal matter. | View |
| SALI LMSS Type | SALI-LMST | The types of LMSS documents. | View |
| SALI Location | SALI-ISO31662 | World locations to the state/province level. | View |
| SALI Matter Narrative | SALI-MATNAR | Codes used to identify the type of narrative. | View |
| SALI Player Role | SALI-PROLE | The types of player roles that can be applied to a matter. | View |
| SALI Process | SALI-PROC | Codes used to define a legal service process. | View |
| SALI Process Status | SALI-PROCSTAT | Codes for the status of a process. | View |
| SALI Representation Role | SALI-RROLE | The types of representation roles for a player. | View |
| SALI Trial Type | SALI-TRITYP | The type of trial format | View |

# 
#
#

## Part D - Fully expanded SALI LMSS tree structure and detailed parameters of SALI LMSS structure and code browsers.

#

### SALI-LMSS Structure Collapsible interactive tree (static pic fully expanded):

### Reference tree: https://salilegal.org/sali3/stree.php

![SALI-LMSS Structure tree](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/Image-of-SALI-LMSS-Structure-Collapsible-Interactive-Tree.png)

#

### Structure Browser: https://salilegal.org/sali3/structure2.php

We use code syntax framing to show the parallelism with SALI LMSS coding samples and practice.

```

Header
    LMSS Type
    LMSS Version
    Title?
    Language?
    Charset?
    Extension Link*

        Extension*
            Code Set
            Code
            Parent
            Name

        Declaration*
            NameID
            Name

Matter+
    Title
    Locale

        Process+
            Title?
            Description?
            Process Type
            Area of Law+

            Player+
                Name
                Player Role+
                Legal Entity?

                Counsel*
                    Name?
                    Firm Name?
                    Representation Role?
                Industry?
                Governmental Authority?

        Process Object*
            Description?
            Status?
            Cross-Border?
            Filing Date?
            Term Sheet Date?
            Effective Date?
            Closing Date?
            Announce Date?
            Asset Location*
            Asset Description?

            Monetary Value?
                Value
                Currency
            Non-Monetary Value?
            Transaction: Consideration?
            Transaction: Location*
            Transaction: Deal Type?
            Transaction Legal Entity*
            Regulatory: Authority*
            Regulatory: Authority Other*
            Dispute: Venue*
            Dispute: Venue Other*
            Dispute: Trial Type?
            Dispute: Case Name?
            Dispute: Resolution?
            Dispute: Resolution Date?
            Dispute: Duration (Months)?
            Dispute: Multi-Jurisdictional?
            Dispute: Number of Depositions?
            Dispute: Number of Experts?


        Narrative*
            Type
            Usage?

            Description+
                Text
                Format
                Language?
            Source*

```

#

### Code Browser: https://salilegal.org/sali3/browser.php

This described a selected sample of SALI LMSS Value encoding, starting from the code browser Value Menu:

#### Code Browser Value Menu:
![SALI-LMSS-Code-Browser-Value-Menu](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/Image-of-SALI-LMSS-Code-Browser-Value-Menu.png)

#### SALI Area of Law - COTL-TRNS - Commercial & Trade Law AND Commercial Transaction
![SALI-LMSS-Area-of-Law-COTL-TRNS](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/Image-of-SALI-LMSS-Code-Browser-COTL-TRNS.png)

#### SALI Legal Entity - ENTITY-LLC - Entity AND Limited Liability Company
![SALI-LMSS-Legal-Entity-ENTITY-LLC](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/Image-of-SALI-LMSS-Code-Browser-ENTITY-LLC.png)

#### SALI Player Role - PART-GENP - Partner AND General Partner
![SALI-LMSS-Player-Role-PART-GENP](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/Image-of-SALI-LMSS-Code-Browser-PART-GENP.png)

#### SALI Process - RMON - Regulatory (Non-Dispute) AND Monitoring
![SALI-LMSS-Process-RMON](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/Image-of-SALI-LMSS-Code-Browser-R-MON.png)

#### SALI Representation Role - LCOUN - Legal Counsel
![SALI-LMSS-Representative-Role-LCOUN](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/Image-of-SALI-LMSS-Code-Browser-LCOUN.png)

#
#

## Part E - Additional samples of SALI LMSS coding 

### Reference https://salilegal.org/sali3/docs/LMSS%20Examples.pdf?1566567194

#### This additional samples of SALI LMSS coding supplement those already provided in the [Body](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#body-of-draft-legal-matter-specification-standard-lmss-10-rev-2-june-2019) of [Part C](https://github.com/CryptosOdysseus/AALE-Contributions/blob/master/20190827-SALI-LMSS-vs-AALE-usability.md#part-c---draft-legal-matter-specification-standard-lmss-10-rev-2-june-2019).

#### Guess the LMSS 01

```

{
    "document" : {
        "header" : {
            "lmss type" : "QRY" //Query
            ,"lmss version" : "1.02" //Draft LMSS 1.0 Rev 2
            ,"language" : "en-us"
            ,"charset" : "UTF-8"
        }
        ,"matter" : {
            "locale" : "NAM-US-US+RI" //North America:United States of America (the):Rhode Island
            ,"process" : {
                "process type" : "B-USCHAP11" //Restructuring/Bankruptcy:US Chapter 11
                ,"area of law" : "BKCY" //Bankruptcy and Restructuring
                ,"player" : {
                    "player role" : "DEBT" //Debtor
                    ,"legal entity" : "ENTITY-LLC" //Entity:Limited Liability Company
                    ,"counsel" : {
                        "firm name" : "Dewey Stockbridge"
                        ,"representation role" : "COUN" //Counsel/Attorney
                    }
                }
            }
        }
    }
}

```
#

#### Guess the LMSS 02

```

{
    "document" : {
        "header" : {
            "lmss type" : "INST" //Instance
            ,"lmss version" : "1.02" //Draft LMSS 1.0 Rev 2
            ,"language" : "en-us"
            ,"charset" : "UTF-8"
        }
        ,"matter" : {
            "locale" : "NAM-US-US+CA" //North America:United States of America (the):California
            ,"process" : {
                "process type" : "D-CCI" //Dispute:Court Proceeding, Civil
                ,"area of law" : "INTP-PATE" //Intellectual Property Law:Patent Law
                ,"player" : [{
                    "name" : "Apple Inc."
                    ,"player role" : "PLTF" //Plaintiff
                    ,"legal entity" : "ENTITY-CORP" //Entity:Corporation
                    ,"industry" : "TEC" //Technology
                }
                ,{
                    "name" : "Samsung Electronics Co. Ltd."
                    ,"player role" : "DEFT" //Defendant
                    ,"legal entity" : "ENTITY-CORP" //Entity:Corporation
                    ,"industry" : "TEC" //Technology
                }
                ,{
                    "name" : "Nathanael M Cousins"
                    ,"player role" : "JUDG" //Judge
                    ,"legal entity" : "INDV" //Individual
                }
                ,{
                    "name" : "Nokia Corporation"
                    ,"player role" : "APPT" //Applicant/Petitioner
                    ,"legal entity" : "ENTITY-CORP" //Entity:Corporation
                    ,"industry" : "TEL" //Telecommunications
                }]
                ,"process object" : {
                    "filing date" : "2011-04-15"
                    ,"dispute: venue" : "USCTS-DISCOUS-CACD" //U.S. Courts:U.S. District Courts:District Court, C.D.      California
                    ,"dispute: venue other" : "US District Court for the Northern District of California"
                    ,"dispute: trial type" : "TRIJRY" //Jury Trial
                    ,"dispute: case name" : "Apple Inc. v. Samsung Electronics Co. Ltd. et al"
                }
            }
        }
    }
}

```
#

#### Guess the LMSS 03

```

{
    "document" : {
        "header" : {
            "lmss type" : "INST" //Instance
            ,"lmss version" : "1.02" //Draft LMSS 1.0 Rev 2
            ,"language" : "en-au"
            ,"charset" : "UTF-8"
        }
        ,"matter" : {
            "locale" : "OCA-AU-AU+NSW" //Oceana:Australia:New South Wales
            ,"process" : {
                "process type" : "T-FOR" //Transaction:Formation
                ,"area of law" : "CORP-MRGA" //Corporate Law:Mergers and Acquisitions
                ,"player" : [{
                    "name" : "Sydney Sailboats"
                    ,"player role" : "AQRR" //Acquiror
                    ,"legal entity" : "ENTITY-CORP" //Entity:Corporation
                    ,"counsel" : {
                        "firm name" : "Sly & Wentworth"
                        ,"representation role" : "SOLI" //Solicitor
                    }
                    ,"industry" : "COP" //Consumer Products
                }
                ,{
                    "name" : "NSW Outboard Motors"
                    ,"player role" : "AQRE" //Acquiree
                    ,"legal entity" : "ENTITY-CORP" //Entity:Corporation
                    ,"counsel" : {
                        "name" : "Howard Clark"
                        ,"representation role" : "SOLI" //Solicitor
                    }
                }]
                ,"process object" : {
                    "term sheet date" : "2018-11-05"
                    ,"effective date" : "2018-12-01"
                    ,"monetary value" : {
                        "currency" : "AUD" //Australian dollar
                        ,"value" : "8000000"
                    }
                    ,"non-monetary value" : "1,000,000 Shares of Preferred Stock to Aquiree"
                }
            }
        }
    }
}

```

#

#### Guess the LMSS 04

```

{
    "document" : {
        "header" : {
            "lmss type" : "QRY" //Query
            ,"lmss version" : "1.02" //Draft LMSS 1.0 Rev 2
            ,"language" : "en-us"
            ,"charset" : "UTF-8"
        }
        ,"matter" : {
             "locale" : "NAM-US-US+CA" //North America:United States of America (the):California
            ,"process" : {
                "process type" : "R-COM" //Regulatory (Non-Dispute):Compliance
                ,"area of law" : "ENVT-ENIA" //Environmental and Natural Resource Law:Impact Assessment
                ,"player" : {
                    "industry" : "FAG" //Food and Agriculture
                }
                ,"process object" : {
                    "asset location" : "Madera County, CA"
                }
            }
        }
    }
}

```

#### ++++ End of text ++++

#### [New File For Pull Request Toward MIT Media Lab AALE Challenge Repository](https://github.com/mitmedialab/AutomatedLegalEntityChallenge/new/master)
