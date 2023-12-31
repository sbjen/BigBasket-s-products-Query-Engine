### BigBasket-s-products-Query-Engine
NLP English Language Query Engine For Extensively Product on Big Basket

[Medium Article here](https://medium.com/@smn.acm/bigbasket-products-query-engine-bert-qdrant-718bee72143a)


### 1. Features


- Can generate response for query related to Extensively Big basket Product's data
- Flask Api to interaction


### 2. Technologies Used

Tools and Technology Used:

- PyTorch] - 
- Qdrant - vector DB for efficient search.
- Flasm Apli - 
 

### 2. Folder Description
#### 2.1 **Notebooks** 
contains all the jupiter notebooks which used in process

##### **BigBasket Product Query Engine  Notebook 1**
- [NoteBook1](https://www.kaggle.com/code/sb0702/bigbasket-product-d-query-engine-notebook-1)
##### It contains
1. smooth data transformation 
2. extracted important meta data,  encoding done using sentence encoder and stored in dict object along with meta data  
3. returns space.pkl which will use to store context in vector db(qdrant) file containg vector representation of context and important meta data

##### **BigBasket Product Query Engine  Notebook 2**
- [NoteBook2](https://www.kaggle.com/code/sb0702/bigbasket-product-s-query-engine-notebook-2)
##### It contains
1. importing vector embedding from file space.pkl which is python dic object vector DB 
2. storing vector in vector DB Qdrant 
3. saving qdrant for api
4. saving bert model for api
5. saving sentence transformer for api

##### **BigBasket Product's Query Engine Notebook 3
- [NoteBook3](https://www.kaggle.com/code/sb0702/bigbasket-product-s-query-engine-notebook-3)

##### It contains
1. Note book is aimed to integrating vector dd qdrant llm model 



### 3. Installation
- Install required dependencies 
- Go in API Folder
```sh
flask run
```


### 4. Results

1. QUERY INPUT: suggest me one product for cleaning vegetables
   
   OUTPUT: Vegetable & Fruit Wash

   Referred Product: Vegetable & Fruit Wash with 100% Natural Action

2. QUERY INPUT: what is most loved beauty product

   OUTPUT: Brightening Beauty Pack

   Referred Product: Brightening Beauty Pack

3. QUERY INPUT: price of dove soap

   OUTPUT: 699.0

   Referred Product: Lavender Soap Spa Set

4. QUERY INPUT: what is most loved beauty product

   OUTPUT: Brightening Beauty Pack

   Referred Product: Brightening Beauty Pack



**VISIT ME ON** 
-  [Important Links][link_tree]
-  [Linked In][link_linkedin]
-  [Kaggle][link_kaggle]
-  [Medium][link_medium]



[link_ganache_download]: <https://trufflesuite.com/ganache/>
[link_portfolio]:<https://master--sbrajen7.netlify.app/>
[link_tree]:<https://linktr.ee/sbrajen07>
[link_kaggle]: <https://www.kaggle.com/sb0702>
[link_linkedin]:<https://www.linkedin.com/in/sbrajendra/>
[link_medium]:<https://medium.com/@smn.acm>
