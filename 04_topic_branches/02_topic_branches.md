<!SLIDE smbullets incremental transition=uncover>

## Good branch names: ##

* remove-name-constraint
* fix-email-validation
* new-responses
* change-uniqueness-rules-of-job

<!SLIDE smbullets incremental transition=cover>

## Bad branch names: ##

* fix
* bob
* new
* old
* fix-some-stuff

<!SLIDE transition=uncover>

## To create a branch locally based on master ##

    $ git checkout master
    $ git checkout -b name_of_new_topic_branch

<!SLIDE center transition=cover>

# Branch Pruning #

![branchpruning](branch_pruning.jpg "Pruning Branches")

<!SLIDE smbullets incremental transition=cover>

## Clean up old/unused branches ##

* If the branch has been merged already
* If there are no branches from it
* If the fix/feature is no longer relevant/needed

<!SLIDE transition=uncover>

## To delete a local merged branch: ##

    $ git branch -d name_of_branch_to_delete

## To delete a local NON-merged branch: ##

    $ git branch -D name_of_branch_to_delete

<!SLIDE transition=cover>

## To delete a remote branch on Github ##

    $ git push origin :name_of_branch_to_delete
