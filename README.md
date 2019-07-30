# IOC datasets
Dataset with raw text and Binary Labels of whether or not a piece text contains an Indicator of Compromise (IOC). Both on Blog and Sentence level, collected from Cyber Security Blogs.  The "label" column contains the binary label, where "1" means contains_IOC and "0" no_IOC. Both csv files are "\t" seperated and utf-8 encoded.

## IOC_documents.csv
Two columens: 1) "document", which contains the text that was extracted from the HTML page and 2) "label", which contains the binary label. 

## IOC_sentences.csv
Two columens: 1) "sentence", which contains the text of the given sentence and 2) "label", which contains the binary label. 
