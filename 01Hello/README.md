## init

1. Open VSCode
2. Create a folder on the desktop with a name `js`
3. Drag this `js` folder on to the VSCode and click `yes, I trust the authors`
4. create a folder called `01Hello`

## The Classic way of writing js

1. creating an HTML file, `index.html` in `01Hello` and using emmet to populate it with data (emmet means using `!` mark) and then click on the file `index.html` from you `js` folder
2. Create a JS file, `script.js` in ` 01Hello` folder and link it using `script` tag in the `index.html` file
3. Create an `h1` tag with `hello` in the `index.html` file
   > console.log("hello world!");
4. Open this `index.html` file in the browser
5. Also, open the console in the browser
6. Console log your name in the `script.js`

So, is this the right way to write js? Absolutely yes, there is no issue in it. But this is not the only way to write js. There is a much better, advanced and modern way to write JavaScript.

## JS Engine

just like any other programming language, JS needs certain tooling so that it can convert what you code into machine understandable code and that is the foundation of running JavaScript.

In Case, if you remember in C or C++ you are supposed to compile the code first before even looking at or executing the file. But for many years people believed that js is magically doing something and running in the browser. So nobody thought about JS Engines. Some of these engines are `V8` by Google, and `Spider Monkey` by Mozilla.

By default, browsers come with these engines, so the above code worked fine. But if we want to write js standalone in our computer without the help of browsers, we need to have a tool that can simulate complies js for us. Things like`NodeJS` are such implementations that can convert standalone js code so that you don't have to always rely on attaching your js to the HTML and then work with it.

Use this link to [download the LTS version](https://nodejs.org/en/download/) of the NodeJS according to your operating system and install `NodeJS`

## If you are a Windows user

- I highly suggest you [install git bash](https://git-scm.com/downloads)
- And then make git bash as the default terminal in your VSCode
- Create a Github account and configure git bash

```
git config --global user.name "YourName"
git config --global user.email "TestEmail@mail.com"
```

> You can run native linux commands using git bash, like `ls`, `pwd` and many

## Confirm if you installed NodeJS or not

1. Open git bash
2. Run the command `node -v`
3. If you can see a node version, then everything is up and running.

## Proof of Concept

As previously mentioned, we are using `NodeJS` so that there is no need to write JS only for us to have a browser application(`index.html`), we can now use our OS to run JavaScript.

Similar to how we linked a `script.js` file using the `script` tag in the `index.html` now we can use the command in git bash

```
node script.js
```

## Which version of JS we should use?

- How HTML, CSS and JavaScript interlined to make a website
- ECMAScript is just a guideline and JS follows these
- ES6 release is a major drastic change
