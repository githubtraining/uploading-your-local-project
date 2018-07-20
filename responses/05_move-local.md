## Step 3: Make the move

Having a project already stored locally enables you to move it to GitHub rather quickly. The following activity provides instructions to move your local project to GitHub using various tools. Select the tool you are most comfortable with and get importing :smile:.

### :keyboard: Activity: Moving your local project

1. In the **Code** tab of this repository, copy the URL shown under **Quick Setup**.
1. Follow the instructions below based on what tool you'd like to use locally.

<details>
  <summary>Using the command line</summary>
  <hr>

  ### Using the command line

  1. In your command line, navigate to your project directory. Type `git init` to initialize the directory as a Git repository.
  1. Type `git remote add origin https://github.com/{{ user.username}}/github-upload.git`
  1. Type `git add .`
  1. Type `git commit -m "initializing repository"`
  1. Type `git push -u origin master` to push the files you have locally to the remote on GitHub. (You may be asked to log in.)

  <hr>
</details>

<details>
  <summary>Using GitHub Desktop</summary>
  <hr>

  ### Using GitHub Desktop

  1. In GitHub Desktop, add a local repository by clicking `File > Add a Local Repository`, and then navigating to your local repository.
  1. Create your first commit by typing a summary commit message in the field provided and clicking **Commit to master**
  2. Add the remote by clicking `Repository > Repository Settings...` and pasting the URL from your repository on GitHub into the "Primary remote repository (origin)" field. Click **Save**.
  3. Click **Publish** in the top right corner to push your repository to GitHub.

  <hr>
</details>

<details>
  <summary>Using Visual Studio Code</summary>
  <hr>

  ### Using Visual Studio Code

  1. In Visual Studio Code, open the folder for your project.
  1. Click the icon on the left for **Source Control**.
  1. On the top of the Source Control panel, click the **Git icon**.
  1. If the files you see match the repository you want to create, click **Initialize Repository**.
  1. Next to the word **CHANGES**, click the symbol of the plus sign to stage all of the changes.
        - This is part of the two stage commit. You can use this staging function to create meaningful commits throughout the development process.
  1. In the box in the Source Control panel, type a commit message. Something like "initial commit - moving project" could work.
  1. Click the checkmark at the top of the Source Control panel.
  1. Open the integrated terminal found under View > Integrated Terminal.
  1. In your command line, type `git remote add origin {{url}}`
  1. In the Source Control Panel, click the expandable three dots that open a menu of options.
  1. When asked if you'd like to publish the branch, click **Okay**.

  <hr>
</details>

<details>
  <summary>Using Atom</summary>
  <hr>

  ### Using Atom

  1. In Atom, open the folder for your project
  1. At the top of your screen, click **Packages**. Select **GitHub**, and then toggle the **Git Tab** from the drop-down menu.
  1. Select **Create Repository** within the Git tab on the right-hand size of your screen.
  1. Select **Init** to accept the default prompt of the pop up window
  1. In the Git tab, you can see that your files are ready for staging. It _should_ be accounted for, but double check to make sure that none of your binaries or files that you listed in the .gitignore are listed in this dialog menu.
          - If they are, double check your .gitignore file to make sure they're included or remove them from your directory.
  1. Select **Stage All**
          - This is part of the two stage commit. You can use this staging function to create meaningful commits throughout the development process.
  1. In the box at the bottom of the Git panel, type a commit message. Something like "initial commit - moving project" could work.
  1. Select **Commit**
  1. Close Atom
  1. In your command line, navigate to your project directory.
  1. Type `git remote add origin {{url}}`
  1. Return to Atom, and select the [Up/Down arrow icon](https://user-images.githubusercontent.com/13326548/36766999-34ff2bb2-1bed-11e8-90c6-3c97d0837244.png) at the bottom of your Git Tab
  1. Click [Push](https://user-images.githubusercontent.com/13326548/36767211-5fd34ce6-1bee-11e8-964a-f49bed227c02.png), above the noted dialog.
  1. Return to your repository, and note a successful push by finding your files on GitHub's code tab.

  <hr>
</details>

<details>
  <summary>Using Eclipse</summary>
  <hr>

  ### Using Eclipse

  1. In Eclipse, from the Eclipse Marketplace, install the [eGit](http://www.eclipse.org/egit/) GitHub plugin.
  2. Open your existing project.
  3. Display the **Git Repositories** window by selecting Window > Show View > Other > Git > Git Repositories.
  3. Click the **Create a Git Repository** button on the Git Repositories pane.
  4. Make changes to your project and create a commit.
  5. Push the master branch.
  5. When asked for a remote, paste the URL you copied earlier.
  6. Click next, and enter the branch name.

  <hr>
</details>

<hr>
<h3 align="center">Watch below for my response</h3>

> :robot: Once you push your project to GitHub, I'll provide the next steps in your journey.
