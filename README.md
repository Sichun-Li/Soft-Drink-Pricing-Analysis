# Soft Drink Pricing Analytics
A soft drink company,kiwi, wants to launch kiwi bubble to compete with competitor's product, mango bubble. The project is to do pricing analysis to help with pricing decisions using consumer loyalty card data in the test market.  <br>

Tool: R

In this project, we built multinomial logit models both without and with segmentation. We found that with segmentation, we could achieve maximum profit with higher profit-maximization price. However, underlying purchase pattern and different customer preference for soft dirnk should not be ignored. So then we did the 'with segmentation' part to build heterogenous pricing strategies in order to maximize the profit. keywords of the process of 'with segmentation' part are as follows.
* cluster modeling (K-means) and customer segmentation using customer demographic data  <br>
* multinomial logit modeling for each customer segment; own- and cross-price elasticities calculation to explore customer preference and any substitution pattern  <br>
* dynamic and competitive pricing analysis under “pricing war” considering competitor responses and cannibalization  <br>

Outcome: launching Kiwi bubble is a wise strategy which will get Kiwi higher profit and greater market share. The equilibrium price for kiwi bubble under Nash equilibrium in price war is $0.98.
