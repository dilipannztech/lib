->how to add the sub_module into your project
git submodule add https://github.com/dilipannztech/lib.git

->update submodule

1.naviagte to your submodule folder

example:
cd path/to/submodule

2.then pull

command
git pull

3.navigate to the main folder

example:
cd ..

command
git submodule update --remote

explanation for git submodule update
Then, go back to the main repository and use the git submodule update command to update the submodule reference:
