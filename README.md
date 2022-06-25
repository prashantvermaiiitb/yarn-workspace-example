# sample readme

1. Creating the yarn workspace, makign this Repository as private so that it will not be published.
2. we are using mono-repo as the workspacename. 
3. Since we have not published it so that's not giving any error in the local and we are able to publish the code easily.
4. Yarn install is not giving any error.

# creating packages for better management of the dependencies.

1. create packages folder.
2. Move the adminclient and webclient inside the packages folder.
3. Inside package json we have to update the workspaces to have packages/* as the path.
   

# installing dependency only in 1 package 
1. do "yarn add bootstrap" in the webclient.
2. Now see the node_modules at the top level, this will be included in the top level folder.git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/prashantvermaiiitb/yarn-workspace-example.git
git push -u origin master

this is my read me