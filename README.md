# MEMORIES_PROJECT

# CLIENT FOLDER............

1. `npx create-react-app ./`
2. `npm cache clean --force` (in case client folder gets removed open a new terminal and try this and then again `npx create-react-app ./`)
3. modify package.json and `npm install` and if it fails with `npm ERR! code ENOTEMPTY while npm install` delete node modules with  
   `rm -r node_modules` & try again.

# SERVER FOLDER............

1.  `npm init -y` (To initialise empty package json run the command in the sever directory)
2.  `npm install body-parser cors express mongoose nodemon`
