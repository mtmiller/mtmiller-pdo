# people.debian.org/~mtmiller

This web content is built using [Jekyll][jekyll]. It requires
[Bootstrap][bootstrap] and [jQuery][jquery]. These files need to be
obtained from their respective sites and dropped into the `css`,
`fonts`, and `js` directories.

Once these externals are in place, the site is built and deployed with

    jekyll build
    rsync -avz _site/ people.debian.org:public_html

# License

The content of this site is licensed under a Creative Commons
Attribution-ShareAlike 4.0 International License (CC-BY-SA-4.0).
See [LICENSE](LICENSE) ([online version][cc-by-sa-license]).

The supporting software components used to build and render the site are
all free software licensed under the [Expat][mit-license] (or MIT)
license.

[jekyll]: http://jekyllrb.com/
[jquery]: https://jquery.com/
[bootstrap]: http://getbootstrap.com/
[cc-by-sa-license]: https://creativecommons.org/licenses/by-sa/4.0/legalcode
[mit-license]: http://spdx.org/licenses/MIT
