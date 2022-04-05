# 3P Learning - Full Stack Coding Task

This information applies to 3P learning's full-stack coding task for full stack dot net (C#) and react developers. The purpose of this task is to be used in follow-up conversations in an interview. Since there are a number of different ways of achieving the task, even with a single programming language, there is no single right answer.

## Background

For this task you need to build a web application which is a source code repository management tool that will allow a user of the application to keep an inventory of source code repositories. The reason for this is so that they can assign a development team as owners of a repository to understand which team owns which parts of the overall codebase. For the purposes of the task you can expect the dummy organisation for which you are building the app to have around 800 source code repositories.

You will be building both the backend api using dot net 6.x (C#), as well as the front-end interface using React 17.x. As a rough time line you should spend between 2 and 3 hours to complete the build. You should complete this at least 24 hours before your interview and send the link to your code implementation (instructions below) to your 3P Learning contact.

You do not need to use a database for this task, in-memory data which is destroyed every time the application is stopped is perfectly acceptable. There are also no limitations on legally usable external libraries you want to use to achieve the task as long as the libraries have an open source license, preferably along the lines of LGPL. 

The language (JS or TS) and any component libraries (Material, Chakra, Semantic, etc.) you want to use for React are also up to you, if you want to use those.

## Requirements

The repository management tool that you are building should have the following features:
1. A list view showing all source code repositories
2. The ability to create a new repository record
3. The ability to remove an existing  repository record
4. The ability to update an existing repository record

A repository should include the following information at a minimum:
- A name
- A URL to the actual repository location (i.e. on Github)
- A text description field that can contain a multi-line text description
- A status flag to show if the repository is active or inactive
- An access flag to show if the repository is private or public
- A team name which will contain the name of the team that owns the code repository

## Instructions

1. Create a new code repository on Github under your personal Github account. You can create a free Github account if you don't have one already
2. In your code repository create a folder called `api` and create a new dotnet 6.x web api project in that folder
3. Create another folder called `ui` and create a new react 17.x project in that folder
4. Create the code needed to meet the requirements above, plus anything you feel is needed for the web application
5. Push the code to your Github repository, along with a README markdown file with any instructions required to be able to run your applications, and send a link to the repository you created to your 3P contact
