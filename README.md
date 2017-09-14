# README

# User stories

# Database (DB)
## ERD (Entity Relationship Diagram)
![erd database](/docs/images/erd.png)


# DB Tables
I made 3 tables for my app, User, Tweet and Profile. User stores the user information like password etc. Tweet stores
 the informatrion message that a user tweets and the Profile table stores information about the user.
 
## User
- email
- password
 
## Profile
- avatar
- first_name
- last_name
- country
- user_id (belongs_to)
 
## Tweet
- message
- user_id (belongs_to)

# Figma


# pages
## homepage
- tweets on page
- login / logout

## tweets show page
- see tweet
- edit tweet (if logged in)

## profile page
- first_name, last_name
- tweet_count
- country
- edit ability 