# SMS-spam-classifier

Performed EDA in which I checked how many characters, words a SMS has.

I applied some data processing techniques also did Vectorization in which I used CountVectorizer on the data using NLTK package.

I applied <b>Multinomial NB, Gaussian NB, Bernoulli NB</b> and using confusion matrix I figured out which one was performing well and as we want less False positives, I selected Bernoulli NB as False positives was 0 and also accuracy score was 97 percent.
I also applied Logistic Regression and the results were same as Bernoulli NB

Performance of different models :

![image](https://github.com/LearningPratik/SMS-spam-classifier/assets/139999671/e82f15d3-69aa-4872-9701-983fc873304a)

Confusion matrix of Bernoulli NB Model :

![Image](image.png)
