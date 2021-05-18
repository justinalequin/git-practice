i# Git practice

> In this assignment, we'll practice using git from the command line. *** I am also going to add random text in nano throught this .md. I wish I knew how to add pictures***

## Step 1: Setting up an SSH key

Before using Git, we'll need to set up our command line to be authenticated with our GitHub account. The best way to do this is to set up what's known as an SSH key.

#### Generate an SSH key

Follow the guide here on how to generate an SSH key (ignoring the section, "Generating a new SSH key for a hardware security key"): https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

#### Add the SSH key to your GitHub account

Follow the guide here: https://docs.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account

If you have any trouble with the command that copies the SSH key to your clipboard, you can instead type `cat ~/.ssh/id_ed25519.pub` and then manually copy the output of that command which will look like `ssh-ed25519 AAAAC3NzaC1l...`.

## Step 2: Configuring the Git program @@@ These at symbols look as though they belong here (=

Now that you have an SSH key set up, we need to configure the git program through the command line. We'll need to tell git what our GitHub email and username is. Additionally, we'll want to set our default command line text editor to the 'nano' program.

In the command line, enter the following commands, substituting the [BRACKETED TEXT] for your information:

1. `git config --global user.email [YOUR GITHUB EMAIL]`
1. `git config --global user.name [YOUR GITHUB USERNAME]`
1. `git config --global core.editor nano

## Step 3: Cloning the repository ## I added the pound signs on the right side of the origianl text.
Also though... Star Wars Episode II: Attack of the Clones was easily on the worst films in the Star Wars universe. 

Fantastic, everything is set up. Now, lets actually use git to download some code.

Go to your `username.github.io` repository and click the green "Code" button.

A pop-up should appear that has a section "Clone". Select the SSH tab and copy the given URL.

In your command line, navigate to your workspace directory and enter `git clone [your copied URL]`, replacing the bracketed text with your copied URL.

Now that you've cloned the repository, a new directory should exist with your code. Enter that new directory.

## Step 4: Making some commits

Now, decide on 3-5 changes that you would like to make to your repository (adding a new picture, editing content, etc.)

Open up VSCode and open up the cloned folder with the code inside. Make one of your changes.
***Here I am in VS Code making changes (= ***)

Now, back in the command line, commit those changes and push them. Repeat for each of your 3-5 changes so that you create 3-5 commits. Make sure each commit message describes the changes that were made!

## Step 5: Submitting

Submit both the link to your GitHub repository as well as a link to your code hosted on GitHub Pages on Populi.
