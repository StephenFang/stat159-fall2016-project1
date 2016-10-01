# Stat159-Fall2016-Project1

## Intro

https://github.com/StephenFang/stat159-fall2016-project1/blob/master/images/stat159-logo.png
This is the Stats 159 Project 1!

## Structure of this project

```
stat159-fall2016-project1/
	.gitignore
	README.md
	Makefile
	paper/
		sections/
			00-abstract.md
			01-introduction.md
			02-discussion.md
			03-conclusions.md
		paper.md
		paper.html
	images/
		git-logo.png
		github-logo.png
		markdown-logo.png
		pandoc-logo.png
		stat159-logo.png
```

## Author's Information

Name: Mingtao Fang

Student ID: 24629295

Creative Common License: https://creativecommons.org/licenses/by-nc-sa/4.0/

## Steps to Reproduce this Paper

### Cloning this Project
If we are talking about download this project and make new changes from there, we can simply start with cloning this repo.

```
git clone https://github.com/StephenFang/stat159-fall2016-project1
```

Then we can just make changes from there and update the repo as we have the access to it.

### Redoing the Project
If we are talking about how to completely redo this whole project, then we need to start from scratch. 

- First of all, we will need to creat a project on GitHub and follow the instructions on GitHub empty folder page to add in more files.

- Later on, we will need to create the same folder strcture as the project spec told us.

```
mkdir proj_name
cd proj_name
mkdir paper
mkdir images
cd paper
mkdir sections
```

- The above code should have given us the same folder structure as the project spec required. After that, we will need to download the images for each of the tools and put them in the images folder.

- The next step is to write up the paper components in the sections folders and name them as `00-abstract.md`, `01-introduction.md`, `02-discussion.md`, `03-conclusion.md`

- With the text completed, it's time to automate the process and use Makefile. We will need to write a Makefile that first remove the paper.html and paper.md file to ensure we have a clean environment. We will also need the makefile to include the commands to generate paper.md from the four md files in the sections folder. Then we will use pandoc to convert the paper.md into paper.html

- Ater the makefile is implemented, we can simply use the `make all` command to run the makefile and generate the files for us. This is the final step and that should be enough for us to reproduce the project