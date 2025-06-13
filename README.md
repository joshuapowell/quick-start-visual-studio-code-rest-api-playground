# Building a REST API Playground Quick Start Environment with Visual Studio Code, Jupyter, and pyenv

This document provides an overview of the software required to follow along with my REST API Plaground presentations. It provides readers with a "quick start" style overview for installing and configuring the most basic environment needed to follow along with the code in these presentations.

Keywords: Jupyter Notebooks, Python, Visual Studio Code, API, Development Environment

- [Setup](#setup)
    - [Visual Studio Code](#visual-studio-code)
    - [Jupyter](#jupyter)
    - [Python](#python)
- [Getting Started](#getting-started)
- [Other Options](#other-options)
- [Conclusion](#conclusion)
- [Further Reading](#further-reading)
- [Disclaimer](#disclaimer)
- [Copyright](#copyright)

## 1. Setup

### 1.1 Visual Studio Code

Microsoft Visual Studio Code is a precompiled desktop application that is available on a variety of operating systems and is a ready-to-use IDE. A copy can be acquired for free by following the steps outlined below.

![select-visualsstudio-environment](https://github.com/user-attachments/assets/d7790212-10ce-49e4-b18a-82e87e830134)

#### 1.1.1 Setup Visual Studio Code

1. Visit [https://code.visualstudio.com/](https://code.visualstudio.com/download)
2. Download the version of Visual Studio Code for your operating system
3. Follow [any additional "setup" instructions](https://code.visualstudio.com/docs/setup/setup-overview) required for your version

While Visual Studio Code is highly customizable, no special customization is required to follow along with any of my REST API playground tutorials.

### 1.2 Jupyter

Jupyter, Jupyter Labs, or Jupyter Notebooks is an interactive coding environment that lets you run isolated blocks of code. It is widely used in the data analytics and data science communitites. Since a lot of the work I perform is with REST APIs and intergrations, Jupyter is great for exploratory data analysis and is the perfect tool for running, rerunning, and fine tuning REST API calls and exploring the data you receive from the calls.

A copy of Jupyter can be acquired for free from the Visual Studio Code Marketplace by either visiting the Marketplace in a browser or via the "Extensions"

![select-jupyter-environment](https://github.com/user-attachments/assets/9bb6fbf1-17e5-40e1-9701-83cf9a045649)

#### 1.2.1 Setup Jupyter Notebooks for Visual Studio Code

1. Visit the [Visual Studio Code Marketplace and search for Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
2. Click the green install button (browser market place) or the blue install button (in-app "Extensions" tab)
3. Follow on-screen instructions to complete the installation

### 1.3 Python

#### 1.3.1 Setup `pyenv`

1. Visit [https://github.com/pyenv/pyenv](https://github.com/pyenv/pyenv)
2. Find the ["Installation" section](https://github.com/pyenv/pyenv?tab=readme-ov-file#installation) in the README. Note: The installation instructions are broken up into sections A. through E., make sure you follow all steps to create a working Python environment.
3. Find Installation Step A. Locate the "Details" for your operating system and follow the instructions
4. Continue following Step B. through Step E. of the Installation section

#### 1.3.2 Install the latest version of Python

```pyenv install 3.13.2```

## 2. Getting Started

Once you've installed Visual Studio Code, Jupyter, and Python as an isolated environment, you'll be able to begin following along with any of my Jupyter Notebook tutorials.

1. The first time you execute a Jupyter Notebook code block, you'll be presented with a small diaglog at the top of your Visual Studio Code window to "Select an environment". You'll want to select "Python Environments..."

![select-python-environment-1](https://github.com/user-attachments/assets/421d9894-0fea-4637-a67c-efdb21209373)

2. Next, you'll be presented with a list of available Python environments, you want to use the environment you installed in the above "`pyenv`" step, so select one of the options under the "PyEnv Env" heading. Pay attention to the path you're selecting, the light gray text should contain a path with a `~/.pyenv` prefix.

![select-python-environment-2](https://github.com/user-attachments/assets/919650cc-06b8-4fa3-843b-21c9f29df9b0)

## 3. Other options
A variety of other options exist for testing REST API calls and some even generate helpful code in a variety of languages. I prefer the Jupyter environment because it allows me to write and test code that I can transfer into an application, pipeline, or other project easily. The following options are great if your just interested in designing, documenting, and exploring a REST API.

1. Swagger (open source)
2. Postman or Insomnia (commerical API platforms)
3. RapidAPI (standalone desktop application)

## 4. Conclusion

Now you should be ready to proceed with any of my REST API Playground tutorials, such as "[Harnessing the Power of Mainframe REST APIS for Modernization](https://github.com/joshuapowell/harnessing-the-power-of-mainframe-rest-apis-for-modernization)".

## 5. Further Reading

1. Download Visual Studio Code - Mac, Linux, Windows. (2021, November 3). https://code.visualstudio.com/download
2. Welcome to Python.org. (2025, June 12). Python.org. https://www.python.org/
3. pyenv/pyenv: Simple Python version management. (Accessed June 13, 2025). GitHub. https://github.com/pyenv/pyenv
4. Project Jupyter. (Accessed June 13, 2025). Home. https://jupyter.org/
5. Visual Studio Marketplace. (Accessed June 13, 2025). https://marketplace.visualstudio.com/vscode
6. Jupyter - Visual Studio Marketplace. (Accessed June 13, 2025). https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter
7. 

## 6. Disclaimer
The content, including but not limited to code, text, images, audio, and/or video, hereafter referred to as "content", in this document are provided for informational and educational purposes only. TO THE EXTENT PERMITTED BY APPLICABLE LAW, THE AUTHOR PROVIDES THIS DOCUMENT "AS IS" WITHOUT WARRANTY OF ANY KIND, INCLUDING WITHOUT LIMITATION, ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR NONINFRINGEMENT. In no event shall the author or their employer be liable for any claim, damages or other liability, direct or indirect, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the code and content or the use or other dealings in the code and content. Use this code and all other content at your own risk. 

**Third-party API Disclaimer:** Additionally, the code examples in this post may interact with third-party APIs and services. The availability and functionality of these APIs are subject to change without notice. The author is not responsible for any issues arising from changes to these APIs or any downtime or limitations imposed by the service providers. You are responsible for complying with the terms of service and usage policies of any third-party APIs you use in conjunction with this code. Use this code at your own risk, and be aware of potential security implications when connecting to external services.

**Product Link Disclaimer:** This blog post may contain links to products or services available for purchase. These links are provided to offer readers additional information and resources. The author's opinions expressed in this post are independent and not influenced by any potential commercial relationships. No compensation is received for including these links, and their presence does not constitute an endorsement. Readers are encouraged to conduct their own research before making any purchasing decisions.

## 7. Copyright
Copyright &copy; 2025 J.I. Powell. All rights reserved.
