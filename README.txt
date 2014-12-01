This is the data used for:

    What Predicts Medica Coverage of Health Science Articles?
    Byron C Wallace, Michael J Paul and Noémie Elhadad
    W3PHI (http://w3phi.com) Workshop at AAAI 2015

There are two datasets here: one comprises scientific citations that were covered in Reuters articles and 'matched' citations that were (at least very probably) not. The other directory contains information about JAMA articles for which press releases were issued by the editor(s) and 'matched' citations for which they were not. See the article for additional description of the corpora and matching procedure. 

The columns in the *_article_info.csv files are: 

    PubMed ID, citation title, journal, authors, affiliation (or missing), abstract, MeSH terms

In the matched_articles files, they are the same except that the first column is the PubMed ID of the corresponding article for which the row was 'matched'. E.g., the first row in the jama matched articles file begins with 

    24687165    24687146

Here this indicates that article 24687165 received a press release and we have matched article 24687146 to this; the remainder of the row includes information for the latter. 

Questions about the data can be sent to Byron Wallace: byron.wallace@utexas.edu; http://byron.ischool.utexas.edu.

