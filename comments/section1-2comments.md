## Lesson 1: Brief History of Python

○ Specifically designed as an easy to use language
○ High focus on readability of code

● Why choose python? 
  ○ Designed for clear, logical code that is easy to read and learn.
  ○ Lots of existing libraries and frameworks written in Python allowing users to apply Python to a wide variety of tasks
  ○ Lots of other programming languages use braces and brackets that can make code convoluted and maybe heard to read, but  
  python makes use of something called white space and indentation that makes its code very accessible

● Other reasons
  ○ Focuses on optimizing developer time, rather than a computer's processing time
  ○ Great documentation online
    ■ `docs.python.org/3`
  ○ So the whole language of python is designed for users to really get prototyping up and running really quickly
  
● What can you do with python? 
  ○ This course first focuses on "base" Python, which consists of the core components of the language and writing scripts
  and small programs
  ○ Later we begin to learn about outside libraries an frameworks that greatly expand Python's capabilities
  ○ Python is often referred to as a program that comes with batteries include, even its base version actually comes
  in with additional modules for writing scripts
    □ An example of this would be something like the random module that comes with Python, which it allows us to quickly
    create random numbers or math module, etc...
  ○ These are frameworks that are not included with base python but we can easily download and work with basic python
  skills

  ● Other uses for python:
    ● Automate simple tasks
      ■ Searching for files and editing them
      ■ Scraping information from a website
      ■ Reading and editing excel files
      ■ Work with PDFs
      ■ Automate emails and text messages
      ■ Fill out forms

    ● Data science and machine learning
      ■ Analyze larger data files
      ■ Create visualizations
      ■ Perform machine learning tasks
      ■ Create and run predictive algorithms

    ● Create websites
      ■ Use web frameworks such as Django and Flask to handle the backend of a website and user data
      ■ Create interactive dashboards for users

## Lesson 2: Command Line Basics

  ● Before we installing anything, its important to have a very quick overview of how to work at the command line
  ● This allows us to programmatically move through our computer's directories

  ● We will cover: 
    ○ Find your current directory
    ○ Listing all files in a directory
    ○ How to change directory
    ○ How to clear the command line screen

    - Some of the commands being taught are the ones i'm used, such as pwd, ls, cd, and so on.
  
## Lesson 3: Installing Python

  ○ Installation Anaconda Distribution For Python
    ■ Anaconda installs python and an easy to use development environment and navigator launch tool.
  ○ Briefly run Jupyter Notebook.
  ○ Explore "no install" online options

  . For this course, the instructor chose the anaconda distribution instead of just going to python.org and only downloading
  python. The anaconda installs the language and a bunch of really useful tools for python.


  ● Quick Note

    ○ There are now many online "no install" Python environments that can run in the browser (as long as we have internet
    connection)
    ○ While not officially part o the course, he will give us a brief tour of these online "no install" options at the
    end just to give us an idea.


  ● Anaconda Installation

    ○ First of all, to install python we will use the free individual Anaconda distribution
    ○ This distribution includes Python as well as many other useful libraries, including Jupyter Notebook environment.
    ○ Anaconda can also easily be installed on to any major OS, Windows, MacOS, or Linux
    ○ Go to `www.anaconda.com/downloads`, input your e-mail and download the free version

  ● Anaconda Navigator

    ○ After installing navigator, we need to run the anaconda navigator, which is GUI that comes with Anaconda Distribution
    ○ It's designed to help you easily manage your python environments, packages, and projects — all without needing to use
    the terminal
    ○ With anaconda we can: 
      . Open apps like `Jupyter notebook`, `JupyterLab`, `Spyder`, `VS Code`, etc.
      . Install, update, or remove Python libraries using `Conda` or `pip` — visually
      . Create isolated Python environments (for example, one for Python 3.10, another for ML)
      . Easily activate and switch between different projects or environments
    ○ Anaconda package is not only for Python, but multiple development environments for you.
    ○ For this project, we will use Jupyter Notebook

  ● Anaconda Navigator Tour

    ○ On the left hand-side we have some other tabs, such as: 
      ■ Home Tab: Simply returns us to home
      ■ Environments Tab: 
        ○ Environments in this case, stands for `virtual environments`
        ○ It essentially allow us to create small virtual environments separate from our base environment to install
          particular versions of libraries.
      ■ Learning Tab: Links for documentation and other training videos — more inclined to machine learning.
      ■ Community Tab: Events and forums we can check out
      

  ● Jupyter Notebook

    ○ As soon as we launch it, a new tab is going to open in our browser
    ○ Jupyter does not require to run, it is just using our browser as the visual interface for us to write our code in
    ○ It is typically going to launch on our main user drive directories, just like the file system
    ○ We can use it to create new folders and new notebook files from here as well, so by clicking in new, we can choose
    to create a folder (just as we would do normally on the OS) and place notebooks inside of it
    ○ As soon as we create a new notebook, it will automatically launch a new notebook
    ○ A notebook is essentially an environment where there are individual cells to write python code
    ○ In order to run a cell putting some code into it, such as 1 + 1, we press the play button on the top bar, and it
    outputs as 2
    ○ Other example is typing 1 + 1 # Shift + Enter it runs the cell and automatically create a new cell underneath it

  ● Brief tour on the no installation options

    ○ jupyter.org/try
    ○ Google Collab Online Notebooks
    ○ Repl.it
      ■ Google Search: 
        ● "Python Interpreter Online"

    ● The reason we would not want to use any of these options instead of installing something locally. For one thing,
    it can be difficult to load our own code, data, or notebooks, in one of these free no installation options
      ○ They have the free tier, that doesn't save our code, and we would have to pay in order to our code be saved
      and executed
      ○ Because these options can change in the future, the instructor chose to not officially support them in this course 

