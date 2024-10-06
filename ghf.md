## 1. What are Enterprise Managed Users?

**It's a GitHub Enterprise feature that allows you to manage user access from an external identity provider such as Azure AD or Okta.**

### Explanation:
Enterprise Managed Users (EMUs) is a feature in **GitHub Enterprise Cloud** that allows enterprises to control and manage user identities and access via external identity providers, such as **Azure AD** or **Okta**. With this feature, all user accounts in the organization are managed directly by the identity provider, enabling enterprises to enforce security policies, such as single sign-on (SSO), and streamline access management.

Other key points:
- With EMUs, users log in via their company-managed credentials (through the identity provider).
- Administrators can manage user provisioning, deprovisioning, and access control from the identity provider.
- EMUs are commonly used in larger organizations with strict compliance and security needs.

## 2. Is there a free version of GitHub for organizations?

**Yes**

### Explanation:
GitHub offers a free plan for organizations. This plan includes:
- Unlimited public and private repositories.
- Access to core collaboration features like pull requests, issues, and GitHub Actions.
- A limited amount of GitHub Actions minutes and storage.

## 3. What is a pull request template?

**Pull request template is a file that defines the default pull request structure that project contributors will automatically see when they open a pull request.**

### Explanation:
A pull request template is a predefined format that helps standardize the information that contributors include when they create pull requests in a repository. It ensures that important details, such as descriptions, related issues, or testing instructions, are not missed. These templates are typically stored in a `.github/PULL_REQUEST_TEMPLATE` directory or in the root directory of the repository.

## 4. Which of these statements about `saved replies` are true? (Choose two.)

1. You can create, edit and delete them in your GitHub account settings in the `Saved replies` section.
2. Saved replies are comments that you can reuse in issues and pull requests.

### Explanation:
- **`Saved replies`** allow users to create reusable comments for common responses in issues and pull requests. These can be managed (created, edited, and deleted) in the **Saved replies** section of GitHub account settings.
- Saved replies are not limited to repository owners but are available to all users for reusing comments to streamline communication.

## 5. On your personal GitHub dashboard you received a notification that user octocat has created a new repository `octocat/my-repo`. Why did you receive that notification?

**Because you are following the user octocat**

### Explanation:
You received the notification because you are following the user **octocat**. When you follow a user on GitHub, you get notifications about their activities, such as repository creation, discussions, and more. The other options do not explain why you would receive a notification about a new repository.

## 6. How can you start using GitHub Copilot after activating the GitHub Copilot subscription?

**Setup GitHub Copilot in one of the supported IDE's such as Visual Studio Code or JetBrains and start coding**

### Explanation:
After activating the GitHub Copilot subscription, you need to install and configure GitHub Copilot in one of the supported IDEs, such as **Visual Studio Code** or **JetBrains** IDEs. Once set up, GitHub Copilot will start providing code suggestions while you write code. There is no need to edit repository settings or set up GitHub Actions for Copilot.

## 7. What is the role of an organization moderator?

**Moderators are organization members who, in addition to their permissions as members, are allowed to block and unblock non-member contributors, set interaction limits, and hide comments in public repositories owned by the organization.**

### Explanation:
Organization moderators in GitHub have additional responsibilities beyond regular members, such as managing interactions with non-member contributors. They can block or unblock non-members, set interaction limits, and hide inappropriate comments in public repositories owned by the organization. They do not manage billing or security settings, and they do not have complete access to the organization.

## 8. What is the GitHub Marketplace?

**GitHub Marketplace is a place where developers can find tools that help build software right alongside their code.**

### Explanation:
GitHub Marketplace is a platform where developers can discover and integrate tools and services that assist with development tasks, such as continuous integration (CI), security, project management, and more. These tools can be used directly in GitHub repositories to streamline workflows and build software more efficiently.


## 9. If you face yourself often writing the same set of comments on issues or pull requests, what GitHub feature would you use to save time?

**Saved replies**

### Explanation:
**Saved replies** is a GitHub feature that allows you to create reusable comments that can be quickly inserted into issues and pull requests. This is particularly useful when you find yourself repeating the same responses frequently. You can create, manage, and use saved replies to save time and streamline communication.


## 10. What are the different options that allow you to automate operations in your GitHub Project? (Choose three.)

1. **GitHub Dependabot**
2. **GitHub GraphQL API**
3. **GitHub Actions**

### Explanation:
- **GitHub Dependabot** helps automate dependency updates, ensuring that your project stays secure and up-to-date by automatically checking for updates in your dependencies.
- **GitHub GraphQL API** allows developers to automate tasks by querying and mutating data from GitHub programmatically, enabling automation for various operations like fetching issues, repositories, and more.
- **GitHub Actions** is a powerful tool for automating workflows, allowing you to build, test, and deploy your code directly from GitHub.

## 11. What is the effect of adding a line `Closes #11` to the pull request's description?

**Once that pull request is merged, the issue #11 will be closed automatically.**

