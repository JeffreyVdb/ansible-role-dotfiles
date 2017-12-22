# Ansible role: dotfiles

An ansible role that configures your dotfiles using stow

## Requirements

None.

## Role variables

Available variables are listed below, along with default values (see defaults/main.yml):

```
# Here you can change your distributions name for the stow package
stow_package: stow
```

```
dotfiles_repository: "https://github.com/xero/dotfiles"
dotfiles_home_directory: "{{ ansible_env.HOME }}"
dotfiles_directory: "{{ dotfiles_home_directory }}/dotfiles"
dotfiles_stow_links: []
```
