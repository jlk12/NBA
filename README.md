# NBA

# Load Libraries
library(tidyverse)

#Load CSV
NBA <- read_csv("~/Downloads/NBA_train.csv")
str(NBA)

#How Many Games Does A Team Need To Win In Order To Make The Playoffs?
table(NBA$W, NBA$Playoffs)
#After 45 games, teams almost always make the playoffs. 
