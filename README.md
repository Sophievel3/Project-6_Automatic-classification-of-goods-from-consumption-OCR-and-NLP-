# -Automatic-classification-of-goods-from-consumption-OCR-and-NLP-
Testing the feasibility of a classification engine, which based on an image and a description can assign to each product an item category.

This work concerns an analysis of the text descriptions and the images of products, through the following steps:
- Preprocessing of text or image data.
- Features extraction.
- Reduction in 2 dimensions, in order to project the products on a 2D graphic, in the form of points whose color will correspond to the real category.
- Analysis of the feasibility of automatically grouping products of the same category.

Constraints: 
- In order to extract text features (NLP):
Description classifier engine: bag-of-words (Countvectorizer, Tf_idf).
Word/sentence embedding (Word2Vec, BERT, USE).
- In order to extract the image features (OCR):
Images classifier engine: SIFT, CNN.
