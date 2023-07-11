# gliu
webpage
## Steps
1. Github account
2. Create a repository
3. Install gh-pages
  * `npm install gh-pages --save-dev` to save to the packages.json as dev dependency
4. Update the package.json
  * update scripts section
    * `"predeploy" : "npm run build",
      "deploy" : "gh-pages -d build",`
  * update the homepage
    *   `http://{github-username}.github.io/{repo-name}`

