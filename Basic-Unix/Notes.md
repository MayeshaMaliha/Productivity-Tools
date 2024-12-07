# Absolute path vs. relative path

A full path specifies the location of a file from the root directory. It is independent of your present directory, and must begin with either a “/” or a “~”. In this example, the full path to our “project-1” file is: 

/home/projects/project-1

A relative path is the path relative to your present working directory. If our present working directory is the “projects” folder, then the relative path to our “project-1” file is simply: 

project-1

# Path shortcuts

One period “.” is your current working directory

Two periods “..” is the parent directory (up one from your present working directory) 

A tilde “~” is your home directory.

# More path examples

Example 1.     Your current working directory is ~/projects and you want to move to the figs directory in the project-1 folder

Solution 1: cd ~/projects/project-1/figs (absolute)
Solution 2:  cd project-1/figs (relative)
Example 2.     Your current working directory is ~/projects and you want to move to the reports folder in the docs directory

Solution 1: cd ~/dos/reports (absolute)
Solution 2: cd ../docs/reports (relative)
Example 3.     Your current working directory is ~/projects/project-1/figs and you want to move to the project-2 folder in the projects directory.

Solution 1: cd ~/projects/project-2 (absolute)
Solution 2: cd ../../project-2 (relative)

