# Read_me
A project I made for a job interview

There are 5 files inside the main branch.

The goal of this project was to create a score that ranked movies based on multiple variables, which I listed below. 

The first .csv 'top_100_films' is the test set which contains the actual rating displayed on the website.

The second .csv 'top_200_films' is the training set which contains the database I worked with. There are 200 films and variables concerning them : 
a unique ID, 
the title of the movie, 
the release date,
rating : the average rating on the site based on their formula (which ignores bot accounts) 
wish_list_count : the number of users that put the movie in their wish list 
review_count : the number of reviews for the movie 
list_count : number of users that put the movie in a list 
n_i : number of users who gave the rating i (n_3 refers to the number of people who rated the movie 3/10)

'sc_films' is the .csv which contains the predictions for the project (was asked by the company for this to be the final outcome). 
You can also find 2 python files inside the main branch. The main one is called 'activite_conviviale', it's a jupyter Notebook that you can execute fully based on 2 conditions. The first condition is to have the training set located in the same file as 'activite_conviviale' is also located  (obviously). The second condition is to also have the 'functions_ACP.py' in the same file also.

Inside the last file, you can find some function relative to an ACP analysis. Some of them are already in others packages, but it was a preference of mine to code them properly, you can open it and scroll to explore.

Please feel free to contact me if you have any suggestions on how to improve it.

Thanks

Victor B.
