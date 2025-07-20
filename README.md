The playbook has been tested with environment base on this image python:3.9-alpine:

NAME="Alpine Linux"
ID=alpine
VERSION_ID=3.22.1
PRETTY_NAME="Alpine Linux v3.22"
HOME_URL="https://alpinelinux.org/"
BUG_REPORT_URL="https://gitlab.alpinelinux.org/alpine/aports/-/issues"


ansible [core 2.15.13]
  config file = None
  configured module search path = ['/root/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/local/lib/python3.9/site-packages/ansible
  ansible collection location = /root/.ansible/collections:/usr/share/ansible/collections
  executable location = /usr/local/bin/ansible
  python version = 3.9.23 (main, Jul 16 2025, 04:53:59) [GCC 14.2.0] (/usr/local/bin/python3.9)
  jinja version = 3.1.6
  libyaml = True

Python 3.9.23

Requirements:
- pip install --upgrade pip setuptools
- pip install ansible
- apk update
- apk add openssh