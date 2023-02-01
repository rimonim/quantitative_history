Semantic Scholar Academic Graph Datasets

The "paper-ids" dataset provides mapping between different IDs representing a paper

The primary key of a paper in the S2AG datasets is the corpusId field. However, the public API and web site also accept a sha-based ID, which is also used in some research datasets. This dataset provides a mapping between the different IDs.

SCHEMA
corpusId - The paper's primary key
sha - A sha-based ID that can be used to access the paper via our API or web site
primary - There should be only one primary sha for each corpusId. Accessing papers using a non-primary sha will redirect to the primary sha.

LICENSE
This collection is licensed under ODC-BY. (https://opendatacommons.org/licenses/by/1.0/)

By downloading this data you acknowledge that you have read and agreed to all the terms in this license.

ATTRIBUTION
When using this data in a product or service, or including data in a redistribution, please cite the following paper:

BibTex format:
@inproceedings{Ammar2018ConstructionOT,
  title={Construction of the Literature Graph in Semantic Scholar},
  author={Waleed Ammar and Dirk Groeneveld and Chandra Bhagavatula and Iz Beltagy and Miles Crawford and Doug Downey and Jason Dunkelberger and Ahmed Elgohary and Sergey Feldman and Vu A. Ha and Rodney Michael Kinney and Sebastian Kohlmeier and Kyle Lo and Tyler C. Murray and Hsu-Han Ooi and Matthew E. Peters and Joanna L. Power and Sam Skjonsberg and Lucy Lu Wang and Christopher Wilhelm and Zheng Yuan and Madeleine van Zuylen and Oren Etzioni},
  booktitle={NAACL},
  year={2018}
}


