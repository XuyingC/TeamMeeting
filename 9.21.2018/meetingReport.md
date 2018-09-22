# Requirement Specification

1. Workspaces
   Kanban board which is similar to projects board in the Gitub. In the Kanban board, there are several columns represent different stage of the developement process, such as TODO, Ready, In Progress, Done... You can customize your own stage.<br>
   Every column contains issue card imported from the Github, and you can easily drug them among the columns. If you drug it to the Done column. The issue in the Github will be automatically closed.
2. Analysis
   Offer a variety of Agile charts and analytics to help you keep track of how your team is doing.
   - Burndown and Burnup Charts
   - Throughput Chart
   - Users Throughput Chart
   - Velocity Chart
3. Chat
   Integrate the chat room into GitGroup, and Team member can easily chat with each other.
   The issue card is easily transported among the team member through the chat system.
4. Issue Dependency
   Support creating dependencies between issues using the "needs #blocker_issue_number" and “needed-by #blocking_issue_number" keywords. If the issue you’re setting up a dependency relationship with is in a different repository you can use a fully qualified issue number like this "organization/repository_name#issue_number".

   For example, if issue #2345 is blocked by issue #1234 you can type "needs #1234" in a comment on issue #2345 and we'll create a relationship showing issue #2345 is dependent on issue #1234.

   Similarly If you’re editing issue #1234 and you want to say that it blocks issue #2345 you can type “needed-by #2345” and we’ll setup a reverse dependency. Reverse dependencies are a convenient way of creating “work item” issues that need to be completed before a larger issue (e.g. a feature) a whole is complete.

   In the blocker issue, GitGroup will list all the issues that are dependent on the blocker.
   [(reference)](https://docs.codetree.com/article/8-dependencies)

5. Notification
   When any state in the process is changed, GitGroup will notify the team member by e-mail or text message.

# Task

Next meeting is scheduled in 25/9/2018. In these days before that, you need:

- Read Ch5, Ch6 and Ch7 of [Textbook](https://edisciplinas.usp.br/pluginfile.php/2150022/mod_resource/content/1/1429431793.203Software%20Engineering%20by%20Somerville.pdf);
- Try to design our system architecture and draw the UML graph;
- Learning React;

# Resources

- [Issue feature in Github](https://guides.github.com/features/issues/)
- [Projects board in Github](https://help.github.com/articles/about-project-boards/)

- [Github video resource](https://resources.github.com/videos/github-best-practices/)

- my favorite react course<br>
  [![Mosh React Course](http://img.youtube.com/vi/Ke90Tje7VS0/0.jpg)](http://www.youtube.com/watch?v=Ke90Tje7VS0)
