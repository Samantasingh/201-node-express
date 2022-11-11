## **Node Express Hello-World**
#### NPM Achievements 201
###### Samanta Singh

1. Create a directory - ($ mkdir hello-world)

2. Once inside the directory, **($ cd hello-world)**, use command **($ npm init)**. This command will create a file named *package.json*

3. Hit return and accept through the defaults unless you want to give your *js* file a unique name.

4. After accepting all defaults, enter command **(npm install express)**.

5. Inside the *js* file (index.js) add the following code;
![](/screencaps/js-code.png)
* The *const port* informs us on what port the server runs. In our case it is **3000**

6. After saving the code, we run the app by using the command **$ node (*name-of-your-js*.js)**

7. You can finally load the [output](http://localhost:3000/) in the browser. http://localhost:3000/**
![](/screencaps/hello-world.png)

8. Create a gitignore file inside the directory (before pushing any commits) **($ touch .gitignore)**

9. Inside *.gitignore* write *node_modules.* By creating a *.gitignore* file, any entries inside the directory/file will be ignored once inside the reposatory.