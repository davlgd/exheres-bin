# davlgd's Exherbo Packages

To add this repository to your Paludis configuration:

* Edit `/etc/paludis/repositories/davlgd-bin.conf`
* Add this content:

```
format = e
location = /var/db/paludis/repositories/davlgd-bin
sync = git+https://github.com/davlgd/exheres-bin.git
sync_options = --branch=main
tool_prefix = x86_64-pc-linux-gnu-
binary_destination = true
binary_distdir = /pbins/
binary_keywords_filter = amd64 ~amd64
binary_uri_prefix = https://cellar-c2.services.clever-cloud.com/pbins/
```
