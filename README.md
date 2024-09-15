# Tech Wars: Episode Docs - May the Knowledge Be with You 💫

We use **docfx** by Microsoft for docs. Read about it [here](https://dotnet.github.io/docfx/). 

## Get Started

To start contributing to the docs, do the following

 1) Make sure you have the [.NET SDK](https://dotnet.microsoft.com/en-us/download) installed.
 2) Open a terminal and run (anywhere) 
`dotnet tool update -g docfx`
 3) On your local machine, create a folder and Git Clone this project to the folder.
 4) In the terminal, go to the docfx project folder and run  
    `docfx docfx.json --serve`
5) You can now preview the docs on http://localhost:8080

## Authoring docs

This is a monorepo for all Profitbase product docs.  
You put the docs in the appropriate `articles\[product]` folder, and images in the `images\[product]` folder. You can add sub-folders as you see fit, but use naming that makes sense and is easy to understand. 

![image](https://github.com/user-attachments/assets/078f54e2-0b11-4af3-b265-28056f04e7d5)

When contributing, use standard git workflow 
1) Create a new branch
2) Do commits
3) Create a PR

Docfx does not support hot reload, so you need to run
`docfx docfx.json --serve`
and refresh the browser to review any changes you make.

