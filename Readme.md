# Grocery Data

20230208

1. Create a file called "package.json"
- You can create package.json automatically

2. Create a git repo and store code files there. 

3. Use npm
```
npm init
```
- fill out application.
- data that you filled will be stored in a  package.json file.

4. How do you run the index.js file.

- #1: You can "node index.js"
- #2: 

    a. Add script to package.json
    b. You can use script to perform certain commands. 
    c. Ther are unlimited scripts that you can write.
    ex: build, compress, etc.

"npm run win"

5. Create a server using ExpressJS
- npm install or npm i
- npm i express: install express.
- notice node_modules get created: folder where all the packages in the file will go.
- there are dependencies that is being used in package.json. 
- created lock file. package-lock.json.

** explore 
npm i will install everything from the package.json because package.json indicates what dependencies are needed to run the project.
**
- This is useful when you transfer files because all you need to do is to share package.json and other pc will just run the npm i to get necessary dependencies you need to run the project.

- package-lock.json checks whether the package has been edited or not to make it secure. If the package works, you don't want people to modify the package. If friends run the package.json, it makes sure that npm is getting the exact version so that it would run the app precisely.

- make sure to save package.json

6. 



