# Net-CR-Dataset

The dataset constructed in the paper _A Deep Semantic-Aware Approach for Cantonese Rumor Detection in Social Networks with Graph Convolutional Network_, which contains 2,395 events and 214,625 posts.

## source_tweet_example.csv
It contains the information of source tweets, including full text and label.

The tweet with a label of '1' is annotated as a rumor. Otherwise, a non-rumor.

## tree_example.csv
It contains the graph structure information of retweets/replies, including root, parent, current, text.

- root: tweet id of source tweet
- parent: index of parent node
- current: index of current node
- text: space separated index-count pairs, where a index-count pair is in format of _index:count_. Index-count pairs are extracted from text contents of tweets

