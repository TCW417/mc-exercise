# What went wrong

Initially, all members of the group were at the same starting point. All was good.

The issue came into play when some members of the group updated the code.
Their code was reviewed, approved, and pushed to the master copy.

However, not all members of the group pulled this master onto their local machine and instead continued working on their own respective branches, creating various merge issues when an ACP was attempted by both sub teams later in the day. They also did not merge the changes to master into their branch before ACP'ing their branch. It seems that merging changes to master with one's feature branch is necessary to avoid problems down the line when pushing one's feature branch up, creating a PR, and then merging with master again. Otherwise, the branch might overwrite elements in the master branch.

# How this problem is solved

To solve this issue, all members of the group must align their local coding with the master copy before they can push their local code. This requires communication between the team members whenever master is to be updated, and before a pull request is created. 

# What we have learned from this

Our intent is to make it known when a change is made to master. At this point, we will send a group message regarding the update to the master, and all individuals should merge the master into their current branch. Their local changes should not be lost, but they should then have the most current updates. The biggest takeaway from today's lab was that merging to master can create a ripple effect of problems throughout an entire team's code if done incorrectly, and that it should be treated as a group event that requires strict attention from every member of the cohort. 
