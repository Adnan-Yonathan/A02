Set up **git** in WebStorm
  Open WebStorm and go to File > Settings
  Navigate to Version Control > **Git**
  Click Test to ensure WebStorm can connect to **Git**

**Cloning** a **github** **Repository**
  go to VCS then Get from Version Control
  select **Git** as the version control type
  paste the URL of the **repository** from **Github**
  Choose a place to **clone** the **repository**
  click **clone**

Creating a New project with **Git** integration
  click file then new project in webstorm
  then go to VCS then enable Version Control Integration
  Select **Git** as the version control system

**Commit** Changes in **Github**
  after making changes to the code, right click on the file in the project view, then select **Git**, Add to lock changes

**push** Changes to **Github**
  go to Vcs, **git**, push
  will push changes to **repository**

**Pull** changes from **Github**
  go to VCS, then **git**, then pull to update the **repository** with the changes from **git**



**Glossary**
**Git**: A distributed version control system that allows developers to track changes in source code during software development.
**GitHub**: A web-based platform for hosting Git repositories and collaborating with other developers.
**Repository**: A storage space where your project files and history are saved. In Git, a Repository contains all your project’s files and the revision history.
**Clone**: A copy of a Repository that is stored on your local machine. You can Clone a remote GitHub repository to your computer to work on it locally.
**Commit**: A snapshot of changes in the codebase at a particular time. Commits represent the history of changes made to a project.
**Push**: Sending your Committed changes to a Remote repository, such as one hosted on GitHub.
**Pull**: Fetching changes from a Remote repository to update your local version with the latest code.
**Fetch**: Downloading the latest updates from the Remote repository without automatically merging them into your working codebase.
**Branch**: A separate version of the codebase, allowing multiple developers to work on different features or bug fixes simultaneously.
**Merge**: Combining different Branches into a single Branch. Often used to integrate new features or bug fixes into the main Branch.
****Merge** Conflict**: A situation where changes from different Commits cannot be automatically combined by Git. This happens when multiple developers make changes to the same part of a file.
**Remote**: A version of the project that is hosted on a server, such as GitHub, that you can Push to or Pull from.
