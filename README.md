### Ubuntu Mirrros
1. Ubuntu mirror " Alibaba Cloud Computing":
```
deb http://mirrors.aliyun.com/ubuntu/ YOUR_UBUNTU_VERSION_HERE main 
deb-src http://mirrors.aliyun.com/ubuntu/ YOUR_UBUNTU_VERSION_HERE main 
```

2. `source.list` Path
```bash
/etc/apt/source.list
```

### How to install Chrome on Ubuntu
1. Add Key:
```bash
wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
```

2. Set repository:
```bash
echo 'deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main' | sudo tee /etc/apt/sources.list.d/google-chrome.list
```

3. Install package:
```bash
sudo apt-get update
sudo apt-get install google-chrome-stable
```

### How to install terminator
```bash
sudo apt-get update
sudo apt-get install terminator
```

### How to install sogou pinyin
[Sogou Pinying for Linus](https://pinyin.sogou.com/linux/?r=pinyin)

```bash
cd path_of_sogoupinyin
sudo dpkg -i *.deb
sudo apt install -f
```

### How to install git
1. For Ubuntu, this PPA provides the latest stable upstream Git version
```bash
sudo add-apt-repository ppa:git-core/ppa
sudo apt update
sudo apt install git
```

### How to install roboware
[Roboware Studio](http://www.roboware.me/)

```bash
sudo dpkg -i *.deb
```

### How to install Ros
[Ros Wiki Installation](http://wiki.ros.org/ROS/Installation)

### How to install Anaconda (conflict with octopus)

