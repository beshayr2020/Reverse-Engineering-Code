# Reverse-Engineering-Code
code Explanation Document [https://docs.google.com/document/d/1K7AQXr73mvvYvEvVjTFopnyNS4_LARjN6UqmU6xQGfI/edit]

PASSWORD AUTHENTICATION

This app allows users to create an account, log into the account and sign back out securely. All user data is stored in a mysql
database.

USER STORY

as someone who wants to safely log in to "X", I want to know my personal details are safely stored so that I don't have to worry
about using "X".

TECH USED 

    BCRYPTJS
    EXPRESS
    EXPRESS-SESSION
    MYSQL2
    PASSPORT
    PASSPORT-LOCAL
    SEQUELIZE

GETTING STARTED

To begin using this app, please clone this repository into your local storage. Once this is complete, please follow these steps;

create a mysql db called "passport_demo"
go into the config file, open config.js and insert your personal data ie username, password etc
open terminal in current repo and run "npm i" to install all node packages
while in terminal, run "node server.js" and you will successfully connect to server
open browser and put "http://localhost:8080" in search bar

