## This is my activity in database 2 and the important codes/snippets are the following: Install package dotenv to use .env```jsnpm install --save dotenv```Add this in the beginning of your js file```jsrequire('dotenv').config()const {Pool} = require('pg')```## In case of error, here are the steps that you need to consider:1. Remove backticks in port ='${process.env.PORT}'2. Change all the double quote into a single quote