# Day 1: 2021-02-15 LIACS Code refinery collaborative notes

Day 1 (today): https://hackmd.io/@svenvanderburg/ryz-zgP1d/edit
Day 2: https://hackmd.io/@svenvanderburg/SkB6D43Ju/edit
Day 3: https://hackmd.io/@svenvanderburg/SkM7ON2y_/edit
 
## 👮Code of Conduct
Participants are expected to follow those guidelines:
* Use welcoming and inclusive language
* Be respectful of different viewpoints and experiences
* Gracefully accept constructive criticism
* Focus on what is best for the community
* Show courtesy and respect towards other community members

Contact one of us if you think those rules have been violated.

## 🧑‍⚖️ License
All content is publicly available under the Creative Commons AttributionLicense:https://creativecommons.org/licenses/by/4.0/

## 🙋Getting help:
* icons below participants list / under 'Reactions' in Zoom:
  * go slower
  * go faster
  * when finished assigned task: ‘yes’ green tick icon
  * when could not finish the assigned task ‘no’ cross icon
* to ask a question, type /hand in the chat window
* to get help, type /help in the chat window
* you can ask questions in the document or chat window and helpers will try to help you

## 🎥 Instructions for working with zoom
https://tinyurl.com/zoom-in-workshop

## 🖥 Workshop website
https://escience-academy.github.io/2021-02-15-LIACS-code-refine/

## 🛠 Setup
https://escience-academy.github.io/2021-02-15-LIACS-code-refine/#setup

## 🧑‍🏫 Instructors
Sven, Jens

## 🧑‍🙋 Helpers
Victor, Alessio, Mateusz, Sander, Jeremie, Daniela

## 🗓️ Agenda
See https://escience-academy.github.io/2021-02-15-LIACS-code-refine/#schedule


## 🧠 Collaborative Notes


### Ice-breaking question: You have a *LOT* of snow. What do you do with it?

* Jens: I would make a giant snow-flake :snowflake: 
* Sven: I like making things you can sit in, like a car for example. :+1: 
* Sander: A cinema :movie_camera: (covid proof ofc.)  :+1: 
* Anne: An emperor pinguin because they are awesome 
* Maedeh: An eskimo house! I saw them from cartoons and really like to live in them.
* Jeremie: A snow moon with a snow planet to orbit around the sun
* Iris: A ski slope 
* Thomas: iglo
* Irene: igloo
* Tanjona: I will make a montain made of ice, or more and I will try to climb it. :+1:
* Bram: Snow plow, that would be ironic
* Matesz: big castle :european_castle: 
* Solomiia: igloo or sledge track
* Daniela: igloo! with ice bar :100: 
* Ying: Give it to somewhere never snow :sun_with_face: :sunny: 
* Charles: I'd get rid of it by throwing it at my neighbors :+1: 
* GJ: https://arcticsnowhotel.fi/ :100: 
* Nathan: An igloo :+1:
* Rohola: an iglo 
* Matthias: Build a giant snowman 
* Tom: A big big big slide 
* Duc: play with my children, making snowmans.
* Richard: Push it to GitHub in order to make it an Ice-Hub (it is Microsoft)!
* Yali: make a great wall. :laughing: 
* Anna: Crop circles but with snow.
* Reza: eating :laughing: 

### GitLab

