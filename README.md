@productivity

# How to setup this Note-taking environment using Sublime

> Sublime Text can become almost anything you need it to be. In skilled hands, it can defeat an army of ninjas without your breaking a sweat. Empty your mind. Be sublime, my friend.

Inspired by [this blogpost][linkThisBlogpost]

## Sublime
* Install [Sublime Text 3](https://www.sublimetext.com/)
* Install Packages
    - Install [Package Control](https://packagecontrol.io/installation)
    - Install [Markdown Editing](https://github.com/SublimeText-Markdown/MarkdownEditing)
    - Install [Advanced New File](https://github.com/skuroda/Sublime-AdvancedNewFile)
    - Install [Markdown Preview][linkMarkdownPreview]
* [Modify Packages](http://docs.sublimetext.info/en/latest/basic_concepts.html#packages-plugins-resources-and-other-terms)
    - Navigate to the user Packages directory: Preferences->Browse Packages...
    - Replace this Packages directory with the contents of [this Git repo](https://github.com/DougMHu/Sublime-Packages-Environment4Notes)
    - Restart Sublime

### Setting up a Project
__SECTION NOT COMPLETE__

## Markdown
### Important key-bindings
* f5: sorts lines in alpha order
* __LIST NOT COMPLETE__

## File Names
* Ctrl+Alt+N to add a new file
default filenames are the current ISO datetime, replacing ':' with '_' because filenames cannot use the ':' character.

## Search
* Ctrl-Shift-R: Shows all symbols in a project
* Type a word in the quick menu to do a fuzzy search over all the symbols
* Navigate the quick menu with arrow keys, and select using Enter

### By markdown title
All Markdown titles (prefaced with 1 - 6 '#' characters) are considered symbols

### By @ label
To create a label, write '@label_name' substituting 'label_name' with any label name consisting of alphanumerics and underscores.

### Fuzzy search entire project
I don't think this is possible... Indexing all words in a project sounds impractical.

### Search by date
__SECTION NOT COMPLETE__

* before
* after
Ctrl-Shift-F and select folders manually?

### Rank files by most views
The idea:

* hit count
* file hit propagates to referenced files

Probably not worth implementing...

## Misc
### Regex
* [Regex reference][linkRegexReference]

[linkThisBlogpost]: http://plaintext-productivity.net/2-04-how-to-set-up-sublime-text-for-markdown-editing.html
[linkRegexReference]: http://regexr.com/
[linkMarkdownPreview]: https://github.com/revolunet/sublimetext-markdown-preview
