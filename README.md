# pkg-quick-conf

Copy a file as a `pkg.conf(5)` file.

Instead of creating the `/usr/local/etc/pkg/repos` directory and placing a custom `pkg.conf(5)` file there over and over again for each Makejail, when this Makejail is included, it does so whenever the `pkg_conf` argument is set. If `pkg_conf` is set, the file is saved as `/usr/local/etc/pkg/repos/${pkg_name}.conf`, where the `pkg_name` argument defaults to `FreeBSD`.
