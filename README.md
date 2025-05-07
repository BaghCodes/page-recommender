Page Recommender

This is a straightforward Python script that suggests new pages to a user based on what others with similar interests have liked. It works off a JSON file that contains user-page data.

Files

data.json: Sample data with users and their liked pages.

recommender.py: Main script that processes the data and generates suggestions.

How it works

Each user has a list of pages they've liked.

The script compares the current user’s liked pages with those of other users.

It identifies pages that similar users liked but the current user hasn’t.

Pages are scored based on how many liked pages the users share.

Running the script

Make sure Python is installed, then open a terminal and run:

python recommender.py

To test with a different user, just update the user_id value in the script.

Output

You'll get a list of recommended page IDs and their scores. The higher the score, the stronger the recommendation.

Example output:

[(7, 2), (15, 1), (29, 1)]

Notes

This is a minimal, working version of a recommender—easy to tweak and expand.

You can build on it by refining the scoring logic or adding real-time data.

Works best when there's overlap in user interests.

