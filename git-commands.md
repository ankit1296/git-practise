Git configuration

# To config system level which applies computer level means values available-

# -to all users

git config --system

# To config global level which applies for every project for that user

git config --global

example:
git config user.name "ankit"
git config user.email "xyz@gmail.com"

# To check git version or to verify git is installed properly

git --version

# To check latest status/changes of working directory

git status

# To check commits

git log

# If wrong repositary added as remote origin or we want to change then we can set-url

git remote set-url origin "url"
