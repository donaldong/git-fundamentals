# Question
You made some changes to `perfection.cpp`, then you realize the changes are
unnecessary. How to discard the changes you made?
- [ ] `git reset HEAD perfection.cpp`
- [ ] `git revert HEAD perfection.cpp`
- [x] `git checkout HEAD perfection.cpp`

# Explanation
`git checkout HEAD perfection.cpp` checks out the copy at HEAD. also `git checkout -- perfection.cpp`.
`git reset HEAD perfection.cpp` unstages perfection, but doesn't remove the changes from the file
`git revert HEAD perfection.cpp` would be used to revert the changes if they had already been committed, but appears to be invalid syntax