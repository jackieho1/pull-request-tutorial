# **FAQ for International Students**

## Table of Contents
### [Introduction to Hack Reactor](#intro)
### [Travel Visas](#travel-visas)
### [Work Visas](#work-visas)
### [Outcomes for International Students](#outcomes)
### [Community](#community)
### [Touch Typing](#touch)


* brief intro to a bootcamp for international students
* Travel Visas (speak to formal HR grads)
* Work Visas (H1B)
* Outcomes for International Students (are there hiring partners elsewhere in the US)
* Touch Typing/shortcuts/mats to cover your keyboard to switch boards (switch keyboard settings on laptop)
* mention we have many international students
* (add to lectures: talk about international students who have found jobs in the US)
* create an email list/community group for international students

### <a name="intro"></a> An Introduction to Hack Reactor
blah blah blah

### <a name="travel-visas"></a>Travel Visas
All visitors coming in to the United States require a visa. A 3 month visa may not be sufficient as our program runs for 13 weeks long (12 learning weeks with 1 break week in the middle of the course). Missing any days can be considered a breach of contract, so we ask that you be mindful of how long you will be able to stay in the United States for.

Please consult with an immigration lawyer to determine which visa you should be applying for. You may reach out to international Hack Reactor alumni for other tips.


### <a name="work-visas"></a>Work Visas
If you are an international student and would like to continue working in the United States after graduating from Hack Reactor, you must apply to a work visa or have a company sponsor you to legally work in the United States.

Hack Reactor does not provide the resources to help individuals with work visas. Make sure to do your research and have a plan of action if you decide to work in the United States after graduation.

### <a name="outcomes"></a>Outcomes for International Students
Outcomes is

### <a name="community"></a>Community
International alumni will have access to an international alumni community once they graduate. We have several different Google Groups for students in vari

### <a name="touch"></a>Touch Typing
The United States uses the international keyboard for typing. If you would like to learn touch typing on the international keyboard, feel free to practice here:  https://www.typingclub.com/


# pull-request-tutorial
# Instructions for creating a PR (non-technical staff)

## Introduction
The objective of this tutorial is to teach basic understanding of how to submit
a pull request. You'll be able to walk through the steps of how a pull request
is made with a student and help them successfully submit their assessment.

## Stage, commit, and push



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
