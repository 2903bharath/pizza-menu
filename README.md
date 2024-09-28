# pizza-menu
Small react website showing pizza menu

deploying procedure:
First, make sure you have the gh-pages package installed. This package helps to deploy your React app to GitHub Pages.

```sh
npm install --save gh-pages
```

Add the predeploy and deploy scripts to your package.json if they are not already there:
```
{
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
  }
}


```
Run the deploy script:
```sh
npm run deploy
```
