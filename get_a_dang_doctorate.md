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
			* See also "Miscellaneous: Section 6.1 provides for the choice of law... After significant discussion, we decided that it was better for FOSS projects to have predictability in interpretation of the terms of the contributor agreement. In addition, the term disclaims a treaty, the United Nations Convention on the International Sale of Goods ("UNCISG"), which is similar to the UCC and would apply automatically to the contributor agreement if the parties are in different countries which are each members of the UNCISG. UNCISG has rarely been used and is an unpredictable combination of civil law and common law, and thus would lead to further ambiguity about the interpretation of the terms of the contributor agreement."

---------
### Random thoughts from COSPAR so far	

How to create a legal or policy framework to guide scientists who may want to collaborate with industry such that their research is protected and open? 

* Ownership of data, metadata, and software
* Dealing with proporetary systems and tools
	* Access ([Iceye](https://www.iceye.com/) as example) -- what is the latency? What does their "archive" look like? -- plan for catastrophic failure? License access or direct access? Long term access to the "raw" data -- do they share their decoders?
	* [Iceye "Product" specification](https://www.iceye.com/hubfs/Downloadables/ICEYE-Level-1-Product-Specs-2019.pdf) -- the "product" is the data they're selling
		* Do the people making the decisions about the policies analyze the specs provided by vendors with these questions in mind?
		* What do they use to analyze the options they're presented with?
		* Who are the "experts" needed to consult/prevent sales pitch problem

* Purchasing data from private companies to fill in gaps discussed by Anthony Freeman (JPL) -- "SmallSat Constellations for Earth Science"
	* Focused on time series capabilities
	* Incorporating Planet data to fill in gaps - compared the Planet data to MODIS, Landsat, and Sentinel 2 
		* Planet data requires calibration using Landsat but presenter called it very useful/"useful in surprising ways"
		* Continuous real time data being made available because it's coming from many sources (i.e. Planet)
			* Brought up LEO *constellation* trends -- claimed this is how many constellations there are (data source?)
				* IoT/M3M - 39
				* Internet - 27
				* Earth observation - 32
				* Weather - 7
				* SAR - 8
	* Still needed for getting time derivative (dx/dt or ẋ)
		* de-orbit and high downlink capabilities


#### Side thoughts
* "[math as code](https://github.com/Jam3/math-as-code/blob/master/README.md#dot--cross)" is helpful
* Open software needs broad testing but you can catch the errors when software is open
	* [An Error in a Python Script May Have Invalidated 150+ Research Projects](https://medium.com/better-programming/an-error-in-a-python-script-may-have-invalidated-150-research-projects-64fe7cda558c)
		* "The error propagated depending on the operating system the scripts were being run on. The scripts were found to give accurate results on Windows 10 and macOS Mavericks but were less accurate by almost a full percent on macOS Mojave and Ubuntu." 
* CubeSat liability questions
	* Possible analogs to Boeing 373 MAX - case for the prosecution is difficult; if major problems arose from working with private company in small sat case how would it be approached?
		* [Prosecutors Face Complex Path to Charging Boeing Over 737 MAX](https://www.wsj.com/articles/prosecutors-face-complex-path-to-charging-boeing-over-737-max-11572777000?shareToken=st1ce92f041e5e47298e6f46bbbf7fe0ec)












	
