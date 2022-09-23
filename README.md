# A03
Part 1: Directions on Using Webstorm (On Windows)

<b>Download Git</b>
1. Download latest version at: https://git-scm.com/downloads  and open the downloaded file and follow the installation directions (click next to all of them)

<br><b>Create GitHub Account</b>
1) Sign up an account at https://github.com/ on the top-right "Sign up" button.
2) If not prompted to do so, "Start a new repository" and make sure to set it to "Public" (and give it a cool name as well).

<br><b>Download Jetbrains' WebStorm</b>

1) Get school license here: https://www.jetbrains.com/community/education/#students
2) Then select the "WebStorm" option in https://account.jetbrains.com/licenses and after opening the downloaded file, follow the installation directions.

<br><B>Validate Everything is Working</B>
* Attempt to connect WebStorm and Github.
  * If not in a prompted area, when opening/creating a project (possibly in an empty looking "Search Project Screen")
    * Click on: "Get From VCS"
  * GitHub should be an option which you should select (sign-in manually if not already prompted to link)
    * If it asks for a "file location" (don't change it, unless the following steps do not work)
  * There should be a list of projects (or in this case, just 1 that was created earlier), and click on the "bottom-right" option "Clone"
  * IF this doesn't work:
    * In WebStorms: Go to menu option in the top left "File" and select Settings (or use the keybinds: "Crtl+Alt+S")
      * Browse options: "Version Control" > "Git" > "Path to Git Executable"
    * If the "TEST" doesn't show a version, it means that Git was either: a) not installed b) was somehow installed in a different "default" directory
      * Link the executable by searching the file path for the "git.exe" file by:
        1. Go to windows search (press the Windows Key)
        2. Type in "git"
        3. If a few apps with the "Git" name popup:
           * Open File Location (of the currently selected app)
           * Right click the selected file
           * Open File Location
           * Open up the "cmd" file
           * On the file directory address bar, hover over it and right click it
           * Choose option "Copy address"
           * Go back to WebStorms and go back to the "Path to Git Executable"
           * Replace the current with the copied text
             * Then add (without the quotation marks) "\git.exe"
  * If everything works:
    * Then after a few seconds, the README.md file should be available to view and edit on the left sidebar on WebStorms. Else, Google.
    * To push changes between your local file changes here to then Github:
      1. On the top right menu, look for "Git"
      2. Choose "Push" (or keybinds: "Crtl + K")
      3. In the popped-out menu, add a text describing the changes to the file, then click on "Commit and Push"
      4. Then press "Commit"


Part 2: GitHub Glossary

* **Branch**
  * A separate part inside a repository that can be worked on without affecting the primary part of the repository. It can be later merged into the primary part to publish the changes.
* **Clone**
  * A copy of a repository that is stored on the computer (rather than on a server). This allows for the user to work offline, but can still be later used to push those worked changes back into the repository.
* **Commit**
  * A saved revision to save your work in the repository. The state of the repository at the moment will be saved alongside future and past revisions.
* **Fetch**
  * Adds changes from the current (remote) repository to your local working branch. It allows you to review the changes before committingthem into the branch.
* **GIT**
  * "An open source program for tracking changes in text files."
* **Github**
  * An internet hosting service for software development using Git.
* **Merge**
  * Takes the changes from one branch (in the repository), then applies them to another. (Commonly occurs in "pull requests")
* **Merge Conflict**
  * Occurs when people make different changes to the same line of the same file (or if someone is editing a file while someone deleted that file). Must be resolved before merging those branches.
* **Push**
  * To send your committed changes to a remote repository on Github
* **Pull**
  * Fetching in changes from the remote repository and merging them
* **Remote**
  * Refers to the version of a repository or branch that is hosted on a server (Github)
* **Repository**
  * A hosted project folder in Github (public or private) that contains all project files (including documentation) and stores each file's revision history.

Part 2: References
- Github Terms
  - https://docs.github.com/en/get-started/quickstart/github-glossary