<h1 id="abstract">Abstract</h1>
<p>For this paper, we are going to walk through some tools that will help us in the reporducible workflow, which are:</p>
<ul>
<li>Makefile</li>
<li>Git</li>
<li>GitHub</li>
<li>Pandoc</li>
<li>Markdown</li>
</ul>
<p>It is essential and important to have these tools because they together create a collborative environment for users and therefore speed up the work process. For the following chapters, we are going to introduce these tools in general and also point out how they could be useful for our use case.</p>
<h1 id="introduction">Introduction</h1>
<p>Nowadays, more and more open-source software are available for users to use, which greatly improves the efficiency of working collaboratively on a project since we don't have to rebuild the wheels. Therefore, it's important for us to learn how to use these softwares and benefit from these resources. # Discussion</p>
<h2 id="makefile">Makefile</h2>
<p>Makefile is a tool to help the user to execute a series of system commands and automate the workflow. For this reproducible workflow, using Makefile helps us to automate and streamline the workflow. It really enables other users to seamlessly reproduce the work. For example, I can have a makefile implemented for other users who want to reproduce this project. What they will need to do is just to run <code>make all</code> from their side of the computer, which saves the addtional work.</p>
<h2 id="git">Git</h2>
<p><img src=https://github.com/StephenFang/stat159-fall2016-project1/blob/master/images/git-logo.png></p>
<p>Git is a version control system for an user to keep track of updates/changes from time to time. There are often times in a project when we need to make changes. If we don't have a version control system, we wouldn't be able to keep track of what changes we made through the way and we are also dumping the older file if we don't have a version control system. However, Git will enable an user to smoothly keep track of the changes and record each version number along the way.</p>
<p>The role of Git in this reproducible workflow is valuable in several ways. First of all, by keeping tracking of changes, we will be able to know how much progress we have made along the way and also be able to remember the changes. Secondly, if we have decide to discard some of our changes and rollback to an earlier version, we will be able to do that since we have used Git to keep track of changes. Moreover, if we are working in a team setting, it's important for each team member to know what are changed each time regarding the project and Git defnitely can show the change history.</p>
<h2 id="github">GitHub</h2>
<p><img src=https://github.com/StephenFang/stat159-fall2016-project1/blob/master/images/github-logo.png></p>
<p>As explained above for Git, it is a version control system but we would love to have a web interface for git and a online storage to store our current project files. This is when GitHub comes in handy. GitHub provide services for users to host their project files at an online storage plaec and also provide this web interface of git for users to use. Moreover, after hosting the git service online, more than one people can remotely access the project if they are granted the access, which is beneficial for teamwork.</p>
<p>In this project, the first role of GitHub is that we will have an online hosting service that allows both the students, GSI and professor to check in for work. Moreover, GSI and professor will be able to see the changes I made from time to time on GitHub. I, as a student, is also able to upload my project online so that I can retrieve from another computer if I use a lab machine.</p>
<h2 id="pandoc">Pandoc</h2>
<p><img src=https://github.com/StephenFang/stat159-fall2016-project1/blob/master/images/pandoc-logo.png></p>
<p>Pandoc is a document converter that helps user to convert documents of one format to another format. For example, a lot of users use pandoc to convert markdown files into html files. Pandoc is a very powerful tool for several reasons. First of all, it is free and we don't have to pay to use it. Secondly, if we need a file of different format, which is, we already have a markdown file and we want to convert it to html. Instead of rewrting a completely new file in html, we can easily utilize pandoc to transfer markdown files into html files, which save both of our time and effort.</p>
<h2 id="markdown">Markdown</h2>
<p><img src=https://github.com/StephenFang/stat159-fall2016-project1/blob/master/images/markdown-logo.png></p>
<p>Markdown is a language that is easy to use to format the text into specific formats. It is designed to be easy to write for the users so that they can quickly format the text in bold, italic and many other formats. The other amazing thing about markdown is that it's very easy to convert from markdown to html and many other formats supported by web broswers.</p>
<h1 id="conclusion">Conclusion</h1>
<p>Hopefully the sections above give you a sense of what these tool are and how to utilize these tools in a reproducible workflow. I hope you find it useful! I also have some personal feelings to share with you:</p>
<p>For this project, I read some articles online introducing Git, Makefile, Markdown, Pandoc and GitHub in order to get a more formal sense of the tool so that I can explain what these tools are with accuracy in my own words later. The &quot;easy&quot; part of this project is setting up the directories and downloading the logos from Professor's github repo. The more challenging parts are writing the paper and readme because I have to think in advance so that others will be able to reproduce this project with reasonable guidance. For me, I would say the most time consuming part is writing the papers because you really want to make sure you are using the right examples and explaining the concept clearly enough. For this project, I worked on it on my own and it took me around 6 hours.</p>
