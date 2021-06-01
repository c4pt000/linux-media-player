
# rebranding "Parole media player" (because not only does it bother me it bothers the mental shit out of other people also"
```
yum groupinstall "C Development Tools and Libraries" -y
yum install xfce4-devel taglib-devel.x86_64 xfce4-dev-tools.x86_64 dbus-glib-devel.x86_64 libxfce4util-devel.x86_64 xfconf-devel libxfce* gstreamer* libnotify* 
sh autogen.sh 
./configure --prefix=/usr
make -j24
make -j24 install


install checkinstall, 
export PAGER=less
checkinstall --install=no --exclude=/sys/fs/selinux -D

```

[![License](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://gitlab.xfce.org/apps/parole/-/blob/master/COPYING)

# parole

Parole is a modern simple media player based on the GStreamer framework and 
written to fit well in the Xfce desktop. Parole features playback of local 
media files, DVD/CD and live streams.

Parole is extensible via plugins, for a complete how-to on writing a plugin for
Parole, see the Plugins API documentation and the plugins directory which 
contains some useful examples.

----


### Homepage

[Parole documentation](https://docs.xfce.org/apps/parole/start)

### Changelog

See [NEWS](https://gitlab.xfce.org/apps/parole/-/blob/master/NEWS) for details on changes and fixes made in the current release.

### Source Code Repository

[Parole source code](https://gitlab.xfce.org/apps/parole)

### Download a Release Tarball

[Parole archive](https://archive.xfce.org/src/apps/parole)
    or
[Parole tags](https://gitlab.xfce.org/apps/parole/-/tags)

### Installation

From source code repository: 

    % cd parole
    % ./autogen.sh
    % make
    % make install

From release tarball:

    % tar xf parole-<version>.tar.bz2
    % cd parole-<version>
    % ./configure
    % make
    % make install

### Reporting Bugs

Visit the [reporting bugs](https://docs.xfce.org/apps/parole/bugs) page to view currently open bug reports and instructions on reporting new bugs or submitting bugfixes.

