# IDL as Markdown

##  Table of Contents
1. [Contents](#contents)
1. [Why Markdown?](#why-markdown)
1. [Getting started](#getting-started)
    1. [Requirements](#requirements)
    1. [Markdown editors](#markdown-editors)
    1. [Creating a new IDL as Markdown repository](#creating-a-new-idl-as-markdown-repository)
    1. [Resources for learning more about git and GitHub](#resources-for-learning-more-about-git-and-github)

<hr>

## Contents

This repository contains documentation and templates that you can use when
defining lab content for an Integrated Digital Lab (IDL) in Markdown format.

## Why Markdown?

There are many reasons why using Markdown as a lab content definition format is
beneficial:

1. **Readability** - A Markdown IDL document reads much like a lab manual would.
1. **Simplicity** - Markdown is structured text without tags. Editing Markdown
   files is much easier and faster than editing lab content inside of a user
   interface.
1. **Offline editing** - There are plenty of free and commercial offline
   Markdown editors available for all mainstream platforms/devices being used
   today: Windows, macOS, Linux, iOS, and Android.
1. **Revision control** - GitHub has native support for Markdown (Markdown is
   the preferred method of documentation on GitHub), and with GitHub comes
   revision control, support for multiple authors, pull requests, forks/clones,
   etc.
1. **Multi-author support** - By using Markdown inside of services like GitHub
   (or similar services like Visual Studio Online), you can support multiple
   content authors contributing to the content for one lab at the same time.
1. **Broad adoption** - Markdown is being adopted all over the place â€“ from
   creation of documentation at Microsoft (MSDN docs, PowerShell Help files,
   etc.) to defining blog content/pages (Wordpress, Ghost, others) to Slack
   channels (you can use Markdown directly inside of Slack messages), and much,
   much more.
1. **Tooling** - There are some great libraries out there to convert from
   Markdown to HTML such as [Markdig](https://github.com/lunet-io/markdig).
   Markdig is very fast and includes extra goodies like AST generation, which
   makes for much easier Markdown conversion to other content by using the
   Visitor pattern.

## Getting started

### Requirements

Before you get started creating a new IDL as Markdown lab, you will need a
[new GitHub account](https://github.com/join) if you don't have one already.

Also, if you want offline editing support, you will need:
- [git](https://git-scm.com/downloads) installed on your local computer
- (Optional) [GitHub Desktop](https://desktop.github.com/) installed on your
local computer if you want to work with GitHub in a UI
- a markdown editor (see below)

### Markdown editors
It is very useful when editing a Markdown document to use an editor that has
native support for Markdown. There are editors available for Windows, macOS,
Linux, iOS, and Android. Some editors are commercial, others free. There are
also editors on the web. Which editor you use is up to you. I have listed a few
noteworthy editors below. The list is by no means comprehensive nor does it try
to highlight the best editors. It simply gives you a place to start looking.

#### Cross platform (some combination of Windows, macOS, and Linux)
- Atom (works on Windows, macOS, and Linux)
- Visual Studio Code (works on Windows, macOS, and Linux)
- Sublime (works on Windows, macOS, and Linux)
- Remarkable (works on Windows and Linux)
- Haroopad (works on Windows, macOS and Linux)

#### for Windows
- MarkdownPad
- Notepad++ (with a plugin)
- MarkPad

#### for macOS/iOS
- Write
- Ulysses
- MacDown (macOS only)

#### for Linux
- GNU Emacs
- ReText
- UberWriter

#### for Android
- JotterPad
- iA Writer
- MarkdownX

### Creating a new IDL as Markdown repository
When you have all of the requirements in place, the easiest way to get started
with a new IDL as markdown project is to clone the
[IDL as Markdown Template](https://github.com/LearnOnDemandSystems/idl-md-template)
repository. This will create a new repository with a template content.md file in
place that is full of step-by-step TODO comments to help you build the
content.md file for your lab.

Another useful resource is the
[IDL as Markdown Sample](https://github.com/LearnOnDemandSystems/idl-md-sample)
repository. This repository contains a complete example illustrating what the
finished product might look like. 

*If git, GitHub, and cloning a repository are new concepts to you, explore the
links in the [Resources](#resources-for-learning-more-about-git-and-github)
section below. Those resources will be very useful as you learn how to use
these highly useful tools.*

Once you have the IDL as Markdown sample repository cloned, you can start work
on the IDL right away by modifying content.md in your own repository as per the
*TODO* instructions in the comments within that file.

### Resources for learning more about git and GitHub

- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
(a GitHub Guide to learning Markdown)
- [Git Tutorial](https://try.github.io/) (a 25 minute online sandbox where you
can learn Git)
- [Pro Git](https://git-scm.com/book/en/v2) (a free, open-source book -- highly
recommended!)
- [GitHub Bootcamp](https://help.github.com/categories/bootcamp/) (A set of
learning resources to get more out of GitHub)
