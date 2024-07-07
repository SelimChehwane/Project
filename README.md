Steps to create linked submodules:

1-Create the repository seperatly
(git init if locally or git clone the repo if remote)

2-Link repo with remote repo if you did it locally(git add remote origin)

3-Make sure each repo has at least one commit

4-Navigate to root repo and create submodules (git submodule add "the link to the repo")

5-Make sure .gitmodules was created in the root repo

6-Use OS module in the python files to create a path to the yaml file in the root repo and access it from inside the submodules.

7-Test to make sure everything is working properly and that the python files in the submodules can access and read the yaml file in the root repo