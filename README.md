
# - Intro

I love the oodles of information recieved from user analytics in games, it's fasciniating to see decisions 
made by other people and discover trends as the userbase interacts with a game/world in ways that are often unexpected. 
[https://www.pcgamesn.com/baldurs-gate-3/character-creator]

The purpose of this project is to break down a mass of information into easy to digest pieces that can be gleemed for helpful insight as to what the userbase is doing and what they're willing to spend money on. 

# - Data Set 
['purchase_data.csv']

The data set was a .csv file showing who purchased what item(s) and for how much, alongside the gender of the purchser. The data set was quite small as it serves as a stepping stone for the development of skills in a learning setting, but having limited data negatively impacts conclusions and visible trends.

# -  Method

The method accompilished by using Jupyter Notebook to create separate databases by examining and grouping data based on relevance to reveal information on what certain age groups, genders, ect. are willing to spend money for in-game purchases.

# - Analysis

The data set was great for displaying this simple
information but it doesn't include the purpose of the items.

Cosmetics are popular choices for games to use as a means of generating income on a product
that has already been developed. Why make new character after new character when some cosmetics will let user amp up a character they love? It will also allow the dev team(s) to fine tune aspects for a patch or develop new characters with less pressure to pump out content.

Knowing the item purpose could also help in understanding why the customers are purchasing a
specific item. If the item offers stat boosts it should meet certain requirements to prevent "OP"status, unless it's planned instance to cause a buying surge of the "New Broken One-Use Item" before its shut down or balanced. On the other hand, if the item offers no game influence and is purely cosmetic, it's nice to know so that the market for trends in pop-culture can be capitalized on before change happens and sales opportunity is missed, and the most focus can be placed in things that the userbase wants in terms of cosmetics.

### - Purchasing Analytics

Another reason to understand what the items offer leads to offering packages for purchasing an in-game currency. If we take a look at the psychology behind market and sizes e.g. movie theatre popcorn, there are usually three options: 

    || Small = $3 @ 8oz ($2.6/oz) | Med = $5 @ 10oz ($2/oz) | Large = $9 @ 20oz ($2.2/oz)|| 

You get less per ounce for Large but it looks like so much more to the customer. Sure they don't need the extra popcorn but its such a great deal.

A brief insight on pricing, I noticed that the items had an average price when comparing values in both "Purchasing Analysis" Data frames. This leads me to think that the game market is utilizng a price gouging technique that raises prices based on demand which may lead to issues in the userbase as people discover the more that they purchase thism the more they pay. They're still getting the same item, why increase the price without increasing the amount delivered? This method of pricing items could actually deter individuals from spending money. Selling is all about managing expectations and increasing the percieved value of a product so that the customer is happy to spend the money, ending in a win-win.

### - Gender Demographics
Males make up 84% of the userbase but have a smaller per-person spending average when compared to Women & Non-Disclosed gender type. If we discover why women are spending more and make the game more appealing to women then there could be a chance to increase the userbase and also the revenue of the game.

Finding out why a certain gender spends more could lead to understanding of user behaviors separate from gender, the ability to take advantage of a person's lack of patience or desire for reward/gratification. Example: Clash of Clans allowing players to use an ingame currency to speed along things that would otherwise be free if they just waited.

### - Age Demographics

The age ranges of 15-29 make up 76% of the user base with the highest percentage of players being in their mid-early twenties. This tidbit if information can be capitalized upon by understanding trends in the pop culture of those in that generation and playing towards them without going too crazy, or including quests, themes, challenges that fit the intellect of an adult so that the game is a mix of challenging and enjoyable.

# - Conclusion

I learned much about grouping and filtering similar data for analyis along side how to format for ease in readability. Being able to quickly assemble data after cutting out whats needed using bins & labels, or through filtering using conditionals, or locating information series based on their name, I came to realize first-hand just how powerful Pandas can be.
