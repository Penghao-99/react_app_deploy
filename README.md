Steps to deploy repository to Github Pages:
1. In the respective folder, run 'npm install gh-pages --save-dev'
2. Head over to package.json, add '"homepage": "https://<USERNAME>.github.io/<REPO_NAME>"', for eg. mine would be "homepage": "https://penghao-99.github.io/react_app_deploy/"
3. In package.json under scripts, add '"deploy": "npm run build&&gh-pages -d build"'
4. run 'npm run deploy' to update your website.
Note: It takes some time for the website to be uploaded
