# Atom Guide

[Atom](https://atom.io/) is a cross-platform text editor. It has its own internal system that allows you to install packages that can add functionality to your editor. Atom is beginner friendly and it is relatively easy to become productive with it quickly. Text editors like Atom can be used for writing code as well as other uses.

The purpose of this short guide is to help you with several different tasks that you might want to accomplish using the text editor Atom. This guide is especially targeted toward new users. Use the table of contents to navigate to the part of the guide which is most relevant to you.

The example systems used in this guide are MacOS Sierra 10.12.1 and Fedora 25. MacOS has some peculiarities but Fedora should be quite representative of other systems. Be aware that you might need to modify some of these instructions based on characteristics of your system.

## Prerequisites

In order to follow this guide, you will need to have installed Atom on your system. Visit the [Atom website](https://atom.io/) to install it, if you have not already done so.

### Table of Contents
**[Opening, Editing, and Saving Files](#opening-editing-and-saving-files)**<br>
**[Opening Folders as Projects, and Editing Files within Projects](#opening-folders-as-projects-and-editing-files-within-projects)**<br>
**[Changing Default Tab Space Size](#changing-default-tab-space-size)**<br>
**[Setting Up, and Using Atom from the Command Line to Open Files and Folders](#setting-up-and-using-atom-from-the-command-line-to-open-files-and-folders)**<br>
**[Installing and Applying Themes](#installing-and-applying-themes)**<br>

# Opening, Editing, and Saving Files

In this section, there will be a focus on getting started with several basic tasks in Atom using the graphical interface of your system. You may prefer to use the [Command Line](#setting-up-and-using-atom-from-the-command-line-to-open-files-and-folders).

### Open a file in Atom

It is relatively simple to open a simple a file in Atom.

You need to find the file you want to open. It can be any file in your filesystem, for instance a file in *Desktop* or *Documents*.

* Right click on the file you want to open.
* Select from the dropdown *Open with* or *Open with Other Application* depending on your system.
* A new window will open. Click on the Atom icon.

You will now have the file you have selected open in Atom.

### Edit a file in Atom

Once a file is open, the cursor will be focussed inside the file you have selected. You can then modify the file as you would like by inputing text.

### Save a file in Atom

There are two ways to save a file in Atom.

*Classic Way*
* Navigate to *File*.
* Select *Save* from the dropdown.

*Using Shortcuts*

To save you can use a keyboard shortcut.
* In **MacOS**: Cmd+s
* In **Other Systems**: Ctrl+s


# Opening Folders as Projects, and Editing Files within Projects

### Opening Atom

To open a project in Atom, you will need to open it in the graphical interface in your system first.

Navigate to Atom in your system:

* In **MacOS**: *Finder* > *Applications* > *Atom*.
* In **Fedora**:
  * Click on *Activities* in the top left hand corner.
  * Click the bottom icon on the left hand side of the screen, it is called *Show Applications*.
  * A new window with a search bar and a selection of icons will open. If you can see the Atom icon, click on it.
  * Otherwise type Atom into the search bar and press enter.

You should now be able to see that Atom has opened successfully.

### Opening Folders as Projects

To open folders in your system as Atom projects, follow the procedure below:

* Navigate to *File*.
* Select from the dropdown *Open*
* A small window will open.
* You are now inside your filesystem. Choose a folder that you would like to open.
* Click *Open* in the bottom right hand corner to confirm your choice.  

Your folder will now be open as a project in Atom.

### Editing Files in Projects

On the left-hand side of the screen, you will see a sidebar with all files in the project.

To navigate to and edit a particular file in the project. Click on the name of the file in the sidebar and the selected file will open. You can now make any edits you wish and [save](#save-a-file-in-atom) the file.

# Changing Default Tab Space Size

You may want to make some modification to your editor like changing the default Tab Space size. For instance, you might be writing Java and need four spaces rather than the default in Atom which two spaces.

To make such changes you need the access the core settings of Atom. To access these setting input the following based on the nature of your system.
* In **MacOS**: Press Cmd + , (command key followed by the comma key)
* In **Other Systems**: Press Ctrl + , (control key followed by the comma key)

You should now have Atom core settings open.

* On the left of the screen select *Editor*.
* Scroll down to the section named *Tab Length*.
* In the text box below input the desired tab length you want.

Your newly chosen tab length will now be in effect across all your projects.

# Setting Up, and Using Atom from the Command Line to Open Files and Folders

### Terminal

For working with your text editor and especially opening new files. It is highly recommended to use Terminal, you might also of heard this described as a Command Line interface or a shell. Terminal is used to create lots of different type of files in a given project for instance: .html, .js(JavaScript), .rb(Ruby) files ect. Terminal is used to give direct commands to your system and work in an efficient manner.

You will need to locate Terminal on your system.

* In **MacOS**: Navigate to *Finder* > *Applications* > *Utilities* > *Terminal*.
* In **Fedora**: Navigate to the top left hand corner and click on activities. Next, go to the bottom icon on the left hand side of the screen, it is called *Show Applications*. A search bar will open, as well as some application icons. If Terminal icon is present, click on this icon, otherwise type into the search bar "Terminal" and press enter.

> **Please Note:**
> Your system may vary. If you do get stuck try a simple internet search, for instance: *how to open Terminal on x*, where x is the system you are using.  

You now have an open terminal and are ready to start using Atom.

### Opening files in Atom

In this section, you will learn how to use [Terminal](#terminal) to open files in Atom.

To create, a new file you will usually locate the new file in a repository to make your project easy to find and add other relevant files.

 first need to create it as it does not exist yet. To create your first file in Atom, type the following commands into your Terminal.
```bash
atom example.txt
```

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
