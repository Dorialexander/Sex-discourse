# Sex-discourse
This repository stores preliminary results in the perspective of a wider project of the development and transformation of the discourse on sexuality in France since the 18th century.

Two different analysis have been undertaken:
- An extraction of all the daily newspaper paragraphs (text blocks) including a word about sexuality. The short list of words was created iteratively from an initial seed of expected words. The dataset is presented as one file per year containing all the text blocks and the word extracted. A separated dataset includes the classification of newspaper paragraph per genres.
- The automated identification of erotic novels in a large corpus of 19,000 volume of fictions extracted from Gallica. The classification was done with an SVM model trained on the "érotisme" tag from Babelio. The 360 results are ordered by the share of segments of 1000 words that are classified as erotism (with a 40% certainty). Obviously, the first novels are much more likely to belong the genre of erotica.

The project has mostly underlined the limitations of using contemporary terms about sexuality, which have been historically elaborated in a medical context. Alternative expression coming from the daily language, slang or literary erotica cover much more extensively, at the cost of being more fuzzy.

Future work aims to better track composite discourse about sexuality, likely using text classification model.
