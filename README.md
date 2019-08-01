# Battle of neighborhoods
Final project for IBM's **Applied Data Science Sapstone** course on Coursera.  

Since it's a project that is supposed to last few weeks, here we'll try to answer a simple question, using **Foursquare API** :https://fr.foursquare.com/.  
We'll use **Paris' Velib dataset** : https://opendata.paris.fr/explore/dataset/velib-disponibilite-en-temps-reel/information/  

Velib is a simple service that started about a decade ago, the department deploy a bunch of bicycle racks in different area of the city and populate them with special bikes that are freed when we pass our card or subscription code into the terminal situated nearby.  
We can then use it for "free" during 30 minutes or longer but with additionnal fees. The course end when we put the bike back in another rack.  
The subscription costs about 40€ to 100€ a year.  
As it is the case for many French governmental services, it is not profitable and effectively lose our precious tax money.  

If velib is still relevant today compared to the scooter model like Lemon that doesn't require racks, is most probably because it's very cheap (90% of the course made are withing the first 30 minutes, so it just cost about 40€ to 100€ a year instead of about 2€ the course for Lemon), raising the price would only be detrimental.  
So instead we'll try to define the most and least popular areas, find out what are the attributes that makes them end up in one or the other category and conclude to a strategy so the mayor can cut some cost or attract more users and generally make a better use of our valuable tax money.  

