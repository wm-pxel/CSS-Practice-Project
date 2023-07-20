# css-wmp
A sample project for WMP CSS code

## Local Setup
  The CSS practice project is a static project. This means that you do not need to have a service running locally in order to see the rendered project.
### Github
  You'll first want to either fork or clone a copy of the project. Forking gives you your own personal copy that will be connected to your Github account. Cloning makes a copy that is directly connected to the original project.

  If you want to contribute to the project, you will need to clone a copy. This means that you have read/write access to the repo. Cloning can be done through SSH or https.
  
  Github has an intro tutorial if this is your first time using Github or git. [Intro Tutorial](https://docs.github.com/en/get-started/quickstart/hello-world)

### Code Editing
  You may use any code editor with this project. VS Code, Atom, SublimeText, Eclipse, etc, all work with HTML and CSS. Be sure to try out syntax highlighting. This can be downloaded in the desired code editor.

  Once you have your code editor and have downloaded the repo to your local machine, you can access the code. Simply open the CSS-WMP project folder in your code editor. You should see the images, pages, and styles folders as well as the index.html and README files.

### Rendering the Project
  From your code editor or file viewer (Mac finder or Windows file explorer), right click on the index.html file. You should see an option to either open the file in your browser or copy the full file path. If you do the latter, paste the full file path into the browser of your choice (preference would be Chrome or Firefox). Hit enter in the url and the project's homepage should appear.

  Congrats, you have the CSS practice project working on your local machine! Time for some fun.

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
  2. Clear concise comments, avoid "this is wrong" or "why did you do this?"
  3. Avoid programmer golf
  4. Give code examples when applicable
  5. Stick to the scope of the ticket
  6. Keep reply threads to a minimum. If further discussion is required, take it off Github
  7. Encourage one another, we are all honing our craft
  
  After pull request approval, developers who created the branch should merge the code changes into dev. Dev changes will be tested periodically. We are not an agile team, more of a light jog.
  
  
