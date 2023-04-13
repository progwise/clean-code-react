# The prerequisite chapter


## VSCode - why?

## clean-coders basic git workflow

* git init/clone
* git add/commit
* git log/reset
* git checkout/switch
* git pull/push/merge
* what is a pull request?

and how to do it in VS Code

## node and npm and why?


# Introduction to GitHub, VSCode, Node.js, and NPM

## The advantages of VSCode in comparison with other IDEs (Integrated Development Environments.)(Why do we use VSCode?) 

VSCode (Visual Studio Code) is a popular code editor that provides a rich set of features for software development. Here are some reasons why many developers prefer to use VSCode for their coding projects instead of other code editors like Atom, Sublime Text, or Notepad++:

1. **Versatility:** VSCode supports a wide range of programming languages and frameworks, making it suitable for various types of projects, from web development to machine learning and data science.

2. **Intuitive User Interface:** VSCode has a clean and user-friendly interface with a responsive layout, making it easy to navigate, edit, and debug code in a single window.

3. **Integrated Version Control:** VSCode has built-in support for popular version control systems like Git, allowing developers to manage their code changes, commits, and branches directly from the editor without having to switch between different applications.

4. **Extensibility:** VSCode has a rich ecosystem of extensions that provide additional functionalities, such as syntax highlighting, code completion, and debugging tools, making it highly customizable to suit individual development needs and preferences.

5. **Debugging Capabilities:** VSCode has robust debugging capabilities with built-in support for various programming languages, making it easy to identify and fix code issues and bugs.

6. **Integrated Terminal:** VSCode has an integrated terminal that allows developers to run commands and scripts directly from the editor, reducing the need to switch between different applications and windows.

### The basic git workflow and how to do it in VS Code as well as in the terminal: 

1. Initialize a Git repository:
- Terminal: Open a terminal window and navigate to the directory of your project. Run `git init` to initialize a new Git repository.
- VS Code: Open your project in VS Code. In the VS Code integrated terminal, you can also run `git init` to initialize a new Git repository.

2. Create a branch:
- Terminal: Run `git checkout -b <branch_name>` to create a new branch and switch to it.
- VS Code: Click on the Git icon in the Activity Bar on the side of the VS Code window to open the Source Control view. Click on the "Create a new branch" button (with a "+" icon) and enter a branch name to create a new branch.

3. Make changes:
- Terminal/VS Code: Make changes to your code using any editor of your choice. Git will automatically track the changes.

4. Stage and commit changes:
- Terminal: Run `git add <file>` or `git add .` to stage the changes. Then run `git commit -m "Your commit message here"` to commit the changes.
- VS Code: In the Source Control view, you'll see a list of changes. Click on the "+" icon next to the changes you want to stage, enter a commit message in the "Message" field, and click on the checkmark icon to commit the changes.

5. Pull and push changes:
- Terminal: Run `git pull origin <branch_name>` to pull changes from the remote repository, and then run `git push origin <branch_name>` to push your changes to the remote repository.
- VS Code: Click on the "Sync Changes" button (with arrows in a circular pattern) in the Source Control view to pull and push changes.

6. Review and merge changes:
- Terminal/VS Code: Once your changes are pushed to the remote repository, you can create a pull request or merge request for review, depending on the code hosting platform you're using. Your team members can review your changes and provide feedback.

7. Repeat the process:
- Terminal/VS Code: You can repeat the above steps for different features or bug fixes by creating new branches, making changes, staging, committing, pulling, pushing, and reviewing until your changes are merged into the main branch.



## Clean Coders Basic Git Workflow

Using Git in VSCode is straightforward and follows a basic workflow that includes the following steps:

1. **Initialize or Clone Repository:** To create a new Git repository in VSCode, you can open your project folder in VSCode, go to the Source Control view by clicking on the Source Control icon in the Activity Bar on the side, and click on the Initialize Repository button. Alternatively, if you want to clone an existing repository, you can use the "Clone Repository" option from the File menu or the Source Control view.

2. **Stage and Commit Changes:** After making changes to your code, you can stage the changes by clicking on the "+" icon next to the changed files in the Source Control view. Once the changes are staged, you can add a commit message and click on the checkmark icon to commit the changes.

3. **View Commit History and Undo Changes:** You can view the commit history by clicking on the "..." icon in the Source Control view and selecting "View History." This will show you a list of commits with their commit messages. You can also right-click on a commit and select "Revert" or "Reset" to undo changes made in a particular commit.

4. **Switch Branches:** You can switch branches in VSCode by clicking on the branch name in the bottom left corner of the VSCode window and selecting the desired branch from the dropdown menu. Alternatively, you can use the "Checkout" option from the Source Control view context menu to switch to a different branch.

5. **Pull, Push, and Merge:** To pull changes from a remote repository, you can use the "Pull" option from the Source Control view context menu or click on the circular arrow icon in the bottom left corner of the VSCode window. To push changes to a remote repository, you can use the "Push" option from the Source Control view context menu or click on the up arrow icon. To merge changes from one branch to another, you can use the "Merge Branch" option from the context menu of the target branch in the Source Control view.

6. **Create and Review Pull Requests:** VSCode provides an extension called "GitHub Pull Requests and Issues" that allows you to create and review pull requests directly from the editor. You can install this extension from the VSCode Extensions Marketplace and use it to create pull requests , review changes, and leave comments on pull requests, making it easy to collaborate with other developers on GitHub.

## Node.js and NPM - Why?

Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine, allowing developers to run JavaScript on the server-side. NPM (Node Package Manager) is the default package manager for Node.js and is used to install, manage, and share third-party libraries or modules. Here are some reasons why Node.js and NPM are popular among developers:

**Server-side JavaScript:** Node.js enables developers to write server-side JavaScript code, which allows for a consistent language and development environment on both the front-end and back-end of web applications.

**Large Package Ecosystem:** NPM has a vast collection of open-source packages that can be easily installed and used in Node.js projects. This makes it convenient for developers to leverage existing libraries and modules to speed up development and add functionality to their applications.

**Fast Performance:** Node.js is known for its fast performance due to its event-driven, non-blocking I/O model. This makes it ideal for building scalable and high-performance applications, especially those that require handling a large number of concurrent connections.

**Asynchronous Programming:** Node.js utilizes asynchronous programming, allowing developers to write code that can handle multiple tasks concurrently without blocking the main thread. This makes it well-suited for applications that require real-time updates, such as chat applications or online gaming.

**Easy Package Management:** NPM provides a straightforward and unified way to manage dependencies in Node.js projects. It allows developers to easily install, update, and manage third-party packages, making it efficient to handle project dependencies and keep applications up-to-date.

**Active Community Support:** Node.js and NPM have a large and active community of developers, which means that there are abundant resources available for learning, troubleshooting, and getting support. There are numerous online forums, documentation, tutorials, and communities where developers can seek help and collaborate with fellow Node.js enthusiasts.

In conclusion, Node.js and NPM are powerful tools that provide developers with the ability to write server-side JavaScript, manage packages, and build scalable and performant applications. Their popularity stems from their versatility, large package ecosystem, fast performance, asynchronous and non-blocking I/O, easy package management, and active community support.

I hope this tutorial provides you with a helpful introduction to GitHub, VSCode, Node.js, and NPM. By familiarizing yourself with these tools and workflows, you can streamline your development process, collaborate with other developers, and efficiently manage your codebase. Happy coding! If you have any further questions or need additional guidance, feel free to ask.
