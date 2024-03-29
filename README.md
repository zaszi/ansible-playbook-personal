# Ansible Playbook Personal

This Ansible playbook provisions my personal machines running [Arch Linux](https://www.archlinux.org/) and [Arch Linux ARM](https://archlinuxarm.org/). It contains a few small tasks, and uses my own Ansible roles:

- [Common](https://github.com/zaszi/ansible-role-common)
- [Dotfiles](https://github.com/zaszi/ansible-role-dotfiles)
- [Wireguard](https://github.com/zaszi/ansible-role-wireguard)
- [Nginx](https://github.com/zaszi/ansible-role-nginx)
- [Certbot](https://github.com/zaszi/ansible-role-certbot)
- [Pihole](https://github.com/zaszi/ansible-role-pihole)
- [Home Assistant](https://github.com/zaszi/ansible-role-homeassistant)

Unlike roles, this particular playbook is tailored specifically to provision the machines on my network and won't be of much use directly to anyone else. This repository has been made public largely as an example of how you can provision your workstations and home servers.

## Contribution

Found a problem or have a suggestion? Feel free to open an issue.

## License

Ansible-playbook-personal is licensed under the [MIT license](LICENSE).
