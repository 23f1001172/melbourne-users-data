# GitHub Developer Analysis - Melbourne
# GitHub Developer Analysis - Melbourne 100

##Project Overview
- This repository contains data about GitHub users in Melbourne with over 100 followers and their repositories.
- Analyzing the data revealed that a surprising number of developers don't use wikis or project boards on their repositories.
- Developers should consider utilizing wikis and project boards more effectively to improve project collaboration and documentation.

## Files

1. `users.csv`: Contains information about 337 GitHub users in Melbourne with over 100 followers
2. `repositories.csv`: Contains information about 29202 public repositories from these users
3. `gitscrap.py`: Python script used to collect this data
4. '*que*.py': Contains the code used to answer the question

## Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-28
- Only included users with 100+ followers
- Up to 500 most recently pushed repositories per user

## Process

1. Start → GitHub API Request: The process starts with a request to the GitHub API.
2. GitHub API Request → Query Users in Melbourne with >100 Followers: It queries users based on city and follower count.
