#                         Python_API_Challenge_6



##    Using api keys to access information from weather and geological locations 

  In Weather.py we generated a randomn list of cities using the citipy library.We used weathermap api to get weather related data on the cities that were generated. We then created plots showing the the relationships if any between the weather variables and Latitude for humidity, temperature, cloudiness and wind. We then created linear regression plots on the same variables and made observations regarding them.
  In the vacation.py we imported a csv file from citipy to plot a map with every city in our dataframe with a plot point whose size is relative to the humidity of that city. We then filtered our dataframe to cities with our ideal weather. Using the new dataframe we created another to find hotels within a 10000 raduis in those cities with the geoapify api. Then used hvplot to display the hotels on a map with points that would show the city and hotel name when cursor was over it. For me it didnt exactly worked well but was pretty cool anyway.
  Much appreciation to teaching staff and tutors for giving guidence and support along with scouring the internet to for helping me achieve this.
 