### Explanation:
When you include a line like `Closes #11` in the pull request description, GitHub will automatically close the referenced issue (in this case, issue #11) when the pull request is merged. This feature helps in linking pull requests to issues, ensuring that once the pull request is resolved, the related issue is also marked as closed.


## 11 - What is the effect of adding a line `Closes #11` to the pull request's description?

**Once that pull request is merged, the issue #11 will be closed automatically.**

### Explanation:
When you include a line like `Closes #11` in the pull request description, GitHub will automatically close the referenced issue (in this case, issue #11) when the pull request is merged. This feature helps in linking pull requests to issues, ensuring that once the pull request is resolved, the related issue is also marked as closed.


## 12 - Can you change a gist from public to secret after creating it?

**No**

### Explanation:
Once a GitHub gist is created as public, it cannot be changed to secret. However, you can delete the public gist and create a new secret one. GitHub does not allow toggling between public and secret states after a gist has been published.


## 13 - Which of these statements regarding GitHub Codespaces lifecycle are true? (Choose three.)

1. **A Codespace's lifecycle begins when you create a Codespace and ends when you delete it.**
2. **You can stop and restart a Codespace without losing the changes that you make to your project.**
3. **You can disconnect and reconnect to an active Codespace without affecting its running processes.**

### Explanation:
- **A Codespace's lifecycle** starts when it is created and ends when it is deleted, allowing users to manage it over its lifecycle.
- You can **stop and restart a Codespace** without losing the changes you've made since these are saved automatically in the environment.
- You can **disconnect and reconnect** to an active Codespace, which continues running even if you disconnect, and you can resume your work without issues.
- Stopping a Codespace manually terminates its running processes, but disconnecting from it does not.



## 14 - What are Repository Insights?

**It's a place where you can see data about the repository such as code frequency, list of the most active contributors and more.**

### Explanation:
**Repository Insights** provide data about repository activity, including code frequency, commit history, and contributor statistics. This feature helps you understand how a repository evolves over time and identify key contributors. It is focused on providing an overview of code activity rather than security or best practices.


## 15 - What are the effects of you following a user on GitHub?

**You will get notifications on your personal dashboard about their public activity.**

### Explanation:
When you follow a user on GitHub, you will receive notifications about their **public activity**, such as new repositories, starred repositories, and public discussions. Following does not grant access to private repositories or enable private conversations, as GitHub does not have a chat feature for private messaging.


## 16 - If there are multiple Readme.md files in a GitHub repository, what is the priority order to show them?

**Root directory, .docs directory, .github directory**

### Explanation:
GitHub prioritizes displaying the `README.md` file from the **Root directory** first. If there is no `README.md` in the root, GitHub will look for one in the `.docs` directory, and if it's not found there, it will check the `.github` directory. This priority ensures that the most relevant documentation is typically shown first.


## 17 - What are GitHub Wikis?

**Wikis is a repository feature for hosting documentation.**

### Explanation:
GitHub **Wikis** are a feature available in repositories that allows project maintainers and contributors to create and host comprehensive documentation for the project. Wikis are ideal for maintaining more detailed information that goes beyond the project's `README.md` file, like usage guides, architecture explanations, and contributor guidelines.


## 18 - What are the different permission levels for a repository owned by a personal account? (Choose two.)

1. **collaborator**
2. **repository owner**

### Explanation:
For repositories owned by a personal GitHub account:
- **Repository owner** has full control over the repository, including managing settings, collaborators, and access control.
- **Collaborator** is someone who has been granted access to contribute to the repository by the owner, with specific permissions such as read, write, or admin.

The other roles (security manager, project owner, billing manager) do not exist as permission levels in personal repositories.


## 19 - What is GitHub Desktop?

**It's a GUI Application for working with Git and GitHub on your computer.**

### Explanation:
**GitHub Desktop** is a graphical user interface (GUI) application that allows users to interact with Git and GitHub directly from their computer. It simplifies the process of managing repositories, making commits, pushing changes, and creating pull requests without using the command line. It is not a pricing plan or a self-hosted version of GitHub.


## 20 - Which of these GitHub features serves the purpose of an adaptable spreadsheet, task board, and a roadmap that integrates with issues and pull requests on GitHub to plan and track your work effectively?

**GitHub Project**

### Explanation:
**GitHub Projects** is a feature that provides an adaptable tool for project management, combining the flexibility of a spreadsheet and the organization of a task board. It integrates with issues and pull requests, allowing teams to plan, track, and manage their work effectively, serving as a roadmap for development and collaboration.


## 21 - Is GitHub Copilot free to use?

**Yes, if you are a student, teacher, or maintainer of a popular open source project**

### Explanation:
**GitHub Copilot** is generally a paid service, but it is free for certain users, including **students, teachers, and maintainers of popular open source projects**. These individuals can apply for a free subscription through specific programs like GitHub Education or GitHub Sponsors. For others, it requires a subscription fee.


## 22 - Who are repository collaborators?

**Collaborators are people who have been granted write access to a repository.**

### Explanation:
**Collaborators** are individuals who have been granted **write access** to a repository. They can make changes to the repository, such as committing code, creating branches, and pushing changes. Raising issues or making contributions does not automatically make someone a collaborator unless they are explicitly given access by the repository owner.


## 23 - What are the use cases for labels?

**Categorizing issues and pull requests**

### Explanation:
**Labels** in GitHub are used primarily for **categorizing issues and pull requests**. They help in organizing and filtering issues by type, priority, status, or other custom categories that the repository maintainers define. Labels are not used for categorizing files, assigning contributor roles, or including them in release notes.


## 24 - What is the name of GitHub's continuous integration and continuous delivery (CI/CD) platform?

**GitHub Actions**

### Explanation:
**GitHub Actions** is GitHub's CI/CD platform that allows developers to automate workflows, such as building, testing, and deploying code, directly from their repositories. It integrates with the rest of GitHub and provides powerful automation capabilities for CI/CD pipelines.


## 25 - Who should have 2 Factor Authentication enabled on GitHub?

**All GitHub users**

### Explanation:
**2 Factor Authentication (2FA)** should be enabled by **all GitHub users** to enhance account security. This adds an extra layer of protection beyond just a password, safeguarding your account from unauthorized access. While it is especially important for GitHub Organization owners and Enterprise Server users, all GitHub users are encouraged to enable 2FA for better security.

## 26 - How can you define guiding protocols for users intending to submit bug reports or propose new features in your repository so they know what information to fill-in?

**Create issue templates**

### Explanation:
**Issue templates** allow repository maintainers to guide users when submitting bug reports or feature requests. These templates can be customized to include specific questions or information that should be provided, ensuring that all necessary details are included. This improves the quality of the issues and makes it easier for maintainers to address them.

## 27 - Which GitHub Project layout would best serve as a Kanban board?

**Board layout**

### Explanation:
The **Board layout** in GitHub Projects is best suited for a **Kanban board**, as it visually organizes tasks in columns, typically representing different stages of progress (e.g., "To Do," "In Progress," "Done"). This layout allows for easy tracking and movement of tasks between stages, which is the core concept of Kanban.


## 28 - What is a repository in GitHub?
**It's a place where you can store your code, your files, and each file's revision history.**

### Explanation:
A **repository** in GitHub is a location where developers can store their source code, files, and track changes to those files over time through **version control**. GitHub repositories help in managing development projects, collaborating with others, and maintaining a history of changes.

## 29 - How can you work together with a friend of yours on a repository that you have created on your personal GitHub account?

**Go to repository settings and invite him as a collaborator**

### Explanation:
To work with someone on a repository created under your personal GitHub account, you can go to the **repository settings** and invite them as a **collaborator**. This will give them the necessary permissions to collaborate on the project, such as making changes, creating pull requests, and pushing commits. Sharing credentials is not recommended and does not follow GitHub security best practices.

## 30 - What is a GitHub Pro plan?

**GitHub Pro is a paid plan for personal accounts that offers additional features in addition to the free plan.**

### Explanation:
**GitHub Pro** is a paid plan designed for **personal accounts**, offering additional features beyond the free plan, such as advanced tools for repository management, insights, and priority support. It is not for organizations or enterprises, nor is it a certification path.


## 31 - What are the different repository visibility options?

**Private, Public and Internal (Enterprise only)**

### Explanation:
Repositories on GitHub can be set to:
- **Public**: Visible to everyone on GitHub.
- **Private**: Only visible to the repository owner and collaborators.
- **Internal**: This option is available only to **GitHub Enterprise** users, making the repository visible to members of the same enterprise but not to the public.

"Personal" is not a visibility option but rather refers to ownership of the repository.

## 32 - If you stop your GitHub Codespace environment can you come back to the changes later if you haven't committed them?

**Yes, that's the default behavior when stopping and then starting a GitHub Codespace.**

### Explanation:
When you stop a **GitHub Codespace**, your changes are not lost even if you haven't committed them. The environment persists the current state, including uncommitted changes, so you can come back and continue working on your project later when you restart the Codespace.

## 33 - Which feature in GitHub Projects enables you to effortlessly generate graphs and charts for visualizing the current status and historical progression of your project?

**Project Insights**

### Explanation:
**Project Insights** in GitHub Projects provides visualizations such as graphs and charts that help track the current status and historical progression of your project. These insights help teams monitor progress, manage workloads, and identify bottlenecks more easily. Other options like GitHub Actions and Milestones are not specific to visualization.

## 34 - Under which GitHub pricing plan can you create an unlimited number of public repositories?

- All of them
- Enterprise
- Free
- Pro
- Team and Enterprise
- Team

**All of them**

### Explanation:
On GitHub, you can create an **unlimited number of public repositories** under all pricing plans, including **Free, Pro, Team, and Enterprise**. GitHub does not limit the number of public repositories a user or organization can create, regardless of the plan.

## 35 - What language is used to write comments on GitHub issues and pull requests?

**Markdown**

### Explanation:
GitHub uses **Markdown** as the language for writing comments on issues, pull requests, and discussions. Markdown allows you to format text using a simple syntax, making it easy to include headings, lists, code snippets, links, and more. While you can embed HTML in Markdown, the primary language is Markdown.


## 36 - Which of these best describes git?

**Git is a distributed version control system.**

### Explanation:
**Git** is a **distributed version control system** that allows developers to track changes in their code, collaborate with others, and manage different versions of their projects. It is independent of GitHub, which is a platform that provides hosting for Git repositories. Git is designed to work without a central server, giving each user a full copy of the repository.

## 37 - What are the differences between GitHub Copilot Individual and GitHub Copilot Business?

**GitHub Copilot Individual can only be used by personal accounts and GitHub Copilot Business is used by organizations and enterprises**

### Explanation:
**GitHub Copilot Individual** is designed for personal use by individuals with personal accounts, while **GitHub Copilot Business** is intended for organizations and enterprises, providing features such as administrative controls, enhanced security, and support for both public and private repositories. Both are paid features, and both use AI models trained on publicly available code, not private source code.


## 38 - What can you find in the security tab of a repository?

**A security overview of that repository such as vulnerabilities in dependencies, code scanning results, and secret scanning alerts**

### Explanation:
The **Security tab** in a GitHub repository provides an overview of the repository's security status. It includes features such as **vulnerability alerts** for dependencies, **code scanning results**, and **secret scanning alerts**. This helps maintainers identify and address security risks within their code and its dependencies.


## 39 - Which of these is a repository feature that is used as a community forum to have conversations, ask questions, post announcements, and share ideas?

**Discussions**

### Explanation:
**GitHub Discussions** is a feature that allows users to create a **community forum** within a repository. It is designed for conversations, asking questions, posting announcements, and sharing ideas, providing a space for collaboration beyond just code contributions. Unlike pull requests and issues, Discussions are more focused on broader conversations and brainstorming.

## 40 - How can you link a pull request to an issue? (Choose two.)

1. **Manually from either the pull request or the issue view.**
2. **By using a keyword in the pull request description and referencing the issue number.**

### Explanation:
You can link a pull request to an issue either:
1. **Manually** by using the interface to link a pull request and an issue.
2. By using **keywords** like "Closes #issue_number" in the **pull request description**. This automatically links the pull request to the referenced issue and closes the issue when the pull request is merged.

Referencing the issue number in the commit message or code changes does not automatically link the pull request to the issue.


## 41 - What are GitHub teams?

**It's a group of GitHub users from the same organization.**

### Explanation:
**GitHub Teams** are groups of GitHub users within an organization. Teams allow organization owners to manage access to repositories and resources more efficiently by granting permissions to a group of users rather than individual accounts. This feature is specific to organizations, not personal repositories.

## 42 - Which git feature allows developers to concurrently work on the same codebase without causing conflicts with each other?

**branch**

### Explanation:
A **branch** in Git allows developers to work on different parts of the codebase concurrently without interfering with each other's work. Each branch is an independent line of development, so changes made in one branch do not affect others until they are merged. This enables collaborative development without immediate conflicts.

## 43 - What is GitHub Mobile?
**It's a mobile app for iOS and Android that allows you to work with GitHub from your phone.**

### Explanation:
**GitHub Mobile** is an app available for **iOS and Android** that allows developers to manage their GitHub repositories, collaborate, review pull requests, and track issues directly from their mobile devices. It helps users stay productive while on the go without needing access to a desktop or laptop.

## 44 - Can you disable the issues tab on a repository?
**Yes**

### Explanation:
You can **disable the issues tab** in a GitHub repository by going to the repository settings and unchecking the "Issues" option under the "Features" section. This will remove the Issues tab from the repository, and contributors will no longer be able to submit issues through GitHub.


## 45 - What are the different available options for adding issues and pull requests to a GitHub Project board?

**Individually, automatically, or in bulk.**

### Explanation:
You can add **issues and pull requests** to a GitHub Project board in various ways:
1. **Individually**: Add them manually, one at a time.
2. **Automatically**: Configure workflows to automatically add issues and pull requests based on conditions.
3. **In bulk**: Select multiple items and add them all at once.

These options provide flexibility in managing tasks on the project board.

## 46 - Which tool helps you keep the repository dependencies up to date?

**Dependabot**

### Explanation:
**Dependabot** is a GitHub tool that helps keep your repository dependencies up to date by automatically checking for outdated dependencies and creating pull requests to update them. This ensures that your project stays secure and uses the latest versions of libraries and packages.

## 47 - What is a GitHub Codespace?

**It's a preconfigured development environment specifically setup for a repository. It allows you immediately start writing code for a project without having to setup a local development environment.**

### Explanation:
A **GitHub Codespace** is a cloud-hosted, preconfigured development environment that allows you to quickly start coding on a project without needing to set up a local environment. It integrates with your GitHub repository, making it easy to collaborate and contribute without worrying about dependencies and environment setup.


## 48 - GitHub Action workflows are triggered by events. Which of these are valid events that GitHub Actions support? (Choose two.)

1. **A pull request is opened**
2. **A commit is pushed to a branch**

### Explanation:
GitHub Actions workflows can be triggered by various events, including when **a pull request is opened** or **a commit is pushed to a branch**. These events initiate the workflows defined in the repository's configuration, allowing automated tasks to be executed in response to specific activities in the repository.


## 49 - How can you assign a person to an issue or pull request?
**By using the Assignees field in the sidebar**

### Explanation:
To assign a person to an issue or pull request, you use the **Assignees field in the sidebar**. This allows you to specify who is responsible for addressing the issue or reviewing the pull request. Mentioning them or adding a label does not officially assign them to the task.

## 50 - Where can you find publicly available GitHub Actions?

**GitHub Marketplace**

### Explanation:
Publicly available **GitHub Actions** can be found in the **GitHub Marketplace**. The marketplace allows users to browse, discover, and integrate third-party actions into their workflows, making it easy to automate tasks like CI/CD, code linting, and deployment without needing to create actions from scratch.


## 51 - What is the meaning of the word distributed in distributed version control system?

**It means that developers can have a full copy of the repository and its history on their local machine.**

### Explanation:
In a **distributed version control system** (like Git), each developer has a full copy of the repository, including its entire history, on their local machine. This allows them to work independently of the central server, commit changes locally, and synchronize with others when needed. This is a key feature of Git that distinguishes it from centralized version control systems.

## 52 - What are some actions you can do in regards to Project Templates in your organization? (Choose three.)

1. **With admin or write permissions, copy an existing project as a template**
2. **Configure recommended templates to your organization's members**
3. **Create a new template to be used as a base for new projects**

### Explanation:
In GitHub organizations, you can:
- **Copy an existing project** with admin or write permissions and use it as a template for new projects.
- **Configure recommended templates** that members of the organization can use to create consistent projects.
- **Create new templates** to serve as a base for future projects.

Publishing templates in GitHub Marketplace is not currently a feature, and setting a project as a template requires admin permissions, not just write permissions.


## 53 - What GitHub feature allows the creation of preconfigured development environments where all necessary tools and dependencies to contribute to a repository are installed?

**GitHub Codespaces**

### Explanation:
**GitHub Codespaces** allows the creation of **preconfigured development environments** that are hosted in the cloud. These environments come with all the necessary tools, configurations, and dependencies already installed, enabling developers to start contributing to a project immediately without setting up a local environment.

## 54 - What is the relation between Git and GitHub?

**Git is a distributed version control system and GitHub is a platform that uses Git as its core technology.**

### Explanation:
**Git** is a **distributed version control system** that developers use to track changes in their codebase. **GitHub** is a platform built on top of Git that provides cloud-based repository hosting, collaboration features, and additional tools for developers to manage their projects. GitHub enhances Git by adding social features and integrations.

## 55 - Which of these files can customize your GitHub profile?

**a profile README.md file**

### Explanation:
You can customize your GitHub profile by creating a **profile repository** with the same name as your GitHub username, and adding a **README.md file** to it. This README will appear on your public GitHub profile page, allowing you to showcase information about yourself, your projects, or anything else you'd like to display.

## 56 - Which of the following Git commands allow you to create a new branch and start working on it in one line? (Select two.)

1. **git switch -c <new_branch_name>**
2. **git checkout -b <new_branch_name>**

### Explanation:
- **`git switch -c <new_branch_name>`** creates a new branch and switches to it.
- **`git checkout -b <new_branch_name>`** also creates a new branch and switches to it.

Both commands allow you to create a new branch and begin working on it in one step. Other commands listed either don't exist or serve different purposes.

## 57 - Which of the following actions cannot be performed directly from GitHub Desktop?

**Managing GitHub Actions**

### Explanation:
**GitHub Desktop** allows users to switch between branches, stash changes, and commit changes directly from the application. However, managing **GitHub Actions** (such as setting up or configuring workflows) must be done through the GitHub web interface, not GitHub Desktop.

## 58 - What is a GitHub Codespace deep link?
**It's a link that points to a specific GitHub.com Page that allows you to create a new GitHub Codespace and select specific configuration.**

### Explanation:
A **GitHub Codespace deep link** is a URL that allows you to quickly create a new Codespace with predefined configurations, such as branch, environment, or resources. This is useful for developers who want to share a direct link that starts a new Codespace with specific settings for others to use or collaborate on.

## 59 - Which of these layouts are available in GitHub Projects? (Choose three.)

1. **Roadmap layout**
2. **Table layout**
3. **Board layout**

### Explanation:
In **GitHub Projects**, you have access to different layouts to organize and manage tasks:
- **Roadmap layout**: Helps visualize project timelines and long-term goals.
- **Table layout**: Displays tasks in a spreadsheet-like view.
- **Board layout**: Provides a Kanban-style view for organizing tasks in columns.

"Scrum layout," "Agile layout," and "Project layout" are not actual layouts in GitHub Projects.


## 60 - What is InnerSource?

**InnerSource refers to the practice of applying open source principles within an organization.**

### Explanation:
**InnerSource** is the practice of adopting **open source methodologies** within a company or organization. It involves leveraging the collaborative, transparent, and decentralized principles of open source software development to improve code sharing, collaboration, and innovation internally.

## 61 - What is a git commit?

**A commit is a snapshot of a repository at a specific point in time.**

### Explanation:
A **git commit** is a snapshot of the repository at a specific point in time. It captures the changes made to files and directories and records them in the repository's history. Each commit is associated with a unique identifier (hash) and typically includes a commit message describing the changes made.


## 62 - Which of these is NOT a role in a GitHub Organization?

- Security manager
- Organization moderator
- GitHub App manager
- Organization member
- Organization owner
- Organization architect
- Outside collaborator
- Billing manager

### Answer:
The correct answer is:

**Organization architect**

### Explanation:
**Organization architect** is not a recognized role in a GitHub Organization. The valid roles include **Organization owner**, **Organization member**, **Outside collaborator**, **Billing manager**, **GitHub App manager**, **Security manager**, and **Organization moderator**. Each of these roles has specific permissions within the organization.

## 63 - What happens when you choose to close a Project?

**The content is retained and you have the ability to reopen it later.**

### Explanation:
When you choose to **close a Project** in GitHub, the content is **retained**, and you can **reopen** the project at any time. Closing a project does not delete it or its associated data; it simply hides it from the active projects view, keeping all data intact.


## 64 - What is one of the main benefits for using a Personal Access Token (PAT) instead of a standard username and password for GitHub authentication?


**PAT can be used for authentication to GitHub when using the GitHub API or the command line. Users generate a token via the GitHub's settings option, and tie the token permissions to a repository or organization.**

### Explanation:
A **Personal Access Token (PAT)** is an authentication method that is primarily used for API or command line interactions with GitHub. Unlike a username and password, PATs provide more granular control by allowing users to specify permissions for certain actions, such as repository access or organization management.


## 65 - What are some actions you can do in regards to Repository Templates? (Choose two.)

1. **Create a new repository from a repository template**
2. **Create a repository template from an existing repository**

### Explanation:
With **Repository Templates**, you can:
1. **Create a new repository from a repository template**, which allows you to quickly replicate the structure and files of the template.
2. **Create a repository template from an existing repository**, enabling others to use it as the base for their projects.

The other actions, such as deleting repositories or creating organizations from templates, are not valid features of repository templates.

## 66 - How does the synchronization between GitHub projects and issues and pull requests work?

**Updates to the issues and pull requests will be automatically reflected in GitHub Projects. This integration works both ways, so that when you change information about a pull request or issue in your project, the pull request or issue reflects that information.**

### Explanation:
GitHub provides **two-way synchronization** between GitHub Projects and associated issues and pull requests. Any updates made to issues or pull requests will automatically be reflected in the project, and vice versa, ensuring that all information remains consistent across the platform.


## 67 - Which of these statements about GitHub Enterprise deployment options are true? (Select two.)

1. **GitHub Enterprise Server is a self-hosted platform that runs on the company's infrastructure.**
2. **GitHub Enterprise Cloud is a set of advanced functionality on GitHub.com.**

### Explanation:
- **GitHub Enterprise Server** allows organizations to host GitHub on their own infrastructure, providing complete control over their data and environment.
- **GitHub Enterprise Cloud** refers to the enhanced features available on the GitHub.com platform, offering advanced tools and integrations without the need for self-hosting. The other options inaccurately describe the nature of GitHub Enterprise products.


## 68 - Why would a repository owner want to use milestones? (Choose two.)

1. **To associate issues and pull requests with specific project phases**
2. **To have an overview of how much work is left to complete a project phase**

### Explanation:
**Milestones** in GitHub are used to organize issues and pull requests into specific project phases, allowing the repository owner to associate tasks with particular goals or deadlines. Additionally, milestones provide a way to visualize progress and understand how much work remains to complete a phase of the project.

## 69 - Which of these is a practice that encourages collaboration, visibility, and sharing of code among different teams within an organization? 

**InnerSource**

### Explanation:
**InnerSource** is a practice that applies open source principles within an organization, encouraging collaboration, visibility, and sharing of code among different teams. It fosters a culture of contribution and knowledge sharing similar to open source communities, allowing for more effective teamwork and project development.


## 70 - What are the different GitHub pricing plans for personal accounts? (Select two)

- Business
- Enterprise
- Pro
- Personal
- Team
- Free
- Advanced

### Answer:
The correct answers are:

1. **Pro**
2. **Free**

### Explanation:
For personal accounts, the available GitHub pricing plans include **Pro**, which offers additional features beyond the free plan, and **Free**, which provides essential functionalities for individual users. Other plans like Business, Enterprise, Team, and Advanced are geared towards organizations rather than individual users.

## 71 - How can you customize the environment that is run in GitHub Codespaces?

**By creating a .devcontainer/devcontainer.json configuration file**

### Explanation:
To customize the environment in **GitHub Codespaces**, you create a `.devcontainer/devcontainer.json` configuration file in your repository. This file allows you to specify the settings, extensions, and tools that should be included in the Codespace environment. You can also use a custom Dockerfile in the `.devcontainer` directory if you need a specific base image, but the primary method for customization is through the `devcontainer.json` file.

## 72 - What feature is unique to GitHub Desktop compared to github.com?

**Visualize branch histories in a graphical interface**

### Explanation:
**GitHub Desktop** offers the unique feature of visualizing branch histories in a **graphical interface**, allowing users to see the relationships between branches and commits in a more intuitive way. While you can clone repositories, view insights, and create new repositories on both GitHub Desktop and github.com, the graphical visualization of branch histories is a specific functionality provided by the desktop application.


## 73 - How can you enforce status checks passing before merging a pull request to the main branch?

**By creating a branch protection rule**

### Explanation:
To enforce that status checks must pass before merging a pull request into the **main branch**, you can create a **branch protection rule**. This rule allows you to specify conditions, such as requiring that specific status checks (like tests) pass before a pull request can be merged. While GitHub Actions can be used to set up these checks, it is the branch protection rule that enforces them at the merge level.

## 74 - What is CodeQL?

**A code analysis tool**

### Explanation:
**CodeQL** is a code analysis tool used to identify vulnerabilities and bugs in source code by allowing developers to write queries to analyze their codebases. It enables automated security analysis, helping developers find and fix security issues in their code. CodeQL is commonly integrated into GitHub workflows to enhance code security.

## 75 - Which of these definitions best describes open source software?

**It's software with source code that anyone can inspect, modify, and enhance.**

### Explanation:
**Open source software** is defined as software that provides its source code to the public, allowing anyone to inspect, modify, and enhance it. This fosters collaboration and transparency, enabling users to contribute to the software's development and improvement. While many open source projects are free to use, the core definition revolves around the accessibility of the source code.


## 76 - Which of these tools serves as an AI pair programmer that offers autocomplete-style suggestions as you code?

**GitHub Copilot**

### Explanation:
**GitHub Copilot** is an AI pair programming tool that provides autocomplete-style suggestions as you write code. It uses machine learning models trained on a vast amount of code from public repositories to offer context-aware code completions and help developers write code more efficiently.

## 77 - What syntax is used in GitHub Markdown to create a task list?

- [ ] and - [x]
- <task> and <done>
- // TODO: and // DONE:
- # TODO: and # DONE:

### Answer:
The correct answer is:

**- [ ] and - [x]**

### Explanation:
In **GitHub Markdown**, task lists are created using the syntax `- [ ]` for an unchecked task and `- [x]` for a checked task. This allows users to create interactive checkboxes in issues, pull requests, and comments, making it easy to track tasks.

## 78 - What are GitHub's slash commands?

**It's a way to quickly insert complex Markdown into your pull request or issue comments and descriptions.**

### Explanation:
**GitHub's slash commands** are used in issues and pull requests to quickly insert predefined text or complex Markdown formatting. By typing a slash (`/`), users can access a list of available commands, making it easier to add templates, labels, or other structured content without manually formatting it.


## 79 - What are the different forms of two-factor or multi-factor authentication supported by GitHub? (Choose five.)

- Passkey
- Time-based one-time password (TOTP)
- Text message
- Phone call
- GitHub mobile
- Email
- Security key

### Answer:
The correct answers are:

1. **Passkey**
2. **Time-based one-time password (TOTP)**
3. **Text message**
4. **Phone call**
5. **Security key**

### Explanation:
GitHub supports multiple forms of two-factor or multi-factor authentication, which enhance account security. The supported methods include:
- **Passkey**: A secure method for authentication.
- **Time-based one-time password (TOTP)**: A time-sensitive code generated by an authenticator app.
- **Text message**: A code sent via SMS.
- **Phone call**: An authentication code received through a phone call.
- **Security key**: A physical device used for authentication, such as a USB or NFC key.

**GitHub mobile** and **email** are not typically considered methods of two-factor or multi-factor authentication in this context.

## 80 - What are the different deployment options for GitHub Enterprise? (Select two.)

- GitHub Enterprise Free
- GitHub Enterprise Cloud
- GitHub Enterprise Pro
- GitHub Enterprise Advanced
- GitHub Enterprise Server
- GitHub Enterprise Team

### Answer:
The correct answers are:

1. **GitHub Enterprise Cloud**
2. **GitHub Enterprise Server**

### Explanation:
The two primary deployment options for **GitHub Enterprise** are:
- **GitHub Enterprise Cloud**: A cloud-hosted version of GitHub Enterprise that provides advanced features and functionality on GitHub.com.
- **GitHub Enterprise Server**: A self-hosted version that allows organizations to run GitHub on their own infrastructure, providing complete control over their data and environment.

Other options listed are not recognized as separate deployment options for GitHub Enterprise.


## 81 - Which of these workflows are built-in automations in GitHub Projects? (Choose two.)

1. **When pull requests in your project are merged, their status is set to Done.**
2. **When issues or pull requests in your project are closed, their status is set to Done.**

### Explanation:
GitHub Projects include built-in automations that can automatically update the status of issues and pull requests based on their state. Specifically, when pull requests are merged or issues are closed, their status can be set to Done, helping teams track progress efficiently. The other options do not represent built-in automations in GitHub Projects.

## 82 - What are draft pull requests?

**Draft pull requests are pull requests that are not ready to be reviewed yet.**

### Explanation:
**Draft pull requests** are a type of pull request that indicates that the changes are not yet ready for review. This allows developers to open a pull request to signal their intention to work on it while communicating to others that it is still a work in progress. Once the author feels the pull request is ready, they can mark it as ready for review.

## 83 - What are the two available options when you no longer need to use a Project?

**Archive and close**

### Explanation:
When you no longer need to use a GitHub Project, you can **archive** it to preserve its state for future reference without actively using it, or **close** it to indicate that the project is no longer in progress. Archiving a project keeps it accessible while preventing further changes, whereas closing a project marks it as completed.

## 84 - Your project requires appropriate hardware to run. Can you customize the amount of CPU cores that will be allocated to your GitHub Codespace environment?

**Yes, you can choose an alternative machine type either when you create a codespace or at any time after you've created a codespace.**

### Explanation:
When creating a **GitHub Codespace**, you have the option to select different machine types, which allows you to customize the amount of CPU cores and memory allocated to your environment. You can also change the machine type at any time after creating the Codespace, providing flexibility based on your project's hardware requirements.


## 85 - Which of these actions will make sure that prior to any push to the main branch, the changes have been approved by at least two people? (Choose three.)

1. **Create a branch protection rule for main branch**
2. **On the branch protection rule, require at least 2 approvals before merging a pull request**
3. **On the branch protection rule, require a pull request before merging**

### Explanation:
To ensure that changes pushed to the main branch are approved by at least two people, you need to:
1. **Create a branch protection rule** for the main branch, which allows you to enforce various rules.
2. **Require at least 2 approvals** on that branch protection rule before merging any pull request.
3. **Require a pull request** to be made before merging, ensuring that all changes are reviewed before they can be integrated into the main branch.

The other options, like status checks or deployment protection rules, do not specifically address the requirement for multiple approvals before merging to the main branch.


## 86 - Which of these statements about the differences of issues and discussions is true?

**GitHub Discussions are for conversations that need to be transparent and accessible but do not need to be tracked on a project board and are not related to code, unlike GitHub Issues.**

### Explanation:
**GitHub Discussions** are designed for broader conversations that can include topics not directly related to issues or bugs, such as feature requests, ideas, or general questions. They do not require tracking on a project board. In contrast, **GitHub Issues** are specifically intended for tracking tasks, bugs, or feature requests, and are often linked to a project board for management and organization.


## 87 - What is the GitHub Sponsors program?

**It's a way to financially support the developers of the open source projects.**

### Explanation:
The **GitHub Sponsors** program allows individuals and organizations to financially support developers and maintainers of open source projects. This initiative aims to provide a sustainable funding model for contributors, enabling them to continue their work on important projects while receiving compensation for their efforts.


## 88 - Where can you disable repository features such as issues, wikis, or projects on a repository that you own?

**In the repository settings**

### Explanation:
You can disable features like **issues, wikis, or projects** for a repository that you own by going to the **repository settings**. In the settings, you will find options to enable or disable these features based on your preferences for managing the repository.


## 89 - Who can set up billing or assign billing managers for an organization? (Select three.)

1. **Owner at the organization level**
2. **Owner at the enterprise level**
3. **Billing managers at the organization level**

### Explanation:
Only specific roles can manage billing for an organization on GitHub. This includes:
- **Owner at the organization level**: Has full control over organization settings, including billing.
- **Owner at the enterprise level**: Can manage billing for all organizations within the enterprise.
- **Billing managers at the organization level**: Designated individuals who can handle billing tasks for the organization.

The other roles listed do not have the authority to set up billing or manage billing managers.


## 90 - How does GitHub help people that want to write proper issue and pull request comments but don't know Markdown syntax?

**There is a text formatting toolbar on issue and pull request comment forms which generates Markdown for you.**

### Explanation:
GitHub provides a **text formatting toolbar** in the comment sections of issues and pull requests, which helps users format their text without needing to remember Markdown syntax. This toolbar includes buttons for common formatting options like bold, italics, code blocks, and lists, making it easier for users to write clear and well-structured comments.

## 91 - What are the possible GitHub account types? (Select three.)

- Organization accounts
- Enterprise accounts
- Company accounts
- Personal accounts
- Shared accounts

### Answer:
The correct answers are:

1. **Organization accounts**
2. **Enterprise accounts**
3. **Personal accounts**

### Explanation:
The possible GitHub account types include:
- **Personal accounts**: Individual user accounts for personal use.
- **Organization accounts**: Accounts that allow multiple users to collaborate on repositories under a single organization.
- **Enterprise accounts**: Designed for large organizations, providing advanced features and control over multiple organization accounts.

"Company accounts" and "shared accounts" are not official account types on GitHub.


## 92 - Which of these is a common use case for GitHub Actions?

**Running automated tests prior to merging a pull request**

### Explanation:
A common use case for **GitHub Actions** is to automate the process of **running tests** on your codebase before merging a pull request. This helps ensure that any new changes do not break existing functionality, allowing for continuous integration and better code quality. While GitHub Actions can also be used for other tasks, running automated tests is a widely adopted practice.


## 93 - What is the GitHub Flow?

**It refers to a branch-based workflow where developers create a branch for each new change they're working on, and then open pull requests to get their code reviewed, tested, and merged into the main branch.**

### Explanation:
**GitHub Flow** is a lightweight, branch-based workflow that allows developers to work on features or fixes in isolated branches. When the work is ready, they open a pull request to facilitate code review, testing, and merging back into the main branch. This method promotes collaboration and helps maintain a stable main branch while allowing for continuous integration of new features.

## 94 - Which of these statements best describes what GitHub is?

**GitHub is a platform that uses Git as its core technology and adds features that make collaboration and code management easier.**

### Explanation:
**GitHub** is a web-based platform that leverages **Git**, a distributed version control system, to facilitate collaboration, code management, and project tracking. It enhances the functionality of Git with features such as pull requests, issues, project boards, and more, making it easier for teams to work together effectively on software development projects.


## 95 - Which of these is true regarding custom fields for items in GitHub Projects?

**Custom fields enable the addition of metadata beyond the built-in options, such as target dates and iteration fields.**

### Explanation:
**Custom fields** in GitHub Projects allow users to add metadata to items beyond the default options. This includes the ability to include various types of data such as target dates, iterations, and other relevant information that can enhance project tracking and management.


## 96 - You want to merge changes from branch feature-a into main and you are creating a pull request. Which branch should be the base branch and which branch should be the compare branch?

**main is the base branch and feature-a is the compare branch.**

### Explanation:
In a pull request, the **base branch** is the branch you want to merge changes into, which in this case is `main`. The **compare branch** is the branch you are merging from, which is `feature-a`. Therefore, when creating the pull request, you set `main` as the base branch and `feature-a` as the compare branch.


## 97 - What are pinned repositories on GitHub?

**Pinned repositories are repositories that you have pinned to the top of your GitHub profile.**

### Explanation:
**Pinned repositories** on GitHub are those that users have selected to highlight on their profiles. This feature allows users to showcase specific repositories, making it easier for visitors to view and access important or favorite projects directly from their profile page.

## 98 - What is/are the common GitHub pricing plan(s) for both personal and organization accounts?

- Business
- Advanced
- Enterprise
- Team
- Personal
- Pro
- Free

### Answer:
The correct answers are:

1. **Pro**
2. **Free**

### Explanation:
Both **Pro** and **Free** plans are available for individual personal accounts as well as for organization accounts on GitHub. The **Free** plan offers basic features suitable for individuals and small teams, while the **Pro** plan provides additional features such as enhanced repository insights and advanced collaboration tools.

## 99 - Which of the GitHub features best serves as a simple way to share small code snippets with others?

**Gists**

### Explanation:
**Gists** are a feature of GitHub that allows users to share small code snippets, notes, or any other text files easily. Gists can be public or secret, making them a convenient way to collaborate on or share code snippets without needing a full repository.


## 100 - Which Markdown element is not correctly paired with its syntax?

- Bold text - **bold**
- Inline code - '''code'''
- Heading - # Heading
- Hyperlink - [title](https://)

### Answer:
The correct answer is:

**Inline code - '''code'''**

### Explanation:
The syntax for **inline code** in Markdown is `` `code` `` (using backticks), not `'''code'''`. The other elements are correctly paired with their respective syntax:
- **Bold text**: `**bold**`
- **Heading**: `# Heading`
- **Hyperlink**: `[title](https://)`

## 101 - If a GitHub Discussion is converted into an Issue and the issue is closed or referred to using its corresponding # number, will the discussion be modified?

**No**

### Explanation:
When a **GitHub Discussion** is converted into an **Issue**, the original discussion remains unchanged. Closing the issue or referring to it using its corresponding number does not modify the original discussion. Both discussions and issues maintain their independent states, even if one is derived from the other.


## 102 - Which information can be found in the Pulse section in the Insights tab of a repository? (Choose four)

1. **List of unresolved conversations**
2. **Pull requests open/merged ratio**
3. **Summary of repository activity**
4. **Amount of code line additions and deletions**

### Explanation:
The **Pulse** section in the **Insights** tab of a repository provides various metrics and summaries related to the repository's activity, including:
- A **list of unresolved conversations** that are pending review or response.
- The **pull requests open/merged ratio**, showing the status of pull requests.
- A **summary of repository activity**, highlighting recent contributions and interactions.
- The **amount of code line additions and deletions**, giving insight into changes made over a specified time period.

The **list of issue discussions** and the **amount of forks of the repo** are not typically found in the Pulse section.


## 103 - In GitHub, a proposal to merge a set of changes from one branch into another branch is called a:

**Pull Request**

### Explanation:
In GitHub, a **Pull Request (PR)** is a proposal to merge changes from one branch into another. It allows team members to review the changes, discuss potential modifications, and approve or request further changes before merging them into the target branch.


## 104 - What GitHub features allow repository contributors to work on simple code changes directly through the web browser? (Choose two.)

1. **GitHub Codespaces**
2. **github.dev editor**

### Explanation:
- **GitHub Codespaces** provides a full development environment in the cloud, allowing contributors to make code changes directly in the browser with access to all the tools they need.
- **github.dev editor** (accessed by appending `.dev` to the repository URL) allows users to edit files in a simplified web-based editor directly in the browser, making it easy to make quick changes to the code.

Other options, like GitHub Dependabot and GitHub Projects, do not provide direct code editing capabilities in the browser.


## 105 - What is the difference between GitHub projects and GitHub projects classic?

**GitHub Projects is the new GitHub experience which offers a lot of new features and improvements over the older GitHub Projects classic.**

### Explanation:
**GitHub Projects** represents a new and improved project management experience on GitHub, providing enhanced features such as better integrations with issues and pull requests, customizable workflows, and more robust visualizations. **GitHub Projects classic** refers to the previous version, which lacked many of the new functionalities and enhancements introduced in the latest iteration.

## 106 - What are the different levels of GitHub organizational hierarchy? (Choose three.)

1. **Enterprise level**
2. **Organization level**
3. **Team level**

### Explanation:
The GitHub organizational hierarchy consists of multiple levels:
- **Enterprise level**: Represents the highest level, typically for large organizations managing multiple repositories and teams.
- **Organization level**: A group of repositories and teams that are managed under a single organizational account.
- **Team level**: A subset within an organization that can manage specific repositories and collaborate on projects.

**Personal level** and **Pro level** are not recognized levels within the GitHub organizational hierarchy.


## 107 - What are the different possible lifecycle phases for a GitHub Codespace?

**Create, Rebuild, Stop, Delete**

### Explanation:
A **GitHub Codespace** can go through the following lifecycle phases:
- **Create**: Initiate a new Codespace for development.
- **Rebuild**: Recreate the Codespace environment, often to apply changes to the configuration or dependencies.
- **Stop**: Temporarily stop the Codespace without deleting it, allowing you to resume later.
- **Delete**: Permanently remove the Codespace from your account.

These phases allow for flexible management of development environments.


## 108 - What improvement do issue forms bring over issue templates?

**Issue forms allow for users to be prompted for information when creating an issue and then have that information automatically added to the issue.**

### Explanation:
**Issue forms** provide an enhanced user experience by prompting users for specific information when they create an issue. This structured approach allows for better data collection and ensures that important details are captured, making it easier for maintainers to understand and address the issues. This is a significant improvement over traditional issue templates, which are static and do not dynamically request information.

## 109 - What is the role of an organization security manager?

**Security managers are organization members who can view security alerts and manage settings for code security across your organization, as well as read permissions for all repositories in the organization.**

### Explanation:
**Organization security managers** have a focused role that allows them to oversee and manage security-related settings, including the ability to view security alerts, manage security settings across repositories, and read permissions. This role is crucial for maintaining the security posture of the organization within GitHub.

## 110 - What is a fork in GitHub?

**A fork is a personal copy of another user's repository that lives on your account.**

### Explanation:
A **fork** in GitHub is a personal copy of someone else's repository that allows you to make changes freely without affecting the original repository. It is commonly used to propose changes or to use the repository as a starting point for your own projects. When you fork a repository, it is added to your GitHub account, and you can then work on it independently.

## 111 - Which of these statements best describes a version control system?

**It's a system that tracks the history of changes made to a collection of files.**

### Explanation:
A **version control system** (VCS) is designed to track changes to files over time, allowing multiple contributors to work on a project collaboratively. It maintains a history of modifications, enabling users to revert to previous versions if necessary, compare changes, and manage conflicts among contributions. While it often uses tools like Git, the defining characteristic is the ability to track changes.

## 112 - Which GitHub pricing plan offers self-hosted deployment of GitHub?

- Pro
- Enterprise
- None of them
- Free
- All of them
- Team

### Answer:
The correct answer is:

**Enterprise**

### Explanation:
The **Enterprise** plan is the only GitHub pricing plan that offers **self-hosted deployment** of GitHub through GitHub Enterprise Server. This allows organizations to host GitHub on their own infrastructure for greater control over their data and workflows. Other plans like Pro, Free, and Team do not include self-hosted options.


## 113 - Which of these can make a repository more discoverable? (Choose three.)

1. **Setting up topics for the repository**
2. **A well-crafted collection of markdown documents like README.md, CONTRIBUTING.md and others.**
3. **Giving the repository a descriptive name**

### Explanation:
- **Setting up topics** helps categorize the repository, making it easier for users to find it when searching for specific subjects.
- A **well-crafted collection of markdown documents** provides important context, guidance, and information about the repository, enhancing its attractiveness and usability.
- Giving the repository a **descriptive name** makes it clear what the repository is about, improving its discoverability through search engines and within GitHub itself.

While the other options contribute to the quality and functionality of the codebase, they do not directly enhance discoverability.


## 114 - What are the different GitHub pricing plans for organization accounts? (Select three.)

- Advanced
- Enterprise
- Team
- Business
- Personal
- Free
- Pro

### Answer:
The correct answers are:

1. **Enterprise**
2. **Team**
3. **Business**

### Explanation:
For **organization accounts**, the available GitHub pricing plans include:
- **Enterprise**: Offers advanced features and control for large organizations.
- **Team**: Designed for small to medium-sized teams with collaborative tools.
- **Business**: A plan that includes features for managing multiple organization accounts and enhancing collaboration.

The **Personal**, **Free**, and **Pro** plans are primarily for individual users rather than organizations.


## 115 - What is the purpose of a CODEOWNERS file?

**The CODEOWNERS file allows you to define individuals or teams that are responsible for specific areas of the codebase or its entirety.**

### Explanation:
The **CODEOWNERS** file is used in GitHub repositories to specify which individuals or teams are responsible for different parts of the codebase. When changes are made to those areas, the specified code owners will automatically be requested for review, ensuring that the appropriate parties are involved in the review process.


## 116 - What are the possible statuses for a pull request review? (Choose three.)

1. **Approve**
2. **Comment**
3. **Request Changes**

### Explanation:
When reviewing a pull request on GitHub, the possible statuses for a review include:
- **Approve**: Indicates that the reviewer approves the changes made in the pull request.
- **Comment**: Allows the reviewer to leave comments without approving or requesting changes.
- **Request Changes**: Indicates that the reviewer has identified issues that need to be addressed before the pull request can be merged.

"**Deny**," "**Applaud**," and "**Close**" are not recognized statuses for a pull request review.






































































































































































 








