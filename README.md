->how to add the sub_module into your project
git submodule add https://github.com/dilipannztech/lib.git

->update submodule

1.naviagte to your submodule folder

example:
cd path/to/submodule

before take a pull please check that your in a main branch of a lib

2.then pull

command
git pull

<!-- other ways of coping the code
git checkout _your_commit_id_ -->

3.navigate to the main folder

example:
cd ..

command
git submodule update

explanation for git submodule update
git submodule update command to update the submodule reference:
