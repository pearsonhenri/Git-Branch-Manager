# Git Branch Manager

USAGE:
Use this handy-dandy script to view a set of git branches in your current repo, filtered either by the "n" most recent branches or by grepping for a keyword, with restriction terms passed as a variable.

Examples:
$./gb -> Prints last 5 branches you committed to in order of commit time
$./gb 10 -> Prints last 10 branches you committed to in order of commit time
$./gb foo -> Prints all branches that are returned from grepping "foo" on your local branches
