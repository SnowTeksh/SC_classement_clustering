# Read_me
a little project for a job interview

There are 5 files inside the main branch.

The goal of this project was to create a score that ranked movies based on multiple variables that I listed below. 

The first .csv 'top_100_films' is the test set. Containing the actual rating on the site.

The second .csv 'top_200_films' is the training set. It contains the database I worked with, there are 200 films and variables concerning them :
An unique ID 
The title of the movie 
The release date
rating : the average rating on the site based on their formula (that ignores bot account)
wish_list_count : the number of users that put the movie ont their wish list
review_count : the numbers of review for the movie
list_count : numbers of users that put the movie in a list
n_i : numbers of users that gave the grade i (n_3 is corresponding to the number of people that put 3/10 for the movie)

The 'sc_films' is the file containing the predictions for the project (was asked by the company as the final outcome).

You can find 2 python files inside the main branch as well. The main one is called 'activite_conviviale', it's a jupyter Notebook that you can execute fully based on 2 conditions.
The first condition is to have the training set located where 'activite_conviviale' is also (obviously). The second condition is to have the 'functions_ACP.py' in the same file also. You can find inside the last one some function relative to an ACP analysis. Some of them are already in others packages, but it was a preference of myself to code them properly, you can open it and scroll to explore.

Please feel free to contact me if you have any suggestions to improve it.

Thanks

Victor B.
