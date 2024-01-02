# Simple_Twitter_with_Python

Today, we're going to fix the major malfunction with social media - other people and their stupid opinions- and create a Twitter for one!

Your program should.

1. Display a menu - Add or View tweets.
2. 'Add' should :
    i.  Get the tweet input.
    ii. Store it to the database with the current timestamp as the key value.
3. 'View' should :
    i.   Show the tweets in reverse chronological order.
    ii.  Show 10 tweets at a time.
    iii. Prompt the user to show another 10 tweets (yes or no).
4. A 'no' choice goes back to the menu.

Timestamp Code -
timestamp = datetime.datetime.now()
