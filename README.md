# text-to-query-benchmark
Data and queries to benchmark text-to-sql and text-to-javascript.

Ideas: 
Movies of wich actors are rented most.
Give me the anaual revenue auf movie XYZ.
Give a table with the mean number of custumers and mean revenue per week day.
Has the customer 'XYZ' brought back all movies?
Give me the phone number of costumer 'CCC'.
I need to replace all movies dont given back. How much does it costs.
Wich manager is responsible for wich store.
Give me a table containing number of rentals and total revenue for each year and each country costumer lives.
wich staff members belong to wich store.

Best selling film for ever film category.


Extra:

1: How many customers live in Japan.
2: Wich is the most expensive film.
3: I will see if the is a correlation between number of rental of a film and the length of a film. Round the length of film by 10 minutes and give me the number of rentals of the rounded film duration.
4: How many rentals in % belong to films of category Drama or Action?
5: Give me a list of all films with rating: NC-17

 
 Extra 2

 6: How many films returned at 2005-06-15.
 7: Which customer brought in the most revenue?
 8: Is there a movie with duration longer: 3 hours?
 9: How many films with a PG rating were rented out in 2006?
 10: Was ist die mittlere Ausleihdauer für die Filme?

 Extra 3

 11 Wie groß ist der Prozentsatz an Filmen, der am nächsten Tag zurückgebracht wurde?
 What is the percentage of films that were returned the next day?

 12 Welcher Film wurde am spätesten zurückgegeben?
 Which film was returned the latest?
 
 13 Geben die Leute Ihre Filme eher vor 12 Uhr oder nach 12 Uhr zurück?
 Do people tend to return your films before 12 o'clock or after 12 o'clock?

 14 Wann wurde der 1. Film ausgeliehen?
When was the first film rented out?

 15 Welche 5 Filme wurden im Mittel am längsten angeschaut?
Which 5 films were rented for the longest time on average?

 Extra 4

16: Give me all films containing Behind the Scenes in special features.
17: Is there a documentary about an agent?
18: How often films with OPRAH KILMER ar rented in July 2005?
19: Give me list of all costumers in Japan. The List should also contain the total revenue of the costumer.
20: Wich staff memeber is responsible for the lagest revenue? 

 Extra 5
21: I need a table with all managers an their assiciated staff members.
22: Give me the top five cities from customer address in regard to revenue.
23: What is the total revenue of film: SATURDAY LAMBS.
24: Which customers rented film: JEEPERS WEDDING
25: In wich cities we have customers?


Problems json:

* Address: Telefon empty.
* Rental: filmId instead inventoryId