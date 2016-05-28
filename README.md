# pull-request-tutorial
# Instructions for creating a PR (non-technical staff)

## Introduction
The objective of this tutorial is to teach basic understanding of how to submit
a pull request. You'll be able to walk through the steps of how a pull request
is made with a student and help them successfully submit their assessment.

## Stage, commit, and push
There are three overarching steps for submitting a pull request. This section
will serve as a quick overview on those three steps. A great comparison to this
process is imagining that you are mailing out a package to your friend.

*1. Staging*
The first step is to stage your changes, which is represented by `git add`. This
means that you'll be adding any modified file changes into your current repo.
Git will about the change, but it won't be permanent in the global repository.

Think of this step as adding all the items you are shipping into a box - you
haven't made the permanent move to mail it out yet, but are staging it to be
shipped.

*2. Committing*
The second step is committing your changes, which is represented by `git commit`.
This means that you are recording your changes to the history of your repository
and writing a message to detail that change.

Think of this step as writing your shipping address to the box. You are
recording the address of your shipment so the postman has a reference of where
to ship it to, similar to recording your changes to your repo.

*3. Pushing*
The third step is to push your changes, which is represented by `git push`.
Staging and committing all happens locally (in your computer only).
Pushing your changes means that you'll be making these changes globally so
everyone can see these changes when they go to your Github account.

This final step is mailing out your box through the post office. Similarly to
pushing your changes, this ensures that your friend will receive your package.


## Instructions
A student may require your help in making a pull request after their assessment.  
1. Ask the student to go to their terminal and enter the repo they were working
on.  
2. Ask the student to do a `git status`  
3. You should either see the following in the terminal:  
    - "Nothing to commit..." Make sure they've saved their file. Do another `git
status`  
    - "Changes to commit..." (go to step 9)  
    - "Changes not staged for commit" (go to step 4)  
4. If the student has not staged their changes, ask them to to a `git add [FILE-NAME]`
 or a `git add .` to add *all* files.  
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
