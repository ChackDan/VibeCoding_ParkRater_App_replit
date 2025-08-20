# VibeCoding_ParkRater_App_replit
Created a sample app - Rating US national parks 

Started with a simple prompt 
Help me build an interactive app for voting and ranking the best national parks
 - The app should allow users to vote on parks head to head , then calculate a ranking for parks based on chess ELO system.
 - The app should prominently display the matchup along with the overall rankings and recent votes
 - Use the data (name , image etc ) from the table of the 63 national parks on this site https://en.wikipedia.org/wiki/List_of_national_parks_of_the_United_States
  -for the web app use my mockup for a start
<img width="431" height="273" alt="image" src="https://github.com/user-attachments/assets/60d38dd7-7217-4bcf-b019-5c4124efec98" />


Refined, tested and gave teh Agent more specific instructions to fix

Added a postgress DB for persistance. Had to be extra explict to get rid of hard coded data
"Make the parks data and voting data persistant, Suggest use a postgress database. You should analyze the strcuture of the data and create a schema for rapid import. Do not use any hard coded parks data in code. Be sure to check the data types and perform all necessary migrations"

All up it took 45 minutes -- Did not deploy to prodcution...

I am see why folks like replit
