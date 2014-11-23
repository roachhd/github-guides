# Mastering Markdown · GitHub Guides

Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform.

**What you will learn:**

* How the Markdown format makes styled collaborative editing easy
* How Markdown differs from traditional formatting approaches
* How to use Markdown to format text
* How to leverage GitHub's automatic Markdown rendering
* How to apply GitHub's unique Markdown extensions

## What is Markdown?

[Markdown][1] is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like `#` or `*`.

You can use Markdown most places around GitHub:

* [Gists][2]
* Comments in Issues and Pull Requests
* Files with the `.md` or `.markdown` extension

## Examples


    It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)


It's very easy to make some words **bold** and other words _italic_ with Markdown. You can even [link to Google!][3]


    Sometimes you want numbered lists:

    1. One
    2. Two
    3. Three

    Sometimes you want bullet points:

    * Start a line with a star
    * Profit!

    Alternatively,

    - Dashes work just as well
    - And if you have sub points, put two spaces before the dash or star:
      - Like this
      - And this


Sometimes you want numbered lists:

1. One
2. Two
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

Alternatively,

* Dashes work just as well
* And if you have sub points, put two spaces before the dash or star:


    If you want to embed images, this is how you do it:

    ![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)


If you want to embed images, this is how you do it:

![Image of Yakotocat][4]


    There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`.  If you've got a longer block of code, you can indent with four spaces:

        if (isAwesome){
          return true
        }

    GitHub also supports something called code fencing, which allows for multiple lines without indentation:

    ```
    if (isAwesome){
      return true
    }
    ```

    And if you'd like to use syntax highlighting, include the language:

    ```javascript
    if (isAwesome){
      return true
    }
    ```


There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`. If you've got a longer block of code, you can indent with four spaces:


    if (isAwesome){
      return true
    }


GitHub also supports something called code fencing, which allows for multiple lines without indentation:


    if (isAwesome){
      return true
    }


And if you'd like to use syntax highlighting, include the language:


    if (isAwesome){
      return true
    }


## Syntax guide

Here's an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.

### Headers


    # This is an 
 tag
    ## This is an 

 tag
    ###### This is an 

 tag


### Emphasis


    *This text will be italic*
    _This will also be italic_

    **This text will be bold**
    __This will also be bold__

    *You **can** combine them*


### Lists

#### Unordered


    * Item 1
    * Item 2
      * Item 2a
      * Item 2b


#### Ordered


    1. Item 1
    2. Item 2
    3. Item 3
       * Item 3a
       * Item 3b


### Images


    ![GitHub Logo](/images/logo.png)
    Format: ![Alt Text](url)


### Links


    http://github.com - automatic!
    [GitHub](http://github.com)


### Blockquotes


    As Kanye West said:

    > We're living the future so
    > the present is our past.


### Inline code


    I think you should use an
    `` element here instead.


## GitHub Flavored Markdown

GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

Note that some features of GitHub Flavored Markdown are only available in the descriptions and comments of Issues and Pull Requests. These include @mentions as well as references to SHA-1 hashes, Issues, and Pull Requests. Task Lists are also available in Gist comments and in Gist Markdown files.

### Syntax highlighting

Here's an example of how you can use syntax highlighting with [GitHub Flavored Markdown][5]:


    ```javascript
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
    ```


You can also simply indent your code by four spaces:


        function fancyAlert(arg) {
          if(arg) {
            $.facebox({div:'#foo'})
          }
        }


Here's an example of Python code without syntax highlighting:


    def foo():
        if not bar:
            return True


### Task Lists


    - [x] @mentions, #refs, [links](), **formatting**, and tags supported
    - [x] list syntax required (any unordered or ordered list supported)
    - [x] this is a complete item
    - [ ] this is an incomplete item


### Tables

You can create tables by assembling a list of words and dividing them with hyphens `-` (for the first row), and then separating each column with a pipe `|`:



    First Header | Second Header
    ------------ | -------------
    Content from cell 1 | Content from cell 2
    Content in the first column | Content in the second column




Would become:



| First Header                | Second Header                |
| --------------------------- | ---------------------------- |
| Content from cell 1         | Content from cell 2          |
| Content in the first column | Content in the second column |



### SHA references

Any reference to a commit's [SHA-1 hash][6] will be automatically converted into a link to that commit on GitHub.


    16c999e8c71134401a78d4d46435517b2271d6ac
    mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
    mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac


### Issue references within a repository

Any number that refers to an Issue or Pull Request will be automatically converted into a link.


    #1
    mojombo#1
    mojombo/github-flavored-markdown#1


### Username @mentions

Typing an `@` symbol, followed by a username, will notify that person to come and view the comment. This is called an "@mention", because you're _mentioning_ the individual. You can also @mention teams within an organization.

### Automatic linking for URLs

Any URL (like `http://www.github.com/`) will be automatically converted into a clickable link.

### Strikethrough

Any word wrapped with two tildes (like `~~this~~`) will appear crossed out.

### Emoji

GitHub supports emoji! ![:sparkles:][7]![:camel:][8]![:boom:][9]

To see a list of every image we support, check out the [Emoji Cheat Sheet][10].

Last updated Jan 15, 2014

[1]: http://daringfireball.net/projects/markdown/
[2]: https://gist.github.com/
[3]: http://google.com
[4]: https://octodex.github.com/images/yaktocat.png
[5]: https://help.github.com/articles/github-flavored-markdown
[6]: http://en.wikipedia.org/wiki/SHA-1
[7]: https://assets.github.com/images/icons/emoji/unicode/2728.png ":sparkles:"
[8]: https://assets.github.com/images/icons/emoji/unicode/1f42b.png ":camel:"
[9]: https://assets.github.com/images/icons/emoji/unicode/1f4a5.png ":boom:"
[10]: http://www.emoji-cheat-sheet.com/
  

[Source](https://guides.github.com/features/mastering-markdown/ "Permalink to Mastering Markdown · GitHub Guides")
