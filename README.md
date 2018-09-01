# Ansible Role: Vagrant

Configures [Vagrant][vagrant] for Mac OS X.

## Requirements

[Vagrant][vagrant] must be installed on the system prior to running this role,
(suggested role: `geerlingguy.homebrew`).

## Role Variables

Available variables with example values are listed below, for default values see
[`defaults/main.yml`](defaults/main.yml)):

    vagrant_profiles:
      - vagrant-vbguest

## Dependencies

None.

## Example Playbook

    - hosts: localhost
      roles:
         - { role: lwalley.vagrant }

## License

MIT

[vagrant]: https://www.vagrantup.com
