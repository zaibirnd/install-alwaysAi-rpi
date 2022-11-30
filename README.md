# install alwaysAi rpi
 Installation of alwaysAi in RaspberryPi

## 1. Install Docker

```bash
sudo curl -sL get.docker.com | sh
sudo usermod -aG docker $USER
sudo reboot
```
### 1.1 Test Docker

```bash
docker run hello-world
```

## 2. Install nodejs on RaspberryPi

```bash
sudo su
curl -fsSL https://deb.nodesource.com/setup_17.x | bash -
sudo apt install -y nodejs
```

### 2.1 Test nodejs

```bash
node -v
```
```bash
npm -v
```

### 2.2 Uninstall nodejs on RaspberryPi

```bash
sudo apt remove nodejs
```

## 3. Install alwaysAi

```bash
sudo npm install --global alwaysai
```

### 3.1 Test alwaysAi

```bash
aai --version
```

That's all. Enjoy alwaysAi.

