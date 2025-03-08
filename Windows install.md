# Windows Installs (frontend tools)
' list all installed packages
choco list -l 

choco install vscode -y

choco install git -y

refreshenv;

choco install postman -y

' list all packages with "node"
' choco list node
choco install nodejs-lts -y

' reboot for git?! uhm...

git config --global user.name "Bastian Kröger"
git config --global user.email "bastian.kroeger@pm.me"
' optional use --local