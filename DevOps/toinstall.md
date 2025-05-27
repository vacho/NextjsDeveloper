# Steps to install

1. Get nodejs working locally

```bash
# Install. 
sudo apt update
sudo apt install curl -y
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs

node -v
npm -v

# Optional, use 'n' to install another node versions.
sudo npm install -g n
sudo n 20

