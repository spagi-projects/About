# About SPAGI Projects

The SPAGI Projects GitHub organisation is designed to house all the projects being worked on in relation to improving the SPAGI algorithm, or applications of it to other projects. It gives the ability to share files across projects, keep up to date with the work that we others are doing and have a central source of truth for the current suite of projects.

## Usage

Individual repositories should be created per project or item that is being worked on. Issues can be created in each repository to show what is currently being worked on. In each repository, a feature branch should be created and committed to until the feature is complete and it can be merged back to the master branch.

### Issues
Issues can be used to track what is being worked on in each of the projects. They are an opportunity to make comment on projects, make some suggestions or ask others for help. This can work as a task management/goal setting system, with people being assigned certain issues, or attaching tags to help categorise the issues. 

## Usage from RStudio

The workflow for working in RStudio requires you to first create a new repository from the organisation and then create a new project from version control in the RStudio GUI. This will prompt you to provide a url from GitHub or another remote, which can be found at the top right of the repository. 

### Committing

After it has been cloned, you can add any files as you normally would and commit them to the repository. This is done through first staging the files (checking the box next to each of the files in the git pane) and then pressing the commit button. This will prompt you for message describing the change that you have made (at first this is something like 'initial commit'). Once you have made a commit, you can push this change to GitHub for others to access. 

### Branching

To create a branch, you can press the purple create branch button. This allows you to work on new features/modifications while preserving the original functionality in the master branch. Commits relating to a particular feature should be grouped into branches. Once a feature branch has been completed, it can be merged back to the master. 

## Accessing Projects

The projects can be used in 2 ways:

1. R packages can be installed through running the function `devtools::install_github("spagi-projects/{package name}")`
2. R packages and other projects can be cloned using the RStudio interface or the GitHub interface. This allows the files to be edited freely, as the project has been downloaded to your computer. 
