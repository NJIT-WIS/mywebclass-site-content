# MyWebClass collaboration and brainstorming activity to identify required content for mywebclass

The purpose of this assignment is to practice collaborating using GIT/GitHub and to do this you need to create a list of things that you have learned in this class, things that you don't understand , and things that you want to learn.  


## Instructions
=======
The purpose of this assignment is to practice collaborating using GIT/GitHub and develop the requirements for the mywebclass.org website's tutorials and courses.  To accomplish this task we are going to create three lists(What I Know, What I Don't Know, and What I Want To Learn) and consolidate the items from everyone in the class into a master list that counts the number of repeated issues.  You need at least **3 items for each list for a total of 9 items** and you should plan that these items are going to be used for project 1 as the basis for the possible topics that people can choose to build online tutorials about.   

## Learning Objectives:
1.  You will learn to collaborate online using GIT
2.  You will learn to merge pull requests and resolve merge conflicts
3.  You will learn to manage a basic project using GitHub Project.

### Complete the Assignment By adding your issues to these 3 lists and count how many times each issue is mentioned.  The number in the bracket next to each issue is the count, you should set your count at 1 for your issue.  We need the count of how many times the issue is mentioned, so that we can prioritze each issue.

### Your list should look like this:
#### Things we understand**

1.  Python print[1]
2.  Git Pull[2]
3.  Linux Commands[1]
=======

1.  Python Print[1]
2.  Linux Directory listing[2]
3.  Docker Installation[1]

#### Things we don't understand

1.  Git stash[1]
2.  Git status[2]
3.  Proper Documentation[1]
#### Things we want to know next**
1.  Vim[1]
2.  Cloud deployment w/ Kubernetes[2]
3.  Ruby[1]
=======
1. Git stash[1]
2. GIt pull[2]
3. Proper Documentation[1]
=======
1.  I know how to create and track projects
2.  I know how to commit changes
3.  I have learnt how to fork repos and work on projects
#### Things we don't understand
1. I don't understand how to do the submissions on canvas after completing the tasks on GitHub
2. I don't understand how to fix errors in Pycharm
3. I don't understand how to use docker hub and for what purpose

#### Things we want to know next**

1. Vim[1]
2. Cloud deployment with Kubernetes[2]
3. Ruby[1]
=======
1.  I want to learn the softwares being taught in this class properly without falling back
2.  I want to learn the softwares being taught in this class properly without falling back
3.  I do feel kind of feel lost in class, I want to know what exactly to learn and how to go about it



## Prerequisite - YOU. MUST SETUP PRIVATE PUBLIC KEY AUTH WITH GITHUB OR YOU WILL GET ACCESS DENIED ERRORS WHEN YOU PUSH FROM THE TERMINAL
Add your ssh public key to github - See video
**open powershell or terminal and run "ssh-keygen -b 4096" and hit enter through the prompts and then open the file **your home directory/.ssh/id_rsa.pub** and copy that text into your github account settings under SSH/GPG keys -> add key.  in one of the prompts it will tell you where it is going to save the key.  If you already have a key reusue the one you have and cancel out of the process with control c **.  I do it on my mac with the command vi ~/.ssh/id_rsa.pub" and then i press shift colon : and q to quit

### [Assignment Video](https://youtu.be/UFLKojO3OtM)

## You will accomplish this assignment in 5 phases:

1.  Each person will follow the instructions below to create one issue per list item i.e. 9 issues.
  **You need one issue per item in your list for a total of 9 issues.**.  Resolve each issue to add each of your items to the appropriate list.

2.  Find a person in class and then make a pull request for each item on your list to **THEIR** repository.  **You make 9 pull requests to someone else**

This person should then merge the pull requests and resolve the merge conflict to add new items to their list and increment the count on dupilicate items.  We want to know how many people said the same thing, so that we can prioritize the requirement, when we decide on what to make in project 1.  

3.  **Once you have merged the pull requests from someone else in class**, you need to find someone new in class to submit a pull request called "merge my list".  that asks to merge your master into their master, so that they can add new items to their list and increment the duplicate issue count for each item in the list.  Create an issue using the template "Assignment Master List" and reference the pull request that you make in the issue.  Make sure you make a issue template to accept this issue on your own repository and provide these instructions.

4. The person that receives the pull request from #3 needs to resolve merge conflics and merge, so that the new issues are added and duplicate counts are incrimented as necessary.

