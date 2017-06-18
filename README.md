# Atom Guide

[Atom](https://atom.io/) is a cross-platform text editor. It has its own internal system that allows you to install packages that can add functionality to your editor. Atom is beginner friendly and it is relatively easy to become productive with it quickly. Text editors like Atom can be used for writing code as well as other uses.

The purpose of this short guide is to help you with several different tasks that you might want to accomplish using the text editor Atom. This guide is especially targeted toward new users. You can use the table of contents to navigate to the part of the guide which is most relevant to you.


**Note:**
> Your system may vary. The example systems used in this guide are MacOS Sierra 10.12.1 and Fedora 25. MacOS has some unique features but Fedora should be quite representative of other operating systems. However, be aware that you might need to modify some of these instructions based on characteristics of your own system. If you do get stuck try a simple search on the internet, for instance: *how to open Terminal on x*, where x is the system you are using.  

## Prerequisites

In order to follow this guide, you will need to have installed Atom on your system. Visit the [Atom website](https://atom.io/) to install it, if you have not already done so.


### Table of Contents
**[Opening, Editing, and Saving Files](#opening-editing-and-saving-files)**<br>
**[Opening Folders as Projects, and Editing Files within Projects](#opening-folders-as-projects-and-editing-files-within-projects)**<br>
**[Changing Default Tab Space Size](#changing-default-tab-space-size)**<br>
**[Setting Up, and Using Atom from the Command Line to Open Files and Folders](#setting-up-and-using-atom-from-the-command-line-to-open-files-and-folders)**<br>
**[Installing and Applying Themes](#installing-and-applying-themes)**<br>


# Opening, Editing, and Saving Files

In this section, there will be a focus on getting started with several basic tasks in Atom using the graphical interface of your system. You can move to a more relevant section if you prefer to use the [command line](#setting-up-and-using-atom-from-the-command-line-to-open-files-and-folders).

### Open a file in Atom

To open a file in Atom use the following procedure:

1. Find the file you want to open. It can be any file in your file system, for instance, a file located in *Desktop* or *Documents*.
2. Right click on the file you want to open.
3. Select from the dropdown *Open with* or *Open with Other Application* depending on your operating system.
4. A new window will open. Click on the Atom icon.

You will now have the file you have selected open in Atom.

### Edit a file in Atom

Once a file is open, the cursor will be located inside the file you have selected. You can then modify the file as you would like by inputing text.

### Save a file in Atom

There are two ways to save a file in Atom.

**Inside Atom**

1. From within Atom navigate to **File**.
2. Select **Save** from the dropdown.

**Using Shortcuts**

To save a file you can use a keyboard shortcut. Use the table below to decide which keyboard shortcut you should use to save your file.

#### Shortcuts for Saving a File

| System        | Shortcut |
| ------------- | -------- |
| MacOS         |  Cmd-s   |
| Other Systems |  Ctrl-s  |



# Opening Folders as Projects, and Editing Files within Projects

### Opening Atom

To open a project in Atom, you will need to open it in the graphical interface in your system first.

Navigate to Atom in your system:

* In **MacOS**:

  * **Finder** > **Applications** > **Atom**.

* In **Fedora**:

  * Click on **Activities** in the top left hand corner.
  * Click the bottom icon on the left hand side of the screen, it is called *Show Applications*.
      * A new window with a search bar and a selection of icons will open. If you can see the Atom icon, click on it.
      * Otherwise type Atom into the search bar and press enter.

You should now be able to see that Atom has opened successfully.

### Opening Folders as Projects

To open folders in your system as Atom projects, follow the procedure below:

1. From within Atom navigate to **File**.
2. Select from the dropdown **Open**.
3. A small window will open.
4. You are now inside your file system. Choose a folder that you would like to open.
5. Click **Open** in the bottom right hand corner to confirm your choice.  

Your folder will now be open as a project in Atom.

### Editing Files in Projects

On the left-hand side of the screen, you will see a sidebar with all files in the project.

To navigate to and edit a particular file in the project. Click on the name of the file in the sidebar and the selected file will open. You can now make any edits you wish and [save](#save-a-file-in-atom) the file.


# Changing Default Tab Space Size

You may want to make some modifications to your editor like changing the default Tab Space size. For instance, you might be writing *Java* and need four spaces rather than the default in Atom which is two spaces.

To make such changes you need to access the core settings of Atom. To access these settings use the table below to decide which shortcut you need, use the modifier key your operating system needs followed by the comma key.

#### Shortcuts to Settings

| System        | Shortcut |
| ------------- | -------- |
| MacOS         |  Cmd-,   |
| Other Systems |  Ctrl-,  |


You should now have Atom's core settings open. Use the procedure below to change the tab length.

1. On the left of the screen select **Editor**.
2. Scroll down to the section named **Tab Length**.
3. In the text box below input the desired tab length you want.

Your newly chosen tab length will now be active across all your projects.

# Setting Up, and Using Atom from the Command Line to Open Files and Folders

### Terminal

For working with your text editor and especially opening new files, you need to use Terminal. You might also hear this described as a command line interface or a shell. Terminal is used to give direct commands to your system. Terminal is useful to you because it can create lots of different types of files for a given project quickly.

You will need to locate Terminal on your system.

* In **MacOS**:

  * Navigate to **Finder** > **Applications** > **Utilities** > **Terminal**.

* In **Fedora**:

    * Click on **Activities** in the top left hand corner.
    * Click the bottom icon on the left hand side of the screen, it is called *Show Applications*.
    * A new window with a search bar and a selection of icons will open. If you can see the Terminal icon, click on it.
    * Otherwise type *Terminal* into the search bar and press enter.

You now have an open Terminal and are ready to start using Atom from the command line.


### Opening files in Atom from the Command Line

In this section, you will learn how to use [Terminal](#terminal) to open files in Atom.

To open a new file you will usually locate the new file in a folder. The purpose of this is to make your project easy to find and add other relevant files.

Make sure that you now have an open Terminal.

#### Create a New File and Open Using Atom

All the following commands should be run sequentially by typing the commands into Terminal and pressing enter.

1. Run the following command to create a new folder:

    ```bash
    mkdir example/
    ```

2. To move into the folder you have created, run the command:

    ```bash
    cd example/
    ```

3. To create a new file in this folder, run the command:

    ```bash
    touch example.txt
    ```

4. Use Atom to open this file:

    ```bash
    Atom example.txt
    ```

You should now have the file open in Atom. In this case `example.txt` should be open.


#### Open Existing Folders from the Command Line Using Atom

There are two ways to open existing folders from the command line. Remember that command line refers to Terminal, so this will need to be open for you to be able to run commands.

* You can follow the Atom command by the folder you want to open. Like running the following command:

    ```bash
    Atom example/
    ```    

* If you are already located in the folder you want to open. The following command opens everything that is inside that folder:

    ```bash
    Atom .
    ```

# Installing and Applying Themes

You may want to change how Atom appears. You do this through changing the theme of the editor.

You need to open the core settings of Atom. Use the table below to decide which shortcut you need, use the modifier key your system needs followed by the comma key.

#### Shortcuts to Settings

| System        | Shortcut |
| ------------- | -------- |
| MacOS         |  Cmd-,   |
| Other Systems |  Ctrl-,  |

You should now have the settings open.

#### Procedure for Selecting a Theme

1. On the left of the screen select **Themes**.
2. Select from the dropdown below **UI Theme** or **Syntax Theme** a theme that you would like to use.

The theme changes will take immediate effect.

### Install a New Theme

It may be the case that none of the default themes that come with Atom meet your needs. There are lots of themes to choose from online which you can add to Atom.

#### Procedure for Installing a New Theme


1. To get more themes navigate to the core settings of Atom as you did in the previous section.
2. On the left of the screen select **Install**.
3. Check **Themes** to the right of the search bar.
4. Search for the theme you would like using the search bar. You can find more information about the themes available [here](https://atom.io/themes).
5. Click install. When the theme has finished downloading, it will be available for you to select from the dropdown in **Themes** as you did with the [default themes](#installing-and-applying-themes).  

--------------------------------------------------------------------
# Contributing

This guide is built in Markdown. Use the following procedure to download the guide locally on your machine, make changes and be able to preview changes.

#### Downloading and Building this Guide Locally on your System

1. Download this repository and change directory into the repository provided:

    ```bash
    git clone https://github.com/Charliemowood/atom-guide && cd atom-guide
    ```

2. Make the changes you would like and save those changes.

3. To preview the changes you have made, you will need the help of a piece of software called [Grip](https://github.com/joeyespo/grip) to help build the Markdown and preview the result in the browser. Run the following command:

    ```bash
    pip install grip
    ```

4. Run Grip inside the repository where the guide is located:

    ```bash
    grip
    ```

5. Navigate to your browser of choice and enter the following for the URL:

    ```URL
    http://localhost:6419/
    ```
 6. You will be able to preview the built Markdown. If you are satisfied with your changes you can push them to Git.
