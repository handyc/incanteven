"Hello, World!"

Documentation is also code, and you can run this just by reading it:

#echo $(realpath "$0") "$0"; sleep 1; eval ./"$0"
echo $(realpath "$0") "$0"; sleep 1; eval ./"$0"
incant README.md

1

2

3

4
5
6
Functions are invoked by their names if known:
Know that there is a library for math --
Add 2 and 2 and show the result,
Add four to that.
Statements not otherwise parseable are considered commentary

to be continued ...
