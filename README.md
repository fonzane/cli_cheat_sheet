# CLI Cheat Sheet
## Debian Setup
Create new user: `adduser <username>`<br/>
Grant sudo: `usermod -aG sudo <username>`<br/>
SetUp firewall: `sudo apt update && sudo apt install ufw`<br/>
Enable Services: `sudo ufw allow OpenSSH && sudo ufw allow http && sudo ufw enable`<br/>
## Linux
Find a specific process: `ps ax | grep <process-name>` <br/>
Check ports usage: `sudo lsof -i -P -n | grep LISTEN`<br/>
Give user recursive permission for all subdirs `sudo chmod -R o+rwx`<br/>
Remove those permissions again `sudo chmod -R o-rwx`<br/>
Restart network service: `sudo /etc/init.d/networking restart`
## Git
Add file changes: `git add --all`<br/>
Commit changes: `git commit -m "<description>"`<br/>
Push changes: `git push <remote-repo(usually origin)> <branch(usually master)>`
## WSL 2
Path on windows explorer: `\\wsl$\`
## Docker
List all running docker containers: `docker ps` for all containers: `docker ps -a` <br/>
Execute a command in a running container: `docker exec -it <container name> <command>`<br/>
Copy files: `docker cp <container name>:<src path> <dest path>`
