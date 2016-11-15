# IDL as Markdown

##  Table of Contents
1. [Introduction](#introduction)
1. [Why Markdown?](#why-markdown)
1. [Getting started](#getting-started)
    1. [Requirements](#requirements)
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
1. **Broad adoption** - Markdown is being adopted all over the place – from
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

Before you get started creating a new IDL as Markdown lab, you will need the
following:
- a [new GitHub account](https://github.com/join) if you don't have one already
- [git](https://git-scm.com/downloads) installed on your local computer
- (Optional) [GitHub Desktop](https://desktop.github.com/) installed on your
local computer

### Creating a new IDL as Markdown repository
When you have all of the requirements in place, the easiest way to get started
with a new IDL as markdown project is to clone the
[IDL as Markdown](https://github.com/LearnOnDemandSystems/idl-md-sample) sample
repository. This will create a new repository with a template idl.md file in
place that is full of step-by-step TODO comments to help you build the idl.md
file for your lab.

*If git, GitHub, and cloning a repository are new concepts to you, explore the
links in the [Resources](#resources-for-learning-more-about-git-and-github)
section below. Those resources will be very useful as you learn how to use
these highly useful tools.*

Once you have the IDL as Markdown sample repository cloned, you can start work
on the IDL right away by modifying idl.md in your own repository as per the
*TODO* instructions in the comments within that file.

### Resources for learning more about git and GitHub

- [Git Tutorial](https://try.github.io/) (a 25 minute online sandbox where you
can learn Git)
- [Pro Git](https://git-scm.com/book/en/v2) (a free, open-source book -- highly
recommended!)
- [GitHub Bootcamp](https://help.github.com/categories/bootcamp/) (A set of
learning resources to get more out of GitHub)
