# Soft-Drink-Pricing-Analytics
A soft drink company,kiwi, wants to launch kiwi bubble to compete with competitor's product, mango bubble. The project is to do pricing analysis to help with pricing decisions using consumer loyalty card data in the test market.  <br>

In this project, we built multinomial logit models both without and with segmentation. We found that with segmentation, we could achieve maximum profit with higher profit-maximization price.  <br>

However, underlying purchase pattern and different customer preference for soft dirnk should not be ignored. So in the 'with segmentation' part, we first utilized machine learning model(K-means) to perform customer segmentation based on demographics data, then implemented multinomial logit model separately for each segment of consumers to build heterogenous pricing strategies in order to maximize the profit.In the segmentation part, we also compared between situations with KB and without KB to test whether the company should launch kiwi bubble or not. We found that launching Kiwi bullble is a wise strategy which will get Kiwi higher profit and greater market share.
Lastly, we deeply studied competitor responses and calculated the equilibrium price under Nash equilibrium in price war.
