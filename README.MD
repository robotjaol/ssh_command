# command untuk membuat SSH di windows.

  git config --global user.email = "emailmu"

  git config --global user.name = "username github"

  ssh-keygen -t ed25519 -C "emailmu"

  ssh-agent -s

  start-ssh-agent.cmd

  eval $(ssh-agent -s)

  ssh-add ~/.ssh/id_rsa


# command untuk membuat SSH di ubuntu.

  cd ~/.ssh

  ssh-keygen -t rsa -b 4096 -C "example@example.com"

  eval $(ssh-agent -s)

  ssh-add

