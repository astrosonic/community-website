# How do we work?

For all the tasks that are performed in our open-source community, we follow the time-tested and widely trusted pull request model. This simplifies the way of creating workflows around task reviews while quantifying progress and giving insights as to what was contributed. This model was widely popularized by GitHub and it slowly found its way in all kinds of workflow – open-source and proprietary alike.

Not aware how it works? It is okay. Read on the following points.

* All the project assets and codes are stored in a remote location. This remote location is called a repository. Every project has their stuffs collected and stored in their own repository. Keep in mind that a regular change is needed in it to add new features or fix existing bugs.
* The event of making changes in a remote repository is called pushing. You can imagine how chaotic it can be if that repository is kept open to pushes made by everyone. Thus, owners of the repository are the only ones that are allowed to make pushes to the repository.
* You might begin to question the openness of open-source if only a selected group of people are allowed to make changes. You are allowed to make contributions but like every stuff out there – your work must be monitored and evaluated before being added.
* To begin making changes, you need to have your own copy of the remote repository. The event of making a copy of a repositories to your version control account is called forking. This would create a fork of the repository with all the changes made till the date of forking.
* This fork gives you complete authority to make any change you want. Keep in mind that all the changes you make would stay in your fork and none of it would be reflected in the source repository. We will talk further about how you can do so on the source repository.
* Your fork of the source repository is stored remotely and in order to make changes to it, you need to download it to your working device. This event of downloading a copy of your fork is called cloning. Now navigate to the folder where you have cloned your fork to start.
* There might be an uncertainty as to if your additions would actually be helpful. It is normal for developers to end up breaking their project while making new additions so you might want to isolate your changes. This event of isolating all changes is called branching.
* Make all the changes you wish to see in the assets and codebase of your newly created branch. You must save those changes in order for them to persist. This event of saving changes is called committing and it helps you track changes and rollback to a previous state.
* All commits that you have made so far would stay only in the cloned copy of your fork. In order to make sure that they make it to the remote fork of your version control account, you need to upload them. This event of uploading commits is called pushing.
* Now that all the made changes are in your remote forked repository, it is time to make these changes on the actual source repository as well. You need to ask the repository owner to take a look at your changes and add them. This event is called making a pull request.
* This pull request is for bringing together the changes made in your branch to the changes made in the primary branch of the source repository. The primary branch is generally known as master and the event of bringing together two branches is called merging.
* Give the source owners some time. Let them review your changes and they will come back to you with more change requests. If all goes good, your changes might just get merged to the master and you would get labeled as a project contributor. Keep going for more now.

You know what to do right now. But here is when you should do this all.

* When you are assigned a task over a collaborative chat, you can follow the aforesaid method to add your part of the contributions.
* When you see an active issue on a bugtracker, you can ask fixing to be assigned to you before you start adding your fixes to code.

To protect the contributions made so far, the following must be kept in mind.

* All commits must be made in a branch, which is not master
* Fork master to source master merging is disallowed
* There can be at most one pull request per issue fixing
* Avoid merging branches if there are active conflicts
* There can be at most one source fork per VCS account
* One commit per file is suggested to ease tracking changes
* Single push for multiple commits is suggested
* Concurrent tasks on multiple branches is not recommended
* Branches should be named appropriately
* Commits should have concise message under 50 chars