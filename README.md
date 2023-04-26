# MEMORIES_PROJECT

# CLIENT FOLDER............

1. `npx create-react-app ./`

2. `npm cache clean --force` (in case client folder gets removed open a new terminal and try this and then again `npx create-react-app ./`)

3. modify package.json and `npm install` and if it fails with `npm ERR! code ENOTEMPTY while npm install` delete node modules with  
   `rm -r node_modules` & try again.

4. In case of error like `digital envelope routines::unsupported` try `export NODE_OPTIONS=--openssl-legacy-provider`. Not sure but it has     something to do with node js version. For details check out `https://stackoverflow.com/questions/69692842/error-message-error0308010cdigital-envelope-routinesunsupported`

5. For front end tried `npm install @material-ui/core`
# SERVER FOLDER............

1.  `npm init -y` (To initialise empty package json run the command in the sever directory)
2.  `npm install body-parser cors express mongoose nodemon`
3.  Learn how to connect & create mongodb cluster - Done but not entirely sure why its not worked in port:5000. It has worked on port:5001
