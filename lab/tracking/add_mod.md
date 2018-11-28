# Question
In a git repository, file `algo.txt` is tracked and unmodified.
Then we do
```
echo "dijkstra" >> algo.txt
git add algo.txt
```

What will happen?
- [x] Git creates a new blob 
- [x] Git updates the index file
- [ ] Git updates the current working tree

# Explanation
The blob contains a compressed copy of the data.  the index keeps track of what is different between the blob and the most recent commits.  The tree will not be updated until it is commited.
