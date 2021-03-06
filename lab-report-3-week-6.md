# Lab Report 3

Hello! My name is Jonathan Anaya Garcia and I will be demonstrating how I streamlined my ssh configuration, how I setup Github access from ieng6 and how I copied whole directories.


## 1. Streamlining ssh Configuration

This is my `.ssh/config` file and I edited it through the terminal.
![configFile](configFile.png)
![EdittingConfig](EdittingConfig.png)

Here I am logging into my ssh with my alias.
![LogInSSH](LogInSSH.png)

At the top of this screenshot you can see me doing the `scp` command in order to copy a file into my account.
![copyingFile](copyingFile.png)


## 2. Setup Github Access from ieng6

Here we see my public key in github.
![keyInGithub](keyInGithub.png)

Here is what it looks like in my ieng6 account.
![keyInIeng6](keyInIeng6.png)

Inside of this file I have my private key and it differs from my public key because my public key has `.pub`

![privatekey](privatekey.png)

Here I commited a few files that were in my ieng6 account.
![gitcommit](fixcommit.png)

When I push these files they are added to a repository on github and you can see the commit with the link below.
![gitPush](fixpush.png)
[commit link](https://github.com/janayagarcia/testt/commit/9868654a07002ece10b26139343f59f1a9fbc0d2)


## 3. Copy Whole Directories With `scp -r`

In this image I am recursively copying my markdown-parser directory.
![recursiveCopy](recursiveCopy.png)

In this image I am running the Junit tests for MarkdownParseTest.
![ranTest](ranTest.png)

Here I do the same thing as the image above the only difference is that I am doing it all in one line.
![allInOneLine](OfficialAllInOneLine.png)