5. Once you have merged someone else's combined list into your project make an issue and a pull request to the "complete_list" branch on the upstream repository i.e. the one you forked from. Use the issue "Complete List" and put a link to the pull request.  Submit a link to the **issue** to Canvas to finish the assignment.  In your pull request include your UCID,  course number, and section.  

### You are done when you have completed the following:
 
1.  Added your issues individually and resolved them
2.  Made 9 pull requests to another person for each item that contains the branch you want to merge 
3.  Merged 9 pull requests from someone else
3.  Made a pull request to another person with your master branch that contains the consolidated list 
4.  Merged the pull request of someone elsesa compiled list
5.  Submmited a pull request to this repository to have your complete list merged

### Canvas Submission instructions

To submit this assignment you need to submit the result of step #5 to canvas.  When you look at the commits for your project you should see a total of 3 different users have contributed items to the list **including yourself** .  If you don't have at least 3  people's commits on the project you will lose 33 points for each person not found.

## Project Setup Instructions

Collaborating on GitHub:

1. Fork the repository: Each person should fork the repository to their own GitHub account. To do this, click the "Fork" button in the top-right corner of the repository page.
2. Enable issues: If you don't see the "Issues" tab in the main menu, you should enable it in the repository settings. Go to the "Issues" tab, and click "Milestones" to add a 0.1.0 milestone and describe it as a consolidated list of issues from your team.  On the issues tab you should also create labels for "I Know", "Want to Know", and "Don't Understand".  Once you create these labels then go to settings and look for the "Issues Template" and create 3 issue templates that will provide the starting text for each issue filed of that type.  At the bottom of each issue you will see that you can automaticly assign a label to that issue type, so connect the respective labels you created with the 3 issue types.
3. Create one issue per item in your list and assign it to the correct issue template.  
4. Create a new project tab and create a new project (you have to click the down arrow next to "link project" to change it to new project). When you create a project you need to select "board" and name it "Documentation Tasks".
5.  Go back to your issues, click on each issue, and assign the issue to the following: assignee i.e. you, miletone i.e. the one you created 0.1.0, project documentation (set the status to todo) and create the branch for the issue.
4. Go to the "Project" board, and if you see any tasks without a status move them to the todo column.  
5. Pick one task and move it to the in progress column to indicate you are going to work on it.
6. If you have not done so already clone the repository to your local and type "git fetch" to see the branch(s) for the issues you created. 
7.  Do a "git checkout <name of branch>" i.e. "git checkout 1-some-issue".
8.  Complete the issue by adding one item to one of the 3 categories.  Do a git status and make sure that only the readme is changed.  If the readme just has the change then you can do a git commit -a -m "PUT A DESCRIPTIVE MESSAGE HERE".  git commit with the -a flag adds all the new and modified files to the commit.
9. Push the branch back by doing a git push origin head or use the push command from the drop down in Pycharm.  
10.  Make a pull request (MAKE SURE YOU DO IT FOR YOUR OWN IT WILL DEFAULT TO MAKING A PULL REQUEST TO THE UPSTREAM REPOSITORY" for the branch and when you come to the part where you have to need the commit message you have to add "closes #?"  the ? is whatever issue number that the pull request resolves.
11.  Check the documentation board and you should see that the task has moved from in progress to done.
12.  Once you have resolved an issue you should go to your partners' fork and make a pull request that to merge your issue branch.  
13.  Your partner will then need to create an issue to merge the pull request.  You first need to save an issue and after you save it will make the right side controls active and you can select the repository / pull request you want to link and fill out the other fields like assigning the task to the milestone, assigning a developer, assiginging it to the right project with the todo status.
14. Once your partner creates the issue they need to merge the pull request and close it with the "closes #?" in the merge message.
15. On your own fork, you will want to make a pull request to yourself to merge their updated master into yours.


# Complete the Assignment By adding your issues to these 3 lists.

## Put your items here
### Things you understand so far
1. I know how to make an ssh key and add it to GitHub So I don't need to login with password
2. I learend GITHUB Issues
3. Merging 
4. pull requests
### Things you don't understand about what we are doing / web development.
1. Add items to the list
2. Terminal commands
3. docker
### Things you want to know next
1. How to connect viewjs to elastic search
2. fdsadfas
3. Java