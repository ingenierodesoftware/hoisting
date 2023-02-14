# hoisting

This repo demonstrates the concept of hoisting. In few words hoisiting is the JS default behaviour of moving all the declarations of functions and variables to the top of the context without initialization. To say, it is possible to use a function or variable before they get declared as long as the keywork `var` preceeds the declaration

# run

`docker build -t demo_hoisting_js .`

`docker docker run -it --rm demo_hoisting_js ash`

Inside the container:

`node app.js`

```
Hello second
Hello first
Hello first
```
