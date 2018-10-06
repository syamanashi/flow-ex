### This is just a demo playground for using and practicing GitFlow.

**To setup GitFlow on a Mac**
1. Install git-flow (AVH Edition): `$ brew install git-flow-avh`
2. Install git-flow-completion for your bash or ZSH environment: 
3. Navigate to a folder and initialize it as a git repo: `$ git init`
4. Initialize the git repo with GitFlow (always required on your local environment): `$ git flow init`
5. Checkout 'master' branch: `$ git checkout master`
6. Either clone a repo or Create a Github repo and add the origin to your local repo: `$ git remote add origin git@github.com:syamanashi/flow-ex.git`
7. Push 'master' and 'develop' branches to origin: `$ git push --all`
8. Create a new feature branch: `$ git flow feature start 1-My-feature-branch`
9. Make changes and then commit: `$ git add .` then `$ git commit -m "commit message"`
10. Publish your changes to origin so others can collaborate (optional): `git flow feature publish`
11. Add more changes, commit them, and push changes: `git push`
12. Finish the feature (which will merge feature branch into develop, checkout develop, and clean up the feature branch locally and remotely): `$ git flow feature finish`
13. Push changes from develop to origin: `$ git push`
14. Create a release branch named v1.0.1: `$ git flow release start v1.0.1`
15. Publish the release branch so that it can be deployed to QA environment from origin (GitHub): `$ git flow release publish`
16. Following QA approval, when ready to merge the release into master (production), finish the release: `$ git flow release finish`
17. Push branch changes to origin: `$ git push --all`
18. Push tags changes to origin: `$ git push --tags`

Note: There are similar commands to work in 'hotfix' or 'bugfix' branching.

**Other resources**
- git-flow cheatsheet: http://danielkummer.github.io/git-flow-cheatsheet/
- Atlassian Gitflow Workflow: https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow
- Install gitflow-avh: https://github.com/petervanderdoes/gitflow-avh/wiki/Installing-on-Mac-OS-X
- Install git-flow-completion: https://github.com/petervanderdoes/git-flow-completion
- Smart branching with SourceTree and Git-flow: https://blog.sourcetreeapp.com/2012/08/01/smart-branching-with-sourcetree-and-git-flow/
- git-flow documentation: https://media.readthedocs.org/pdf/git-flow/latest/git-flow.pdf
  
