## 🤷🏻‍♀️ 🛰️ 📚

### Ideas for scope:

International legal/ethical/policy/security implications of [NASA's Small Satellite Data Buy Program](https://earthdata.nasa.gov/esds/small-satellite-data-buy-program) or other  hypothetical public/private collaborations using small satellites: 

1.  Considerations about different software licenses

	* Practical: What should we recommend to people developing small sats? (e.g. MetaSat's recommended license for payload telemetry decoders)? -- "open" is vague.
	* Unknowns but possibly relevant: 
		* Does the [ESDS open source policy](https://earthdata.nasa.gov/collaborate/open-data-services-and-software/esds-open-source-policy) apply to vendors in the commercial buy program? Does it require code to be archived? Mentions GitHub but nothing else. 
		* Does NASA's [Data and Information Policy](https://earthdata.nasa.gov/collaborate/open-data-services-and-software/data-information-policy) apply to vendors in the commercial buy program?

* Note - To be subject to a license, a work must still be in copyright
	* With U.S. government work (not copyrightable) the software must be released into the public domain. 
		* No license but the software is effectively open source, assuming that in the laws of the releasing jurisdiction the meaning of "public domain" is compatible with the Open Source Definition
	* [NASA license](https://opensource.org/licenses/NASA-1.3)
		* "Special purpose: for use by an agency of the United States federal government, which has special concerns regarding some issues such as copyright protection, copyright notices, disclaimer of warranty and indemnification, and choice of law." - [Report of the OSI License Proliferation Committee](https://opensource.org/proliferation-report)

2. Considerations about different format choices re: software metadata

	* Vendors need to adhear to the [NASA Earth Science Data Preservation Content Specification](https://cdn.earthdata.nasa.gov/conduit/upload/10607/NASA_ESD_Preservation_Spec.pdf)
		* NASA is not legislatively mandated to preserve data permanently and the specification does not say "how" to do this --- "The focus of this document is on the contents (i.e., “what”) and not on the implementation or representation (i.e., “how”) of the content items."

3. Considerations about different approaches to software attribution/credit

	* What "attribution" actually looks like veries widely depending on the license used. 
		* e.g. [OSS Attribution Oblications](https://www.nexb.com/blog/oss_attribution_obligations.html)
	* How to represent individual people? (e.g. the copyright holder is an individual or something like "the <something> project")
		* Contributor License Agreement (CLA) and Copyright Assignment Agreement (CAA) - with both CLAs and CAAs it is necessary that "the project" be some kind of legal entity able to enter into agreements
			* "The assumption of all of the agreements is that the FOSS project is managed by an entity, whether it is an individual, foundation, non-profit corporation, or for profit corporation." - [Harmony Guide to the Contributor Agreements](http://harmonyagreements.org/guide.html) 
			* See also "Miscellaneous: Section 6.1 provides for the choice of law... After significant discussion, we decided that it was better for FOSS projects to have predictability in interpretation of the terms of the contributor agreement. In addition, the term disclaims a treaty, the United Nations Convention on the International Sale of Goods ("UNCISG"), which is similar to the UCC and would apply automatically to the contributor agreement if the parties are in different countries which are each members of the UNCISG. UNCISG has rarely been used and is an unpredictable combination of civil law and common law, and thus would lead to further ambiguity about the interpretation of the terms of the contributor agreement.""
