EasyRedditGiveaway
==================

HTML + JS page to manage a giveaway f.e. RandomActsOfGaming.
Copy in the url to your reddit post and press Go!

Uses the Reddit API (http://www.reddit.com/dev/api) to load all comments, and checks every user for age, link karma, and comment karma.
Additionally checks if a link to a Steam account is in the comment.

Only checks the first level comments.

ToDo
==================

* Options (Rules)
* Documentation and Cleanup

Uses
==================
* jQuery
* Boostrap
* Font Awesome
* handlebars JS

Issues
==================
* Why are the users loaded so slow?
The API access rules states "Make no more than thirty requests per minute.", so we load a user only every 2 seconds.
