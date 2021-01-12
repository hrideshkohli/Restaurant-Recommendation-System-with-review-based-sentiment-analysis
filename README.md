# Restaurant-Recommendation-System-with-review-based-sentiment-analysis

![alt text](https://github.com/hrideshkohli/Restaurant-Recommendation-System-with-review-based-sentiment-analysis/blob/main/img.jpg)

# Background..

The basic idea of analyzing the Zomato dataset is to get a fair idea about the factors affecting the establishment of different types of restaurant at different places in Bengaluru, aggregate rating of each restaurant, Bengaluru being one such city has more than 12,000 restaurants with restaurants serving dishes from all over the world. With each day new restaurants opening the industry has’nt been saturated yet and the demand is increasing day by day. Inspite of increasing demand it however has become difficult for new restaurants to compete with established restaurants. Most of them serving the same food. Bengaluru being an IT capital of India. Most of the people here are dependent mainly on the restaurant food as they don’t have time to cook for themselves. With such an overwhelming demand of restaurants it has therefore become important to study the demography of a location.

What kind of a food is more popular in a locality.
Do the entire locality loves vegetarian food. If yes then is that locality populated by a particular sect of people for eg. Jain, Marwaris, Gujaratis who are mostly vegetarian. These kind of analysis can be done using the data, by studying the factors such as • Location of the restaurant • Approx Price of food Theme based restaurant or not
Which locality of that city serves that cuisines with maximum number of restaurants • The needs of people who are striving to get the best cuisine of the neighborhood • Is a particular neighborhood famous for its own kind of food.

# Project highlights:

- Perform extensive EDA on the data and understand the relationships
- Use folium to display the heatmap on the map for better visualization
- Perform Cosine similarity amongst the restaurants to find similar restaurants and group them together
- Create a recommendation system where various similar restaurants will be recommended to the user on providing any restaurant of his choice.
- Perform sentiment analysis on the reviews

### Columns description

**url** contains the url of the restaurant in the zomato website

**address** contains the address of the restaurant in Bengaluru

**name** contains the name of the restaurant

**online_order** whether online ordering is available in the restaurant or not

**book_table** table book option available or not

**rate** contains the overall rating of the restaurant out of 5

**votes** contains total number of rating for the restaurant as of the above mentioned date

**phone** contains the phone number of the restaurant

**location** contains the neighborhood in which the restaurant is located

**rest_type** restaurant type

**dish_liked** dishes people liked in the restaurant

**cuisines** food styles, separated by comma

**approx_cost(for two people)** contains the approximate cost for meal for two people

**reviews_list** list of tuples containing reviews for the restaurant, each tuple

**menu_item** contains list of menus available in the restaurant

**listed_in(type)** type of meal

**listed_in(city)** contains the neighborhood in which the restaurant is listed

## Various conclusions from EDA:

- Almost 90 percent of restaurants in Banglore do not provide table booking facility.
- In India you cannot find table booking facility in any average restaurants,usually only five star restaurants provides table booking
- Almost more than 50 percent of restaurants has rating between 3 and 4.
- Restaurants having rating more than 4.5 are very rare.
- We can see that the distribution if left skewed.
- This means almost 90percent of restaurants serve food for budget less than 1000 INR.($15)
- Restaurants accepting online orders tend to get more votes from customers as there is a rating option poping up after each order through zomato application.
- The median approximate cost for two people is 400 for a single meal.
- 50 percent of restaurants charge between 300 and 650 for single meal for two people
