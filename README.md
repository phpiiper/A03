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
      2. Choose "Push" (or keybinds: "Crtl + Shift + K")
      3. In the popped-out menu, add a text describing the changes to the file, then click on "Commit and Push"


Part 2: Directions on Using Webstorm (On Windows)
