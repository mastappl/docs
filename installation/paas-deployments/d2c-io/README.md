# Deploying Rocket.Chat on D2C.io

## Supported cloud providers

- AWS
- Digital Ocean
- Google Cloud Platform
- Vultr
- UpCloud

## Supported operation systems and other requirements for connecting own servers:

- OS: Ubuntu server 16.04, 18.04; Debian 8, 9
- We strongly recommend to use a kernel with version >= 4.0 for better Docker performance using OverlayFS, otherwise the storage driver - will be "devicemapper"
- Free disk space: 5 Gb
- Opened incoming ssh port
- For the Weave network to work, you must open ports 6783, 6784 (TCP/UDP)

## Deploy

Single click deployment:

[![Deploy](https://raw.githubusercontent.com/mastappl/images/master/deployTo.png)](https://panel.d2c.io/?import=https://github.com/d2cio/rocketchat-stack/archive/master.zip/)

### Demo

![How to deploy a stack](https://raw.githubusercontent.com/mastappl/images/master/rocketchat.gif)
