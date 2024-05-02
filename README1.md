Introduction of GIT

Git is one of the ways of implementing the idea of version control. It is Distributed
Version Control System.
Installing GIT

it’s already installed, it’s probably a good idea to update to the latest version. You can either
install it as a package or via another installer, or download the source code and compile it
yourself.
Installing on Windows

The easiest way to get Git is to download the executable from the Git website.
Click "64-bit Git for Windows Setup" to start the download, and then wait a moment — the
download is only about 50 megabytes, so it shouldn't take very long.

Double-click the executable you just downloaded, then click "Next" to move through the
installation prompts.
The first is the text editor Git will use. The default selection is Vim. Vim is ubiquitous and a
hallmark of command-line interfaces everywhere but learning to use its idiosyncratic
Before you start using Git, you have to make it available on your computer.
Even if

There are also a few ways to install Git on Windows. The most official build is
available for download on the Git website. Just go to https://git-scm.com/download/win
and the download will start automatically
To get an automated installation you can use the Git Chocolatey package.

18

commands can be daunting. You should probably pick something else instead, like Visual
Studio Code, Sublime, NotePad++, or any other plain text editor you like.

The second is the way Git integrates itself into your PC's PATH. Make sure that the "Git
From The Command Line And Also From 3rd-Party Software" is selected.

19

Click through the remaining options, and wait for everything to finish downloading. The time
requires to download everything will vary depending on what you chose to install. The default
selection results in a download that is about 270 megabytes.

Managing Private and Public RepositoryMaking a
repository Private
• GitHub will detach public forks of the public repository and put them into a new
network. Public forks are not made private.
• If you're using GitHub Free for personal accounts or organizations, some features won't
be available in the repository after you change the visibility to private. Any published
GitHub Pages site will be automatically unpublished. If you added a customdomain to
the GitHub Pages site, you should remove or update your DNS records before making
the repository private, to avoid the risk of a domain takeover.
• GitHub will no longer include the repository in the GitHub Archive Program.
• GitHub Advanced Security features, such as code scanning, will stop working.

20

Making a repository Public
• GitHub will detach private forks and turn them into a standalone private repository.
• If you're converting your private repository to a public repository as part of a move
toward creating an open source project.
• Once your repository is public, you can also view your repository's community profile
to see whether your project meets best practices for supporting contributors.
• The repository will automatically gain access to GitHub Advanced Security features.
Changing a repository’s Visibility
1. On GitHub.com, navigate to the main page of the repository.
2. Under your repository name, click Settings. If you cannot see the "Settings" tab, select
the dropdown menu, then click Settings.

3. In the "Danger Zone" section, to the right of to "Change repository visibility",
click Change visibility.
4. Select a visibility.
5. To verify that you're changing the correct repository's visibility, type the name of the
repository you want to change the visibility of.
6. Click I understand, change repository visibility.

21

Pushing changes to the repository
1. On Github.com, ensure your repository is public.
2. Clone the repository to your local machine.
i. Open a terminal on your local machine.

ii. Use the following command to clone the repository to your local machine. Replace 'your-
username' and 'your-repo-name' with your GitHub username and repository name

git clone https://github.com/your-username/your-repo-name.git
iii. Move into the newly cloned repository
cd your-repo-name
3. Make a change to the README file (Create a README.md file if it does not exist).
4. Commit the change.
i. Add the modified README file to the staging area using the following command:
git add README.md
ii. Commit the changes with a meaningful commit message:
git commit -m "Update README file"
5. Push it to the GitHub repository using the following command. If your main branch is called
‘master’, then replace ‘main’ with ‘master’.
git push origin main
