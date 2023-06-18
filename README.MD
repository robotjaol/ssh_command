# command untuk membuat SSH di windows.

1. git config --global user.email = "emailmu"
2. git config --global user.name = "username github"
3. ssh-keygen -t ed25519 -C "emailmu"
4. ssh-agent -s
5. start-ssh-agent.cmd
6. eval $(ssh-agent -s)
7.  ssh-add ~/.ssh/id_rsa


# command untuk membuat SSH di ubuntu.

1. cd ~/.ssh
2. ssh-keygen -t rsa -b 4096 -C "example@example.com"
3. eval $(ssh-agent -s)
4. ssh-add