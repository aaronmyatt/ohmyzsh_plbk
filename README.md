# oh-my-zsh

## All credits to the original author https://github.com/mashimom/ohmyzsh_plbk
> Unfortunately he was a little too slow to merge an update that was breaking the playbook.

Ansible role to install and configure oh-my-zsh on both APT and YUM based distros.
> Tested on Ubuntu 14.04 64bit and Fedora 21 64bit.

## Role Variables

The role's variables are:

| Variable | Default value | Description |
|----------|---------------|-------------|
| `ohmyzsh_plugins` | `[git, vagrant, docker, command-not-found, gradle, lein]` | List of the plugins that should be added to oh-my-zsh |
| `ohmyzsh_theme` | `pygmalion` | Theme to be ser on oh-my-zsh |

## Example Playbook

Including an example of how to use this role:

    - hosts: all
      roles:
         - { role: aaronmyatt.ohmyzsh_plbk, ohmyzsh_theme: "lambda" }

## License

[Apache License v2.0](LICENSE)
