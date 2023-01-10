# LAB - Capital Finder
# Author: Matthew Gebhart
## Date: 1/9/2023

## Overview:
Deploy a serverless function to the cloud.
- use requests library to interact with REST countries API

## Feature Tasks
Serverless function handles two kinds of queries
- a GET request with a given country name that responds with the capital of that country. 
  - accessed at the following link (replace "{query}" with your country to search)
  - https://capital-finder-matthewgebhart.vercel.app/api/capital_finder?country={query}
- a GET request with a given capital name that responds with the corresponding country 
  - accessed at the following link (replace "{query}" with your capital to search)
  - https://capital-finder-matthewgebhart.vercel.app/api/capital_finder?capital={query}