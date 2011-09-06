<!SLIDE center transition=fade>

# OOPS #

![oops](oops.jpg "Wait, what?")

<!SLIDE smbullets incremental transition=cover>

## Mistake Prevention ##

* Always merge any changes with master branch
* Be cautious when merging

<!SLIDE smbullets incremental transition=uncover>

## Using Caution while Merging: ##

* Do _not_ merge with uncommited changes
* Use "safety flags" when merging

<!SLIDE transition=cover>

## To merge changes from master safely ##

    $ git checkout master
    $ git pull origin master
    $ git checkout your-topic-branch
    $ git merge master --no-commit --no-ff
