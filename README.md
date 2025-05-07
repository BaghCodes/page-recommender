# Page Recommender

This is a straightforward Python script that suggests new pages to a user based on what others with similar interests have liked. It works off a JSON file that contains user-page data.

## Files

- `data.json`: Sample data with users and their liked pages.
- `recommender.py`: Main script that processes the data and generates suggestions.

## How it works

- Each user has a list of pages they've liked.
- The script compares the current user’s liked pages with those of other users.
- It identifies pages that similar users liked but the current user hasn’t.
- Pages are scored based on how many liked pages the users share.

## Running the script

Make sure Python is installed, then open a terminal and run:

```bash
python recommender.py
