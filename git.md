mkdir new_folder
cd new_folder
git init
git flow init
git remote add origin <URL> 
git push --set-upstream origin develop

git flow feature start <NAME>
git flow feature finish <NAME>