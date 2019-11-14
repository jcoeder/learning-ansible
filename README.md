# learning-ansible
---
## General Ansible for Networking Environment
#### Install Python3
`sudo yum install gcc openssl-devel bzip2-devel`

`sudo wget https://www.python.org/ftp/python/3.7.2/Python-3.7.2.tgz`

`sudo tar xzf Python-3.7.2.tgz`

`cd Python-3.7.2`

`sudo ./configure --enable-optimizations`

`sudo make altinstall`

#### Create Python3 virtualenv

`cd ~/WORKING_DIR`
`python3 -m venv venv`

#### Activate virtualenv

`source ~/WORKING_DIR/venv/bin/activate`

#### Install requirements

`pip install -r requirements.txt`

Generally...

`pip install netmiko`

`pip install napalm`

---
