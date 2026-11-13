rm ~/.ssh/id_ed25519.pub
rm ~/.ssh/id_ed25519.pub
ssh-keygen -t ed25519 -C "veduisback"

gedit key

cat ~/.ssh/id_ed25519.pub

put the key inside the web

ssh -T git@github.com
