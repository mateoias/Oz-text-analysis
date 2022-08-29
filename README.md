# Oz-text-analysis, an exploration of vocabulary and sentiment in the works of Frank Baum

* This project is a text analysis of *The Wizard of Oz* and *The Marvelous Land of Oz* by Frank L. Baum. It uses the tidytext framework in R developed by Julia Silge and David Robinson for data cleaning, tokenization, word count and sentiment analysis. For more details see https://www.tidytextmining.com/.
* The project seeks to understand the story arc and emotional tone of the books by analyzing word frequencies and plotting the sentiment of the text at  increments of 10, 50 and 100 lines of text. 
* The project includes the use of Bootstrap to create a responsive web page of the results. To view the results go to:
* https://mateoias.github.io/Oz-text-analysis/index.html

### Tools/Packages Used:
* Conda R environment
* tidytext
* sentiment dataset
* ggplot
* wordcloud
* pandas
* VS code

## What is the pattern of positive and negative sentiment in the novel over the course of the plot? 
### This is a graph of the word sentiment in *The Wizard of Oz* and *The Land of Oz*. Each bar represents the relative positive/negative sentiment over a span of fifty lines of the text.

![Sentiment Plot](https://github.com/mateoias/Oz-text-analysis/blob/master/OZ_plots/sentiment_50_plot.jpg)

### In order to smooth out the graph we can plot a point for every 100 lines of text instead.
![Sentiment Plot 100 lines](https://github.com/mateoias/Oz-text-analysis/blob/master/OZ_plots/sentiment_100_plot.jpg)

## What types of vocabulary does the author use to show sentiment and what are the most common words?
### This word cloud shows the sentiments of the 100 most common words in the two texts. The sentiment is shown with negative words at the top and positive words at the bottom. The relative frequency of the words in the text is shown by their size.
![Sentiment word cloud](https://github.com/mateoias/Oz-text-analysis/blob/master/OZ_plots/revised_sentiment_word_cloud.jpg)

## Analysis
Looking at the story arc of the novels, charted by measuring the sentiment of the text over spans of 100 lines, shows that both stories follow a conventional adventure narrative. A happy beginning is followed by a series of events, which go back and forth between positive and negative and then there is the standard happy ending (although the final 20 lines of "The Wonderful Wizard of Oz" go negative again, perhaps because of the description of Dorothy's abrupt and bumpy flight home.) 
It's interesting though that the overall sentiment of the text is distinctly more negative than positive. Perhaps the popular perception of OZ as a fun children's world comes more from the movie version of the story, which is both light hearted and musical. In contrast, the original texts emphasize a number of disturbing and frightening plot elements. They show more resemblance to the harsh moral world of Grimm's fairy tales than to contemporary children's entertainment in the style of Disney.
