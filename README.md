# Song recommendation for autonomous Vehicle

## Introduction
Everything from cars to the tap in your is automatic now a days. you do not need driver in car. Your phone is booking appointments at the salon for you. Have you ever wondered if an assistance can recommend you song in Car on uttering some words and analysing your gender, age, mood and weather for better prediction.

Well, point to be noted here is, these uttered words are not singer name, song name, genre or word in lyrics. These can be anything from "I want to hear some fast hard band loud music which feels like storm" to "I am feeling bored play some awesome music". Now "awesome music" is different for a guy of an age 22 and man of age 36, Its different for a woman and a man. What if the weather is rainy or sunny, your desire to listen "awesome song" may vary. it will be different for a guy going through a breakup and a guy who just got a job in Facebook.

--- Photo 1 ---

### Why Users query
Whatever the situation, mood, weather, age or gender. If users want to listen to some kind of song, that should be the first preference. AI has grown up fast, it can predict what your age, gender, etc is. But it still cannot read minds. Only user knows what kind of song one wants to listen. it does not matter if user seems 22 years old but if he wants to listen to old songs, then old song must be recommended to him.
### Why user age
Statistics obtained by survey shows that the song preference vary according to our age. And this is obvious too, your grandma may not love to listen, "I love it when you call me Senorita", or may be. In simple words, our preference changes as our age passes.

--- Photo 2 --- 

### Why user gender
According to a survey Female love to listen Pop and Rock and Male love to listen Rap, Hip-Hop and Electronic music. So its necessary to predict gender of user for better recommendations. (When male and female are together, you should ignore man's preference for betterment of both, just kidding )

--- photo 3 ---

### Why emotion

We prefer listening to different songs at different mood. If we are happy, we would go for some hip-hop kinda song, if sad we would prefer listening slow song. So emotions directly affect the desire for song. 

--- photo 4 ---

### Why weather

There are two things, one is that our mood depends on the weather, for examples, in summers people seem more happy while in winters people can be found sleepy, low in energy. Second, weather directly affect our preference too. let say in rain, we usually want to listen the song having words in lyrics related to rain. Direct relation between weather to genre could not be found but survey results says our desire to mode, tempo, pitch, rhythm, melody changes according to the weather.

### Huge factor : Privacy

Privacy has become a big factor nowadays. User would never want his/her music preference to be leaked. Recommendation model contain a lot of private information about user like query, image of the face, image of his location. There has been various adversarial attacking techniques like model inversion attacks which can be used to reverse engineer the model and input. Even image of your face can be obtained from model parameters and prediction probabilities.

--- Photo 5 --- 

Read this awesome paper for more details. 
https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=2ahUKEwjf_NC-npHkAhXHfn0KHZvUAQMQFjAAegQIBhAC&url=https%3A%2F%2Fwww.cs.cmu.edu%2F~mfredrik%2Fpapers%2Ffjr2015ccs.pdf&usg=AOvVaw2Zl7-ovye12xyCeYm3tnhu

So here the novel idea was to combine Natural Language Processing, Computer Vision and privacy preserving techniques to provide better service with privacy than currently existing systems.

## Related Work

 There had been various work  done related to song recommendation using various techniques like naive bayes, simple logistic regression, multinomial naive bayes. But I have not seen recent work using Neural network. There has also been some work on music recommendation on the basis of mood or feature detection from image. But combining various factors is a novel idea for better song recommendation.
The awesomeness of this project comes from privacy. I have not yet seen any privacy preserving techniques in autonomous cars. But it will play a huge role in the near future.

## Datasets

NLP dataset

http://millionsongdataset.com/

Dataset has been derived from musiXmatch dataset, a subset of the famous Million Song Dataset (MSD) that includes the lyrics of 237,701 songs. 
The lyrics are stored in a bag-of-words format, where words are represented as positive integers. For efficiency, only the top 5000 most frequently uttered words in the total song vocabulary were included. Therefore, each song’s lyrics are delineated by the list of (token, n) tuples, where n is the number of instances of that token (i.e. word) in the song. We are also given a mapping of integer tokens to their corresponding word, which comes in lemmatized form.

The preprocessed dataset contains:















