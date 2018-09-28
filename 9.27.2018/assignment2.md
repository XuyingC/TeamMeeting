# Assignment #2 Killer App Team proposal: GitGroup - A web-based software development management system

Runbo(Chuck) Zhao(Team leader)
JingYu Bao
Xuying Cao
Chengxiang Yin

## Introduction

### Git and GitHub

If you are a web developer, you must be familiar with the git - a version control system for tracking changes in computer files and coordinating work on those files among multiple people, and GitHub - a web-based hosting service for version control using git. You almost can use it to do anything when your team develop a software, such as bug tracking, feature requests, task management, and wikis.

### GitHub Apps

Apps on GitHub allow you to automate and improve your workflow. You can build apps, share and purchase them from GitHub Marketplace, or browse useful tools and services that integrate with GitHub in Works with GitHub. To learn how to list an app on GitHub Marketplace, see "Getting started with GitHub Marketplace."<br>
GitHub Apps are the officially recommended way to integrate with GitHub because they offer much more granular permissions to access data, but GitHub supports both OAuth Apps and GitHub Apps. For information on choosing a type of app, see "About apps" and "Differences between apps."

## Application Idea

Although GitHub is very famous among the programmers and developers. But there are also some disadvantages. One of them is that Git and GitHub have a high entrance standard. For example, when you want to create an issue to suggest a new idea or track a bug, you need to learn markdown
syntax, emoji code. And it is even more complex when you do pull request and merge the project. In Most time, developers need to communicate with the boss or product manager. However, most managers are not good at programming, and GitHub is not very suitable to them. <br>
My idea is to make GitGroup more easy to use by person who has little development experience, such as product manager. When you use the GitGroup, you can sign up an account and access to the GitHub api. The user can create online group chat, schedule and record the conference. After the discussion between the team member, they will have some their project idea, thus, our online app also provide the task management service. In each project, every team member’s work is recorded in the system. And according to those information, every user will have their own grade. <br>
For example, the product managers or the developing leader can create their own project in the GitGroup. One project in the GitGroup can be linked to multiple repository in GitHub. Then the administrator of this project can invites the team member to join this software development<br>
In the process of development, the manager can use the Workspaces to manage the development. The major part of the WorkSpaces is Kanban board. (Kanban board which is similar to projects board in the Gitub. In the Kanban board, there are several columns represent different stage of the developement process, such as TODO, Ready, In Progress, Done... You can customize your own stage. Every column contains issue card imported from the Github, and you can easily drug them among the columns. If you drug it to the Done column. The issue in the Github will be automatically closed) <br>
Also, manager can use GitGroup to analysis the development duration, quality and the team work situation of the project. GitGroup offers a variety of Agile charts and analytics to help you keep track of how your team is doing.

- Burndown and Burnup Charts
- Throughput Chart
- Users Throughput Chart
- Velocity Chart

When you use GitGroup, the commucation among team members can also be done in the page of the GitGroup. Integrate the chat room into GitGroup, and Team member can easily chat with each other.
The issue cards are easily transported among the team member through the chat system.

## Why we think what you are proposing is a killer app

Although there are some product management app in the GitHub marketplace, every app has their own advantages and also disadvantages. Some good features appears in these apps, for exampe some app can parse the content of the issues in GitHub, according to the predefined syntax, the app can record more information like issue dependency which is not provided in GitHub. There is a lot of good idea to improve the GitHub. So we dicide combine these features and improve the user experience. That is also the advantage of GitGroup beyond the any other project management apps and why it is a killer app.

## Future enhancements

Furthermore, the online web can have a recommendation system which help the product manager and programmer match each other. In conclusion, it is a online service based on the GitHub API, and improve the user experience.
In details, we will foucus on:

- Issue Dependency<br>
  Support creating dependencies between issues using the "needs #blocker_issue_number" and “needed-by #blocking_issue_number" keywords. If the issue you’re setting up a dependency relationship with is in a different repository you can use a fully qualified issue number like this "organization/repository_name#issue_number".
  For example, if issue #2345 is blocked by issue #1234 you can type "needs #1234" in a comment on issue #2345 and we'll create a relationship showing issue #2345 is dependent on issue #1234.<br>
  Similarly If you’re editing issue #1234 and you want to say that it blocks issue #2345 you can type “needed-by #2345” and we’ll setup a reverse dependency. Reverse dependencies are a convenient way of creating “work item” issues that need to be completed before a larger issue (e.g. a feature) a whole is complete.<br>In the blocker issue, GitGroup will list all the issues that are dependent on the blocker.
  [(reference)](https://docs.codetree.com/article/8-dependencies)

- Notification
  When any state in the process is changed, GitGroup will notify the team member by e-mail or text message.
