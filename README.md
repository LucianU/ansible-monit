monit
=====
- Downloads `monit`
- Installs `monit`
- Installs `monit` config

Role Variables
--------------
| Variable | Description | Default value |
|----------|-------------|---------------|
|`monit_config`| Path to the config file template | `monitrc.j2` |
|`monit_download_url`| URL to download `monit` | `https://mmonit.com/monit/dist/binary/5.15/monit-{{
monit_version }}-linux-x64.tar.gz` |
|`monit_version` | Version of `monit` to download | `5.15` |

Dependencies
------------
none

License
-------
BSD
