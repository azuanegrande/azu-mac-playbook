# Automation playbook for my usual MacOS install.



**Installation**

xcode-select --install

export PATH="$HOME/Library/Python/3.9/bin:/opt/homebrew/bin:$PATH"

sudo pip3 install --upgrade pip

pip3 install ansible

cd to dir

ansible-galaxy install -r requirements.yml

ansible-playbook main.yml --ask-become-pass
