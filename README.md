# Writing a systemd Service in Python

Tested on Ubuntu 22.04.1 LTS/jammy

Service file in /lib/systemd/system/python_demo_service.service done by root/sudo
Python file in /usr/local/lib/python_demo_service/python_demo_service.py done by root/sudo

sudo systemctl daemon-reload
sudo systemctl start python_demo_service
sudo systemctl  start python_demo_service
