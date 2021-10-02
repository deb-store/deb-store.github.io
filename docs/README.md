Package repository for Debian.

## Install

### Package Store

```sh
echo 'deb http://download.opensuse.org/repositories/home:/pkgstore:/deb/Debian_11/ /' | tee /etc/apt/sources.list.d/pkgstore.deb.list && curl -fsSL 'https://download.opensuse.org/repositories/home:pkgstore:deb/Debian_11/Release.key' | gpg --dearmor | tee /etc/apt/trusted.gpg.d/pkgstore.deb.gpg > /dev/null && apt update
```

### Package Store (EXT)

```sh
echo 'deb http://download.opensuse.org/repositories/home:/pkgstore:/deb-ext/Debian_11/ /' | tee /etc/apt/sources.list.d/pkgstore.deb-ext.list && curl -fsSL 'https://download.opensuse.org/repositories/home:pkgstore:deb-ext/Debian_11/Release.key' | gpg --dearmor | tee /etc/apt/trusted.gpg.d/pkgstore.deb-ext.gpg > /dev/null && apt update
```

### Package Store (FIX)

```sh
echo 'deb http://download.opensuse.org/repositories/home:/pkgstore:/deb-fix/Debian_11/ /' | tee /etc/apt/sources.list.d/pkgstore.deb-fix.list && curl -fsSL 'https://download.opensuse.org/repositories/home:pkgstore:deb-fix/Debian_11/Release.key' | gpg --dearmor | tee /etc/apt/trusted.gpg.d/pkgstore.deb-fix.gpg > /dev/null && apt update
```

---

## Backup

- [GitLab](https://gitlab.com/deb-store)
