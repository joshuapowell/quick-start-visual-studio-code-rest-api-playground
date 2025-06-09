# Setup a REST API Playground with Visual Studio Code

## Visual Studio Code

1. Visit [https://code.visualstudio.com/](https://code.visualstudio.com/download)
2. Download the version of Visual Studio Code for your operating system
3. Follow [any additional "setup" instructions](https://code.visualstudio.com/docs/setup/setup-overview) required for your version

## Jupyter

1. Visit the [Visual Studio Code Marketplace and search for Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
2. Click the green install button
![Screenshot 2025-06-09 at 12 52 42](https://github.com/user-attachments/assets/e3be0903-6999-4158-bbcb-afe3824cca31)
3. "Open in Visual Studio Code [.app, .exe]" to launch the extension in your locally installed version of Visual Studio Code

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

The first time you run one of the Jupyter Notebook tutorials, you'll be asked to:

1. Select a Python Environment
2. Select the Kernel you'd like to use.

Pay attention to the path you're selecting—the Python version you installed in the last step, should appear in this step and contain a `~/.pyenv` prefix.

All of the `.pyenv` installed versions of Python will be grouped under the "PyEnv Env" heading (notice the blue text to the right in the purple box).

![select-python-environment](https://github.com/user-attachments/assets/e5e41b1a-1124-4a29-aa45-dbbfb73da340)
