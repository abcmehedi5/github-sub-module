* Step-1 connect sub module into main repo or main module =>  git submodule add git@github.com:abcmehedi5/github-sub-module-1.git submodule-1
* Step-2 Initialize and update the submodule=> git submodule update --init --recursive
* Step-3 Commit the Submodule => git add submodule-1

# After the change sub module-----------
Update the submodule to the latest commit:
* git submodule update --remote submodule-1