* [Public LIACS GitLab](https://git.liacs.nl/)
* [Private LIACS GitLab](htts://privgit.liacs.nl/)
* (priv)git.liacs.nl login issues? Contact krietvel@liacs.nl
* [GitLab Website](https://gitlab.com)

gitlab.com is completely separate from git.liacs.nl!

**We will be using [GitLab.com] for this workshop**

Repository on GitLab.com. Visibility options:
 - Private: only specified people can see it
 - Public: anyone can see it on GitLab.com

To get the code from a GitLab project, find the blue 'clone' button, copy the 'HTTPS' URL and type `git clone <copied URL>` in your terminal.


### Exercise 1: Creating a Gitlab Repository

- Log into gitlab and create a new repository ( Projects-> my projects -> New repository)
- Make the repository public
- Add a license file ( Repository->Files -> click on the plus -> This directory -> new file ->Select a Template-> license )
- clone it to your desktop
- add some code
- push the changes to the repository
- Explore the Gitlab interface a bit especially the left Taskbar-> Repository. Write interesting things into the collaborative document.

Some general remarks about Licenses:
 - Code without a license cannot be used by someone other than the copyright holder
 - Only the copyright holder can add a license:
   - If you write it in your spare time, you are the copyright holder
   - If you were paid to write it/were paid for your time, the company/institute paying for it is (probably) the copyright holder.
   - **When in doubt, check with your legal department on whether you are allowed to add a license**
   

### Break 1 (10:30 - 10:45)

### Collaboration with git and gitlab part II

GitLab has a decent online editor

The 'Repository' tab on GitLab gives some extra information and nice visualizations, such as a graph view of the commit history.

### Collaborating with people you trust: direct access

You can add someone as a member to your repository under 'Members' in the sidebar on the left. You can search for people by (user)name and assign them a role. The person you added will then be able to see your project in their project list.

As someone who was added to the project, you can now edit the files in the browser and create a commit of the changes. However, by default you cannot push directly to the master branch as a collaborator! GitLab will automatically create the commit on a new branch and start a **Merge Request**.

[Merge request that Sven created](https://gitlab.com/jenswehner/coderefinery/-/merge_requests/1)

In the Merge Request (online on gitlab.com), you can review and discuss the proposed changes using general comments in the Merge Request or at specific lines of code.

Recommendations:
 - Make Merge Requests early on, so the other developers are aware of what is happening.
 - Make a new branch per feature: this keeps the amount of changes to merge small
 - It is the feature branch's responsibility to keep up with the master branch -- i.e., updating the branch regularly 


### Exercise 2: Working as a project collaborator (in breakout rooms) till 11:45 +5

- Exchange your gitlab repository URL with your group
- Add one person as a collaborator (left Taskbar -> Members)
- Create an issue in the repo where you are a collaborator
- Clone that repo
- make changes on a new branch
- push the changes
- submit a Merge Request (left Taskbar -> Merge Requests)
- wait for approval
- At the same time review a collaborators Merge Request
- Learn about Protecting branches (left Taskbar -> Settings -> Repository -> Protected Branches)

### Break 2 (12:00 - 12:15)

Q: What is the difference between an Issue and Merge Request?
- An issue is a discussion of a problem/suggestion in general, before any code is written. A Merge Request is specifically to discuss the code changes that were suggested. 

Closing a merge request doesn't means that the merge request is merged. This is a green MERGE button for that.




### Collaborating with people you don't trust: no direct access

* Fork creates a full copy of the project inside your own workspace. You have full ownership of this copy.
* You can make modifications on this copy. 
* You can _offer_ those change to be integrated into someone else repository (in this case the orignal one) by making a merge request. 


### Exercise 3: Working as an external contributor (in breakout rooms) 

- Fork another group members repo (Project page , top right corner)
- Create an issue on the other repository
- Clone your forked repo to your computer
- Make some changes 
- Push it to your fork
- Make a change and commit it to a new branch
- push the changes
- make a merge request from your fork to the main repository mentioning the issue
- Consider turning your Merge Request into a draft Merge Request.
- let your code be reviewed by tagging the repo owner using (@Username)
- At the same time review Merge request using comments on individual lines
- Accept or reject the MR


Name clash issue! You cannot fork a project if you have one with the same name. 
-> can you rename the project? It doesn't change the "real" name, only the display name and the issue remain.
-> You can solve the problem by changing the path: Setting -> Advanced -> Change path

Issues are the smallest way to contribute to a project: No code required! Simply mentioning a bug is already helpful, even if you don't know how to fix it.

It is polite to first create an issue to propose a fix/addition and start working on the merge request once confirmed by the owners of the repository.

### Feedback for today
Just add your name (or not if you want to give anonymous feedback) with your feedback for today!

#### What went well:
* Anne: I liked the interactive exercises in breakout room with a helper for each room :+1: 
* I find the collaborative document very useful! Especially the Resources chapter. :+1: 
* Sander in the group session was really helpful!
* Marios: the exercises with eachother really helped how to collaborate!:+1:
* Elaborate answers on all aksed questions, interesting topics covered.
* Nice group of people together!
* Spliting us into smaller groups really helps. I am comfortable to ask for help.
* Nice mix of collaboration, interactivity and learning from going through the exercises in class
* Small groups worked well, exercises were well sized
* Nice to have time to play around with gitlab (seeing both sides of requests/issues)
* Nice tutorial, thanks
* Nice to have a collaborative doc, very useful. Also nice to have a lot of people involved to support this big group 



#### What could be improved:
* Anne: You could cover how to create a branch in the command line. 
* Same basic command line git command 
* working in small groups was a bit chaotic when working in pairs in a bigger group
* splitting into breakout rooms was a little too much/ would have been nice to have a little more plenary time
* Maybe more time in the group session
* I miss a bit of an overview of what can be done with branches their types, and what is the purpose of reviewing, approving, so the workflow of collaboration.
* I would have liked a bit more context on how the different steps fit into the dynamics of a project, and best practices for e.g., how to write a good commit message. Now I had the feeling that we were going through the motions, with knowing how different features fit together (e.g., how issues and merge requests interact exactly.)
* The exercises were not straightforward. 
* The explanations without seeing was difficult -- perhaps the helper could guide better with shared screen
* Perhaps the helper can better access its repository publicly? No passwords needed.
* 

## 📚 Resources

[Markdown github-flavored introduction](https://guides.github.com/features/mastering-markdown/)
[GitLab SSH key managment](https://docs.gitlab.com/ee/ssh/) 

### What license to choose
* https://choosealicense.com/
* https://guide.esciencecenter.nl/#/best_practices/licensing (to see what we use at the eScience Center)
* https://www.tudelft.nl/en/ict-innovation/articles/open-source-software-guidelines-for-researchers
 

### Git guides
* https://rogerdudler.github.io/git-guide/
* https://swcarpentry.github.io/git-novice/

### good practices for collaborating online
https://opensource.guide/

## :question: Q&A
* What is the best way to incorporate different licenses into one repository (e.g., when different parts of your code have different licenses, or when datasets that you generate have different licenses than the code)?
    * And if you just need a single license, what would be a good starting point? (assuming that I want to share it all)
    * You can also write the licence at the beginning of the file when it's specific to the file.
        * I tend to put a short version in the comments at the top of the files, with a link to the long version.
    
* Where can I get help on choosing the right license for my project?
    * ask university Library
    * check the project agreement (i.e., project office)
    * ask your PI
    * https://choosealicense.com/licenses/
    
* If you get an 403 while pushing to gitlab then you might have to set your password through the browser first 
    * in Windows Platform, you need first re-check in the Windows Credentials (control panel/user accounts/). Please adjust the credential both username and password for gitlab 

    
* Is there a general Surf GitLab for dutch uni's and research institutes?
    * Not that I'm aware of
