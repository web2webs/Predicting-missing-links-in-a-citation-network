# Predicting-missing-links-in-a-citation-network
Text Mining and NLP in-class Data Challenge - Predicting missing links in a citation network

This a notbook for Text Mining and NLP in-class Data Challenge:
https://www.kaggle.com/c/text-mining-and-nlp-in-class-data-challenge

## Description:
A citation network is represented as a graph G(V,E) where V is the set of nodes and E is the set of edges (links). Each node corresponds to a paper and the existence of an edge between two nodes u and v means that one of the papers cites the other. Each node is associated with information such as the title of the paper, publication year, author names and a short abstract. A number of edges have been randomly deleted from the original citation network. Your mission is to accurately reconstruct the initial network using graph-theoretical and textual features, and possibly other information. Your solution can be based on supervised or unsupervised techniques or on a combination of both. You should aim for the maximum F1 score.

## Evaluation:
### Evaluation Metric

For each node pair in the testing set, your model should predict whether there is an edge between the two nodes (1) or not (0). The testing set contains 50% of true edges (the ones that have been removed from the original network) and 50% of synthetic, wrong edges (pairs of randomly selected nodes between which there was no edge).

The evaluation metric for this competition is Mean F1-Score. The F1 score measures accuracy using precision and recall. Precision is the ratio of true positives (tp) to all predicted positives (tp + fp). Recall is the ratio of true positives to all actual positives (tp + fn). 

## 
