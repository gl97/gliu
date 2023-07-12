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
5. Run the deploy `npm run deploy`
6. You can change where you deploy from but always remember to reset the repository origin back 
 * If you want to deploy from a private repository use the command `git remote set-url origin https://github.com/gl97/gliu.git`
 * To reset back to the original repository use the command `git remote set-url origin https://github.com/gl97/javascript.git`


