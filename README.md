Peco installation
=========

Install your dotfiles

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Example Playbook
----------------

```yaml
hosts: servers
roles:
   - role: kentrino.dotfiles
      # you must specify https url.
      dotfiles_repository: https://github.com/kentrino/dotfiles.git
      dotfiles_repository_branch: master
```

License
-------

MIT
