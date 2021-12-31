# Amazon_electronics_recommender
A hybrid recommender of Amazon electronics based off product text reviews

Despite user-based collaborative recommender systems where a user rates certain items and items favored by the user are passed on to similar users popularity, they do possess certain disadvantages. The disadvantages include not having ratings for new products from many users, and also not having side features being included in the recommendation of the item. Basing recommendations off user reviews of the products solves these problems because we can use the lone review as a guidance to pair similar products. The second disadvantage is answered since the review often describes the side features that can be factored in to our similarity process. 

Hybrid systems try to take advantage of both types of rec systems. Our recommender utilizes content-based recommendations because it uses NER in the product name to 
recommend a product but it is a user-based collaborative system since it utilizes user reviews to make its second tier of recommendations. The cold start problem is eliminated in the content based phase of the recommender. 

Here is some preliminary EDA on our dataset. The dataset was downloaded from https://nijianmo.github.io/amazon/index.html ELECTRONICS reviews. 
