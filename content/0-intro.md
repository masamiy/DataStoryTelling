---
title: What is data storytelling?
nav: What is data storytelling?
topics: What is data storytelling?; From data to knowledge; What we cover in this resource
---

# What is data storytelling?
 `{% include figure.html img="Data_Narrative_Visuals.png" alt="cat" caption="Data Storytelling elements" width="70%" %}`

# From data to knowledge
 `{% include figure.html img="From_data_to_knowledge.jpg" alt="cat" caption="From data to Knowledge" width="80%" %}`


If a story is brought together by your data, visuals and narratives- let’s start by looking at your data.  

Data is the basis of your research, where you derive your insights.  

Data starts off as numbers and letters but by exploring the relationships between your data, you create information.  

This information is great, but you need to explain what this information means .. creating Knowledge.  

This knowledge is what we want to share with people 

## Activity - Gapminder

Watch this 4 minutes video. 
{% include video-embed.html youtubeid="jbkSRLYSojo" caption="Visualise Your Thesis" %}

Do you find his finding interesting? Did you feel Hans Roslling's excitement?

Do you think you feel the same excitement if he presents his finding in a data file, e.g., Microsoft Excel sheet?



To create your own materials using `workshop-template-b`, please create a free [GitHub account](https://github.com/join) if you do not have one already.
Basic familiarity with the GitHub web interface will be helpful.

For a quick introduction check out GitHub's [Hello World guide](https://guides.github.com/activities/hello-world/), or the extensive [GitHub Learning Lab](https://lab.github.com/).

It is possible to create a website with this template using only GitHub's web interface--in fact, it works great!
However, for more advanced uses you will want Git, Ruby, and Jekyll installed on your computer to do local development.

{% capture text %}
1. Have a [GitHub](https://github.com) account.
2. Click the green "Use this template" button on the [workshop-template-b repository](https://github.com/evanwill/workshop-template-b) to make your own copy.
3. Optional: have [Git](https://git-scm.com/), [Jekyll](https://jekyllrb.com/), and a nice [text editor](https://code.visualstudio.com/) installed.
{% endcapture %}
{% include card.html text=text header="Setup Overview" %}





[Git](https://git-scm.com/) is a [free](https://www.gnu.org/philosophy/free-sw.en.html), [distributed](https://en.wikipedia.org/wiki/Distributed_version_control) version control system. [GitHub](https://github.com/) is a Git repository hosting service, a place to store and sync your work in the cloud--your Jekyll and GitHub Pages projects will be under Git version control, so you need the software on your machine. 

- Windows: install [Git for Windows](https://git-for-windows.github.io/) using the default options. This will give you Git, Git Bash, and Git GUI. Git Bash is a great terminal that lets you use UNIX style commands on Windows.
- Mac: check if Git is already installed by opening terminal and typing `git --version`. If you do not have it, download the official [Mac installer](https://git-scm.com/downloads).
- Linux: check if Git is already installed by opening terminal and typing `git --version`. If you do not have it, install from your distribution's software center or package manager (for Ubuntu `sudo apt install git`).

If you are interested in using a visual GUI application integrated with GitHub, Windows and Mac users should also install [GitHub Desktop](https://desktop.github.com/) using the default options.
You can install GitHub Desktop in addition to other versions of Git.

There are other [GUI apps available](https://git-scm.com/downloads/guis) for managing and visualizing Git repositories, including Linux options.




- **Windows:** Use [RubyInstaller for Windows](https://rubyinstaller.org/). 
    - First, [download](https://rubyinstaller.org/downloads/) the suggested stable version "WITH DEVKIT" (as of this writing, Ruby+Devkit 2.7.X (x64)) and double click to install. Use the install defaults, but make sure "Add Ruby executables to your PATH" is checked. On the final step, ensure the box to start the MSYS2 DevKit is checked.
    - Second, the installer will open a terminal window with options to install MSYS2 DevKit components. Choose option 3, "MSYS2 and MINGW development toolchain", or simply press ENTER to install all the necessary dependencies. (This installer can be restarted by typing `ridk install` into a command prompt)
- **Mac:** OS X has a version of Ruby installed by default. Check the version with `ruby -v`. If it is > 2.2.5 you can use the system Ruby. However, a newer version can be installed using [Homebrew](https://brew.sh/), `brew install ruby`, or a manager such as [rbenv](https://github.com/rbenv/rbenv) or [RVM](http://rvm.io/). Check the official Jekyll [Mac install docs](https://jekyllrb.com/docs/installation/#macOS) for tips.
- **Linux:** Even though the version will not be the most up-to-date, the simplest method is to use your distro's repositories. For example on Ubuntu, `sudo apt install ruby-full`. Make sure the repository version is > 2.2.5. You will also need the build tools Make and GCC, on Ubuntu get them with `sudo apt install build-essential`. For a more up-to-date version, use a manager such as [RVM](http://rvm.io/).

## What is covered in this resource

Jekyll is a Gem, a software package installed via Ruby's management system called RubyGems (similar to Python's Pip). 
Open a terminal and type:
`gem install jekyll bundler`

This will take a minute as Gem installs all the dependencies and builds extensions. 

# Text Editor

When working with code you should have a good text editor.
Windows notepad does not handle UTF-8 encoding or UNIX line endings that are standard for cross platform applications. 
For basic editing, Windows [Notepad++](https://notepad-plus-plus.org/), Mac TextEdit, or Linux Gedit are sufficient.
However, a more complete code editor will be helpful for managing Jekyll projects.

Open-source cross platform suggestions:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Atom](https://atom.io/)
