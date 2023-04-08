Steps to deploy repository to Github Pages:
1. In the respective folder, run 'npm install gh-pages --save-dev'
2. Head over to package.json, in the top level, add '"homepage": "https://<USERNAME>.github.io/<REPO_NAME>"', for eg. mine would be "homepage": "https://penghao-99.github.io/react_app_deploy/"
3. In package.json under scripts, add '"deploy": "npm run build&&gh-pages -d build"'
4. run 'npm run deploy' to build your project and then deploy it to your gh-pages branch
5. Under Settings for your repo, find the GitHub Pages section and select “gh-pages branch” under Source
  
And you should be good to go!
  
Note: It will take awhile for you to see the live site url, and some more time for the website to be uploaded
