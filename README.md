# XHateStability
Data from the paper:

Gavin Abercrombie, Dirk Hovy, and Vinodkumar Prabhakaran. 2023. Temporal and Second Language Influence on Intra-Annotator Agreement and Stability in Hate Speech Labelling. Linguistic Annotation Workshop. Association for Computational Linguistics.

Data is presented in `annotations.csv`, with the following columns:

 `row`: the row number of the text item from the original dataset, available at [https://github.com/codogogo/xhate/tree/main/test](https://github.com/codogogo/xhate/tree/main/test)
 
 `condition`: the language condition of the item: english-english, german-german, english-german, or german-english	
 
 `annotator`: anonymised ID of the annotator	
 
 `label1`: label applied in round 1	
 
 `label2`: label applied in round 2

The order in which the items were presented to participants in available in `order.csv`. This data is presented in tow columns for `round1` and `round2`, with the language and row number of each item.
