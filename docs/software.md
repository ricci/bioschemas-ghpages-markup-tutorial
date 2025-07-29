# TREC-doc-2-doc-relevance

[TREC-doc-2-doc-relevance](https://github.com/zbmed-semtec/TREC-doc-2-doc-relevance) is a web-based interface to add document-to-document relevance assessments to pairs of documents retrieved from [TREC 2005 Genomics Track](https://trec.nist.gov/data/genomics/05/genomics.qrels.large.txt). It first takes the topic-to-document relevance assessments from TREC, create pairs af articles, and presents them to annotators on a we-based interface for them to add their document-to-document relevance assessments. 

This page has been created to embed schema.org and Bioschemas markup describing [TREC-doc-2-doc-relevance](https://github.com/zbmed-semtec/TREC-doc-2-doc-relevance) source code and its current release deposited in Zenodo. 

<script type="application/ld+json">
  {
    "@context": "https://schema.org", 
    "@type": "Dataset",
    "@id": "https://doi.org/10.5281/zenodo.7338056",
    "conformsTo": "https://bioschemas.org/profiles/Dataset/1.1-DRAFT", 
    "identifier": "DOI:10.5281/zenodo.7338056",
    "citation": "Giraldo O, Solanki D, Rebholz-Schuhmann D, Castro LJ. Fleiss kappa for doc-2-doc relevance assessment. Zenodo; 2022. doi:10.5281/zenodo.7338056",
    "name": "Fleiss kappa for doc-2-doc relevance assessment",
    "description": "Fleiss' kappa measuring inter-annotator agreement on a document-to-document relevance assessment task. The table contains 7 columns, the first one presents the topics, 8 in total. The second column shows the \"reference articles\", represented by their PubMed-ID and organized by topic. The third column shows the Fleiss’ Kappa results. The fourth column shows the interpretation of the Fleiss' Kappa results being: i) \"Poor\" results <0.20, ii) \"Fair\" results within 0.21 - 0.40, and iii) \"Moderate\" results within 0.41 - 0.60. The fifth column shows the PubMed-IDs of evaluation articles rated by the four annotators as \"Relevant\" regarding its corresponding \"reference article\". The sixth column shows the PubMed-IDs of evaluation articles rated by the four annotators as \"Partially relevant\" regarding its corresponding \"reference article\". The seventh column shows the PubMed-IDs of evaluation articles rated by the four annotators as \"Non-relevant\" regarding its corresponding \"reference article\".",
    "keywords": "Fleiss' Kappa, Inter-annoator agreement, TREC Genomics Track 2005, relevance assessment", 
    "license": {
      "@type": "CreativeWork",
      "@id": "http://spdx.org/licenses/CC-BY-4.0",
      "name": "Creative Commons Attribution 4.0 International", 
      "alternateName": "CC BY 4.0",
      "url": "https://creativecommons.org/licenses/by/4.0/"
    },
    "url": "https://zenodo.org/record/7338056",
    "datePublished": "2022-11-19",
    "author": [                
      {"@id": "https://orcid.org/0000-0003-2978-8922"},
      {"@id": "https://orcid.org/0009-0004-1529-0095"},
      {"@id": "https://orcid.org/0000-0002-1018-0370"},
      {"@id": "https://orcid.org/0000-0003-3986-0510"}
    ]
  }
  </script>
