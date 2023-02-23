# css-wmp
A sample project for WMP CSS code

## Development
### Branching
  To get started on developing a feature, first have a local copy of the dev branch. 
  
  `git fetch origin dev
  git checkout dev`
  
  All new development features must be branched off dev. 
  
  `git checkout -b feature/madams/CSSPOD-1-create-index-page`
  
  Name your branch by using a prefix, your first initial and lastname, and the JIRA ticket number.
  
  #### Prefixes
  - feature
  - bugfix
  
  Optionally, you can choose to include a summary of the ticket after the JIRA ticket number. Summaries must use kabob format.
  
  `feature/madams/CSSPOD-1-create-index-page`
  
  #### Hotfixes
  When a hotfix is necessary, developers will branch off the main branch, not dev. The hotfix prefix must be used
  
  `git checkout main
  git branch -b hotfix/madams/CSSPOD-0-everything-is-green-fix-it`
  
  To merge a hotfix branch, it must first be merged into dev. Once it passes testing in dev, it can then be merged into main
  
 ### Pull Requests
  Pull requests must be made before changes can be merged. Users will need to open a PR to dev. Another developer must then code review the changes. If the reviewer finds errors or has suggestions, they must leave comments in the PR so that the original developer may make the necessary changes.
  
  #### Code Review Etiquitte
  The following rules need to be followed when conducting and receiving code review. Multiple violations will have users banned from further development
  1. No bullying
  2. Clear concise comments, avoid "this is wrong" or "do this instead"
  3. Avoid programmer golf
  4. Give code examples when applicable
  5. Stick to the scope of the ticket
  6. Keep reply threads to a minimum. If further discussion is required, take it off Github
  7. Encourage one another, we are all honing our craft
  
  After pull request approval, developers who created the branch should merge the code changes into dev. Dev changes will be tested periodically. We are not an agile team, more of a light jog.
  
  
