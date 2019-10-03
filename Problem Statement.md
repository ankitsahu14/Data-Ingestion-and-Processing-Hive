# Data-Ingestion-and-Processing-Hive

Analysis-I
1.	Compare the overall average fare per trip for November and December.
2.	Explore the ‘number of passengers per trip’ - how many trips are made by each level of ‘Passenger_count’? Do most people travel solo or with other people?
3.	Which is the most preferred mode of payment?
4.	What is the average tip paid per trip? Compare the average tip with the 25th, 50th and 75th percentiles and comment whether the ‘average tip’ is a representative statistic (of the central tendency) of ‘tip amount paid’. Hint: You may use percentile_approx(DOUBLE col, p): Returns an approximate pth percentile of a numeric column (including floating point types) in the group.
5.	Explore the ‘Extra’ (charge) variable - what fraction of total trips have an extra charge is levied?

Analysis-II
1.	What is the correlation between the number of passengers on any given trip, and the tip paid per trip? Do multiple travellers tip more compared to solo travellers? Hint: Use CORR(Col_1, Col_2)
2.	Segregate the data into five segments of ‘tip paid’: [0-5), [5-10), [10-15) , [15-20) and >=20. Calculate the percentage share of each bucket (i.e. the fraction of trips falling in each bucket).
3.	Which month has a greater average ‘speed’ - November or December? Note that the variable ‘speed’ will have to be derived from other metrics. Hint: You have columns for distance and time.
4.	Analyse the average speed of the most happening days of the year, i.e. 31st December (New year’s eve) and 25th December (Christmas) and compare it with the overall average. 

