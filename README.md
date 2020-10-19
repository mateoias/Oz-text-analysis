# Oz-text-analysis, an exploration of vocabulary and sentiment in the works of Frank Baum

* This project is a text analysis of *The Wizard of Oz* and *The Marvelous Land of Oz* by Frank L. Baum. It uses the tidytext framework in R developed by Julia Silge and David Robinson for data cleaning, tokenization, word count and sentiment analysis. For more details see https://www.tidytextmining.com/.
* The analysis includes word frequencies and a sentiment analysis which plots the sentiment vs the plot of the text at different increments. 
* The project includes the use of Bootstrap to create a responsive web page of the results. To view the results go to:
* https://mateoias.github.io/Oz-text-analysis/index.html

### Tools/Packages Used:
*Conda R environment
* tidytext
* sentiment dataset
* ggplot
* wordcloud
* pandas
* VS code

## What is the pattern of positive and negative sentiment in the novel over the course of the plot? 
### This is a graph of the word sentiment in *The Wizard of Oz* and *The Land of Oz*. Each bar represents the relative positive/negative sentiment over a span of fifty lines of the text.

![Sentiment Plot](https://github.com/mateoias/Oz-text-analysis/blob/master/OZ_plots/sentiment_50_plot.jpg)

## What types of vocabulary does the author use to show sentiment and what are the most common words?
### This word cloud shows the sentiments of the 100 most common words in the two texts. The sentiment is shown with negative words at the top and positive words at the bottom. The relative frequency of the words in the text is shown by their size.
![Sentiment word cloud](https://github.com/mateoias/Oz-text-analysis/blob/master/OZ_plots/revised_sentiment_word_cloud.jpg)
