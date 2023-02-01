Semantic Scholar Academic Graph Datasets

The "publication-venues" dataset contains meta-data for a research paper's publication
journal or venue. The data sources of the venue data comes from The Fatcat Archive, documented
here: https://archive.org/details/fatcat_snapshots_and_exports?sort=-publicdate, and the now deprecated Microsoft
Academic Graph (MAG).

SCHEMA
 - id: The id of the venue data. The value also corresponds to the "venueId" field in the papers dataset.
 - issn: The issn of the publication venue
 - alternate_issns: The alternative issns for the publication venue
 - name: The name of the venue
 - alternate_names: The alternative names for the publication venue
 - url:  The publication venue's url
 - alternate_urls: The alternative urls of the publication venue
 - type: The type (journal / conference) of the publication venue

LICENSE
This collection is licensed under ODC-BY. (https://opendatacommons.org/licenses/by/1.0/)

By downloading this data you acknowledge that you have read and agreed to all the terms in this license.

ATTRIBUTION
When using this data in a product or service, or including data in a redistribution, please cite the following paper:

@inproceedings{Ammar2018ConstructionOT,
  title={Construction of the Literature Graph in Semantic Scholar},
  author={Waleed Ammar and Dirk Groeneveld and Chandra Bhagavatula and Iz Beltagy and Miles Crawford and Doug Downey and Jason Dunkelberger and Ahmed Elgohary and Sergey Feldman and Vu A. Ha and Rodney Michael Kinney and Sebastian Kohlmeier and Kyle Lo and Tyler C. Murray and Hsu-Han Ooi and Matthew E. Peters and Joanna L. Power and Sam Skjonsberg and Lucy Lu Wang and Christopher Wilhelm and Zheng Yuan and Madeleine van Zuylen and Oren Etzioni},
  booktitle={NAACL},
  year={2018}
}

