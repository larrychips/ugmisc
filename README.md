UgMisc 0.1
==========

Small, basic miscellaneous language support header library for C++ standards
C++17 and later, with an MIT licence.

Getting the source
------------------

The [repository] is hosted at Codeberg.

Installing
----------

The Meson build system is used.

    $ meson setup build /path/to/source
    $ cd build
    $ meson test # Run unit tests, if you want.
    $ meson install # Install headers.

Documentation
-------------

You can read the [documentation] online.  Alternatively, the documentation can
be built and installed from the sources if you have Doxygen on your path.

    $ meson setup build /path/to/source -Ddoc-types=html
    $ cd build
    $ meson install -tags=doc # Install just the docs.

... or install the headers and docs ...

    $ meson install

... or compile without installing ...

    $ meson compile

If installing the man pages, the install tag to use is not `doc`, but `man`.

[repository]: https://codeberg.org/larrychips/ugmisc "UgMisc repo"
[documentation]: https://www.larrychips.net/@ugmisc-en-head/ "UgMisc 0.1, English"
