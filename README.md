# Movie-Recommendation-System

## Recommendation System <br/>

>A recommendation system is a subclass of Information filtering Systems that seeks to predict the rating or the preference a user might give to an item. In simple words,  it is an algorithm that suggests relevant items to users. Eg: In the case of Netflix which movie to watch, In the case of e-commerce which product to buy, or In the    case of kindle which book to read, etc.

### Recommendation System is of two types: <br/>

a) Content Based Recommendation <br/>
b) Collaborative Filtering.

> Developed a content based movie recommendation engine.It uses the attributes or features of an item  (this is the content part) to recommend other items similar to the user’s preferences. This approach is based on similarity of item and user features,  given information about a user and items they have interacted with.

> It gives recommendations mainly based on the director name, the actor name, movie genre, and the movie title.If any user searches for a comedy film,from then on he would get comedy movies as the recommendations.

<img src="https://user-images.githubusercontent.com/69798079/216786215-46930db9-9cba-4d69-9e30-28f83f10e911.png" width="50%" height="50%">

## Vectorization <br/>
Vectorization is a classic approach of converting input data from its raw format text into vectors of real numbers which is the format that Machine Learning models support. 
> Used TF-IDF vectorizer for the vectorization. <br/>

## TF-IDF Vectorizer  <br/>
Term frequency-inverse document frequency is a text vectorizer that transforms the text into a usable vector. It combines 2 concepts, Term Frequency (TF) and Document Frequency (DF).

### Term Frequency (TF) <br/>
Term frequency is defined as the number of times a word appears in a document divided by the total number of words in the document.  <br/>

![image](https://user-images.githubusercontent.com/69798079/216804615-5a0d040e-cef4-4e56-9545-c81d66f224ed.png)

### Inverse Document Frequency (IDF) <br/>
Inverse document frequency refers to the log of the total number of documents divided by the number of documents that contain the word. The logarithm is added to dampen the importance of a very high value of IDF. <br/>

![image](https://user-images.githubusercontent.com/69798079/216804669-02a9efc4-3a22-4c26-bf28-f070d7e0dd99.png)

### TF-IDF = TF x IDF <br/>
> Tf-IDF is calculated by multiplying the term frequency and inverse document frequency.

## How the items are recommended to the user?  <br/>
Based on the similarity score, movies are recommended to the users. The similarity score lies between 0 to 1. 1 being the highly similar case and 0 being totally uncorrelated. 
> Similarity score can be computed with the help of cosine similarity. 

### Cosine Similarity <br/>
Cosine similarity is a metric used to measure how similar two items are. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. 






