# St.Martin

# WebApp boilerplate with React 

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://f4287f81-b219-4b05-a038-b7abc73cd6a0.ws-us0.gitpod.io/#/workspace/St.Martin)

### Requirements:
- Make sure you are using node version 8

##### Install the packages:
```
$ npm install
```

## Start coding!

Start the webpack server with live reload:
- `$ npm run start` for windows, mac, linux or Gitpod.
- `$ npm run gitpod` for gitpod Users.

### Styles
You can update the `styles/index.scss` or create new `.scss` files inside `styles/` and import them into your current scss or js files depending on your needs.

### Components
Add more files into your `./src/js/components` or styles folder as you need them and import them into your current files as needed.

### Views (Components)
Add more files into your `./src/js/views` and import them in `./src/js/layout.jsx`.

### Context
This boilerplate comes with a centralized general Context API. The file `./src/js/store/flux.js` has a base structure for the store, we encourage you to change it and adapt it to your needs.

React Context [docs](https://reactjs.org/docs/context.html)

The `Context.Provider` is already set, you can use the `Context.Consumer` to get the `store` and `actions` from the Context. Check `/views/demo.jsx` to see a demo.

## Publish your website!

This boilerplate is 100% compatible with the free github pages hosting.
To publish your website you need to push your code to your github repository and run the following command after:
```sh
$ npm run deploy
```
Note: You will need to [configure github pages for the branch gh-pages](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/#enabling-github-pages-to-publish-your-site-from-master-or-gh-pages)
