# Setting up Environments and Installing Packages Using Conda

## Summary of steps to complete

- [x] Fork this repository so you have your own copy to work on.
- [x] Clone the repository on your local machine. 
- [x] Edit this README.md file on your machine.
- [x] Run the Conda commands shown in the video and describe them in the table below.
- [x] Push your changes to your GitHub repository.
- [x] Submit a link to this GitHub repository in Canvas.

## 1. Fork & Clone this repository

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/exerGitPractice
* This can also be done directly in VSCode
  * Create a new folder on your machine where you want to put this repository if you don't already have one you want to use.
  * Copy the Clone or Download path for this repository from GitHub.
  * In VSCode from the command pallette (Ctrl-Shift-P) run Git: Clone
  * Paste the path into the path field which pops up
  * Select your new folder you created on your machine
  * A new folder for the repository with the repository files should be in the folder you selected showing in the Explorer window in VSCode on the left side.
  
## Edit your README.md file

* [x] In an editor of your choice (i.e. VSCode) edit this README.md file to add the answers requested in the tables.

## Follow along with this tutorial

* Conda What and Why? (27 min): https://www.youtube.com/watch?v=23aQdrS58e0&list=PLG9A6ovzPqX6d9uWzx0UYN9pm0zzl5ofA&index=13&t=0s
  * He installs Miniconda. We will be using Anaconda. Don't install Miniconda.
  * Follow along with the rest of the tutorial.
  * Go ahead and create the environments as he creates them in the tutorial.
  * (2021 update: I recommend managing environments as shown in the new Anaconda introduction video. https://anaconda.cloud/tutorials/getting-started-with-anaconda-individual-edition%3Fsource%3Dindividual-edition-tutorial) If you want to try creating the environments using the user interface for Anaconda Navigator instead of the command line shown in the Conda What and Why tutorial, that's fine. But watch the Conda What and Why tutorial to understand some of the differences between Conda environments and other types of virtual environments available in Python.

## Conda Concepts

* [x] Describe the Conda concepts used in the video and listed in the table below.

|   Concept   |         Description or short answer         |
|     ---     |                     ---                     |
|What is the purpose of having different environments?     |Having different environments allows you to create an isolated place to work on individual projects with access to the specific applications that you will be needing without creating excess clutter. |
|What is the default package manager in Python?            |Python 3.7.0 |
|How do you manage environments and packages in Anaconda?  |Environments can be managed by looking up the environment list 'conda env list' and then typing 'conda activate "name of env". Additionally, packages in the current env can be looked up using the 'conda list' command. |
|`conda list`       |Shows all default packages that are installed with anaconda. |
|`conda env list`       |Shows a list of all environments that we have created. |
|How do you keep your base environment unchanged?       |Create new environments where changes can be made. |
|What is the link to the Conda cheat sheet? (link in video notes is broken)      |https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf |
|`conda create --name XXXX`       |This command is used to create a new environment. |
|`conda activate XXXX`       |The command allows the user to enter the previously created environment. |
|`conda install YYYY`       |This command allows the user to download packages from the default channel/package installer. |
|channels in Conda       |Channels are, to my understanding, a place where conda goes to look for the various packages that are being installed; like a package installer. |
|`conda install -c ZZZZ YYYY`       |This command allows the user to look into a specific channel/package installer "ZZZZ" to download a specific package "YYYY". |
|`conda config --show channels`       |This command allows the user to see what channels have been used previously to download packages. |
|`conda config --add channels ZZZZ`       |This commonad allows the user to add a specific channel to the channel list for future use when adding packages. |
|conda-forge.org       |Conda-forge is a channel that can be added to the channel list and provides access to additional packages. |
|`conda deactivate`       |Closes the activated environment. |
|`conda config --get channels`       |Allows the user to see the accessible channels with ranking in priority. |

* After creating the environments he created in the video on your computer, what would the results of running the command `conda env list` look like with the da35 environment activated. Paste the output from your command prompt in the code block below.

```
#Paste your results here.


```
* What command would you use to remove the environments you created for this exercise from your computer?

```
#Type the command here.

```
## 2021 Update
Python, Anaconda, and many programming languages are constantly evolving. The video Conda What and Why provides a great explanation of why you may want to use virtual environments for your Python projects, and it provides a nice demonstration of how to work in the command line. However, environment management using Anaconda Navigator is more user friently than ever. I personally will be using Anaconda Navigator to manage environments and packages since it seems easier to see what is going on using the GUI. If you haven't done so already watch the introduction to Anaconda video and pay close attention to the section on using Anaconda Navigator to create environments and install packages. https://anaconda.cloud/tutorials/getting-started-with-anaconda-individual-edition%3Fsource%3Dindividual-edition-tutorial
