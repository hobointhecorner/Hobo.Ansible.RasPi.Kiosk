# Hobo.Ansible.RasPi.Kiosk

## Requirements
* [Hobo.Ansible.RasPi.Common](https://github.com/hobointhecorner/Hobo.Ansible.RasPi.Common)

## Install Role
From inside your playbook roles directory:
`git submodule add [-b <branch or tag>] https://github.com/hobointhecorner/Hobo.Ansible.RasPi.Kiosk.git`

## Variables
| Name          | Type   | Required | Default | Desctiption |
|---------------|--------|----------|---------|-------------|
| rpi_kiosk_url | string | Yes      |         | URL for the Raspberry Pi kiosk to display on boot |
