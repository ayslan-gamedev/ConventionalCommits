# 🚀 Commit Patterns with Emojis and Conventional Commits
<a href="https://github.com/Ayslan-gamedev/ConventionalCommits/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ayslan-gamedev/ConventionalCommits?color=blue&style=flat-square"></a>

This repository demonstrates a commit pattern that combines emojis and the Conventional Commits style for more descriptive and informative commit messages.

According to the Conventional Commits documentation, Semantic Commits are a simple convention to use in commit messages. This convention defines a set of rules for creating an explicit commit history, making it easier to create automated tools.

## ⚙️ Initial Setup

  Follow the steps below to set up and start using this commit pattern in your project:
  
  ### 1. Initialize a Git Repository
  
  If you don't have a Git repository yet, initialize one with the following command:

       git init
  
  ### 2. Install Dependencies
  
  Install the necessary dependencies to work with this commit pattern:
  
       npm install --save-dev commitizen cz-customizable
       npm install --save-dev commitizen

  ### 3. Add Configuration Files
  Add the .czrc and .cz-config.js files to your project. You can find these files directly in this repository in the releases section.

  ### 4. Update the package.json
  In the package.json file, add the following section to your scripts:

       "scripts": {
         "test": "echo \"Error: no test specified\" && exit 1",
         "commit": "npx git-cz"
       }
  Now, you're ready to start using the commit pattern!

## 🛠️ How to Use
To create commits following this pattern, follow these steps:

Run the custom commit command:

    npx git-cz
    
You will be presented with a series of interactive questions. Fill in the requested information, such as the commit type, a concise description, and optionally a more detailed body.
After answering the questions, the commit will be automatically generated with the proper formatting, including emojis and the Conventional Commits format.

## 🙏 Acknowledgments

This commit pattern was inspired by the work of [Holivane](https://github.com/Holivane) and their repository [padroes-de-commit](https://github.com/Holivane/padroes-de-commit). We appreciate Holivane for their contribution to the development community and for sharing their knowledge of commit best practices.

Detailed documentation on how to use commit messages is available in Holivane's repository. Be sure to check [here](https://github.com/Holivane/padroes-de-commit) for more information on commit message formatting.

This project is an evolution based on the excellent work started by Holivane.
