# Book-Recommended-System
Recommanded system : every where we are using recommended system. like youtube, amazon(commerce), netflex, oreily(e-com book) etc. if i am searching any movie in netflex means it will give similar kind of suggestions. here we can use any akind of website whether its fashion kind of website like cosmetics cloth shoes etc.  

How we can build this kind of recommandation system with the help of machine learning. we can pick up any kind of data whether its cloth, shoes, cosmetics, movie or books data etc. 

Here we are using ML algorithms like clustering model class called nearest neighbor. clustering models are KMeans clustering, DBScan, Nearest neighbor.

Recommended system having 3 types:
1. content based: it will recommand the product based on the content. ex: actors related give similar movies.
2. collaborative filtering: means we are trying to collaborate with user1 to another user2 to give the recommandation it works based on the clustering technique. This project developed will be using collaborative filtering technique because content based familar with NLP because convert the textual data into numerical representation. similarity measurament  based on that we can recommend the product working with different different users. 
3. Hybrid: It combines multiple recommendation strategies to enhance the accuracy and diversity of recommendations. These systems typically integrate collaborative filtering, which analyzes user behavior and preferences, with content-based filtering, which focuses on item characteristics.

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/Bharatimudigoudra/Book-Recommended-System.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n books python=3.7.10 -y
```

```bash
conda activate books
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```