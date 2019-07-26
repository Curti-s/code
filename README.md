# 👾 Coding Project
This repository contains code for the protocols and attacks covered in the Cryptoeconomics.study course. This includes implementing a payment processor blockchain, proof of work, proof of stake, and Plasma.

## Prerequisites

### Command Line Basics

In order to install the packages you need for development you're going to have to know how to navigate around the terminal. 
- [OSX and Linux](https://www.taniarascia.com/how-to-use-the-command-line-for-apple-macos-and-linux/) 
- [Windows, OSX, and Linux](https://lifehacker.com/a-command-line-primer-for-beginners-5633909)
- [Windows](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/)

### NodeJS and NPM

You're going to need *Node.js* and *npm* to complete these assignments. Install both at once [here](https://nodejs.org/en/).

### Git and GitHub

You'll also need a Github account and `git` installed on your computer.

* Create a Github account [here](https://github.com/join).

* Setting up Git:
	* [Download and install the latest version of Git.](https://git-scm.com/downloads)
	* [Set your username in Git.](https://help.github.com/en/articles/setting-your-username-in-git)
	* [Set your commit email address in Git.](https://help.github.com/en/articles/setting-your-commit-email-address)
	* [Authenticate with Github from Git](https://help.github.com/en/articles/set-up-git#next-steps-authenticating-with-github-from-git)

### Mocha

We're going to be using [Mocha](https://mochajs.org/) in order to run tests, so install the Mocha package globally by running: 
`npm install -g mocha`

## Local Development Environment

Once you have the prerequisites installed without error, fork [this repository](https://github.com/cryptoeconomics-study/code) ([guide](https://help.github.com/en/articles/fork-a-repo)).
Once you have your own fork at `github.com/YOUR_USERNAME/code`, create a local clone of your fork ([guide](https://help.github.com/en/articles/fork-a-repo#keep-your-fork-synced)).
`cd` into your local clone and run `npm install` to install all of the required dependencies.

## Technical Difficulties?

Often the first steps are the hardest and we want to make sure you have a great experience learning about cryptoeconomics. If you get stuck or encounter difficulty setting up your development environment please [reach out to the community](https://forum.cryptoeconomics.study/t/technical-difficulties-thread/512). Chances are you're not the only one experiencing difficulties. Reaching out allows us to
- solve your problem directly
- document what the problem was and how we solved it so that in the future people can find those answers quickly
- understand the problem and improve the course material so that it's more intuitive for everyone
It's a win for everyone! So if you get stuck, don't worry about it. Just post your problem on the community forum [technical difficulties thread](https://forum.cryptoeconomics.study/t/technical-difficulties-thread/512) and we'll do our best to help :)

## Taking the Course

Now that you're good to go, let's start the course!

You'll start off at Section 1.1, so `cd` into Section 1.1 of the Chapter 1 folder `/c1_CentralPaymentOperator/1.1 - Hashes_and_Signatures`. 

Open the `README.md` for instructions on how to complete this part of the coding project. 
You'll be editing the `Client.js` file in the root of this folder to complete this assignment.

 In order to run tests on your work, `cd` into `/test` and run `mocha test.js`. Once you pass all the tests, you can move on to the next section!
 
Don't forget to commit your progress to Github, so we can verify your work and give you a certificate of completion at the end of the course!

## Contributing

See our [CONTRIBUTING.md](CONTRIBUTING.md) for more information about how to join the team and help improve the coding projects! :)



