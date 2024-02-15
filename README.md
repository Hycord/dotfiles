## Setup

```bash
sudo apt update -y && sudo apt upgrade -y
sudo apt install git -y
sudo apt install stow -y
git clone git@github.com/hycord/dotfiles
cd dotfiles
stow .
```