##### computation occurs here
date; echo "$0"; cat "$0"; echo $(realpath "$0"); sleep 1; eval ./"$0"
###### more computation .... [] # moving the eval to the end becomes dangerous
##### end computation block
#### Documentation is also code, and you can run this just by reading it:
```
git clone https://github.com/handyc/incanteven \
chmod 700 incanteven/README.md; incanteven/README.md
```
#### echo $(realpath "$0") "$0"; sleep 1; eval ./"$0"
##### 1documentation occurs here
###### more documentation .... []
###### more documentation .... []
###### more documentation .... []
###### more documentation .... []
###### more documentation .... []
#### Code is documentation and can go anywhere; code and output are distinct:
echo $0 # output will appear at the bottom if code executes anywhere
#### Statements not otherwise parseable are considered commentary
####
#### to be continued ...
