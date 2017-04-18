# Day 2: Merge Conflicts

### What we did in class today:
- We worked in the same repository as Day 1
- We went through how to make changes to the branches
- We merged!, ending in glorious merges and a reveal of the final project. :sparkles:
- We introduced the concept of merge conflicts:
  - Why merge conflicts happen
  - How Git handles merge conflicts
  - How we (the humans) handle merge conflicts
- Synchronously, we partnered up and created our own merge conflict   

### Day 2 Partner Activity

#### Resolve the rest of the merge conflicts
- We've set up some open pull requests with merge conflicts for you :open_mouth:
  - _Every person_ has their own repository. Even though you're working with a partner, each person should fix the merge conflicts
  - We won't make you turn in your homework, but we will run a script to see if the activities are completed later.
- Work with your partner to resolve the merge conflicts in the conflicts repository.
  - Don't remember the steps from class? No worries. As a general rule of thumb, here is a starting point:
  - Working locally, merge `master` into the feature branch.
  - When you see there's a conflict, that's OK! Type `git status` to verify which file has the conflict.
  - Open that file in your text editor, and look for the merge conflict markers. (`<<<<<<<`, `=======`, `>>>>>>>`)
  - Both branches' versions of code are present - pick which one you want to keep, and save the changes.
  - Add and commit the saved changes to resolve the merge conflict.
  - Push the feature branch up to the remote, and see the resolution in the pull request.
