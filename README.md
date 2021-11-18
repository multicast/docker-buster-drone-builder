# buster-drone-builder

![Pulls](https://img.shields.io/docker/pulls/mkovac/buster-drone-builder.svg)
![Stars](https://img.shields.io/docker/stars/mkovac/buster-drone-builder.svg)

The [Debian](https://debian.org/) [Buster](https://wiki.debian.org/DebianBuster)
[container image](https://hub.docker.com/r/mkovac/buster-drone-builder/) for use as
drone.io builder container.

# Packages

    Desired=Unknown/Install/Remove/Purge/Hold
    | Status=Not/Inst/Conf-files/Unpacked/halF-conf/Half-inst/trig-aWait/Trig-pend
    |/ Err?=(none)/Reinst-required (Status,Err: uppercase=bad)
    ||/ Name                          Version                      Architecture Description
    +++-=============================-============================-============-===============================================================================
    ii  adduser                       3.118                        all          add and remove users and groups
    ii  apt                           1.8.2.3                      amd64        commandline package manager
    ii  apt-transport-https           1.8.2.3                      all          transitional package for https support
    ii  apt-utils                     1.8.2.3                      amd64        package management related utility programs
    ii  base-files                    10.3+deb10u11                amd64        Debian base system miscellaneous files
    ii  base-passwd                   3.5.46                       amd64        Debian base system master password and group files
    ii  bash                          5.0-4                        amd64        GNU Bourne Again SHell
    ii  binutils                      2.31.1-16                    amd64        GNU assembler, linker and binary utilities
    ii  binutils-common:amd64         2.31.1-16                    amd64        Common files for the GNU assembler, linker and binary utilities
    ii  binutils-x86-64-linux-gnu     2.31.1-16                    amd64        GNU binary utilities, for x86-64-linux-gnu target
    ii  bsdutils                      1:2.33.1-0.1                 amd64        basic utilities from 4.4BSD-Lite
    ii  build-essential               12.6                         amd64        Informational list of build-essential packages
    ii  bzip2                         1.0.6-9.2~deb10u1            amd64        high-quality block-sorting file compressor - utilities
    ii  ca-certificates               20200601~deb10u2             all          Common CA certificates
    ii  containerd.io                 1.4.12-1                     amd64        An open and reliable container runtime
    ii  coreutils                     8.30-3                       amd64        GNU core utilities
    ii  cpp                           4:8.3.0-1                    amd64        GNU C preprocessor (cpp)
    ii  cpp-8                         8.3.0-6                      amd64        GNU C preprocessor
    ii  curl                          7.64.0-4+deb10u2             amd64        command line tool for transferring data with URL syntax
    ii  dash                          0.5.10.2-5                   amd64        POSIX-compliant shell
    ii  debconf                       1.5.71+deb10u1               all          Debian configuration management system
    ii  debian-archive-keyring        2019.1+deb10u1               all          GnuPG archive keys of the Debian archive
    ii  debianutils                   4.8.6.1                      amd64        Miscellaneous utilities specific to Debian
    ii  di                            4.47-1                       amd64        advanced df like disk information utility
    ii  diffutils                     1:3.7-3                      amd64        File comparison utilities
    ii  dirmngr                       2.2.12-1+deb10u1             amd64        GNU privacy guard - network certificate management service
    ii  distro-info-data              0.41+deb10u4                 all          information about the distributions' releases (data files)
    ii  dmsetup                       2:1.02.155-3                 amd64        Linux Kernel Device Mapper userspace library
    ii  docker-ce                     5:20.10.10~3-0~debian-buster amd64        Docker: the open-source application container engine
    ii  docker-ce-cli                 5:20.10.10~3-0~debian-buster amd64        Docker CLI: the open-source application container engine
    ii  docutils-common               0.14+dfsg-4                  all          text processing system for reStructuredText - common data
    ii  dpkg                          1.19.7                       amd64        Debian package management system
    ii  dpkg-dev                      1.19.7                       all          Debian package development tools
    ii  e2fsprogs                     1.44.5-1+deb10u3             amd64        ext2/ext3/ext4 file system utilities
    ii  etckeeper                     1.18.10-1                    all          store /etc in git, mercurial, bzr or darcs
    ii  fdisk                         2.33.1-0.1                   amd64        collection of partitioning utilities
    ii  findutils                     4.6.0+git+20190209-2         amd64        utilities for finding files--find, xargs
    ii  fontconfig-config             2.13.1-2                     all          generic font configuration library - configuration
    ii  fonts-dejavu-core             2.37-1                       all          Vera font family derivate with additional characters
    ii  fonts-font-awesome            5.0.10+really4.7.0~dfsg-1    all          iconic font designed for use with Twitter Bootstrap
    ii  fonts-lato                    2.0-2                        all          sans-serif typeface family font
    ii  fonts-lmodern                 2.004.5-6                    all          OpenType fonts based on Computer Modern
    ii  fonts-roboto-slab             1.100263+20170512-1          all          Google's signature family of fonts (slab)
    ii  g++                           4:8.3.0-1                    amd64        GNU C++ compiler
    ii  g++-8                         8.3.0-6                      amd64        GNU C++ compiler
    ii  gcc                           4:8.3.0-1                    amd64        GNU C compiler
    ii  gcc-8                         8.3.0-6                      amd64        GNU C compiler
    ii  gcc-8-base:amd64              8.3.0-6                      amd64        GCC, the GNU Compiler Collection (base package)
    ii  ghostscript                   9.27~dfsg-2+deb10u4          amd64        interpreter for the PostScript language and for PDF
    ii  git                           1:2.20.1-2+deb10u3           amd64        fast, scalable, distributed revision control system
    ii  git-man                       1:2.20.1-2+deb10u3           all          fast, scalable, distributed revision control system (manual pages)
    ii  gnupg                         2.2.12-1+deb10u1             all          GNU privacy guard - a free PGP replacement
    ii  gnupg-l10n                    2.2.12-1+deb10u1             all          GNU privacy guard - localization files
    ii  gnupg-utils                   2.2.12-1+deb10u1             amd64        GNU privacy guard - utility programs
    ii  gpg                           2.2.12-1+deb10u1             amd64        GNU Privacy Guard -- minimalist public key operations
    ii  gpg-agent                     2.2.12-1+deb10u1             amd64        GNU privacy guard - cryptographic agent
    ii  gpg-wks-client                2.2.12-1+deb10u1             amd64        GNU privacy guard - Web Key Service client
    ii  gpg-wks-server                2.2.12-1+deb10u1             amd64        GNU privacy guard - Web Key Service server
    ii  gpgconf                       2.2.12-1+deb10u1             amd64        GNU privacy guard - core configuration utilities
    ii  gpgsm                         2.2.12-1+deb10u1             amd64        GNU privacy guard - S/MIME version
    ii  gpgv                          2.2.12-1+deb10u1             amd64        GNU privacy guard - signature verification tool
    ii  grep                          3.3-1                        amd64        GNU grep, egrep and fgrep
    ii  gzip                          1.9-3                        amd64        GNU compression utilities
    ii  hostname                      3.21                         amd64        utility to set/show the host name or domain name
    ii  init-system-helpers           1.56+nmu1                    all          helper tools for all init systems
    ii  iproute2                      4.20.0-2+deb10u1             amd64        networking and traffic control tools
    ii  iptables                      1.8.2-4                      amd64        administration tools for packet filtering and NAT
    ii  iputils-ping                  3:20180629-2+deb10u2         amd64        Tools to test the reachability of network hosts
    ii  joe                           4.6-1+b1                     amd64        user friendly full screen text editor
    ii  jq                            1.5+dfsg-2+b1                amd64        lightweight and flexible command-line JSON processor
    ii  latexmk                       1:4.61-0.1                   all          Perl script for running LaTeX the correct number of times
    ii  less                          487-0.1+b1                   amd64        pager program similar to more
    ii  libacl1:amd64                 2.2.53-4                     amd64        access control list - shared library
    ii  libapt-inst2.0:amd64          1.8.2.3                      amd64        deb package format runtime library
    ii  libapt-pkg5.0:amd64           1.8.2.3                      amd64        package management runtime library
    ii  libasan5:amd64                8.3.0-6                      amd64        AddressSanitizer -- a fast memory error detector
    ii  libassuan0:amd64              2.5.2-1                      amd64        IPC library for the GnuPG components
    ii  libatomic1:amd64              8.3.0-6                      amd64        support library providing __atomic built-in functions
    ii  libattr1:amd64                1:2.4.48-4                   amd64        extended attribute handling - shared library
    ii  libaudit-common               1:2.8.4-3                    all          Dynamic library for security auditing - common files
    ii  libaudit1:amd64               1:2.8.4-3                    amd64        Dynamic library for security auditing
    ii  libavahi-client3:amd64        0.7-4+deb10u1                amd64        Avahi client library
    ii  libavahi-common-data:amd64    0.7-4+deb10u1                amd64        Avahi common data files
    ii  libavahi-common3:amd64        0.7-4+deb10u1                amd64        Avahi common library
    ii  libbinutils:amd64             2.31.1-16                    amd64        GNU binary utilities (private shared library)
    ii  libblkid1:amd64               2.33.1-0.1                   amd64        block device ID library
    ii  libbrotli1:amd64              1.0.7-2+deb10u1              amd64        library implementing brotli encoder and decoder (shared libraries)
    ii  libbsd0:amd64                 0.9.1-2+deb10u1              amd64        utility functions from BSD systems - shared library
    ii  libbz2-1.0:amd64              1.0.6-9.2~deb10u1            amd64        high-quality block-sorting file compressor library - runtime
    ii  libc-bin                      2.28-10                      amd64        GNU C Library: Binaries
    ii  libc-dev-bin                  2.28-10                      amd64        GNU C Library: Development binaries
    ii  libc-l10n                     2.28-10                      all          GNU C Library: localization files
    ii  libc6:amd64                   2.28-10                      amd64        GNU C Library: Shared libraries
    ii  libc6-dev:amd64               2.28-10                      amd64        GNU C Library: Development Libraries and Header Files
    ii  libcairo2:amd64               1.16.0-4+deb10u1             amd64        Cairo 2D vector graphics library
    ii  libcap-ng0:amd64              0.7.9-2                      amd64        An alternate POSIX capabilities library
    ii  libcap2:amd64                 1:2.25-2                     amd64        POSIX 1003.1e capabilities (library)
    ii  libcap2-bin                   1:2.25-2                     amd64        POSIX 1003.1e capabilities (utilities)
    ii  libcc1-0:amd64                8.3.0-6                      amd64        GCC cc1 plugin for GDB
    ii  libcom-err2:amd64             1.44.5-1+deb10u3             amd64        common error description library
    ii  libcups2:amd64                2.2.10-6+deb10u4             amd64        Common UNIX Printing System(tm) - Core library
    ii  libcupsimage2:amd64           2.2.10-6+deb10u4             amd64        Common UNIX Printing System(tm) - Raster image library
    ii  libcurl3-gnutls:amd64         7.64.0-4+deb10u2             amd64        easy-to-use client-side URL transfer library (GnuTLS flavour)
    ii  libcurl4:amd64                7.64.0-4+deb10u2             amd64        easy-to-use client-side URL transfer library (OpenSSL flavour)
    ii  libdb5.3:amd64                5.3.28+dfsg1-0.5             amd64        Berkeley v5.3 Database Libraries [runtime]
    ii  libdbus-1-3:amd64             1.12.20-0+deb10u1            amd64        simple interprocess messaging system (library)
    ii  libdebconfclient0:amd64       0.249                        amd64        Debian Configuration Management System (C-implementation library)
    ii  libdevmapper1.02.1:amd64      2:1.02.155-3                 amd64        Linux Kernel Device Mapper userspace library
    ii  libdpkg-perl                  1.19.7                       all          Dpkg perl modules
    ii  libedit2:amd64                3.1-20181209-1               amd64        BSD editline and history libraries
    ii  libelf1:amd64                 0.176-1.1                    amd64        library to read and write ELF files
    ii  liberror-perl                 0.17027-2                    all          Perl module for error/exception handling in an OO-ish way
    ii  libexpat1:amd64               2.2.6-2+deb10u1              amd64        XML parsing C library - runtime library
    ii  libext2fs2:amd64              1.44.5-1+deb10u3             amd64        ext2/ext3/ext4 file system libraries
    ii  libfdisk1:amd64               2.33.1-0.1                   amd64        fdisk partitioning library
    ii  libffi6:amd64                 3.2.1-9                      amd64        Foreign Function Interface library runtime
    ii  libfontconfig1:amd64          2.13.1-2                     amd64        generic font configuration library - runtime
    ii  libfreetype6:amd64            2.9.1-3+deb10u2              amd64        FreeType 2 font engine, shared library files
    ii  libgcc-8-dev:amd64            8.3.0-6                      amd64        GCC support library (development files)
    ii  libgcc1:amd64                 1:8.3.0-6                    amd64        GCC support library
    ii  libgcrypt20:amd64             1.8.4-5+deb10u1              amd64        LGPL Crypto library - runtime library
    ii  libgdbm-compat4:amd64         1.18.1-4                     amd64        GNU dbm database routines (legacy support runtime version) 
    ii  libgdbm6:amd64                1.18.1-4                     amd64        GNU dbm database routines (runtime version) 
    ii  libglib2.0-0:amd64            2.58.3-2+deb10u3             amd64        GLib library of C routines
    ii  libgmp10:amd64                2:6.1.2+dfsg-4               amd64        Multiprecision arithmetic library
    ii  libgnutls30:amd64             3.6.7-4+deb10u7              amd64        GNU TLS library - main runtime library
    ii  libgomp1:amd64                8.3.0-6                      amd64        GCC OpenMP (GOMP) support library
    ii  libgpg-error0:amd64           1.35-1                       amd64        GnuPG development runtime library
    ii  libgraphite2-3:amd64          1.3.13-7                     amd64        Font rendering engine for Complex Scripts -- library
    ii  libgs9:amd64                  9.27~dfsg-2+deb10u4          amd64        interpreter for the PostScript language and for PDF - Library
    ii  libgs9-common                 9.27~dfsg-2+deb10u4          all          interpreter for the PostScript language and for PDF - common files
    ii  libgssapi-krb5-2:amd64        1.17-3+deb10u3               amd64        MIT Kerberos runtime libraries - krb5 GSS-API Mechanism
    ii  libharfbuzz-icu0:amd64        2.3.1-1                      amd64        OpenType text shaping engine ICU backend
    ii  libharfbuzz0b:amd64           2.3.1-1                      amd64        OpenType text shaping engine (shared library)
    ii  libhogweed4:amd64             3.4.1-1+deb10u1              amd64        low level cryptographic library (public-key cryptos)
    ii  libice6:amd64                 2:1.0.9-2                    amd64        X11 Inter-Client Exchange library
    ii  libicu63:amd64                63.1-6+deb10u1               amd64        International Components for Unicode
    ii  libidn11:amd64                1.33-2.2                     amd64        GNU Libidn library, implementation of IETF IDN specifications
    ii  libidn2-0:amd64               2.0.5-1+deb10u1              amd64        Internationalized domain names (IDNA2008/TR46) library
    ii  libijs-0.35:amd64             0.35-14                      amd64        IJS raster image transport protocol: shared library
    ii  libip4tc0:amd64               1.8.2-4                      amd64        netfilter libip4tc library
    ii  libip6tc0:amd64               1.8.2-4                      amd64        netfilter libip6tc library
    ii  libiptc0:amd64                1.8.2-4                      amd64        netfilter libiptc library
    ii  libisl19:amd64                0.20-2                       amd64        manipulating sets and relations of integer points bounded by linear constraints
    ii  libitm1:amd64                 8.3.0-6                      amd64        GNU Transactional Memory Library
    ii  libjbig0:amd64                2.1-3.1+b2                   amd64        JBIGkit libraries
    ii  libjbig2dec0:amd64            0.16-1                       amd64        JBIG2 decoder library - shared libraries
    ii  libjpeg62-turbo:amd64         1:1.5.2-2+deb10u1            amd64        libjpeg-turbo JPEG runtime library
    ii  libjq1:amd64                  1.5+dfsg-2+b1                amd64        lightweight and flexible command-line JSON processor - shared library
    ii  libjs-jquery                  3.3.1~dfsg-3+deb10u1         all          JavaScript library for dynamic web applications
    ii  libjs-modernizr               2.6.2+ds1-3                  all          JavaScript library to detect HTML5 and CSS3 features in the user's browser
    ii  libjs-sphinxdoc               1.8.4-1                      all          JavaScript support for Sphinx documentation
    ii  libjs-underscore              1.9.1~dfsg-1+deb10u1         all          JavaScript's functional programming helper library
    ii  libk5crypto3:amd64            1.17-3+deb10u3               amd64        MIT Kerberos runtime libraries - Crypto Library
    ii  libkeyutils1:amd64            1.6-6                        amd64        Linux Key Management Utilities (library)
    ii  libkpathsea6:amd64            2018.20181218.49446-1        amd64        TeX Live: path search library for TeX (runtime part)
    ii  libkrb5-3:amd64               1.17-3+deb10u3               amd64        MIT Kerberos runtime libraries
    ii  libkrb5support0:amd64         1.17-3+deb10u3               amd64        MIT Kerberos runtime libraries - Support library
    ii  libksba8:amd64                1.3.5-2                      amd64        X.509 and CMS support library
    ii  liblcms2-2:amd64              2.9-3                        amd64        Little CMS 2 color management library
    ii  libldap-2.4-2:amd64           2.4.47+dfsg-3+deb10u6        amd64        OpenLDAP libraries
    ii  libldap-common                2.4.47+dfsg-3+deb10u6        all          OpenLDAP common files for libraries
    ii  liblsan0:amd64                8.3.0-6                      amd64        LeakSanitizer -- a memory leak detector (runtime)
    ii  liblz4-1:amd64                1.8.3-1+deb10u1              amd64        Fast LZ compression algorithm library - runtime
    ii  liblzma5:amd64                5.2.4-1                      amd64        XZ-format compression library
    ii  libmnl0:amd64                 1.0.4-2                      amd64        minimalistic Netlink communication library
    ii  libmount1:amd64               2.33.1-0.1                   amd64        device mounting library
    ii  libmpc3:amd64                 1.1.0-1                      amd64        multiple precision complex floating-point library
    ii  libmpdec2:amd64               2.4.2-2                      amd64        library for decimal floating point arithmetic (runtime library)
    ii  libmpfr6:amd64                4.0.2-1                      amd64        multiple precision floating-point computation
    ii  libmpx2:amd64                 8.3.0-6                      amd64        Intel memory protection extensions (runtime)
    ii  libncurses6:amd64             6.1+20181013-2+deb10u2       amd64        shared libraries for terminal handling
    ii  libncursesw6:amd64            6.1+20181013-2+deb10u2       amd64        shared libraries for terminal handling (wide character support)
    ii  libnetfilter-conntrack3:amd64 1.0.7-1                      amd64        Netfilter netlink-conntrack library
    ii  libnettle6:amd64              3.4.1-1+deb10u1              amd64        low level cryptographic library (symmetric and one-way cryptos)
    ii  libnewt0.52:amd64             0.52.20-8                    amd64        Not Erik's Windowing Toolkit - text mode windowing with slang
    ii  libnfnetlink0:amd64           1.0.1-3+b1                   amd64        Netfilter netlink library
    ii  libnftnl11:amd64              1.1.2-2                      amd64        Netfilter nftables userspace API library
    ii  libnghttp2-14:amd64           1.36.0-2+deb10u1             amd64        library implementing HTTP/2 protocol (shared library)
    ii  libnpth0:amd64                1.6-1                        amd64        replacement for GNU Pth using system threads
    ii  libonig5:amd64                6.9.1-1                      amd64        regular expressions library
    ii  libopenjp2-7:amd64            2.3.0-2+deb10u2              amd64        JPEG 2000 image compression/decompression library
    ii  libp11-kit0:amd64             0.23.15-2+deb10u1            amd64        library for loading and coordinating access to PKCS#11 modules - runtime
    ii  libpam-modules:amd64          1.3.1-5                      amd64        Pluggable Authentication Modules for PAM
    ii  libpam-modules-bin            1.3.1-5                      amd64        Pluggable Authentication Modules for PAM - helper binaries
    ii  libpam-runtime                1.3.1-5                      all          Runtime support for the PAM library
    ii  libpam0g:amd64                1.3.1-5                      amd64        Pluggable Authentication Modules library
    ii  libpaper-utils                1.1.28                       amd64        library for handling paper characteristics (utilities)
    ii  libpaper1:amd64               1.1.28                       amd64        library for handling paper characteristics
    ii  libpcre2-8-0:amd64            10.32-5                      amd64        New Perl Compatible Regular Expression Library- 8 bit runtime files
    ii  libpcre3:amd64                2:8.39-12                    amd64        Old Perl 5 Compatible Regular Expression Library - runtime files
    ii  libperl5.28:amd64             5.28.1-6+deb10u1             amd64        shared Perl library
    ii  libpixman-1-0:amd64           0.36.0-1                     amd64        pixel-manipulation library for X and cairo
    ii  libpng16-16:amd64             1.6.36-6                     amd64        PNG library - runtime (version 1.6)
    ii  libpopt0:amd64                1.16-12                      amd64        lib for parsing cmdline parameters
    ii  libpotrace0:amd64             1.15-1                       amd64        library for tracing bitmaps
    ii  libprocps7:amd64              2:3.3.15-2                   amd64        library for accessing process information from /proc
    ii  libpsl5:amd64                 0.20.2-2                     amd64        Library for Public Suffix List (shared libraries)
    ii  libptexenc1:amd64             2018.20181218.49446-1        amd64        TeX Live: pTeX encoding library
    ii  libpython-stdlib:amd64        2.7.16-1                     amd64        interactive high-level object-oriented language (Python2)
    ii  libpython2-stdlib:amd64       2.7.16-1                     amd64        interactive high-level object-oriented language (Python2)
    ii  libpython2.7-minimal:amd64    2.7.16-2+deb10u1             amd64        Minimal subset of the Python language (version 2.7)
    ii  libpython2.7-stdlib:amd64     2.7.16-2+deb10u1             amd64        Interactive high-level object-oriented language (standard library, version 2.7)
    ii  libpython3-stdlib:amd64       3.7.3-1                      amd64        interactive high-level object-oriented language (default python3 version)
    ii  libpython3.7-minimal:amd64    3.7.3-2+deb10u3              amd64        Minimal subset of the Python language (version 3.7)
    ii  libpython3.7-stdlib:amd64     3.7.3-2+deb10u3              amd64        Interactive high-level object-oriented language (standard library, version 3.7)
    ii  libquadmath0:amd64            8.3.0-6                      amd64        GCC Quad-Precision Math Library
    ii  libreadline7:amd64            7.0-5                        amd64        GNU readline and history libraries, run-time libraries
    ii  librtmp1:amd64                2.4+20151223.gitfa8646d.1-2  amd64        toolkit for RTMP streams (shared library)
    ii  libsasl2-2:amd64              2.1.27+dfsg-1+deb10u1        amd64        Cyrus SASL - authentication abstraction library
    ii  libsasl2-modules-db:amd64     2.1.27+dfsg-1+deb10u1        amd64        Cyrus SASL - pluggable authentication modules (DB)
    ii  libseccomp2:amd64             2.3.3-4                      amd64        high level interface to Linux seccomp filter
    ii  libselinux1:amd64             2.8-1+b1                     amd64        SELinux runtime shared libraries
    ii  libsemanage-common            2.8-2                        all          Common files for SELinux policy management libraries
    ii  libsemanage1:amd64            2.8-2                        amd64        SELinux policy management library
    ii  libsepol1:amd64               2.8-1                        amd64        SELinux library for manipulating binary security policies
    ii  libslang2:amd64               2.3.2-2                      amd64        S-Lang programming library - runtime version
    ii  libsm6:amd64                  2:1.2.3-1                    amd64        X11 Session Management library
    ii  libsmartcols1:amd64           2.33.1-0.1                   amd64        smart column output alignment library
    ii  libsqlite3-0:amd64            3.27.2-3+deb10u1             amd64        SQLite 3 shared library
    ii  libss2:amd64                  1.44.5-1+deb10u3             amd64        command-line interface parsing library
    ii  libssh2-1:amd64               1.8.0-2.1                    amd64        SSH2 client-side library
    ii  libssl1.1:amd64               1.1.1d-0+deb10u7             amd64        Secure Sockets Layer toolkit - shared libraries
    ii  libstdc++-8-dev:amd64         8.3.0-6                      amd64        GNU Standard C++ Library v3 (development files)
    ii  libstdc++6:amd64              8.3.0-6                      amd64        GNU Standard C++ Library v3
    ii  libsynctex2:amd64             2018.20181218.49446-1        amd64        TeX Live: SyncTeX parser library
    ii  libsystemd0:amd64             241-7~deb10u8                amd64        systemd utility library
    ii  libtasn1-6:amd64              4.13-3                       amd64        Manage ASN.1 structures (runtime)
    ii  libteckit0:amd64              2.5.8+ds2-5                  amd64        Encoding conversion library
    ii  libtexlua52:amd64             2018.20181218.49446-1        amd64        TeX Live: Lua 5.2, modified for use with LuaTeX
    ii  libtexlua53:amd64             2018.20181218.49446-1        amd64        TeX Live: Lua 5.3, modified for use with LuaTeX
    ii  libtexluajit2:amd64           2018.20181218.49446-1        amd64        TeX Live: LuaJIT, modified for use with LuaJITTeX
    ii  libtiff5:amd64                4.1.0+git191117-2~deb10u3    amd64        Tag Image File Format (TIFF) library
    ii  libtinfo6:amd64               6.1+20181013-2+deb10u2       amd64        shared low-level terminfo library for terminal handling
    ii  libtsan0:amd64                8.3.0-6                      amd64        ThreadSanitizer -- a Valgrind-based detector of data races (runtime)
    ii  libubsan1:amd64               8.3.0-6                      amd64        UBSan -- undefined behaviour sanitizer (runtime)
    ii  libudev1:amd64                241-7~deb10u8                amd64        libudev shared library
    ii  libunistring2:amd64           0.9.10-1                     amd64        Unicode string library for C
    ii  libuuid1:amd64                2.33.1-0.1                   amd64        Universally Unique ID library
    ii  libwebp6:amd64                0.6.1-2+deb10u1              amd64        Lossy compression of digital photographic images.
    ii  libwoff1:amd64                1.0.2-1                      amd64        library for converting fonts to WOFF 2.0
    ii  libx11-6:amd64                2:1.6.7-1+deb10u2            amd64        X11 client-side library
    ii  libx11-data                   2:1.6.7-1+deb10u2            all          X11 client-side library
    ii  libxau6:amd64                 1:1.0.8-1+b2                 amd64        X11 authorisation library
    ii  libxaw7:amd64                 2:1.0.13-1+b2                amd64        X11 Athena Widget library
    ii  libxcb-render0:amd64          1.13.1-2                     amd64        X C Binding, render extension
    ii  libxcb-shm0:amd64             1.13.1-2                     amd64        X C Binding, shm extension
    ii  libxcb1:amd64                 1.13.1-2                     amd64        X C Binding
    ii  libxdmcp6:amd64               1:1.1.2-3                    amd64        X11 Display Manager Control Protocol library
    ii  libxext6:amd64                2:1.3.3-1+b2                 amd64        X11 miscellaneous extension library
    ii  libxi6:amd64                  2:1.7.9-1                    amd64        X11 Input extension library
    ii  libxmu6:amd64                 2:1.1.2-2+b3                 amd64        X11 miscellaneous utility library
    ii  libxpm4:amd64                 1:3.5.12-1                   amd64        X11 pixmap library
    ii  libxrender1:amd64             1:0.9.10-1                   amd64        X Rendering Extension client library
    ii  libxt6:amd64                  1:1.1.5-1+b3                 amd64        X11 toolkit intrinsics library
    ii  libxtables12:amd64            1.8.2-4                      amd64        netfilter xtables library
    ii  libxxhash0:amd64              0.6.5-2                      amd64        shared library for xxhash
    ii  libzstd1:amd64                1.3.8+dfsg-3+deb10u2         amd64        fast lossless compression algorithm
    ii  libzzip-0-13:amd64            0.13.62-3.2                  amd64        library providing read access on ZIP-archives - library
    ii  linux-libc-dev:amd64          4.19.208-1                   amd64        Linux support headers for userspace development
    ii  localepurge                   0.7.3.5                      all          reclaim disk space by removing unneeded localizations
    ii  locales                       2.28-10                      all          GNU C Library: National Language (locale) data [support]
    ii  login                         1:4.5-1.1                    amd64        system login tools
    ii  lsb-base                      10.2019051400                all          Linux Standard Base init script functionality
    ii  lsb-release                   10.2019051400                all          Linux Standard Base version reporting utility
    ii  make                          4.2.1-1.2                    amd64        utility for directing compilation
    ii  mawk                          1.3.3-17+b3                  amd64        a pattern scanning and text processing language
    ii  mime-support                  3.62                         all          MIME files 'mime.types' & 'mailcap', and support programs
    ii  mount                         2.33.1-0.1                   amd64        tools for mounting and manipulating filesystems
    ii  ncurses-base                  6.1+20181013-2+deb10u2       all          basic terminal type definitions
    ii  ncurses-bin                   6.1+20181013-2+deb10u2       amd64        terminal-related programs and man pages
    ii  net-tools                     1.60+git20180626.aebd88e-1   amd64        NET-3 networking toolkit
    ii  openssh-client                1:7.9p1-10+deb10u2           amd64        secure shell (SSH) client, for secure access to remote machines
    ii  openssl                       1.1.1d-0+deb10u7             amd64        Secure Sockets Layer toolkit - cryptographic utility
    ii  passwd                        1:4.5-1.1                    amd64        change and administer password and group data
    ii  patch                         2.7.6-3+deb10u1              amd64        Apply a diff file to an original
    ii  perl                          5.28.1-6+deb10u1             amd64        Larry Wall's Practical Extraction and Report Language
    ii  perl-base                     5.28.1-6+deb10u1             amd64        minimal Perl system
    ii  perl-modules-5.28             5.28.1-6+deb10u1             all          Core Perl modules
    ii  pinentry-curses               1.1.0-2                      amd64        curses-based PIN or pass-phrase entry dialog for GnuPG
    ii  poppler-data                  0.4.9-2                      all          encoding data for the poppler PDF rendering library
    ii  preview-latex-style           11.91-2                      all          extraction of elements from LaTeX documents as graphics
    ii  procps                        2:3.3.15-2                   amd64        /proc file system utilities
    ii  ps2eps                        1.68+binaryfree-2            amd64        convert PostScript to EPS (Encapsulated PostScript) files
    ii  psmisc                        23.2-1+deb10u1               amd64        utilities that use the proc file system
    ii  python                        2.7.16-1                     amd64        interactive high-level object-oriented language (Python2 version)
    ii  python-babel-localedata       2.6.0+dfsg.1-1               all          tools for internationalizing Python applications - locale data files
    ii  python-minimal                2.7.16-1                     amd64        minimal subset of the Python2 language
    ii  python2                       2.7.16-1                     amd64        interactive high-level object-oriented language (Python2 version)
    ii  python2-minimal               2.7.16-1                     amd64        minimal subset of the Python2 language
    ii  python2.7                     2.7.16-2+deb10u1             amd64        Interactive high-level object-oriented language (version 2.7)
    ii  python2.7-minimal             2.7.16-2+deb10u1             amd64        Minimal subset of the Python language (version 2.7)
    ii  python3                       3.7.3-1                      amd64        interactive high-level object-oriented language (default python3 version)
    ii  python3-alabaster             0.7.8-1                      all          Configurable sidebar-enabled Sphinx theme (Python 3)
    ii  python3-babel                 2.6.0+dfsg.1-1               all          tools for internationalizing Python applications - Python 3.x
    ii  python3-certifi               2018.8.24-1                  all          root certificates for validating SSL certs and verifying TLS hosts (python3)
    ii  python3-chardet               3.0.4-3                      all          universal character encoding detector for Python3
    ii  python3-distutils             3.7.3-1                      all          distutils package for Python 3.x
    ii  python3-docutils              0.14+dfsg-4                  all          text processing system for reStructuredText (implemented in Python 3)
    ii  python3-idna                  2.6-1                        all          Python IDNA2008 (RFC 5891) handling (Python 3)
    ii  python3-imagesize             1.0.0-1                      all          Python 3 module for getting image size from png/jpeg/jpeg2000/gif file
    ii  python3-jinja2                2.10-2                       all          small but fast and easy to use stand-alone template engine
    ii  python3-lib2to3               3.7.3-1                      all          Interactive high-level object-oriented language (2to3, version 3.6)
    ii  python3-markupsafe            1.1.0-1                      amd64        HTML/XHTML/XML string library for Python 3
    ii  python3-minimal               3.7.3-1                      amd64        minimal subset of the Python language (default python3 version)
    ii  python3-packaging             19.0-1                       all          core utilities for python3 packages
    ii  python3-pkg-resources         40.8.0-1                     all          Package Discovery and Resource Access using pkg_resources
    ii  python3-pygments              2.3.1+dfsg-1+deb10u2         all          syntax highlighting package written in Python 3
    ii  python3-pyparsing             2.2.0+dfsg1-2                all          alternative to creating and executing simple grammars - Python 3.x
    ii  python3-requests              2.21.0-1                     all          elegant and simple HTTP library for Python3, built for human beings
    ii  python3-roman                 2.0.0-3                      all          module for generating/analyzing Roman numerals for Python 3
    ii  python3-six                   1.12.0-1                     all          Python 2 and 3 compatibility library (Python 3 interface)
    ii  python3-sphinx                1.8.4-1                      all          documentation generator for Python projects (implemented in Python 3)
    ii  python3-sphinx-rtd-theme      0.4.3+dfsg-1                 all          sphinx theme from readthedocs.org (Python 3)
    ii  python3-tz                    2019.1-1                     all          Python3 version of the Olson timezone database
    ii  python3-urllib3               1.24.1-1                     all          HTTP library with thread-safe connection pooling for Python3
    ii  python3.7                     3.7.3-2+deb10u3              amd64        Interactive high-level object-oriented language (version 3.7)
    ii  python3.7-minimal             3.7.3-2+deb10u3              amd64        Minimal subset of the Python language (version 3.7)
    ii  readline-common               7.0-5                        all          GNU readline and history libraries, common files
    ii  sed                           4.7-1                        amd64        GNU stream editor for filtering/transforming text
    ii  sensible-utils                0.0.12                       all          Utilities for sensible alternative selection
    ii  sgml-base                     1.29                         all          SGML infrastructure and SGML catalog file support
    ii  sphinx-common                 1.8.4-1                      all          documentation generator for Python projects - common data
    ii  sphinx-rtd-theme-common       0.4.3+dfsg-1                 all          sphinx theme from readthedocs.org (common files)
    ii  sudo                          1.8.27-1+deb10u3             amd64        Provide limited super user privileges to specific users
    ii  sysvinit-utils                2.93-8                       amd64        System-V-like utilities
    ii  t1utils                       1.41-3                       amd64        Collection of simple Type 1 font manipulation programs
    ii  tar                           1.30+dfsg-6                  amd64        GNU version of the tar archiving utility
    ii  tex-common                    6.11                         all          common infrastructure for building and installing TeX
    ii  texlive                       2018.20190227-2              all          TeX Live: A decent selection of the TeX Live packages
    ii  texlive-base                  2018.20190227-2              all          TeX Live: Essential programs and files
    ii  texlive-binaries              2018.20181218.49446-1        amd64        Binaries for TeX Live
    ii  texlive-font-utils            2018.20190227-2              all          TeX Live: Graphics and font utilities
    ii  texlive-fonts-extra           2018.20190227-2              all          TeX Live: Additional fonts
    ii  texlive-fonts-recommended     2018.20190227-2              all          TeX Live: Recommended fonts
    ii  texlive-generic-recommended   2018.20190227-2              all          TeX Live: transitional dummy package
    ii  texlive-lang-english          2018.20190227-2              all          TeX Live: US and UK English
    ii  texlive-latex-base            2018.20190227-2              all          TeX Live: LaTeX fundamental packages
    ii  texlive-latex-extra           2018.20190227-2              all          TeX Live: LaTeX additional packages
    ii  texlive-latex-recommended     2018.20190227-2              all          TeX Live: LaTeX recommended packages
    ii  texlive-pictures              2018.20190227-2              all          TeX Live: Graphics, pictures, diagrams
    ii  texlive-plain-generic         2018.20190227-2              all          TeX Live: Plain (La)TeX packages
    ii  tzdata                        2021a-0+deb10u3              all          time zone and daylight-saving time data
    ii  ucf                           3.0038+nmu1                  all          Update Configuration File(s): preserve user changes to config files
    ii  unzip                         6.0-23+deb10u2               amd64        De-archiver for .zip files
    ii  util-linux                    2.33.1-0.1                   amd64        miscellaneous system utilities
    ii  wget                          1.20.1-1.1                   amd64        retrieves files from the web
    ii  whiptail                      0.52.20-8                    amd64        Displays user-friendly dialog boxes from shell scripts
    ii  x11-common                    1:7.7+19                     all          X Window System (X.Org) infrastructure
    ii  xdg-utils                     1.1.3-1+deb10u1              all          desktop integration utilities from freedesktop.org
    ii  xml-core                      0.18+nmu1                    all          XML infrastructure and XML catalog file support
    ii  xtail                         2.1-6                        amd64        like "tail -f", but works on truncated files, directories, more
    ii  xz-utils                      5.2.4-1                      amd64        XZ-format compression utilities
    ii  zlib1g:amd64                  1:1.2.11.dfsg-1              amd64        compression library - runtime
