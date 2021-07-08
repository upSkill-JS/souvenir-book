## Important Note

This is an embedded git repository. There is 2 level git tracking one at the root project level and another at the client folder.

The embedded git at client folder is tracking the frontend (client) development.

### Whole project tracking is done via **Manual, brute force method** .

 Here my goal was just to archive a bunch of git repos inside a bigger parent repo. 
 So the simplest brute-force solution is to just rename all nested .git folders to anything else--ex: to ..git. Now, git add -A will add them all just like any other normal folder inside the parent git project, and we can git commit everything inside the parent repo easily.