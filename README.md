This script is written in ruby and should make use of your system ruby.

Install this file into a folder in your path (e.g. /usr/bin), then it will
be available as a git command:

    git cycle-time

This will produce a table output of the last 20 merge commits into the current
branch, with stats on the age in days of how long commits took to be merged.

This is useful in measuring how long it takes code to reach your mainline or
release branch.
