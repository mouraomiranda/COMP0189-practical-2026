# COMP0189 2026 lab exercises
This repo contains the lab exercises for the 2026 COMP0189 module. All exercises are written as Python notebooks. We'll add each week's notebook to this repo before the lab session; afterwards, we'll also add a suggested solution.

## Setting up your environment
You can work on the lab exercises in 2 ways: either using a cloud-based editor called Google Colab, or locally on your machine.

### Cloud setup (Google Colab)
Using Colab doesn't require installing anything on your computer. Simply go to the [Google Colab](https://colab.research.google.com/) website and open the notebook you want to work on.

Note that Colab can be slow at times and has been known to crash. Make sure you save your work regularly.

### Local setup
You may prefer to work on the labs on your own computer. The code will run faster and with less delay than on Colab, especially since none of the labs require a GPU.

1. Download and install [Python](https://www.python.org/downloads/) for your operating system (version 3.14 is recommended). If you're on Linux, the easiest way to do this is through your package manager
    - The notebooks should also work on any recent Python version, but we'll mostly test them on 3.14
2. Download and install [Git](https://git-scm.com/). Again, on Linux you should use your package manager for this
3. Open a terminal window and go to your home directory: `cd ~/`
4. Clone this repo: `git clone https://github.com/mouraomiranda/COMP0189-practical-2026`
5. Move into the repo: `cd COMP0189-practical-2026`
6. Create a virtual environment for this module: `python3 -m venv .venv`
    - This ensures that the packages required by the labs will not conflict with the ones required by other Python projects you may be working on
7. We recommend using [Visual Studio Code](https://code.visualstudio.com/) as your editor. To set it up:
    1. Install and open Visual Studio Code
    2. Install the Jupyter and Python extensions
    3. Open this repo: "File" -> "Open folder" -> (select the cloned repo on your computer)
    4. Open the notebook you want to work on. When asked to select a kernel, pick the virtual environment we created in `.venv` directory. If asked, let VSCode install the required ipython packages
