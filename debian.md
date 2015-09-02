---
layout: default
title: Debian packages
shorttitle: Debian
---

I host a handful of personal Debian packages that I find useful, maybe
others will too. The packages can be installed with the following apt
lines (the `deb-src` line is optional):

    deb {{ site.baseurl | prepend: site.url }}/debian unstable/
    deb-src {{ site.baseurl | prepend: site.url }}/debian unstable/

**Note:** You will need the `apt-transport-https` package installed to
use this repository.

For now, this repository entirely consists of personal packages with a
`mtmiller-` prefix.

The source packages are maintained in git at

 * [https://anonscm.debian.org/cgit/users/mtmiller/mtmiller-defaults.git](https://anonscm.debian.org/cgit/users/mtmiller/mtmiller-defaults.git)
