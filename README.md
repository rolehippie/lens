# lens

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/lens)
[![General Workflow](https://github.com/rolehippie/lens/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/lens/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/lens/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/lens/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/lens/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/lens/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/lens)](https://github.com/rolehippie/lens/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.lens-blue)](https://galaxy.ansible.com/rolehippie/lens)

> [!IMPORTANT]
> This role have been archived because of the lack of maintenance and because
> we are not actively using it anymore. If you are using this role feel free
> to fork and maintain it on your own. Maybe we will unarchive this repository
> in the future at some point, maybe not... Who knows...

Ansible role to install lens Kubernetes interface.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [lens_keyring](#lens_keyring)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### lens_keyring

Path for the repository keyring

#### Default value

```YAML
lens_keyring: /usr/share/keyrings/lens-archive-keyring.gpg
```

## Discovered Tags

**_lens_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
