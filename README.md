# USA_CAR_SELLING_PRICE
# Deployment Link :https://carsellingprice.herokuapp.com/
This model is made on Linear-Regression model. In this data we have columns like Transmission ,Selling Price ,Present price etc in which we have to predictg selling price . 
After checking the distribution, i observed that i does not follow normal distribution so i removed some outiers from in it and after that i applied log normal disrtribution on numerical data .
On the categorical data i applied one-hot-encoding . 
After all the steps i scaled the data by standard normal distribution 
Now it's time to dividing the data in trainig set and testing set.
I used the linear regression model and it gives me around 77 and 78 percent accuracy in that. 
i used flask to make my model.
