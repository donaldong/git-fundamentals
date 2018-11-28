# Question
We can create a new branch `iss53` by
- [x] `git branch iss53`
- [ ] `git checkout iss53`
- [x] `git checkout -b iss53`

# Explanation
`git branch` is the "standard" command to create a branch. However, this does not explicitly switch our current branch to the one we just created. To then switch to the branch we just created, we can use `git checkout`. Conversely, using `git checkout -b` will create the branch if it does not exist (akin to calling `git branch` first).
