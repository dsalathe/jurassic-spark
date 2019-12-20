## Notebook for Milestone 3 : Milestone3.ipynb
Milestone3.ipynb is an extension of Milestone2.ipynb. No need to reread it from the beginning. A table of contents at the begigning is available to help you navigate through this.

## Data story
4 main data stories are presented on `data_story/index.html`. If you wanted to know the deepest secret hidden behind avocadoes, cigarettes, coffee and wheats, we invite you to have a look at it!
You can also directly see the website on the following link : jdsalomon.github.io/index

# Exploring agriculture trends to highlight global phenomena

# Abstract
People are questioning more and more their eating habits, regarding ethical, ecological or health issues. Due to misinformation, many people have preconceived notions about those issues and how to be responsible consumers. The difficulty of knowing the actual story behind what goes in your plate is the topic that interests us. We ask ourselves: where does our food come from,  how was it produced?
Using datasets containing insights about food production and trade in the world, we will explore this topic. We will try to find the major actors in terms of agricultural products and countries to understand how trades and production are done nowadays and see what the current trends are and analyse the disparities we might observe.

# Research questions
- What are the most prominent agricultural products in the world, either in terms of quantity or gross profits?
- Is there a balance between countries and their importation and exportation of agricultural products?
- What is the evolution of the global agricultural production throughout time?
- What are the agricultural effects on a country that is a major exporter?

# Dataset
Our main source of data comes from `FAOSTAT` dataset from the United Nation website. It shows production, land use and other information around treatment of goods. We might later complement our dataset with additional data showing trade statistics, also on the United Nation website (`Commodity Trade Statistics` dataset).

# A list of internal objectives up until project milestone 2
- Download and clean the dataset from the FAO Stats (Data wrangling).
- Group some agricultural products in categories (cereals, fruits and vegetables…).
- Analyse products on two different dimensions: products-centered versus country-centered in order to find major actors in the current state of agricultural production.
- Compare these observations throughout time. Check modern ways to handle time series data.
- Find a good way to visualize all this information on the three following dimensions: geographic coordinates, time and goods.

# Obsevation through milestone 2
All objectives were reached, except the timeseries representation. We decided to keep a product-centered point of view, because we developped a sophisticated method that can plot several statistics on a folium map.

# Milestone 3
We went mainly through deep analysis on the four following stories: avocadoes, cigarettes, coffee and wheats. Our folium method was greatly enhanced. Here are how we split the overall work:
- Justine: Focused on the coffee data story and some finalizations on merging different dataframe, such as population statistics, production, trades and item regroupment of food.
- Julien: Handled the tobacco data story. Linked crops to trades on the dataframe (stemmer technique). Was in charge of the template of the website. Developped interactive plots with plotLy.
- Nils: Went through the wheat and avocado stories. Also focused on cleaning the dataset. Will take the presentation in charge.
- David: Developped the folium maps. Helped through the cleaning phase. Was in charge of global vizualisation. Peer-reviewed each data stories and merge them in a consistent manner.
