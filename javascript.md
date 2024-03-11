# Javascript

If you're writing a short simple script, something like applying specific styles to all elements with a specific class if a user does something, you can use vanilla javascript.

Don't bother with framworks or build tools, and simply write your code in a filename.js file and include it in your HTML file.

Or just write your javascript in a script tag in your HTML file.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Page</title>
  </head>
  <body>
    <h1>My Page</h1>
    <p>Some text</p>
    <script src="filename.js"></script>
    <script>
      console.log('Hello, world!');
    </script>
  </body>
</html>
```

If you're writing a more complex application or module, you'll want to use a buildtool and probably a framework.

There are many to choose from but personally I use:

- [volta](https://volta.sh/) as the node/npm version manager
- [vite](https://vitejs.dev/guide/) as the build tool

- [react](https://reactjs.org/) or
- [next](https://nextjs.org) as the framework

## Steps

install volta

```sh
brew install volta
brew doctor
# do some config
volta install node@lts
```

```sh
npm create vite@latest [appname]
# choose appropriate options
```

```sh
cd [appname]
volta pin node@lts
volta pin npm@latest
npm install
npm run dev
```
