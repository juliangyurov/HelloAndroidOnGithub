# HelloAndroidOnGithub
This projects tests creating Android Studio Project and Pushing it to Github

Used: https://learntodroid.com/how-to-use-git-and-github-in-android-studio/

# Steps
Step 1: Download/Upgrade and Install Git

Step 2: Configure the Path to Git in Android Studio

First, launch Android Studio, then select the “File” menu and click the “Settings” menu item

In the settings screen, expand the “Version Control” option and click on “Git”. 

In the “Path to the Git executable” field enter the path to Git executable on your local machine.

To verify that the path to the Git is correct, select the “Test” button to the right of the “Path to the Git executable” field. If it is successful you should see the version of Git , if it fails correct the Git path and select the “Test” button again.

Select the “OK” button to close the settings screen.

Step 3: Creating a Git Repository in Android Studio

You can use an existing Android Project or create a new Android Project using by selecting the “File” menu, with “New” and selecting “New Project” and following the wizard to create the project.

Once you have your Android Project open in Android Studio, select the “VCS” menu and click on the “Enable Version Control Integration…” menu item.

Step4: Then add/edit files from our Android Project in Android Studio.

To add files from your Android Project into to the Git repository you first need to get into the Project View in Android Studio. In the left side bar, select “Project view” from the drop down list.

Next right click on the Android Project name, find the “Git” menu item and click the “Add” menu item.

Step5: To commit these files that have been added using Android Studio, right click on the Android Project name, find the “Git” menu item and click the “Commit Directory"

Next we are presented with a pop up showing the changes that are going to be committed to the Git repository.

Enter a “Commit Message” describing the change being made and select the “Commit” button.

To see that the commit has been successfully made, in the bottom section of Android Studio, select “Version Control” and select “Log” to review your commit transaction.

Now You have successfully created a snapshot in your local Git repository containing the files of your Android Project that you have added.

Step6: Creating a GitHub Repository

In your web browser create a new GitHub account if you don’t already have.

After logging in, select the “+” drop down list in the upper right section of the screen and select “New repository”. You will be presented with the screen used to create a new GitHub repository. Enter a name for your code repository-select “Create repository”.

Step 7: Push Code Changes to a GitHub Repository from Android Studio

To push our local changes to our GitHub repository using Android Studio, first right click on the Project, hover over the “Git” menu item, hover over “Repository” and select “Push”.

You will be presented with a pop up screen with the title “Push Commits”. Click on “Define remote”.

Open your GitHub repository in your web browser and copy the repository URL (ending in .git) in the section highlighted by the screenshot below.

Enter this URL into the URL requested in the “Define Remote” pop up screen in Android Studio and press the “OK” button.

Once the URL has been successfully added select the “Push” button.

When prompted enter your GitHub user name and password credentials and select “Log In”.

If successful you will see a “Push successful” confirmation message in the bottom right corner of the screen.

Next you can access your GitHub repository via the web browser and check that your code is available.







