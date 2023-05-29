# User Settings Installation Script

This script is like your personal stylist, but for your terminal. It will help you dress your shell in fine garments – a Git repository of dotfiles for `.bash_aliases`, `.bash_profile`, `.bashrc`, and `.vimrc`. After an intense but friendly debate, you will be asked to pick one of our meticulously crafted `.vimrc` options, either for C or Python. They both have been carefully engineered with an unmistakable charm of Vim, a text editor so advanced, you'll probably need a quantum physics degree just to quit it. 

## Requirements

- Bash shell
- Git (the script will offer to install Git if it is not already installed)

## Installation

1. Download the script file (`install_settings.sh`).
2. Navigate to the directory containing the script file.
3. Make the script executable using the following command:
```bash
chmod u+x install_settings.sh
```
4. Run the script:
```bash 
./install_settings.sh
```


You will be asked to confirm overwriting of each file. After you make your selections, the script will install the files and then source `~/.bashrc` to apply the changes to your current shell session.

## Note

- This script will overwrite the existing dotfiles in your home directory if you confirm during the prompt. Make sure to back up any important settings before running this script.
- The changes will only apply to the current shell session and any new shell sessions you start after running the script. They will not apply to other currently open shell sessions.

#

>***In case you were wondering about Emacs: yes, it still exists. But, let's face it, Vim is the future. We know it, you know it, and even Emacs knows it deep down. So save yourself the time, the existential crisis and beard-stroking debates. Jump on the Vim express. We Riders!***