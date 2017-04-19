# Day 2: Merge Conflicts

### In Class Activities:

#### Finish Workflow
- Work in the same repository as Day 1, "caption this"
- We opened pull requests yesterday; Today we make more changes to the same branches
- Merging, ending in glorious merges and a reveal of the final project. :sparkles:

#### Merge Conflicts
- Introduced the concept of merge conflicts:
  - Why merge conflicts happen
  - How Git handles merge conflicts
  - How we (the humans) handle merge conflicts
- Synchronously, we partner up and created merge conflicts  

### After Class Activities:

#### Resolve the rest of the merge conflicts
- We've set up some open pull requests with merge conflicts for you :open_mouth:
  - _Every person_ has their own repository. Each person should fix the merge conflicts in their own repo. It wil be called `github.com/githubschool/conflict-practice-username`, with username being your actual username.
  - We won't make you turn in your homework, but we will run a script to see if the activities are completed later. :wink:
- Work to resolve the merge conflicts in the conflicts repository.
  - Don't remember the steps from class? No worries. As a general rule of thumb, here is a starting point:
  - Working locally, merge `master` into the feature branch.
  - When you see there's a conflict, that's OK! Type `git status` to verify which file has the conflict.
  - Open that file in your text editor, and look for the merge conflict markers. (`<<<<<<<`, `=======`, `>>>>>>>`)
  - Both branches' versions of code are present - pick which one you want to keep, and save the changes.
  - Add and commit the saved changes to resolve the merge conflict.
  - Push the feature branch up to the remote, and see the resolution in the pull request.
