# Cryptocurrencies

This project is to provide insight to Accountability Accounting, an investment bank.  The results are to assist in the decision making of offering Cryptocurrency investment to customers.  
<br>
This analysis creates a report on cryptocurrencies that are actively trading on the market.  They were grouped in clusters to create a class report for this invesment proposal.
<br>
Since the data is so large and there are unknown outputs; unsupervised machine learning models was used to group cryptocurrencies for clustering algorithms.  The below images show the findings. 
<br>
<br>
The data was standardized to avoid skewing of results,  The PCA statistical technique was used to reduce the dimensions to 3 components, specifically on the cryptocurrency algorithm and type.  <br>

![crypto_pca](https://user-images.githubusercontent.com/75437852/116322189-82b21880-a789-11eb-8610-f063006a9503.PNG)<br>
<br>
After compiling the components, the array was used to create the Elbow curve.  This identifies that the data has 4 KMeans clusters.<br>

![bokeh_plot](https://user-images.githubusercontent.com/75437852/116323036-39fb5f00-a78b-11eb-8d19-6c44ba15dc16.png)<br>
<br>
The 3D graph was created to visualize the 4 KMeans clusters.<br>

* One outlier principal component for Class 2
* Class 1 group is the lowest principal component; the lowest tradable cryptocurrency.
* Class 0 group is the mediocre principal component; an average tradable cryptocurrency.
* Class 3 group is the highest principal component; the higher tradable cryptocurrency. <br>

![3D](https://user-images.githubusercontent.com/75437852/116323544-387e6680-a78c-11eb-82b5-9e9361e87000.PNG)<br>
<br>
A table was also created with the tradable cryptocurrency information and can be sorted based on performance.<br>

![traders_table](https://user-images.githubusercontent.com/75437852/116329623-c14fcf00-a799-11eb-8947-54c883df527a.PNG)<br>
<br>
Last a scatter plot shows relation of total coins in circulation (Total Coin Supply) and coins earned (Total Coins Mined).<br>

![bokeh_plot (1)](https://user-images.githubusercontent.com/75437852/116329164-afb9f780-a798-11eb-9757-322d0bbd82b8.png)


