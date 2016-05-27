# pull-request-tutorial
Instructions for creating a PR (non-technical staff)

## Introduction
This tutorial is meant to teach basic understanding of how a pull request is
made ...

## Stage, commit, and push

## Instructions
A student may require your help in making a pull request after their assessment.
1. Ask the student to go to their terminal and enter the repo they were working
on.
2. Ask the student to do a `git status`
3. You should either see the following in the terminal:
* "Nothing to commit..." (go to step #)
* "Changes to commit..." (go to step 9)
* Changes not staged for commit (go to step 4)
4. If the student has not staged their changes, ask them to to a
`git add [FILE-NAME]` or a `git add .` to add *all* files.
5. Ask the student to do a `git status`. You should now see "Changes to be
committed" on the terminal. If not, repeat step 4 until all files have been
added.
6. Ask the student to type `git commit` into their terminal. Their text editor
should open up, and that's where they will add their commit message.
7. Save and quit the text editor to complete the commit.
8. Go back to the terminal. The student should see that the commit has been
made.
9. Do another `git status`. It should now say "Your branch is ahead of
'origin/master' by 1 commit". (The number of commits can be interchangeable)
10. Ask the student to do a `git push origin master`. The terminal should run
a few things. You've successfully completed pushing the repo from your local to
your remote repo.
11. Ask the student to go to www.github.com and go to *their* fork (not Hack
  Reactor's fork).
12. Ask them to make a pull request (either the green icon or a button called '
New pull request').
13. Creating a new PR will lead the student to a page that looks like this:
  [image here]
  Make sure the student changes the base branch from "master" to their own branch.
14. Remind the students to add any necessary comments (it is in their README).
Scroll down the page and submit the pull request.
15. Success! You've helped a student make a pull request for their assessment!
I'm so proud of you, you da best.
