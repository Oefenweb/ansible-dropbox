## dropbox

[![Build Status](https://travis-ci.org/Oefenweb/ansible-dropbox.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-dropbox) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-dropbox-blue.svg)](https://galaxy.ansible.com/Oefenweb/ansible-dropbox)

Set up [Dropbox](https://www.dropbox.com/) in Debian-like systems.

#### Requirements

* `curl` (will be installed)

#### Variables

* `dropbox_version` [default: `2019.02.14`]: Version to install

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - dropbox
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-dropbox/issues)!
