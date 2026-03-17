## dropbox

[![CI](https://github.com/Oefenweb/ansible-dropbox/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-dropbox/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-dropbox-blue.svg)](https://galaxy.ansible.com/Oefenweb/ansible-dropbox)

Set up [Dropbox](https://www.dropbox.com/) in Debian-like systems.

#### Requirements

* `curl` (will be installed)

#### Variables

* `dropbox_version` [default: `2026.01.15`]: Version to install

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.dropbox
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-dropbox/issues)!
