# Making Your Code Citable · GitHub Guides

[Digital Object Identifiers][1] (DOI) are the backbone of the academic reference and metrics system. If you're a researcher writing software, this guide will show you how to make the work you share on GitHub citable by archiving one of your GitHub repositories and assigning a DOI with the data archiving tool [Zenodo][2].

> **ProTip:** This tutorial is aimed at researchers who want to cite GitHub repositories in academic literature. Provided you've already set up a GitHub repository, this tutorial can be completed without installing any special software. If you haven't yet created a project on GitHub, start first by [uploading your work][3] to a repository.

## Choose your repository

Repositories are the most basic element of GitHub. They're easiest to imagine as your project's folder. The first step in creating a DOI is to select the repository you want to archive in Zenodo. To do so, head over to your profile and click the **Repositories** tab.

![login][4]

> **Important!** Make sure you tell people how they can reuse your work by including a license in your repository. If you don't know which license is right for you, then take a look at [choosealicense.com][5].

## Login to Zenodo

Next, head over to [Zenodo][6] and click the **Sign In** button at the top right of the page, which gives you an option to login with your GitHub account.

![login][7]

Zenodo will redirect you back to GitHub to ask for your permission to share your email address and the ability to configure [webhooks][8] on your repositories. Go ahead and click **Authorize application** to give Zenodo the permissions it needs.

![auth][9]

### Pick the repository you want to archive

At this point, you've authorized Zenodo to configure the repository webhooks needed to allow for archiving and DOI-issuing. To enable this functionality, simply click the **On** toggle button next to your repository (in this case **My-Awesome-Science-Software**).

![toggle][10]

## Check repository settings

By enabling archiving in Zenodo, you have set up a new webhook on your repository. Click the settings icon  in your repository, and then click 'Webhooks & Services' in the left-hand menu. You should see something like the image below, which shows a new webhook configured to send messages to Zenodo.

![webhooks][11]

## Create a new release

By default, Zenodo takes an archive of your GitHub repository each time you create a new [Release][12]. To test this out, head back to the main repository view and click on the **releases** header item.

![repo][13]

Unless you've created releases for this repository before, you will be asked to **Create a new release**. Go ahead and click this button and fill in the new release form.

![create-release][14]

If this is the first release of your code then you should give it a version number of `1.0`. Fill in any release notes and click the **Publish release** button.

![first-release][15]

## Checking everything has worked

Creating a new release will trigger Zenodo into archiving your repository. You can confirm that this process took place by click the **Upload** tab in your Zenodo profile. You should see a new upload in the right-hand panel.

![uploads][16]

## Minting a DOI

Before Zenodo can issue a DOI for your repository, you will need to provide some information about the GitHub repo that you've just archived.

Once you're happy with the description of your software, click the **Submit** button at the bottom of the Zenodo form, and voilà, you've just made a shiny new DOI for your GitHub repo!

![form][17]

## Finishing up

Back on your [Zenodo GitHub page][18] you should now see your repository listed with a shiny new badge showing your new DOI!

> **ProTip:** If you really want to show off, then right click on the gray and blue DOI image and copy the URL and place it in your README on your GitHub repo.

![releases-present][19]

Last updated May, 2014

[1]: http://en.wikipedia.org/wiki/Digital_object_identifier
[2]: https://zenodo.org/about
[3]: https://guides.github.com/introduction/desktop/
[4]: https://guides.github.com/repos.png
[5]: http://choosealicense.com/
[6]: http://zenodo.org
[7]: https://guides.github.com/zenodo-login.png
[8]: https://developer.github.com/webhooks/
[9]: https://guides.github.com/zenodo-authorize.png
[10]: https://guides.github.com/zenodo-toggle-on.png
[11]: https://guides.github.com/webhook-view.png
[12]: https://help.github.com/articles/about-releases
[13]: https://guides.github.com/repo-view.png
[14]: https://guides.github.com/create-release.png
[15]: https://guides.github.com/first-release.png
[16]: https://guides.github.com/upload-tab.png
[17]: https://guides.github.com/zenodo-form.png
[18]: https://zenodo.org/account/settings/github
[19]: https://guides.github.com/releases-present.png


[Source](https://guides.github.com/activities/citable-code/ "Permalink to Making Your Code Citable · GitHub Guides")

  
