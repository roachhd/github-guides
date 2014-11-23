# Mastering Wikis · GitHub Guides

Good documentation is key to the success of any project. Making documentation accessible enables people to learn about a project; making it easy to update ensures that documentation stays relevant. **Wikis** on GitHub help you present information about your project in a useful way.

## Creating your wiki

Every repository on GitHub comes with a wiki. After you've created a repository, you can set up the included wiki through the sidebar navigation. Starting your wiki is simply a matter of clicking the wiki button and creating your first page.

![Screenshot of the starting page][1]

## Adding content

Wiki content is designed to be easily editable. You can add or change content on any wiki page by clicking the **Edit** button located in the upper right corner of each page. This opens up the wiki editor.

![Screenshot of the wiki editor][2]

Wiki pages can be written in any format supported by [GitHub Markup][3]. Using the drop-down menu in the editor, you can select the format of your wiki, and then use wiki toolbar to create and include content on a page. Wikis also give you the option of including a custom footer where you can list things like contact details or license information for your project.

GitHub keeps track of changes made to each page in your wiki. Below a page title, you can see who made the most recent edits, in addition to the number of commits made to the page. Clicking on this information will take you to the full page history where you can compare revisions or see a detailed list of edits over time.

## Adding pages

You can add additional pages to your wiki by selecting **New Page** in the upper right corner. By default, each page you create is included automatically in your wiki's sidebar and listed in alphabetical order.

![Screenshot of the wiki sidebar][4]

You can also add a custom sidebar to your wiki by clicking the **Add custom sidebar** link. Custom sidebar content can include text, images, and links.

Note: The page called "Home" functions as the entrance page to your wiki. If it is missing, an automatically generated table of contents will be shown instead.

If you're knowledgable with the command line, you can also modify wikis locally. Check out [our help article][5] for more info.

## Syntax highlighting

Wiki pages support automatic syntax highlighting of code for a wide range of languages by using the following syntax:


    ```ruby
      def foo
        puts 'bar'
      end
    ```


The block must start with three backticks, optionally followed by the the name of the language that is contained by the block. See [Pygments for the list of languages][6] that can be syntax highlighted.

The block contents should be indented at the same level than the opening backticks. The block must end with three backticks indented at the same level than the opening backticks.

Last updated April 28, 2014

[1]: https://guides.github.com/wiki-blank-slate.png
[2]: https://guides.github.com/wiki-editor.png
[3]: http://github.com/github/markup
[4]: https://guides.github.com/wiki-sidebar-closeup.png
[5]: https://help.github.com/articles/adding-and-editing-wiki-pages-locally

[6]: http://pygments.org/docs/lexers/

[Source](https://guides.github.com/features/wikis/ "Permalink to Mastering Wikis · GitHub Guides")
  
