# Zotero for EPI publications
These are tips for using Zotero to generate citations/bibliographies that are relatively consistent with EPI's style guidelines.

## Initial setup
1. Download and install [Zotero's desktop app](https://www.zotero.org/)
2. Install the [Zotero Connector](https://www.zotero.org/download/connectors) for your web browser if you want to use Zotero from your browser or if you want to use Zotero with Google Docs. (The Zotero plugins for Word or LibreOffice should automatically install the next time you open those word processors)
3. Create a free [Zotero account](https://www.zotero.org/) to get access the EPI-test group library. Set up syncing with your desktop app (Edit >> Preferences >> Sync)
4. Download the [EPI style file](https://raw.githubusercontent.com/Economic/epi_zotero/main/epi-chicago-author-date.csl) and add it to Zotero (Edit >> Preferences >> Cite >> Style Manager >> plus sign)

## Best practices
### Categories
- EPI report item type = Report
- EPI blog item type = Blog Post, with Extra field `publisher: Economic Policy Institute`
- Data source item type = Document, with Extra field `type: dataset`
- NBER working paper item type = Journal Article, with Publication field blank and Volume field `National Bureau of Economic Research (NBER) Working Paper XXXXX`

## Problems
- No perfect solution to have both abbreviations and full name of a government agency when it the author. Try using first name = abbreviation, last name = full name. This will nail the in-text citation abbreviation but will fudge the bibliography format a bit.

- EPI prefers hyperlinked titles to articles, reports, etc., but this is currently impossible with Zotero for Word and Google Docs.

- Generated blog post style not completely consistent with EPI style, which depends on context

- Not sure it is worth the trouble to include data sources in Zotero. EPI's data source citation style depends on context.

## Bibliography differences from the 17th edition Chicago author-date style
- journal article issue numbers as "no. 4" instead of "(4)"
- same authored bibliography sources ordered by (coarser) year instead of (finer) date, forcing sources with identical author-year to be sorted by title
- reports and documents include month and year


