# CLI Cheat Sheet
## Debian Setup
Create new user: `# adduser <username>`<br/>
Grant sudo: `# usermod -aG sudo <username>`<br/>
SetUp firewall: `# sudo apt update && sudo apt install ufw`<br/>
Enable Services: `# sudo ufw allow OpenSSH && sudo ufw allow http && sudo ufw enable`<br/>
## Linux
Check ports usage: `sudo lsof -i -P -n | grep LISTEN`
## Git
Commit changes: `git commit -m "<description>"`<br/>
Push changes: `git push <remote-repo(usually origin)> <branch(usually master)>`
