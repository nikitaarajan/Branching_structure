# Branching_structure

## Main Branch
* This repository is created to review and test the branching structure
* The main branch is the gold-standard branch which will have clean and runnable code. 
* Any changes/ updates to the main branch will come from pseudo_main/ Release branches

## Pseudo_main/Release Branches

* A release branch is created from the main branch for every checkpoint in the project.
* No multiple release branches are allowed to be created simultaneously. A new release branch is created only after the current release branch has been merged to the main branch.
* The release branches are the point of contact between main branch and the dev branch.


## Dev Branch

* The Dev branch is the place for continuous integration (CI). 
* Any and every modifications performed by the researchers will be committed to Dev branch alone. 
* Once the code in dev is ready for release, it is merged to the lastest release branch. 

## <researcher_name> function Branch

* These are sub branches/ the lowest level of branch created for independent work.
* The researcher has full flexibility in making modifications to this branch. 
* Best Practice: Keep this branch upto date with the Dev branch. 
* Any merge should be done only to the Dev branch and every merge should be performed after the pull request is reviewed by other members. 

