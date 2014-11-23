# Forking Projects · GitHub Guides

After using GitHub by yourself for a while, you may find yourself wanting to contribute to someone else's project. Or maybe you'd like to use someone's project as the starting point for your own. This process is known as _forking._

Creating a "fork" is producing a personal copy of someone else's project. Forks act as a sort of bridge between the original repository and your personal copy. You can submit _Pull Requests_ to help make other people's projects better by offering your changes up to the original project. Forking is at the core of social coding at GitHub.

For this tutorial, we'll be using [the Spoon-Knife project][1], a test repository that's hosted on GitHub.com that lets you test the Pull Request workflow and the GitHub Desktop application. To download the desktop application, head over to  or  depending on your operating system.

## Fork the repository

To fork the Spoon-Knife repository, click the **Fork** button in the header of the repository.

![A repository's fork button][2]

Sit back and watch the forking magic. When it's finished, you'll be taken to your copy of the Spoon-Knife repository.

## Clone your fork

You've successfully forked the Spoon-Knife repository, but so far, it only exists on GitHub. To be able to work on the project, you will need to clone it to your computer.

If you're using GitHub for Desktop application, this process is a breeze. On your fork of Spoon-Knife, navigate over to the bottom of the right hand side bar and click **Clone in Desktop**. Once we click this, it'll ask us if we want to launch our desktop application to clone the repository, and where we want to save it. Pick a location on your computer that you feel comfortable with creating files and folders.

![Clone in Desktop][3]

## Making and pushing changes

Go ahead and make a few changes to the project using your favorite text editor, like [Atom][4]. You could, for example, change the text in _index.html_ to add your GitHub username.

When you're ready to submit your changes, type up a _commit summary_ in GitHub for Desktop, and click **Commit**.

![GHfM commit changes view][5]

Right now, you've essentially told Git, "Okay, I've taken a snapshot of my changes!" You can continue to make more changes, and take more commit snapshots. When you're ready to push your changes up to GitHub.com, click on the **Sync** button, which is right above your list of changes.

## Making a Pull Request

At last, you're ready to propose changes into the main project! This is the final step in producing a fork of someone else's project, and arguably the most important. If you've made a change that you feel would benefit the community as a whole, you should definitely consider contributing back.

To do so, head on over to the repository on GitHub.com where your project lives. For this example, it would be at `https://www.github.com//Spoon-Knife`. You'll see a banner indicating that you've recently pushed a new branch, and that you can submit this branch "upstream," to the original repository:

![Recently pushed branch banner][6]

Clicking on **Compare and Pull Request** sends you to a discussion page, where you can enter a title and optional description. It's important to provide as much useful information and a rationale for _why_ you're making this Pull Request in the first place. The project owner needs to be able to determine whether your change is as useful to everyone as you think it is.

When you're ready typing out your heartfelt argument, click on **Send pull request**. You're done!

![Send Pull Request button][7]

Pull Requests are an area for discussion. In this case, the Octocat is very busy, and probably won't merge your changes. For other projects, don't be offended if the project owner rejects your Pull Request, or asks for more information on why it's been made. It may even be that the project owner chooses not to merge your pull request, and that's totally okay. Your copy will exist in infamy on the Internet. And who knows–maybe someone you've never met will find your changes much more valuable than the original project. Share and share alike!

## Huzzah!

You've successfuly forked and contributed back to a repository. Go forth, and contribute some more!

Last updated Jan 23, 2014

[1]: https://github.com/octocat/Spoon-Knife
[2]: https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png
[3]: https://guides.github.com/clone-in-desktop.png
[4]: https://atom.io
[5]: https://github-images.s3.amazonaws.com/mac/changes/changes.jpg
[6]: https://github-images.s3.amazonaws.com/help/pull_requests/recently_pushed_branch.png
[7]: https://github-images.s3.amazonaws.com/help/pull_requests/pullrequest-send.png
  
