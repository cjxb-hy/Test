sudo apt install git
git config --global user.name "your name"
git config --global user.email "your email"
git config --list

cd ~/.ssh
ssh-keygen -t rsa -C "your email"
