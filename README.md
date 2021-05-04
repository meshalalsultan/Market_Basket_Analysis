# Market_Basket_Analysis
Market Basket Analysis using Apriori Algorithm in Machine Learning

In Machine Learning, the Apriori algorithm is used for data mining association rules. In this article, I will take you through Market Basket Analysis using the Apriori algorithm in Machine Learning by using the Python programming language.

## What is Association Mining?
Association mining is typically performed on transaction data from a retail marketplace or online e-commerce store. Since most transaction data is large, the a priori algorithm makes it easy to find these patterns or rules quickly.


Association rules are used to analyze retail or transactional data and are intended to identify strong rules mainly found in transactional data using measures of interest, based on the concept of strong principals.

## How does the Apriori Algorithm Work?

The Apriori algorithm is the most popular algorithm for mining association rules. It finds the most frequent combinations in a database and identifies the rules of association between elements, based on 3 important factors.

1- Support: the probability that X and Y meet
2- Confidence: the conditional probability that Y knows x. In other words, how often does Y occur when X came first.
3- Lift: the relationship between support and confidence. An increase of 2 means that the probability of buying X and Y together is twice as high as the probability of simply buying Y.

Apriori uses a “bottom-up” approach, in which frequent subsets are extended one item at a time (one step is called candidate generation) and groups of candidates are tested against the data. The algorithm ends when no other successful extension is found.

Now, I will take you through the task of Market Basket analysis using the Apriori Algorithm using Python and Machine Learning.

#### Market Basket Analysis with Apriori Algorithm using Python

Market basket analysis, also known as association rule learning or affinity analysis, is a data mining technique that can be used in various fields, such as marketing, bioinformatics, the field of marketing. education, nuclear science, etc.

The main goal of market basket analysis in marketing is to provide the retailer with the information necessary to understand the buyer’s purchasing behaviour, which can help the retailer make incorrect decisions.

There are different algorithms for performing market basket analysis. Existing algorithms operate on static data and do not capture data changes over time. But the Apriori algorithm not only leverages static data but also provides a new way to account for changes that occur in the data.

link : https://thecleverprogrammer.com/2020/11/16/apriori-algorithm-using-python/