## Lesson 4 - Running python code

● There are several ways to run Python code.
● There are 3 main types of environments: 
  ○ Text Editors
    ■ General editors for any text-file, they're designed in a general format where they can open a text-file, or a .html
    or .py. This means that any variety of file types we will be able to open them up and edit them.
    ■ Can be  customized with plugins and addons
    ■ Because of that, and their general format, they're not designed with only python in mind, meaning we would sacrifice
    some python specific functionality, such as auto complete for python, or looking up things and documentation automatically
    with python.
    ■ If we wish this functionality we would need to download them or an addon/extension for it.

  ○ Full IDEs

    ■ Development environments designed specifically for Python
    ■ Used in larger programs.
    ■ Only community editions are free
    ■ Lots of extra functionality
    ■ Great when we have pieces of code that need to interact with each other 


    ■ Most popular: PyCharm and Spyder
    

  ○ Notebook Environments

    ■ Great for learning
    ■ We can see the input code and the output code right next to each other
    ■ Notebooks use blocs of code that are referred to as cells, and we can split our code into different cells and run
    pieces of code by running individual cells
    ■ Different from the approach of text editors and development environments, since we have to develop a larger script
    first and then run the whole script

    ■ Other things that differentiates the notebook environment is that they support inline markdown notes, which mean we
    can write for ourselves pieces of notes — pieces of text, as well as visualizations, videos, and more
    ● Special file formats that are not .py, and because of that, typically, if we see a .py script in our computer, we
     double click on them, some sort of text editor is going to open it. Since notebooks are able to support extra stuff,
     they have their own notebook format, which is .ipynb (i python notebook), and because of that, we can't actually open
     a notebook file, we need to launch it using the jupyter notebook launcher.
    ● Jupyter notebook is almost the only notebook environment for python because of how important it is.
    
  ● Running first python code

      ■ Create a file and save it with a .py extension.\

      ○ Running in different environments

        ■ Terminal: open the terminal, move to the folder where the file is located an run `python fileName.py`
        ■ Python: Anaconda direct connection: type python and we'll enter a direct connection which allow us to write python
        code
        ■ Notebook Environment: Open the anaconda navigator -> launch jupyter notebook -> create .py file -> type any python
        code
        
      ○ Jupyter Notebook System

        ■ Since we'll not use jupyter notebook for larger files like this, inside jupyter tab, we'll create a new python
        notebook file
        ■ Notebook uses a cell based system, meaning that we write code in a cell, execute, and then see the actual output
        right below the cell (We can check this by simply printing something)
        ■ Notebook system can hold markdown text, to do so, we simply click on a cell, then on a dropdown where it says code
        and change it to markdown

      ○ .ipynb

        ■ We can notice that by double clicking .ipynb files, if we don't open it with an editor or system that supports
        that kind of file, we'll end up seeing some scrambled code. Therefore, we'll have to open anaconda navigator,
        jupyter notebook, and then open the file in order to edit or visualize it
      




