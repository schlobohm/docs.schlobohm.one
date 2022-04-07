# datadyne

## At a glance

| K        | V                                             |
| -------- | --------------------------------------------- |
| hostname | `datadyne.i.schlobohm.one`                    |
| ip       | `10.0.10.3`                                   |
| ilo      | `10.0.10.2` or `ilo.datadyne.i.schlobohm.one` |
| os       | Proxmox VE 7.1                                |
| users    | `['nks']`                                     |

## Specs

| K            | V                                                   |
| ------------ | --------------------------------------------------- |
| Manufacturer | Dell                                                |
| Model        | PowerEdge R720                                      |
| CPU          | 2 x Intel(R) Xeon(R) CPU E5-2680 v2 @ 2.80 GHz      |
| Memory       | 256GB                                               |

## VMs

### `nightfly`

Media servers

| K        | V                                                        |
| -------- | -------------------------------------------------------- |
| hostname | `nightfly.vm.datadyne.i.schlobohm.one`                   |
| ip       | `10.0.30.2`                                              |
| os       | Debian Bookworm                                          |
| users    | `['nks']`                                                |
| namesake | Donald Fagen's debut studio album, 1982's _The Nightfly_ |

#### Services

- [Plex](https://plex.tv/)
- [Jellyfin](https://jellyfin.org/)
- [Navidrome](https://www.navidrome.org/)

### whitedragon

Business and document-related services

| K        | V                                                           |
| -------- | ----------------------------------------------------------- |
| hostname | `whitedragon.vm.datadyne.i.schlobohm.one`                   |
| ip       | `10.0.30.3`                                                 |
| os       | Debian Bookworm                                             |
| users    | `['nks']`                                                   |
| namesake | the White Dragon noodle bar in the 1982 film _Blade Runner_ |

#### Services

- [ERPNext](https://erpnext.com/)
- [Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)

