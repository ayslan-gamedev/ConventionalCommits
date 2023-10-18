# 🚀 Commit Patterns with Emojis and Conventional Commits
<a href="https://github.com/Ayslan-gamedev/ConventionalCommits/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ayslan-gamedev/ConventionalCommits?color=blue&style=flat-square"></a>

This repository creates an automatic way to write automatically organized commits through git commands, using a commit pattern that combines emojis and the Conventional Commits style for more descriptive and informative commit messages.

According to the Conventional Commits documentation, Semantic Commits are a simple convention to use in commit messages. This convention defines a set of rules for creating an explicit commit history, facilitating the creation of automated tools.

## ⚙️ Initial Setup

  Follow the steps below to set up and start using this commit pattern in your project:
  
  ### 1. Make sure you already have node.js installed on your machine.
  
  If you don't have Node.js installed yet, install in [nodejs.org](https://nodejs.org/en)
  
  ### 2. Start the repository and enter the following commands to install dependencies into the repository:

    npm install --save-dev commitizen cz-customizable
    npm install --save-dev commitizen
       

  ### 3. Extract the files released in this repository
  
  ### 4. Then move the “.czrc” and “.cz-config.js” files to the root of the repository.
  
  ### 5. write the following lines in your .gitignore file:
    # Node Modules (commitzen dependencies)
    /node_modules/
    
    # CommitzenConfiguration
    .czrc
    .cz-config.js
    package.json
    package-lock.json
    cz-config.js
  
  ### 6. Update the package.json
  Write the item below inside "package.json":

     "scripts": {
       "test": "echo \"Error: no test specified\" && exit 1",
       "commit": "npx git-cz"
     }
  Now, you're ready to start using the commit pattern! use “npx git-cz” to commit

## 🛠️ How to Use
To create commits following this pattern, follow these steps:

Run the custom commit command:

    npx git-cz
    
You will be presented with a series of interactive questions. Fill in the requested information, such as the commit type, a concise description, and optionally a more detailed body.
After answering the questions, the commit will be automatically generated with the proper formatting, including emojis and the Conventional Commits format.
you can read the commit instructions at https://github.com/Holivane/padroes-de-commit

## 🙏 Acknowledgments

This commit pattern was inspired by the work of [Holivane](https://github.com/Holivane) and their repository [padroes-de-commit](https://github.com/Holivane/padroes-de-commit). We appreciate Holivane for their contribution to the development community and for sharing their knowledge of commit best practices.

Detailed documentation on how to use commit messages is available in Holivane's repository. Be sure to check [here](https://github.com/Holivane/padroes-de-commit) for more information on commit message formatting.

This project is an evolution based on the excellent work started by Holivane.
