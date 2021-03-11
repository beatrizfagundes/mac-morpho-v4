# MAC-Morpho v4
MAC-Morpho is a manually annotated corpus with POS tags. It consists of Brazilian portuguese sentences extracted from news texts. More information about the corpus can be accessed on: http://nilc.icmc.usp.br/macmorpho/

In this new revision, the following steps were performed to improve the text quality:

1. Remove empty ( ) and " "
2. Some sentences boundaries were better defined by fixing sentences splitted into multiples lines
3. Very low quality sentences were removed (for e.g.: "( )" and "Arraia ; Ajax")
4. Remove repeated sentences
5. Remove ",", ":" and other punctuation signs in the beginning of sentences. In this case, either the token was removed, or the sentence was coupled with the previous sentences, or the entire sentence was removed when it did not make much sense without the punctuation sign.
6. Join punctuation signs with a previous token corresponding to an abbreviation to standardize this pattern
7. Remove/fix some non-closing signs like "(", ")", "[", "]", '"'
8. Replace single quotes with double quotes
