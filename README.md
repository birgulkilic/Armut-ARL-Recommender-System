# Armut-ARL-Recommender-System
![image](https://github.com/user-attachments/assets/8819e776-2271-440f-b8b2-26e7ae382de7)

📊 What is Association Rule Learning (ARL)?

Association Rule Learning is a machine learning method that finds patterns in data. The Apriori Algorithm helps discover which items are often bought together.

🔹 Support → How often X and Y appear together.

Support(X, Y) = Freq(X, Y) / Total Transaction

🔹 Confidence → The chance of buying Y if X is bought.

Confidence(X, Y) = Freq(X, Y) / Freq(X)

🔹 Lift → How much X increases the chance of buying Y.

Lift = Support(X, Y) / (Support(X) * Support(Y))

These metrics help in sales, marketing, and recommendation systems. 🚀

Bussines Problem
--- Armut, Turkey's largest online service platform, brings together service providers and those who want to receive service. It provides easy access to services such as cleaning, modification and transportation with a few touches on your computer or smart phone.

It is desired to create a product recommendation system with Association Rule Learning by using the data set containing the services and categories that the users have purchased.

Dataset Story
The data set consists of the services customers receive and the categories of these services. It contains the date and time information of each service received.

1- UserId : Customer Id

2- ServiceId : They are anonymized services belonging to each category. (Example: Upholstery washing service under cleaning) A ServiceId can be foundunder different categories and refers to different services under different categories. (Example: Furniture assembly with CategoryId 2 ServiceId 4 during service core cleaning with CategoryId 7 ServiceId 4)

3- CategoryId : They are anonymized categories. (Example: Cleaning, shipping, as follows)

4- CreateDate : The date the service was purchased
