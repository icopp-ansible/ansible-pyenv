# ansible-pyenv

Install pyenv via Homebrew.

This role also adds pyenv's init scripts for bash, fish, and zsh shells.

## Dependencies

* [icopp.homebrew](https://github.com/icopp/ansible-homebrew)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.pyenv
```

## License

MIT
