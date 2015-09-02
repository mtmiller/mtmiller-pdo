---
layout: default
title: RPM packages
shorttitle: RPMs
---

A small set of RPM repositories maintained by me, providing a handful of
packages, primarily for testing rpm and yum-related tools in Debian.
{:.lead}

The repositories are also useful as working examples of yum repositories
built with the [createrepo][createrepo] Debian package. And lastly, the
RPM packages themselves are also intended to be useful.

Each of the following URLs is suitable for use in a yum repository
configuration file:

 * [{{ "el5/i386"      | prepend: page.url | prepend: site.baseurl | prepend: site.url }}]({{ "el5/i386"      | prepend: page.url | prepend: site.baseurl | prepend: site.url }})
 * [{{ "el5/x86_64"    | prepend: page.url | prepend: site.baseurl | prepend: site.url }}]({{ "el5/x86_64"    | prepend: page.url | prepend: site.baseurl | prepend: site.url }})
 * [{{ "el5/source"    | prepend: page.url | prepend: site.baseurl | prepend: site.url }}]({{ "el5/source"    | prepend: page.url | prepend: site.baseurl | prepend: site.url }})
 * [{{ "el5/debuginfo" | prepend: page.url | prepend: site.baseurl | prepend: site.url }}]({{ "el5/debuginfo" | prepend: page.url | prepend: site.baseurl | prepend: site.url }})

For now, these repositories contain patched versions of the atlas, blas,
and lapack packages for Red Hat Enterprise Linux 5. These packages fix
[bug #557977: dlamch is miscompiled][bz557977].

[createrepo]: https://packages.debian.org/sid/createrepo
[bz557977]: https://bugzilla.redhat.com/show_bug.cgi?id=557977
