## ETL-with-Natural-Language-Processing
Created by: Helen Yu

In this project, I selected an article found online, and used NLP to extract the theme of the article. This machine learning algorithm helps us reduce the reading time but still get the core of the article. 

![Article Title](https://github.com/helenyu18/ETL-with-Natural-Language-Processing/blob/master/Picture1.png)

In the Natural Language Processing, I have used both bi-gram and tri-gram method for testing, together with a comparison between the results.

# Here are 3 examples of results under *bi-gram* method:
![Example1.1](https://github.com/helenyu18/ETL-with-Natural-Language-Processing/blob/master/Picture2.png)
![Example1.2](https://github.com/helenyu18/ETL-with-Natural-Language-Processing/blob/master/Picture3.png)
![Example1.3](https://github.com/helenyu18/ETL-with-Natural-Language-Processing/blob/master/Picture4.png)

# Here are 3 examples of results under *tri-gram* method:
![Example2.1](https://github.com/helenyu18/ETL-with-Natural-Language-Processing/blob/master/Picture5.png)
![Example2.2](https://github.com/helenyu18/ETL-with-Natural-Language-Processing/blob/master/Picture6.png)
![Example2.3](https://github.com/helenyu18/ETL-with-Natural-Language-Processing/blob/master/Picture7.png)

We can see that bi-gram sometimes generates an extremely long sentence and sometimes generates an extremely short sentence. Tri-gram usually generates a moderate length of sentence, though it is not verified yet. 

At the end of the test, I was wondering which method is better. Recall the principle of these two methods are to make the 2(or 3) adjacent words into a group, and tri-gram predicts the next word better, so the result has better accuracy.

## Reference: 

“Harvard Business Review | Blue Ocean Strategy Articles.” Blue Ocean Strategy, www.blueoceanstrategy.com/bos-related-articles-by-kim-mauborgne/harvard-business-review/.
