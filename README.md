# [Ninja](https://ninja-build.org/) [![CI Status](https://api.travis-ci.org/ndsol/subninja.svg?branch=master)](https://travis-ci.org/ndsol/subninja) [![Build status](https://ci.appveyor.com/api/projects/status/xkjxsyb0kjqblokx?svg=true)](https://ci.appveyor.com/project/ndsol/subninja/branch/master)

Ninja is a small build system with a focus on speed.

See [the manual](https://ninja-build.org/manual.html) included in the
distribution for background and more details.

Run `./ninja -h` for Ninja help.

To build your own binary, on many platforms it should be sufficient to
just run `./configure.py --bootstrap`; for more details see
[HACKING.md](HACKING.md). (Also read that before making changes to Ninja, as it
has advice.)

Installation is not necessary because the only required file is the
resulting ninja binary. However, to enable features like Bash
completion and Emacs and Vim editing modes, some files in misc/ must be
copied to appropriate locations.

If you're interested in making changes to Ninja, read [HACKING.md](HACKING.md)
first.
