# Setup 

Linux, Python, and GitHub are recommended for convenient computing.

## Windows
1. In PowerShell, run ``wsl --install``.  Once WSL is installed, you can run linux operating systems on your Windows PC.
1. Install your favorite linux distribution(s). One option is the one on the [Microsoft Store](https://ubuntu.com/desktop/wsl).
1. Open Windows Terminal and select the linux operating system. Now you can use linux.

## Windows and Mac
1. In Windows, use linux's terminal, which has bash as the default shell. In Mac, use the built-in Terminal, which has zsh as the default shell.
1. Install Python and the conda package management, miniforge from the command line as specified [here](https://github.com/conda-forge/miniforge?tab=readme-ov-file).  Now you can run Python and manage your environments with conda.
1. Add an SSH key for GitHub and clone your repositories: [Step 1](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent), [Step 2](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account). At the end, if you see a message along the lines of ``The authenticity... can't be established... Are you sure you want to continue...?``, just reply `yes`.  Now you can push and pull to GitHub from the command line.
1. When performing git actions in the command line, if git tells you to "Please tell me who you are" and run `git config --global...`, follow git's instructions.

