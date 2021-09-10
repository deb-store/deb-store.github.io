Package repository for Debian.

## Install

```sh
echo 'deb http://download.opensuse.org/repositories/home:/pkgstore:/deb/Debian_11/ /' | tee /etc/apt/sources.list.d/home:pkgstore:deb.list && curl -fsSL 'https://download.opensuse.org/repositories/home:pkgstore:deb/Debian_11/Release.key' | gpg --dearmor | tee /etc/apt/trusted.gpg.d/home_pkgstore_deb.gpg > /dev/null && apt update
```

```sh
echo 'deb http://download.opensuse.org/repositories/home:/pkgstore:/deb-ext/Debian_11/ /' | tee /etc/apt/sources.list.d/home:pkgstore:deb-ext.list && curl -fsSL 'https://download.opensuse.org/repositories/home:pkgstore:deb-ext/Debian_11/Release.key' | gpg --dearmor | tee /etc/apt/trusted.gpg.d/home_pkgstore_deb-ext.gpg > /dev/null && apt update
```

---

## Backup

- [GitLab](https://gitlab.com/deb-store)
