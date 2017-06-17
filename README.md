# Atom Guide

[Atom](https://atom.io/) is a cross-platform text editor. It has its own internal system that allows you to install packages that can add functionality to your editor. Atom is beginner friendly and it is relatively easy to become productive with it quickly. Text editors like Atom can be used for writing code as well as other uses.

The purpose of this short guide is to help you with several different tasks that you might want to accomplish using the text editor Atom. It is especially targeted toward new users. Use the table of contents to navigate to the part of the guide which is most relevant to you.

## Prerequisites

In order to follow this guide, you will need to have installed Atom on your system. Visit the [Atom website](https://atom.io/) to install it, if you have not already done so.

### Table of Contents
**[Opening, Editing, and Saving Files](#opening-editing-and-saving-files)**<br>
**[Opening Folders as Projects, and Editing Files within Projects](#opening-folders-as-projects-and-editing-files-within-projects)**<br>
**[Changing Default Tab Space Size](#changing-default-tab-space-size)**<br>
**[Setting Up, and Using Atom from the Command Line to Open Files and Folders](#setting-up-and-using-atom-from-the-command-line-to-open-files-and-folders)**<br>
**[Installing and Applying Themes](#installing-and-applying-themes)**<br>


# Opening, Editing, and Saving Files

### Terminal

For working with your text editor and especially opening new files. It is highly recommended to use Terminal, you might also of heard this described as a Command Line interface or a shell. Terminal is used because we usually create lots of different type of files in a given project for instance: .html, .js(JavaScript), .rb(ruby) files ect. Terminal is used to give direct commands to your system and work an efficient manner.

You will need to locate Terminal on your system.

* In **MacOS**: Navigate to *Finder* > *Utilities* > *Terminal*.
* In **Fedora**: Navigate to the top left hand corner and click on activities. Next, go to the bottom icon on the left hand side of the screen, it is called *Show Applications*. A search bar will open, as well as some application icons. If Terminal icon is present, click on this icon, otherwise type into the search bar "Terminal" and press enter.

> **Note**
Your system may vary! If you do get stuck try a simple internet search, for instance: *how to open Terminal on x*, where x is the system you are using.  

You now have an open terminal and now ready to start using Atom.

# Opening Folders as Projects, and Editing Files within Projects

# Changing Default Tab Space Size

# Setting Up, and Using Atom from the Command Line to Open Files and Folders

# Installing and Applying Themes

# Contributing

This guide is built in Markdown. To download the guide locally on your machine, make changes and be able to preview changes: follow these steps.

1. Download this repository and change directory into the repository provided.
```bash
git clone https://github.com/Charliemowood/atom-guide && cd atom-guide
```

2. Make the changes you require and save those changes.

3. To preview the changes you have made, you will need the help of a piece of software called [grip](https://github.com/joeyespo/grip) to help build the Markdown and preview the result in the browser. Run the following command.
```bash
pip install grip
```

4. Run grip inside the repository where the guide is located.
```bash
grip
```

5. Navigate to your browser of choice and enter the following for the URL. You will be able to preview the built Markdown.
```URL
http://localhost:6419/
```
 6. If you are satisfied with your changes you can push them to git.
