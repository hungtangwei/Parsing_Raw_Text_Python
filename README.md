# Parsing_Raw_Text_Python
Extracting data from semi-structured text files.

## Introduction
Text documents, such as crawled web data, are usually comprised of topically coherent text data,
which within each topically coherent data, one would expect that the word usage demonstrates
more consistent lexical distributions than that across data-set. A linear partition of texts into topic
segments can be used for text analysis tasks, such as passage retrieval in IR (information retrieval),
document summarization, recommender systems, and learning-to-rank methods.

## Parsing Raw Text Files
This assessment touches the very first step of analyzing textual data, i.e., extracting data from semi-structured text files. Each group is provided with a data-set that contains information about grants given for IP patent claims (please find your group file on the GDrive, i.e., <your_group_number>.txt). Each data-set contains information about several patent grants, e.g., patent title, patent ID, citation network, abstract etc. (see sample_input.txt). Your task is to extract the data and transform the data into the CSV and JSON format with the following elements:

- 1. grant_id: a unique ID for a patent grant consisting of alphanumeric characters.
- 2. patent_kind: a category to which the patent grant belongs.
- 3. patent_title: a title given by the inventor to the patent claim.
- 4. number_of_claims: an integer denoting the number of claims for a given grant.
- 5. citations_examiner_count: an integer denoting the number of citations made by the
examiner for a given patent grant (0 if None)
- 6. citations_applicant_count: an integer denoting the number of citations made by the
applicant for a given patent grant (0 if None)
- 7. inventors: a list of the patent inventors’ names ([NA] if the value is Null).
- 8. claims_text: a list of claim texts for the different patent claims ([NA] if the value is Null). 9. abstract: the patent abstract text (‘NA’ if the value is Null)

## Authors

Tangwei, Hung

## Contact
hung.tangwei@gmail.com
