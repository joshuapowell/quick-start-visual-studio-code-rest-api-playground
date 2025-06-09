# Setup a REST API Playground with Visual Studio Code

## Visual Studio Code

Microsoft Visual Studio Code is a precompiled desktop application that is available on a variety of operating systems and is a ready-to-use IDE. A copy can be acquired for free by following the steps outlined below.

![select-visualsstudio-environment](https://github.com/user-attachments/assets/d7790212-10ce-49e4-b18a-82e87e830134)

### Setup Visual Studio Code

1. Visit [https://code.visualstudio.com/](https://code.visualstudio.com/download)
2. Download the version of Visual Studio Code for your operating system
3. Follow [any additional "setup" instructions](https://code.visualstudio.com/docs/setup/setup-overview) required for your version

While Visual Studio Code is highly customizable, no special customization is required to follow along with any of my REST API playground tutorials.

## Jupyter

Jupyter, Jupyter Labs, or Jupyter Notebooks is an interactive coding environment that lets you run isolated blocks of code. It is widely used in the data analytics and data science communitites. Since a lot of the work I perform is with REST APIs and intergrations, Jupyter is great for exploratory data analysis and is the perfect tool for running, rerunning, and fine tuning REST API calls and exploring the data you receive from the calls.

A copy of Jupyter can be acquired for free from the Visual Studio Code Marketplace by either visiting the Marketplace in a browser or via the "Extensions"

![select-jupyter-environment](https://github.com/user-attachments/assets/9bb6fbf1-17e5-40e1-9701-83cf9a045649)

### Setup Jupyter Notebooks for Visual Studio Code

1. Visit the [Visual Studio Code Marketplace and search for Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
2. Click the green install button (browser market place) or the blue install button (in-app "Extensions" tab)
3. Follow on-screen instructions to complete the installation

## Python

### Setup `pyenv`

1. Visit [https://github.com/pyenv/pyenv](https://github.com/pyenv/pyenv)
2. Find the ["Installation" section](https://github.com/pyenv/pyenv?tab=readme-ov-file#installation) in the README. Note: The installation instructions are broken up into sections A. through E., make sure you follow all steps to create a working Python environment.
3. Find Installation Step A. Locate the "Details" for your operating system and follow the instructions
4. Continue following Step B. through Step E. of the Installation section

### Install the latest version of Python

```pyenv install 3.13.2```

## Getting Started

Once you've installed Visual Studio Code, Jupyter, and Python as an isolated environment, you'll be able to begin following along with any of my Jupyter Notebook tutorials.

1. The first time you execute a Jupyter Notebook code block, you'll be presented with a small diaglog at the top of your Visual Studio Code window to "Select an environment". You'll want to select "Python Environments..."

![select-python-environment-1](https://github.com/user-attachments/assets/421d9894-0fea-4637-a67c-efdb21209373)

2. Next, you'll be presented with a list of available Python environments, you want to use the environment you installed in the above "`pyenv`" step, so select one of the options under the "PyEnv Env" heading. Pay attention to the path you're selecting, the light gray text should contain a path with a `~/.pyenv` prefix.

![select-python-environment-2](https://github.com/user-attachments/assets/919650cc-06b8-4fa3-843b-21c9f29df9b0)

## Conclusion

Now you should be ready to proceed with any of my REST API Playground tutorials, such as "[Harnessing the Power of Mainframe REST APIS for Modernization](https://github.com/joshuapowell/harnessing-the-power-of-mainframe-rest-apis-for-modernization)".
