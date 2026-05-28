# fch-opendata

Additional Information in regards of the Open Data Sets of the Federal Chancellery. In general the open data sets are provided through the Linked Data Services [LINDAS](https://lindas.admin.ch/).

This repositories representes a starting guide, tips and tricks about Open Data Sets provided by the Federal Chancellery.

## Contributions

Pull-request with corrections, additional explanation or examples are appreciated. For questions regarding the datasets please open an Issue.


## Overview of the available Datasets

### Political Rigths
All published information in regards to Political Rights (Votations, Initiatives, Petitions to the Federal Council) are availabel on LINDAS. Some datasets are also available on http://visualize.admin.ch.

* **Overview on Visualize**: https://visualize.admin.ch/en/browse/theme/https%3A%2F%2Fregister.ld.admin.ch%2Fopendataswiss%2Fcategory%2Fpolitics?dataSource=Prod


### Extra-parliamentary Commission
Extra-parliamentary commissions are bodies established by the Federal Council or a federal department that perform public functions on behalf of the government and the administration.
All information available at https://www.admin.ch/de/ausserparlamentarische-kommissionen-gremienverzeichnis is based on open data available on LINDAS.

### Terminology
The entries of the [terminology database](https://www.termdat.bk.admin.ch/) of the Swiss Confederation is mostly available as open-data.

* **Dataset Description**: https://register.ld.admin.ch/.well-known/dataset/termdat

Note: In general entries under register.ld.admin.ch/termdat/ are redirected to end-user interface www.termdat.bk.admin.ch. You can [disable the redirect](https://lindas.admin.ch/know-how/dereferencing/) by providing an URI parameter `disableSchemaUrlRedirect=true` (e.g. https://register.ld.admin.ch/termdat/56905?disableSchemaUrlRedirect=true).

### Official Publications (Laws and Ordonances)
The official publications of the Swiss Confederations are available as open data. The metadata of the published documents are described in the JOLux Ontology. All new published documents are itself available as XML Documents following the [LegalDocML](Datamodellhttps://www.oasis-open.org/committees/tc_home.php?wg_abbrev=legaldocml).

* **Overview**: https://fedlex.data.admin.ch/en-CH/home/intro
* **Introduction to the Data Model JOLux**: https://swiss.github.io/fedlex-jolux/introduction.html
* **Fedlex SPARQL Tutorial**: https://github.com/swiss/fedlex-sparql
